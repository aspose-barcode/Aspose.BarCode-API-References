---
title: "枚举"
linktitle: "AztecEncodeMode"
second_title: "Aspose.BarCode for C++ API 参考"
description: "枚举。C++ 中 Aztec 条码的编码模式。"
type: docs
weight: 5300
url: /zh/cpp/aspose.barcode.generation/aztecencodemode/
---
## AztecEncodeMode enum


Aztec 条形码的编码模式。

```cpp
enum class AztecEncodeMode
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| 自动 | 0 | 在 Auto 模式下，CodeText 以最大数据紧凑度进行编码。Unicode 字符会使用指定的 ECIEncoding 重新编码，并插入 ECI 标识符。如果发现字符不受所选 ECI 编码支持，则会抛出异常。 |
| 扩展 | 3 |  |
| 二进制 | 4 | 在二进制模式下，CodeText 以最大数据紧凑度进行编码。如果发现 Unicode 字符，则会抛出异常。 |
| ECI | 5 | 在 ECI 模式下，整个消息会使用指定的 ECIEncoding 重新编码，并插入 ECI 标识符。如果发现字符不受所选 ECI 编码支持，则会抛出异常。请注意，某些旧（2006 年之前）的扫描仪可能不支持此模式。 |

## 备注



```cpp
[C#]
//自动模式
var codetext = "犬Right狗";
using (var generator = new BarcodeGenerator(EncodeTypes.Aztec, codetext))
{
    generator.Parameters.Barcode.Aztec.ECIEncoding = ECIEncodings.UTF8;
    generator.Save("test.bmp");
}

byte[] encodedArr = { 0xFF, 0xFE, 0xFD, 0xFC, 0xFB, 0xFA, 0xF9 };
using (var generator = new BarcodeGenerator(EncodeTypes.Aztec))
{
    generator.SetCodetext(encodedArr);
    generator.Parameters.Barcode.Aztec.AztecEncodeMode = AztecEncodeMode.Binary;
    generator.Save("test.bmp");
}

//Extended 模式
//创建码文本
AztecExtCodetextBuilder textBuilder = new AztecExtCodetextBuilder();
textBuilder.AddECICodetext(ECIEncodings.Win1251, "Will");
textBuilder.AddECICodetext(ECIEncodings.UTF8, "犬Right狗");
textBuilder.AddECICodetext(ECIEncodings.UTF16BE, "犬Power狗");
textBuilder.AddPlainCodetext("Plain text");

//生成码文本
string codetext = textBuilder.GetExtendedCodetext();

//生成
using(BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Aztec, codetext))
{
    generator.Parameters.Barcode.Aztec.AztecEncodeMode = AztecEncodeMode.Extended;
    generator.Parameters.Barcode.CodeTextParameters.TwoDDisplayText = "My Text";
    generator.Save("test.bmp");
}
```

## 另见

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
