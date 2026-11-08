---
title: "metot"
linktitle: "get_IgnoreEndingFillingPatternsForCTable"
second_title: "Aspose.BarCode for C++ API Referansı"
description: " metot. AustraliaPost kod çözücüsünün, CTable yöntemiyle kod çözme sırasında Müşteri Bilgisi Alanındaki son doldurma desenlerini yok saymasını zorlayan bayrak. CTable kodlama yöntemi kodlama tablosunda boşluk içermez ve \"333\" doldurma deseni C++'ta \"z\" harfi olarak çözülür."
type: docs
weight: 300
url: /tr/cpp/aspose.barcode.barcoderecognition/australiapostsettings/get_ignoreendingfillingpatternsforctable/
---
## AustraliaPostSettings::get_IgnoreEndingFillingPatternsForCTable method


Müşteri Bilgi Alanı'nda CTable yöntemiyle çözümleme sırasında AustraliaPost çözücüsünün son doldurma desenlerini yok saymasını zorlayan bayrak. CTable kodlama yöntemi kodlama tablosunda boşluk içermez ve "333" doldurma deseni dizisi "z" harfi olarak çözülür.

```cpp
bool Aspose::BarCode::BarCodeRecognition::AustraliaPostSettings::get_IgnoreEndingFillingPatternsForCTable() const
```

## Açıklamalar


CTable yöntemiyle kod çözme sırasında AustraliaPost kod çözücünün son doldurma desenlerini yok saymasını zorlayan bayrak

Bu örnek, CTable Yorumlama Türü ve doldurma desenlerini yok sayarak Australia Post barkodunun nasıl oluşturulup tanınacağını gösterir.
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

## Ayrıca Bakınız

* Class [AustraliaPostSettings](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
