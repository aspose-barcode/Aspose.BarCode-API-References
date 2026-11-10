---
title: "Pdf417Parameters.IsLinked"
second_title: "مرجع API لـ Aspose.BarCode for .NET"
description: "خاصية Pdf417Parameters. تُعرّف أوضاع الربط مع باركودات GS1MicroPdf417 وMicroPdf417 وPdf417. مع ترميز GS1MicroPdf417 يتم ترميز الأوضاع المرتبطة 906 907 912 913 914 915 لنظام UCC/EAN128. ومع ترميزات MicroPdf417 وPdf417 يتم ترميز علم الربط 918 إلى المكوّن الخطي المرتبط غير EAN.UCC."
type: docs
weight: 70
url: /ar/net/aspose.barcode.generation/pdf417parameters/islinked/
---
## Pdf417Parameters.IsLinked property

يحدد أوضاع الربط مع رموز GS1MicroPdf417 و MicroPdf417 و Pdf417 مع ترميز GS1MicroPdf417 يشفّر 906، 907، 912، 913، 914، 915 أوضاع “Linked” UCC/EAN-128 مع رموز MicroPdf417 و Pdf417 يشفّر علم الربط 918 للمكوّن الخطي المرتبط غير الـ EAN.UCC

```csharp
public bool IsLinked { get; set; }
```

## أمثلة

تُظهر هذه الأمثلة كيفية ترميز أوضاع \"Linked\" UCC/EAN-128 في GS1MicroPdf417 وعلم الربط (918) في باركودات MicroPdf417 وPdf417.

```csharp
[C#]
//يقوم بترميز وضع الربط GS1 912 مع حقل التاريخ AI 11 (تاريخ الإنتاج) و AI 10 (رقم الدفعة).
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(11)991231(10)ABCD");
generator.Parameters.Barcode.Pdf417.IsLinked = true;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());

//يقوم بترميز وضع الربط GS1 912 مع حقل التاريخ AI 13 (تاريخ التعبئة) و AI 21 (الرقم التسلسلي).
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(13)991231(21)ABCD");
generator.Parameters.Barcode.Pdf417.IsLinked = true;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());

//يقوم بترميز وضع الربط GS1 912 مع حقل التاريخ AI 15 (تاريخ البيع) و AI 10 (رقم الدفعة).
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(15)991231(10)ABCD");
generator.Parameters.Barcode.Pdf417.IsLinked = true;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());

//يقوم بترميز وضع الربط GS1 912 مع حقل التاريخ AI 17 (تاريخ الانتهاء) و AI 21 (الرقم التسلسلي).
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(17)991231(21)ABCD");
generator.Parameters.Barcode.Pdf417.IsLinked = true;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());

//يقوم بترميز وضع الربط GS1 914 مع AI 10 (رقم الدفعة).
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(10)ABCD12345");
generator.Parameters.Barcode.Pdf417.IsLinked = true;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());

//يقوم بترميز وضع الربط GS1 915 مع AI 21 (الرقم التسلسلي).
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(21)ABCD12345");
generator.Parameters.Barcode.Pdf417.IsLinked = true;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());

//يقوم بترميز أوضاع الربط GS1 906، 907 مع أي AI.
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(240)123456789012345");
generator.Parameters.Barcode.Pdf417.IsLinked = true;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());

//يقوم بترميز وضع الربط MicroPdf417 NON EAN.UCC 918.
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "ABCDE123456789012345678");
generator.Parameters.Barcode.Pdf417.IsLinked = true;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());

//يقوم بترميز وضع الربط Pdf417 NON EAN.UCC 918.
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Pdf417, "ABCDE123456789012345678");
generator.Parameters.Barcode.Pdf417.IsLinked = true;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.Pdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());
```

### انظر أيضًا

* class [Pdf417Parameters](../)
* namespace [Aspose.BarCode.Generation](../../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../../)


