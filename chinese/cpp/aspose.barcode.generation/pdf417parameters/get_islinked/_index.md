---
title: "method"
linktitle: "get_IsLinked"
second_title: "Aspose.BarCode for C++ API 参考"
description: " 方法。定义与 GS1MicroPdf417、MicroPdf417 和 Pdf417 条码的链接模式。使用 GS1MicroPdf417 符号可编码 906、907、912、913、914、915 “链接” UCC/EAN-128 模式；使用 MicroPdf417 和 Pdf417 符号可编码 918 链接标志，以关联除 EAN.UCC 之外的线性组件，在 C++ 中。"
type: docs
weight: 4100
url: /zh/cpp/aspose.barcode.generation/pdf417parameters/get_islinked/
---
## Pdf417Parameters::get_IsLinked method


定义了与 GS1MicroPdf417、MicroPdf417 和 Pdf417 条码的链接模式。使用 GS1MicroPdf417 符号时，编码 906、907、912、913、914、915 “链接” UCC/EAN-128 模式。使用 MicroPdf417 和 Pdf417 符号时，编码 918 链接标志，以关联除 EAN.UCC 之外的线性组件。

```cpp
bool Aspose::BarCode::Generation::Pdf417Parameters::get_IsLinked() const
```

## 备注


这些示例展示了如何在 GS1MicroPdf417 中编码 \"Linked\" UCC/EAN-128 模式，以及在 MicroPdf417 和 Pdf417 条码中编码链接标志 (918)。
```cpp
[C#]
//使用日期字段 AI 11（生产日期）和 AI 10（批号）对 GS1 链接模式 912 进行编码。
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(11)991231(10)ABCD");
generator.Parameters.Barcode.Pdf417.IsLinked = true;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());

//使用日期字段 AI 13（包装日期）和 AI 21（序列号）对 GS1 链接模式 912 进行编码。
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(13)991231(21)ABCD");
generator.Parameters.Barcode.Pdf417.IsLinked = true;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());

//使用日期字段 AI 15（售卖日期）和 AI 10（批号）对 GS1 链接模式 912 进行编码。
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(15)991231(10)ABCD");
generator.Parameters.Barcode.Pdf417.IsLinked = true;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());

//使用日期字段 AI 17（有效期）和 AI 21（序列号）对 GS1 链接模式 912 进行编码。
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(17)991231(21)ABCD");
generator.Parameters.Barcode.Pdf417.IsLinked = true;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());

//对 GS1 链接模式 914 使用 AI 10（批号）进行编码
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(10)ABCD12345");
generator.Parameters.Barcode.Pdf417.IsLinked = true;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());

//对 GS1 链接模式 915 使用 AI 21（序列号）进行编码
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(21)ABCD12345");
generator.Parameters.Barcode.Pdf417.IsLinked = true;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());

//对 GS1 链接模式 906、907 使用任意 AI 进行编码
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(240)123456789012345");
generator.Parameters.Barcode.Pdf417.IsLinked = true;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());

//对 MicroPdf417 非 EAN.UCC 链接模式 918 进行编码
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "ABCDE123456789012345678");
generator.Parameters.Barcode.Pdf417.IsLinked = true;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());

//对 Pdf417 非 EAN.UCC 链接模式 918 进行编码
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Pdf417, "ABCDE123456789012345678");
generator.Parameters.Barcode.Pdf417.IsLinked = true;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.Pdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());
```

## 另见

* Class [Pdf417Parameters](../)
* Namespace [Aspose::BarCode::Generation](../../)
* Library [Aspose.BarCode for C++](../../../)
