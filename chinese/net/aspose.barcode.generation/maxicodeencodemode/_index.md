---
title: "枚举 MaxiCodeEncodeMode"
second_title: "Aspose.BarCode 适用于 .NET API 参考"
description: "Aspose.BarCode.Generation.MaxiCodeEncodeMode 枚举。MaxiCode 条码的编码模式"
type: docs
weight: 1460
url: /zh/net/aspose.barcode.generation/maxicodeencodemode/
---
## MaxiCodeEncodeMode enumeration

MaxiCode 条形码的编码模式。

```csharp
public enum MaxiCodeEncodeMode
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| Auto | `0` | 在 Auto 模式下，CodeText 以最高的数据紧凑度进行编码。Unicode 字符会在指定的 ECIEncoding 编码中重新编码，并插入 ECI 标识符。如果发现字符不受所选 ECI 编码支持，则会抛出异常。 |
| Extended | `3` | 支持多 ECI 模式的扩展模式。 |
| Binary | `4` | 在 Binary 模式下，CodeText 以最高的数据紧凑度进行编码。如果发现 Unicode 字符，则会抛出异常。 |
| ECI | `5` | 在 ECI 模式下，整个消息会在指定的 ECIEncoding 编码中重新编码，并插入 ECI 标识符。如果发现字符不受所选 ECI 编码支持，则会抛出异常。请注意，某些旧的（2006 年前）扫描仪可能不支持此模式。 |

## 示例

```csharp
[C#]
//Auto 模式
var codetext = "犬Right狗";
using (var generator = new BarcodeGenerator(EncodeTypes.MaxiCode, codetext))
{
    generator.Parameters.Barcode.MaxiCode.ECIEncoding = ECIEncodings.UTF8;
    generator.Save("test.bmp");
}

//Bytes 模式
byte[] encodedArr = { 0xFF, 0xFE, 0xFD, 0xFC, 0xFB, 0xFA, 0xF9 };
using (var generator = new BarcodeGenerator(EncodeTypes.MaxiCode))
{
    generator.SetCodetext(encodedArr);
    generator.Parameters.Barcode.MaxiCode.MaxiCodeEncodeMode = MaxiCodeEncodeMode.Binary;
    generator.Save("test.bmp");
}

//Extended codetext 模式
//创建代码文本
MaxiCodeExtCodetextBuilder textBuilder = new MaxiCodeExtCodetextBuilder();
textBuilder.AddECICodetext(ECIEncodings.Win1251, "Will");
textBuilder.AddECICodetext(ECIEncodings.UTF8, "犬Right狗");
textBuilder.AddECICodetext(ECIEncodings.UTF16BE, "犬Power狗");
textBuilder.AddPlainCodetext("Plain text");

//生成代码文本
string codetext = textBuilder.GetExtendedCodetext();    

//生成
using(BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MaxiCode, codetext))
{
    generator.Parameters.Barcode.MaxiCode.MaxiCodeEncodeMode = MaxiCodeEncodeMode.Extended;
    generator.Parameters.Barcode.CodeTextParameters.TwoDDisplayText = "My Text";
	generator.Save("test.bmp");
}
```

### 另见

* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


