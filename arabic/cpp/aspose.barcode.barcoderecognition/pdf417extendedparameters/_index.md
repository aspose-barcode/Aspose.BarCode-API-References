---
title: "Aspose::BarCode::BarCodeRecognition::Pdf417ExtendedParameters فئة"
linktitle: "Pdf417ExtendedParameters"
second_title: "Aspose.BarCode للـ C++ مرجع API"
description: "Aspose::BarCode::BarCodeRecognition::Pdf417ExtendedParameters فئة. يخزن معلومات بيانات تعريفية لMacroPdf417 لباركود تم التعرف عليه في C++."
type: docs
weight: 2800
url: /ar/cpp/aspose.barcode.barcoderecognition/pdf417extendedparameters/
---
## Pdf417ExtendedParameters class


يخزن معلومات بيانات تعريفية لـ MacroPdf417 للباركود المُعترف به

```cpp
class Pdf417ExtendedParameters : public Aspose::BarCode::BarCodeRecognition::BaseExtendedParameters
```

## الطرق

| طريقة | الوصف |
| --- | --- |
| [get_IsCode128Emulation](./get_iscode128emulation/)() const | علامة تشير إلى أن باركود MicroPdf417 مشفر باستخدام كلمات محاكاة Code 128 908 أو 909 أو 910 أو 911. |
| [get_IsEmpty](../baseextendedparameters/get_isempty/)() const | **Tests** ما إذا كانت جميع المعلمات تحتوي فقط على القيم الافتراضية |
| [get_IsLinked](./get_islinked/)() const | علامة تشير إلى أن الباركود يجب ربطه بباركود 1D. |
| [get_IsReaderInitialization](./get_isreaderinitialization/)() const | يُستخدم لإرشاد القارئ لتفسير البيانات الموجودة داخل الرمز كبرمجة لتهيئة القارئ. |
| [get_MacroPdf417Addressee](./get_macropdf417addressee/)() const | اسم المستلم Macro PDF417 (اختياري). |
| [get_MacroPdf417Checksum](./get_macropdf417checksum/)() const | مجموع التحقق Macro PDF417 (اختياري). |
| [get_MacroPdf417FileID](./get_macropdf417fileid/)() const | يحصل على معرف الملف للباركود، متاح فقط مع MacroPdf417. |
| [get_MacroPdf417FileName](./get_macropdf417filename/)() const | اسم ملف Macro PDF417 (اختياري). |
| [get_MacroPdf417FileSize](./get_macropdf417filesize/)() const | حجم ملف Macro PDF417 (اختياري). |
| [get_MacroPdf417SegmentID](./get_macropdf417segmentid/)() const | يحصل على معرف الجزء للباركود، متاح فقط مع MacroPdf417. |
| [get_MacroPdf417SegmentsCount](./get_macropdf417segmentscount/)() const | يحصل على عدد أجزاء باركود macro pdf417. القيمة الافتراضية هي -1. |
| [get_MacroPdf417Sender](./get_macropdf417sender/)() const | اسم المرسل Macro PDF417 (اختياري). |
| [get_MacroPdf417Terminator](./get_macropdf417terminator/)() const | يشير إلى ما إذا كان الجزء هو الجزء الأخير من ملف Macro PDF417. |
| [get_MacroPdf417TimeStamp](./get_macropdf417timestamp/)() const | الطابع الزمني Macro PDF417 (اختياري). |
| [GetHashCode](./gethashcode/)() const override | يعيد قيمة التجزئة لهذه المثيلة. |
| [ToString](./tostring/)() const override | يرجع تمثيل سلسلة مقروءة للإنسان لهذا [Pdf417ExtendedParameters](./). |
## ملاحظات


هذا المثال يوضح كيفية الحصول على بيانات تعريفية لMacro Pdf417
```cpp
[C#]
using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MacroPdf417, "12345"))
{
    generator.Parameters.Barcode.Pdf417.Pdf417MacroFileID = 10;
    generator.Parameters.Barcode.Pdf417.Pdf417MacroSegmentsCount = 2;
    generator.Parameters.Barcode.Pdf417.Pdf417MacroSegmentID = 1;
    generator.Save(@"c:\test.png");
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.MacroPdf417))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
        Console.WriteLine("Macro Pdf417 FileID: " + result.Extended.Pdf417.MacroPdf417FileID);
        Console.WriteLine("Macro Pdf417 Segments: " + result.Extended.Pdf417.MacroPdf417SegmentsCount);
        Console.WriteLine("Macro Pdf417 SegmentID: " + result.Extended.Pdf417.MacroPdf417SegmentID);
    }
}
[VB.NET]
Using generator As New BarcodeGenerator(EncodeTypes.MacroPdf417, "12345")
    generator.Parameters.Barcode.Pdf417.Pdf417MacroFileID = 10
    generator.Parameters.Barcode.Pdf417.Pdf417MacroSegmentsCount = 2
    generator.Parameters.Barcode.Pdf417.Pdf417MacroSegmentID = 1
    generator.Save("c:\test.png")
End Using
Using reader As New BarCodeReader("c:\test.png", DecodeType.MacroPdf417)
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
        Console.WriteLine("Macro Pdf417 FileID: " + result.Extended.Pdf417.MacroPdf417FileID)
        Console.WriteLine("Macro Pdf417 Segments: " + result.Extended.Pdf417.MacroPdf417SegmentsCount)
        Console.WriteLine("Macro Pdf417 SegmentID: " + result.Extended.Pdf417.MacroPdf417SegmentID)
    Next
End Using
```

## انظر أيضًا

* Class [BaseExtendedParameters](../baseextendedparameters/)
* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
