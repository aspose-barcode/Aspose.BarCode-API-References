---
title: "method"
linktitle: "SetCodeText"
second_title: "Aspose.BarCode for C++ API 参考"
description: "方法。在 C++ 中将 codetext 设置为字节序列。"
type: docs
weight: 700
url: /zh/cpp/aspose.barcode.generation/barcodegenerator/setcodetext/
---
## BarcodeGenerator::SetCodeText(System::ArrayPtr\<uint8_t\>) method


将 codetext 设置为字节序列。

```cpp
void Aspose::BarCode::Generation::BarcodeGenerator::SetCodeText(System::ArrayPtr<uint8_t> codeBytes)
```


| Parameter | Type | 描述 |
| --- | --- | --- |
| codeBytes | System::ArrayPtr\<uint8_t\> | codetext 的字节 |

## 另见

* Class [BarcodeGenerator](../)
* Namespace [Aspose::BarCode::Generation](../../)
* Library [Aspose.BarCode for C++](../../../)
## BarcodeGenerator::SetCodeText(System::String, System::SharedPtr\<System::Text::Encoding\>) method




```cpp
void Aspose::BarCode::Generation::BarcodeGenerator::SetCodeText(System::String codeText, System::SharedPtr<System::Text::Encoding> encoding)
```


| Parameter | Type | 描述 |
| --- | --- | --- |
| codeText | System::String | CodeText 字符串 |
| 编码 | System::SharedPtr\<System::Text::Encoding\> | 应用的编码 |
## 备注


将 Unicode **codeText** 使用指定的 **encoding** 编码为字节序列。UTF-8 是最常用的编码。如果该编码支持，函数会自动插入 [byte order mark (BOM)](https://en.wikipedia.org/wiki/Byte_order_mark#Byte-order_marks_by_encoding)。

此函数仅用于 2D 条码（例如 Aztec、QR、DataMatrix、PDF417、MaxiCode、DotCode、HanXin、RectMicroQR 等）。它允许使用国家或特殊编码手动编码 Unicode 文本；然而，在现代应用中此方法已被视为过时。对于现代使用场景，建议对 Unicode 数据使用 [ECI](https://en.wikipedia.org/wiki/Extended_Channel_Interpretation) 编码。

使用此函数处理 1D 条码、符合 GS1 标准的条码（包括 2D）或 HIBC 条码（包括 2D）不受相应条码标准支持，可能导致不可预测的结果。


此示例展示了如何使用 **SetCodeText** 为 2D 条码设置不同编码的 Unicode 编码文本：


```cpp
[C#]
//使用带 BOM 的 UTF-8 编码 QR Code 文本
using (BarcodeGenerator gen = new BarcodeGenerator(EncodeTypes.QR))
{
    gen.SetCodeText("車種名", Encoding.UTF8);
    gen.Save("barcode.png", BarCodeImageFormat.Png);
}
    using (BarCodeReader reader = new BarCodeReader("barcode.png", DecodeType.QR))
        foreach (BarCodeResult result in reader.ReadBarCodes())
            Console.WriteLine("BarCode CodeText: " + result.CodeText);

    //使用 Shift-JIS（日文编码）编码 DataMatrix 文本
    using (BarcodeGenerator gen = new BarcodeGenerator(EncodeTypes.DataMatrix))
    {
        gen.SetCodeText("車種名", Encoding.GetEncoding(932));
        gen.Save("barcode.png", BarCodeImageFormat.Png);
    }
    using (BarCodeReader reader = new BarCodeReader("barcode.png", DecodeType.DataMatrix))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine("BarCode CodeText: " + result.GetCodeText(Encoding.GetEncoding(932)));
```

## 另见

* Class [BarcodeGenerator](../)
* Namespace [Aspose::BarCode::Generation](../../)
* Library [Aspose.BarCode for C++](../../../)
## BarcodeGenerator::SetCodeText(System::String, System::SharedPtr\<System::Text::Encoding\>, bool) method




```cpp
void Aspose::BarCode::Generation::BarcodeGenerator::SetCodeText(System::String codeText, System::SharedPtr<System::Text::Encoding> encoding, bool insertBOM)
```


| Parameter | Type | 描述 |
| --- | --- | --- |
| codeText | System::String | CodeText 字符串 |
| 编码 | System::SharedPtr\<System::Text::Encoding\> | 应用的编码 |
| insertBOM | bool | 指示在指定的编码支持时（例如 UTF-8、UTF-16、UTF-32）是否插入字节顺序标记 (BOM)。如果设置为 **true**，则添加 BOM；如果设置为 **false**，即使该编码通常使用 BOM，也会省略。 |
## 备注


将 Unicode **codeText** 使用指定的 **encoding** 编码为字节序列。UTF-8 是最常用的编码。如果该编码支持且 **insertBOM** 设置为 **true**，函数会包含一个 [byte order mark (BOM)](https://en.wikipedia.org/wiki/Byte_order_mark#Byte-order_marks_by_encoding)。

此函数仅用于 2D 条码（例如 Aztec、QR、DataMatrix、PDF417、MaxiCode、DotCode、HanXin、RectMicroQR 等）。它允许使用国家或特殊编码手动编码 Unicode 文本；然而，在现代应用中此方法已被视为过时。对于现代使用场景，建议对 Unicode 数据使用 [ECI](https://en.wikipedia.org/wiki/Extended_Channel_Interpretation) 编码。

使用此函数处理 1D 条码、符合 GS1 标准的条码（包括 2D）或 HIBC 条码（包括 2D）不受相应条码标准支持，可能导致不可预测的结果。


此示例展示了如何在 2D 条码中使用 **SetCodeText**（带或不带 BOM）。


```cpp
[C#]
    //使用带 BOM 的 UTF-8 编码代码文本
    using (BarcodeGenerator gen = new BarcodeGenerator(EncodeTypes.QR))
    {
        gen.SetCodeText("車種名", Encoding.UTF8, true);
        gen.Save("barcode.png", BarCodeImageFormat.Png);
    }
    using (BarCodeReader reader = new BarCodeReader("barcode.png", DecodeType.QR))
        foreach (BarCodeResult result in reader.ReadBarCodes())
            Console.WriteLine("BarCode CodeText: " + result.CodeText);

    //使用不带 BOM 的 UTF-8 编码代码文本
    using (BarcodeGenerator gen = new BarcodeGenerator(EncodeTypes.QR))
    {
        gen.SetCodeText("車種名", Encoding.UTF8, false);
        gen.Save("barcode.png", BarCodeImageFormat.Png);
    }
    using (BarCodeReader reader = new BarCodeReader("barcode.png", DecodeType.QR))
        foreach (BarCodeResult result in reader.ReadBarCodes())
            Console.WriteLine("BarCode CodeText: " + result.CodeText);
```

## 另见

* Class [BarcodeGenerator](../)
* Namespace [Aspose::BarCode::Generation](../../)
* Library [Aspose.BarCode for C++](../../../)
