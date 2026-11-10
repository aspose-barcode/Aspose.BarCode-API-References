---
title: "Pdf417Parameters.IsCode128Emulation"
second_title: "مرجع API لـ Aspose.BarCode for .NET"
description: "خاصية Pdf417Parameters. يمكن استخدامها فقط مع MicroPdf417 وتشفّر أوضاع محاكاة Code 128. يمكنها ترميز FNC1 في الموضع الثاني للأوضاع 908 و909، كما يمكنها ترميز 910 و911 التي تشير فقط إلى أن MicroPdf417 المُعترف به يمكن تفسيره كـ Code 128"
type: docs
weight: 60
url: /ar/net/aspose.barcode.generation/pdf417parameters/iscode128emulation/
---
## Pdf417Parameters.IsCode128Emulation property

يمكن استخدامها فقط مع MicroPdf417 وتشفير أوضاع محاكاة Code 128 يمكنها تشفير FNC1 في الموضع الثاني في أوضاع 908 و 909، كما يمكنها تشفير 910 و 911 والتي تشير فقط إلى أن MicroPdf417 المعترف به يمكن تفسيره كـ Code 128

```csharp
public bool IsCode128Emulation { get; set; }
```

## أمثلة

تُظهر هذه الأمثلة كيفية ترميز أوضاع محاكاة Code 128 مع FNC1 في الموضع الثاني وبدونه. بهذه الطريقة يمكن فك ترميز MicroPdf417 كباركود Code 128

```csharp
[C#]
//يقوم بترميز MicroPdf417 في وضع محاكاة Code 128 مع FNC1 في الموضع الثاني ومؤشر التطبيق "a"، الوضع 908.
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "a\u001d1222322323");
generator.Parameters.Barcode.Pdf417.IsCode128Emulation = true;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText + " IsCode128Emulation:" + result.Extended.Pdf417.IsCode128Emulation.ToString());

//يقوم بترميز MicroPdf417 في وضع محاكاة Code 128 مع FNC1 في الموضع الثاني ومؤشر التطبيق "99"، الوضع 909.
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "99\u001d1222322323");
generator.Parameters.Barcode.Pdf417.IsCode128Emulation = true;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText + " IsCode128Emulation:" + result.Extended.Pdf417.IsCode128Emulation.ToString());

//يقوم بترميز MicroPdf417 في وضع محاكاة Code 128، الأوضاع 910، 911
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "123456789012345678");
generator.Parameters.Barcode.Pdf417.IsCode128Emulation = true;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText + " IsCode128Emulation:" + result.Extended.Pdf417.IsCode128Emulation.ToString());
```

### انظر أيضًا

* class [Pdf417Parameters](../)
* namespace [Aspose.BarCode.Generation](../../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../../)


