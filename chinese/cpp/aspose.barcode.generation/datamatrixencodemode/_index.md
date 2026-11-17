---
title: "枚举"
linktitle: "DataMatrixEncodeMode"
second_title: "Aspose.BarCode for C++ API 参考"
description: "枚举。DataMatrix 编码器的编码模式，默认在 C++ 中为 Auto。"
type: docs
weight: 6300
url: /zh/cpp/aspose.barcode.generation/datamatrixencodemode/
---
## DataMatrixEncodeMode enum


DataMatrix 编码器的编码模式，默认 Auto

```cpp
enum class DataMatrixEncodeMode
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| 自动 | 0 | 在 Auto 模式下，CodeText 以最大数据紧凑度进行编码。Unicode 字符会使用指定的 ECIEncoding 重新编码，并插入 ECI 标识符。如果发现字符不受所选 ECI 编码支持，则会抛出异常。 |
| ASCII | 1 | 每字节编码一个字母数字字符或两个数字字符 |
| C40 | 8 | 使用 C40 编码。编码大写字母数字字符、 小写字符和特殊字符 |
| 文本 | 9 | 使用 Text 编码。编码小写字母数字字符、大写字符和特殊字符 |
| EDIFACT | 10 | 使用 EDIFACT 编码。每个字符使用六位，编码数字、大写字母和许多标点符号，但不支持小写字母。 |
| ANSIX12 | 11 | 使用 ANSI X12 编码。 |
| 扩展 | 13 |  |
| Base256 | 14 | 编码 8 位值 |
| 二进制 | 15 | 在二进制模式下，CodeText 以最大数据紧凑度进行编码。如果发现 Unicode 字符，则会抛出异常。 |
| ECI | 16 | 在 ECI 模式下，整个消息会使用指定的 ECIEncoding 重新编码，并插入 ECI 标识符。如果发现字符不受所选 ECI 编码支持，则会抛出异常。请注意，某些旧（2006 年之前）的扫描仪可能不支持此模式。 |

## 备注


此示例展示了如何在扩展模式下进行 codetext。
```cpp
[C#]
//自动模式
string codetext = "犬Right狗";
using (var generator = new BarcodeGenerator(EncodeTypes.DataMatrix, codetext))
{
    generator.Parameters.Barcode.DataMatrix.ECIEncoding = ECIEncodings.UTF8;
    generator.Save("test.bmp");
}

//字节模式
byte[] encodedArr = { 0xFF, 0xFE, 0xFD, 0xFC, 0xFB, 0xFA, 0xF9 };
using (var generator = new BarcodeGenerator(EncodeTypes.DataMatrix))
{
    generator.SetCodetext(encodedArr);
    generator.Parameters.Barcode.DataMatrix.EncodeMode = EncodeMode.Binary;
    generator.Save("test.bmp");
}


//扩展码文本模式
//创建码文本
DataMatrixExtCodetextBuilder textBuilder = new DataMatrixExtCodetextBuilder();
codetextBuilder.AddECICodetextWithEncodeMode(ECIEncodings.Win1251, EncodeMode.Bytes, "World");
codetextBuilder.AddPlainCodetext("Will");
codetextBuilder.AddECICodetext(ECIEncodings.UTF8, "犬Right狗");
codetextBuilder.AddCodetextWithEncodeMode(EncodeMode.C40, "ABCDE");

//生成码文本
string codetext = textBuilder.GetExtendedCodetext();

//生成
using(BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DataMatrix, codetext))
{
    generator.Parameters.Barcode.DataMatrix.EncodeMode = EncodeMode.Extended;
    generator.Save("test.bmp");
}
```

## 另见

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
