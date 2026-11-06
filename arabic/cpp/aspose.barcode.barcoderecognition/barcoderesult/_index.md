---
title: "فئة Aspose::BarCode::BarCodeRecognition::BarCodeResult"
linktitle: "BarCodeResult"
second_title: "Aspose.BarCode للـ C++ مرجع API"
description: "فئة Aspose::BarCode::BarCodeRecognition::BarCodeResult. تخزن بيانات الباركود التي تم التعرف عليها مثل النوع SingleDecodeType، System::String codetext، BarCodeRegionParameters region وغيرها من المعلمات في C++."
type: docs
weight: 700
url: /ar/cpp/aspose.barcode.barcoderecognition/barcoderesult/
---
## BarCodeResult class


تخزن بيانات الباركود التي تم التعرف عليها مثل النوع [SingleDecodeType](../singledecodetype/) ، **System::String** codetext ، [BarCodeRegionParameters](../barcoderegionparameters/) region وغيرها من المعلمات

```cpp
class BarCodeResult : public System::ICloneable,
                      public System::IEquatable<System::SharedPtr<BarCodeResult>>
```

## الطرق

| طريقة | الوصف |
| --- | --- |
| [BarCodeResult](./barcoderesult/)(System::SharedPtr\<BarCodeResult\>) | ينشئ نسخة من الفئة [BarCodeResult](./). |
| [Clone](./clone/)() override | ينشئ نسخة من الفئة [BarCodeResult](./). |
| [Equals](./equals/)(System::SharedPtr\<BarCodeResult\>) override | يعيد قيمة تشير إلى ما إذا كانت هذه المثيلة مساوية لقيمة [BarCodeResult](./) المحددة. |
| [get_CodeBytes](./get_codebytes/)() const | يحصل على بايتات الشيفرة المشفرة |
| [get_CodeText](./get_codetext/)() const | يحصل على نص الشيفرة |
| [get_CodeType](./get_codetype/)() const | يحصل على نوع الباركود |
| [get_CodeTypeName](./get_codetypename/)() | يحصل على اسم نوع الباركود |
| [get_Confidence](./get_confidence/)() const | يحصل على مستوى ثقة التعرف للباركود الذي تم التعرف عليه |
| [get_Extended](./get_extended/)() const | يحصل على المعلمات الموسعة للباركود الذي تم التعرف عليه |
| [get_IsoSymbolQuality](./get_isosymbolquality/)() const | يحصل على نتائج تقييم جودة الرمز ISO/IEC للباركود الذي تم التعرف عليه. |
| [get_ReadingQuality](./get_readingquality/)() const | يحصل على جودة القراءة. يعمل مع الباركودات أحادية البعد والبريدية. |
| [get_Region](./get_region/)() const | يحصل على منطقة الباركود |
| [GetCodeText](./getcodetext/)(System::SharedPtr\<System::Text::Encoding\>) | يحصل على نص الشيفرة مع الترميز. |
| [GetHashCode](./gethashcode/)() const override | يعيد قيمة التجزئة لهذه المثيلة. |
| [ToString](./tostring/)() const override | يعيد تمثيلًا نصيًا مقروءًا للإنسان لهذا [BarCodeResult](./). |
## ملاحظات


يعرض هذا المثال كيفية الحصول على [BarCodeResult](./).
```cpp
[C#]
using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Code128, "12345"))
{
    generator.Save(@"c:\test.png");
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39, DecodeType.Code128))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
        Console.WriteLine("BarCode Confidence: " + result.Confidence);
        Console.WriteLine("BarCode ReadingQuality: " + result.ReadingQuality);
        Console.WriteLine("BarCode Angle: " + result.Region.Angle);
    }
}
[VB.NET]
Using generator As New BarcodeGenerator(EncodeTypes.Code128, "12345")
    generator.Save("c:\test.png")
End Using
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39, DecodeType.Code128)
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
        Console.WriteLine("BarCode Confidence: " + result.Confidence)
        Console.WriteLine("BarCode ReadingQuality: " + result.ReadingQuality)
        Console.WriteLine("BarCode Angle: " + result.Region.Angle)
    Next
End Using
```

## انظر أيضًا

* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
