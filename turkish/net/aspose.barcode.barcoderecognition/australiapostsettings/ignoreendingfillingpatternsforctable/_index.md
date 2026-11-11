---
title: "AustraliaPostSettings.IgnoreEndingFillingPatternsForCTable"
second_title: "Aspose.BarCode for .NET API Referansı"
description: "AustraliaPostSettings özelliği. AustraliaPost kod çözücünün CTable yöntemiyle kod çözme sırasında Müşteri Bilgi Alanındaki son doldurma desenlerini yok saymasını zorlayan bayrak. CTable kodlama yöntemi kodlama tablosunda boşluk içermez ve doldurma desenleri dizisi 333, z harfi olarak çözülür."
type: docs
weight: 30
url: /tr/net/aspose.barcode.barcoderecognition/australiapostsettings/ignoreendingfillingpatternsforctable/
---
## AustraliaPostSettings.IgnoreEndingFillingPatternsForCTable property

AustraliaPost çözücüsünün, Customer Information Field içindeki son doldurma desenlerini CTable yöntemiyle kod çözme sırasında yok saymasını zorlayan bayrak. CTable kodlama yöntemi kodlama tablosunda boşluk içermez ve "333" doldurma deseni dizisi "z" harfi olarak kod çözülür.

```csharp
public bool IgnoreEndingFillingPatternsForCTable { get; set; }
```

### Property Value

CTable yöntemiyle kod çözme sırasında AustraliaPost kod çözücünün son doldurma desenlerini yok saymasını zorlayan bayrak

## Örnekler

Bu örnek, CTable Yorumlama Türü ve doldurma desenlerini yok sayarak Australia Post barkodu oluşturma ve tanıma yöntemini gösterir.

```csharp
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

### Ayrıca Bakınız

* class [AustraliaPostSettings](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)


