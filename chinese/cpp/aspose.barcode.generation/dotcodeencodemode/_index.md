---
title: "枚举"
linktitle: "DotCodeEncodeMode"
second_title: "Aspose.BarCode for C++ API 参考"
description: "枚举。DotCode 条码的编码模式，适用于 C++。"
type: docs
weight: 6500
url: /zh/cpp/aspose.barcode.generation/dotcodeencodemode/
---
## DotCodeEncodeMode enum


DotCode 条码的编码模式。

```cpp
enum class DotCodeEncodeMode
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| 自动 | 0 | 在 Auto 模式下，CodeText 以最大数据紧凑度进行编码。Unicode 字符会使用指定的 ECIEncoding 重新编码，并插入 ECI 标识符。如果发现字符不受所选 ECI 编码支持，则会抛出异常。 |
| 二进制 | 3 | 在二进制模式下，CodeText 以最大数据紧凑度进行编码。如果发现 Unicode 字符，则会抛出异常。 |
| ECI | 4 | 在 ECI 模式下，整个消息会使用指定的 ECIEncoding 重新编码，并插入 ECI 标识符。如果发现字符不受所选 ECI 编码支持，则会抛出异常。请注意，某些旧（2006 年之前）的扫描仪可能不支持此模式。 |
| 扩展 | 5 |  |

## 备注



```cpp
[C#]
//带宏的自动模式
var codetext = ""[)>\u001E05\u001DCodetextWithMacros05\u001E\u0004"";
using (var generator = new BarcodeGenerator(EncodeTypes.DotCode, codetext))
{
    generator.Save("test.bmp");
}

//自动模式
var codetext = "犬Right狗";
using (var generator = new BarcodeGenerator(EncodeTypes.DotCode, codetext))
{
    generator.Parameters.Barcode.DotCode.ECIEncoding = ECIEncodings.UTF8;
    generator.Save("test.bmp");
}

//字节模式
byte[] encodedArr = { 0xFF, 0xFE, 0xFD, 0xFC, 0xFB, 0xFA, 0xF9 };
using (var generator = new BarcodeGenerator(EncodeTypes.DotCode))
{
    generator.SetCodetext(encodedArr);
    generator.Parameters.Barcode.DotCode.DotCodeEncodeMode = DotCodeEncodeMode.Binary;
    generator.Save("test.bmp");
}

//扩展码文本模式
//创建码文本
DotCodeExtCodetextBuilder textBuilder = new DotCodeExtCodetextBuilder();
textBuilder.AddFNC1FormatIdentifier();
textBuilder.AddECICodetext(ECIEncodings.Win1251, "Will");
textBuilder.AddFNC1FormatIdentifier();
textBuilder.AddECICodetext(ECIEncodings.UTF8, "犬Right狗");
textBuilder.AddFNC3SymbolSeparator();
textBuilder.AddFNC1FormatIdentifier();
textBuilder.AddECICodetext(ECIEncodings.UTF16BE, "犬Power狗");
textBuilder.AddPlainCodetext("Plain text");

//生成码文本
string codetext = textBuilder.GetExtendedCodetext();

//生成
using(BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DotCode, codetext))
{
    generator.Parameters.Barcode.DotCode.DotCodeEncodeMode = DotCodeEncodeMode.Extended;
    generator.Save("test.bmp");
}
```

## 另见

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
