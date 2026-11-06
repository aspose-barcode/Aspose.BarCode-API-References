---
title: "طريقة"
linktitle: "get_IsCode128Emulation"
second_title: "Aspose.BarCode للـ C++ مرجع API"
description: " طريقة. يمكن استخدامها فقط مع MicroPdf417 وتشفّر أوضاع محاكاة Code 128. يمكنها تشفير FNC1 في الموضع الثاني للأوضاع 908 و909، كما يمكنها تشفير 910 و911 التي تشير فقط إلى أن MicroPdf417 المعترف به يمكن تفسيره كـ Code 128 في C++."
type: docs
weight: 4300
url: /ar/cpp/aspose.barcode.generation/pdf417parameters/get_iscode128emulation/
---
## Pdf417Parameters::get_IsCode128Emulation method


يمكن استخدامه فقط مع MicroPdf417 ويشفّر أوضاع محاكاة Code 128. يمكنه تشفير FNC1 في الوضع الثاني للأوضاع 908 و909، كما يمكنه تشفير 910 و911 التي تشير فقط إلى أن MicroPdf417 المعترف به يمكن تفسيره كـ Code 128.

```cpp
bool Aspose::BarCode::Generation::Pdf417Parameters::get_IsCode128Emulation() const
```

## ملاحظات


تظهر هذه العينات كيفية تشفير أوضاع محاكاة Code 128 مع FNC1 في الموضع الثاني وبدونه. بهذه الطريقة يمكن فك تشفير MicroPdf417 كرمز شريطي Code 128.
```cpp
[C#]
//يقوم بتشفير MicroPdf417 في وضع محاكاة Code 128 مع FNC1 في الموضع الثاني ومؤشر التطبيق "a", الوضع 908.
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "a\u001d1222322323");
generator.Parameters.Barcode.Pdf417.IsCode128Emulation = true;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText + " IsCode128Emulation:" + result.Extended.Pdf417.IsCode128Emulation.ToString());

//يقوم بتشفير MicroPdf417 في وضع محاكاة Code 128 مع FNC1 في الموضع الثاني ومؤشر التطبيق "99", الوضع 909.
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "99\u001d1222322323");
generator.Parameters.Barcode.Pdf417.IsCode128Emulation = true;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText + " IsCode128Emulation:" + result.Extended.Pdf417.IsCode128Emulation.ToString());

//يقوم بتشفير MicroPdf417 في وضع محاكاة Code 128، الأوضاع 910، 911
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "123456789012345678");
generator.Parameters.Barcode.Pdf417.IsCode128Emulation = true;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText + " IsCode128Emulation:" + result.Extended.Pdf417.IsCode128Emulation.ToString());
```

## انظر أيضًا

* Class [Pdf417Parameters](../)
* Namespace [Aspose::BarCode::Generation](../../)
* Library [Aspose.BarCode for C++](../../../)
