---
title: "枚举 DotCodeEncodeMode"
second_title: "Aspose.BarCode 适用于 .NET API 参考"
description: "Aspose.BarCode.Generation.DotCodeEncodeMode 枚举。DotCode 条形码的编码模式"
type: docs
weight: 1240
url: /zh/net/aspose.barcode.generation/dotcodeencodemode/
---
## DotCodeEncodeMode enumeration

DotCode 条形码的编码模式。

```csharp
public enum DotCodeEncodeMode
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| Auto | `0` | 在 Auto 模式下，CodeText 以最高的数据紧凑度进行编码。Unicode 字符会在指定的 ECIEncoding 编码中重新编码，并插入 ECI 标识符。如果发现字符不受所选 ECI 编码支持，则会抛出异常。 |
| Binary | `3` | 在 Binary 模式下，CodeText 以最高的数据紧凑度进行编码。如果发现 Unicode 字符，则会抛出异常。 |
| ECI | `4` | 在 ECI 模式下，整个消息会在指定的 ECIEncoding 编码中重新编码，并插入 ECI 标识符。如果发现字符不受所选 ECI 编码支持，则会抛出异常。请注意，某些旧的（2006 年前）扫描仪可能不支持此模式。 |
| Extended | `5` | 支持多 ECI 模式的扩展模式。 |

## 示例

```csharp
[C#]
//自动模式（带宏）
var codetext = ""[)>\u001E05\u001DCodetextWithMacros05\u001E\u0004"";
using (var generator = new BarcodeGenerator(EncodeTypes.DotCode, codetext))
{
    generator.Save("test.bmp");
}

//Auto 模式
var codetext = "犬Right狗";
using (var generator = new BarcodeGenerator(EncodeTypes.DotCode, codetext))
{
    generator.Parameters.Barcode.DotCode.ECIEncoding = ECIEncodings.UTF8;
    generator.Save("test.bmp");
}

//Bytes 模式
byte[] encodedArr = { 0xFF, 0xFE, 0xFD, 0xFC, 0xFB, 0xFA, 0xF9 };
using (var generator = new BarcodeGenerator(EncodeTypes.DotCode))
{
    generator.SetCodetext(encodedArr);
    generator.Parameters.Barcode.DotCode.DotCodeEncodeMode = DotCodeEncodeMode.Binary;
    generator.Save("test.bmp");
}

//Extended codetext 模式
//创建代码文本
DotCodeExtCodetextBuilder textBuilder = new DotCodeExtCodetextBuilder();
textBuilder.AddFNC1FormatIdentifier();
textBuilder.AddECICodetext(ECIEncodings.Win1251, "Will");
textBuilder.AddFNC1FormatIdentifier();
textBuilder.AddECICodetext(ECIEncodings.UTF8, "犬Right狗");
textBuilder.AddFNC3SymbolSeparator();
textBuilder.AddFNC1FormatIdentifier();
textBuilder.AddECICodetext(ECIEncodings.UTF16BE, "犬Power狗");
textBuilder.AddPlainCodetext("Plain text");

//生成代码文本
string codetext = textBuilder.GetExtendedCodetext();    

//生成
using(BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DotCode, codetext))
{
    generator.Parameters.Barcode.DotCode.DotCodeEncodeMode = DotCodeEncodeMode.Extended;
	generator.Save("test.bmp");
}
```

### 另见

* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


