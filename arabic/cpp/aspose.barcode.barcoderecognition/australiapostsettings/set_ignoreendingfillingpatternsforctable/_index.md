---
title: "طريقة"
linktitle: "set_IgnoreEndingFillingPatternsForCTable"
second_title: "Aspose.BarCode للـ C++ مرجع API"
description: "طريقة. العلامة التي تجبر فك ترميز AustraliaPost على تجاهل أنماط التعبئة الأخيرة في حقل معلومات العميل أثناء الفك كطريقة CTable. طريقة ترميز CTable لا تحتوي على أي فجوات في جدول الترميز وتُفسَّر السلسلة \\\"333\\\" من أنماط التعبئة كحرف \\\"z\\\" في C++."
type: docs
weight: 400
url: /ar/cpp/aspose.barcode.barcoderecognition/australiapostsettings/set_ignoreendingfillingpatternsforctable/
---
## AustraliaPostSettings::set_IgnoreEndingFillingPatternsForCTable method


العلم الذي يجبر فك ترميز AustraliaPost على تجاهل أنماط التعبئة الأخيرة في حقل معلومات العميل أثناء الفك كطريقة CTable. طريقة ترميز CTable لا تحتوي على أي فجوات في جدول الترميز وتسلسل "333" لأنماط التعبئة يتم فك ترميزه كحرف "z".

```cpp
void Aspose::BarCode::BarCodeRecognition::AustraliaPostSettings::set_IgnoreEndingFillingPatternsForCTable(bool value)
```

## ملاحظات


العلامة التي تجبر فك ترميز AustraliaPost على تجاهل أنماط التعبئة الأخيرة أثناء فك ترميز طريقة CTable

يوضح هذا المثال كيفية إنشاء وتعرف على باركود Australia Post باستخدام نوع تفسير CTable وتجاهل أنماط التعبئة.
```cpp
    [C#]
using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.AustraliaPost, "5912345678AB"))
{
    generator.Parameters.Barcode.AustralianPost.AustralianPostEncodingTable = CustomerInformationInterpretingType.CTable;
    using (Bitmap image = generator.GenerateBarCodeImage())
    using (BarCodeReader reader = new BarCodeReader(image, DecodeType.AustraliaPost))
     {
        reader.BarcodeSettings.AustraliaPost.CustomerInformationInterpretingType = CustomerInformationInterpretingType.CTable;
        reader.BarcodeSettings.AustraliaPost.IgnoreEndingFillingPatternsForCTable = true;
        foreach (BarCodeResult result in reader.ReadBarCodes())
        {
            Console.WriteLine("BarCode Type: " + result.CodeType);
            Console.WriteLine("BarCode CodeText: " + result.CodeText);
        }
    }
}
[VB.NET]
Using generator As New BarcodeGenerator(EncodeTypes.AustraliaPost, "5912345678AB")
    generator.Parameters.Barcode.AustralianPost.AustralianPostEncodingTable = CustomerInformationInterpretingType.CTable
    Using image As Bitmap = generator.GenerateBarCodeImage()
        Using reader As New BarCodeReader(image, DecodeType.AustraliaPost)
            reader.BarcodeSettings.AustraliaPost.CustomerInformationInterpretingType = CustomerInformationInterpretingType.CTable
            reader.BarcodeSettings.AustraliaPost.IgnoreEndingFillingPatternsForCTable = True
            For Each result As BarCodeResult In reader.ReadBarCodes()
                Console.WriteLine("BarCode Type: " + result.CodeTypeName)
                Console.WriteLine("BarCode CodeText: " + result.CodeText)
            Next
        End Using
    End Using
End Using
```

## انظر أيضًا

* Class [AustraliaPostSettings](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
