---
title: "طريقة"
linktitle: "set_IsLinked"
second_title: "Aspose.BarCode للـ C++ مرجع API"
description: " طريقة. يحدد أوضاع الربط مع باركودات GS1MicroPdf417 وMicroPdf417 وPdf417. مع ترميز GS1MicroPdf417 يتم تشفير 906، 907، 912، 913، 914، 915 أوضاع “Linked” UCC/EAN-128. مع ترميزات MicroPdf417 وPdf417 يتم تشفير علم الربط 918 إلى المكوّن الخطي المرتبط غير EAN.UCC في C++."
type: docs
weight: 4200
url: /ar/cpp/aspose.barcode.generation/pdf417parameters/set_islinked/
---
## Pdf417Parameters::set_IsLinked method


يحدد أوضاع الربط مع باركودات GS1MicroPdf417 وMicroPdf417 وPdf417. مع ترميز GS1MicroPdf417 يتم تشفير الأوضاع 906 و907 و912 و913 و914 و915 “Linked” UCC/EAN-128. ومع ترميزات MicroPdf417 وPdf417 يتم تشفير علم الربط 918 إلى المكوّن الخطي المرتبط غير EAN.UCC.

```cpp
void Aspose::BarCode::Generation::Pdf417Parameters::set_IsLinked(bool value)
```

## ملاحظات


تظهر هذه العينات كيفية تشفير أوضاع "Linked" UCC/EAN-128 في GS1MicroPdf417 وعلم الربط (918) في باركودات MicroPdf417 وPdf417.
```cpp
[C#]
//يقوم بتشفير وضع GS1 Linked 912 مع حقل التاريخ AI 11 (تاريخ الإنتاج) و AI 10 (رقم الدفعة).
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(11)991231(10)ABCD");
generator.Parameters.Barcode.Pdf417.IsLinked = true;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());

//يقوم بتشفير وضع GS1 Linked 912 مع حقل التاريخ AI 13 (تاريخ التعبئة) و AI 21 (الرقم التسلسلي).
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(13)991231(21)ABCD");
generator.Parameters.Barcode.Pdf417.IsLinked = true;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());

//يقوم بتشفير وضع GS1 Linked 912 مع حقل التاريخ AI 15 (تاريخ الانتهاء للبيع) و AI 10 (رقم الدفعة).
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(15)991231(10)ABCD");
generator.Parameters.Barcode.Pdf417.IsLinked = true;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());

//يقوم بتشفير وضع GS1 Linked 912 مع حقل التاريخ AI 17 (تاريخ الانتهاء) و AI 21 (الرقم التسلسلي).
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(17)991231(21)ABCD");
generator.Parameters.Barcode.Pdf417.IsLinked = true;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());

//يقوم بترميز وضع GS1 المرتبط 914 مع AI 10 (رقم الدفعة)
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(10)ABCD12345");
generator.Parameters.Barcode.Pdf417.IsLinked = true;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());

//يقوم بترميز وضع GS1 المرتبط 915 مع AI 21 (رقم التسلسل)
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(21)ABCD12345");
generator.Parameters.Barcode.Pdf417.IsLinked = true;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());

//يقوم بترميز أوضاع GS1 المرتبطة 906, 907 مع أي AI
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(240)123456789012345");
generator.Parameters.Barcode.Pdf417.IsLinked = true;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());

//يقوم بترميز وضع MicroPdf417 NON EAN.UCC المرتبط 918
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "ABCDE123456789012345678");
generator.Parameters.Barcode.Pdf417.IsLinked = true;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());

//يقوم بترميز وضع Pdf417 NON EAN.UCC المرتبط 918
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Pdf417, "ABCDE123456789012345678");
generator.Parameters.Barcode.Pdf417.IsLinked = true;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.Pdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());
```

## انظر أيضًا

* Class [Pdf417Parameters](../)
* Namespace [Aspose::BarCode::Generation](../../)
* Library [Aspose.BarCode for C++](../../../)
