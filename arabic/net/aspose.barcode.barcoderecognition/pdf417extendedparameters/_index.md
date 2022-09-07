---
title: Pdf417ExtendedParameters
second_title: Aspose.BarCode لمرجع .NET API
description: يخزن معلومات بيانات تعريف MacroPdf417 للرمز الشريطي المعترف به
type: docs
weight: 220
url: /ar/net/aspose.barcode.barcoderecognition/pdf417extendedparameters/
---
## Pdf417ExtendedParameters class

يخزن معلومات بيانات تعريف MacroPdf417 للرمز الشريطي المعترف به

```csharp
public sealed class Pdf417ExtendedParameters : BaseExtendedParameters
```

## الخصائص

| اسم | وصف |
| --- | --- |
| [IsEmpty](../../aspose.barcode.barcoderecognition/baseextendedparameters/isempty) { get; } | يختبر ما إذا كانت جميع المعلمات تحتوي على قيم افتراضية فقط |
| [MacroPdf417Addressee](../../aspose.barcode.barcoderecognition/pdf417extendedparameters/macropdf417addressee) { get; } | ماكرو PDF417 اسم المرسل إليه (اختياري). |
| [MacroPdf417Checksum](../../aspose.barcode.barcoderecognition/pdf417extendedparameters/macropdf417checksum) { get; } | المجموع الاختباري Macro PDF417 (اختياري). |
| [MacroPdf417FileID](../../aspose.barcode.barcoderecognition/pdf417extendedparameters/macropdf417fileid) { get; } | يحصل على معرف ملف الرمز الشريطي ، المتاح فقط مع MacroPdf417. |
| [MacroPdf417FileName](../../aspose.barcode.barcoderecognition/pdf417extendedparameters/macropdf417filename) { get; } | اسم ملف Macro PDF417 (اختياري). |
| [MacroPdf417FileSize](../../aspose.barcode.barcoderecognition/pdf417extendedparameters/macropdf417filesize) { get; } | حجم ملف ماكرو PDF417 (اختياري). |
| [MacroPdf417SegmentID](../../aspose.barcode.barcoderecognition/pdf417extendedparameters/macropdf417segmentid) { get; } | الحصول على معرف مقطع الباركود ، متاح فقط مع MacroPdf417. |
| [MacroPdf417SegmentsCount](../../aspose.barcode.barcoderecognition/pdf417extendedparameters/macropdf417segmentscount) { get; } | الحصول على عدد مقاطع الباركود pdf417 الماكرو. القيمة الافتراضية هي -1. |
| [MacroPdf417Sender](../../aspose.barcode.barcoderecognition/pdf417extendedparameters/macropdf417sender) { get; } | اسم مرسل Macro PDF417 (اختياري). |
| [MacroPdf417TimeStamp](../../aspose.barcode.barcoderecognition/pdf417extendedparameters/macropdf417timestamp) { get; } | طابع زمني ماكرو PDF417 (اختياري). |

## طُرق

| اسم | وصف |
| --- | --- |
| override [Equals](../../aspose.barcode.barcoderecognition/pdf417extendedparameters/equals)(object) | إرجاع قيمة تشير إلى ما إذا كان هذا المثيل يساوي قيمة محددة[`Pdf417ExtendedParameters`](../pdf417extendedparameters) القيمة . |
| override [GetHashCode](../../aspose.barcode.barcoderecognition/pdf417extendedparameters/gethashcode)() | إرجاع رمز التجزئة لهذا المثال. |
| override [ToString](../../aspose.barcode.barcoderecognition/pdf417extendedparameters/tostring)() | إرجاع تمثيل سلسلة يمكن قراءته من قبل الإنسان[`Pdf417ExtendedParameters`](../pdf417extendedparameters) . |
| [operator ==](../../aspose.barcode.barcoderecognition/pdf417extendedparameters/op_equality) | تُرجع قيمة تشير إلى ما إذا كان الأول[`Pdf417ExtendedParameters`](../pdf417extendedparameters) القيمة تساوي الثانية. |
| [operator !=](../../aspose.barcode.barcoderecognition/pdf417extendedparameters/op_inequality) | إرجاع قيمة تشير إلى ما إذا كان الأول[`Pdf417ExtendedParameters`](../pdf417extendedparameters) القيمة مختلفة عن الثانية. |

### أمثلة

يوضح هذا النموذج كيفية الحصول على بيانات تعريف Macro Pdf417

```csharp
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

### أنظر أيضا

* class [BaseExtendedParameters](../baseextendedparameters)
* مساحة الاسم [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition)
* المجسم [Aspose.BarCode](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->
