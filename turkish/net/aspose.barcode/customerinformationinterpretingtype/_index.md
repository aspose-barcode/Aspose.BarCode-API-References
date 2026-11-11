---
title: "Enum CustomerInformationInterpretingType"
second_title: "Aspose.BarCode for .NET API Referansı"
description: "Aspose.BarCode.CustomerInformationInterpretingType enum. AustralianPost Barkodu için müşteri bilgilerinin CTable, NTable veya Diğer yorumlama tipini tanımlar"
type: docs
weight: 910
url: /tr/net/aspose.barcode/customerinformationinterpretingtype/
---
## CustomerInformationInterpretingType enumeration

AustralianPost Barkod için müşteri bilgilerinin yorumlama türünü (CTable, NTable veya Diğer) tanımlar.

```csharp
public enum CustomerInformationInterpretingType
```

### Değerler

| Ad | Değer | Açıklama |
| --- | --- | --- |
| CTable | `0` | Müşteri bilgilerini yorumlamak için CTable kullanın. A..Z, a..z, 1..9, boşluk ve # işaretine izin verir. |
| NTable | `1` | Müşteri bilgilerini yorumlamak için NTable kullanın. Rakamları izin verir. |
| Other | `2` | Müşteri bilgilerini yorumlamayın. Yalnızca 0, 1, 2 veya 3 sembolüne izin verir. |

## Örnekler

Bu örnekler, Australia Post barkodunun nasıl oluşturulacağını ve tanınacağını gösterir

```csharp
[C#]
//Bu örnek, CTable Yorumlama Tipi ile Australia Post barkodunun nasıl oluşturulacağını ve tanınacağını gösterir.
using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.AustraliaPost, "5912345678ABCde"))
{
    generator.Parameters.Barcode.AustralianPost.AustralianPostEncodingTable = CustomerInformationInterpretingType.CTable;
    using (Bitmap image = generator.GenerateBarCodeImage())
    using (BarCodeReader reader = new BarCodeReader(image, DecodeType.AustraliaPost))
     {
        reader.BarcodeSettings.AustraliaPost.CustomerInformationInterpretingType = CustomerInformationInterpretingType.CTable;
        foreach (BarCodeResult result in reader.ReadBarCodes())
        {
            Console.WriteLine("BarCode Type: " + result.CodeType);
            Console.WriteLine("BarCode CodeText: " + result.CodeText);
        }
    }
}
[VB.NET]
Using generator As New BarcodeGenerator(EncodeTypes.AustraliaPost, "5912345678ABCde")
    generator.Parameters.Barcode.AustralianPost.AustralianPostEncodingTable = CustomerInformationInterpretingType.CTable
    Using image As Bitmap = generator.GenerateBarCodeImage()
        Using reader As New BarCodeReader(image, DecodeType.AustraliaPost)
            reader.BarcodeSettings.AustraliaPost.CustomerInformationInterpretingType = CustomerInformationInterpretingType.CTable
            For Each result As BarCodeResult In reader.ReadBarCodes()
                Console.WriteLine("BarCode Type: " + result.CodeTypeName)
                Console.WriteLine("BarCode CodeText: " + result.CodeText)
            Next
        End Using
    End Using
End Using
//Bu örnek, Müşteri Yorumlama Tipi olmadan Australia Post barkodunun nasıl oluşturulacağını ve tanınacağını gösterir
[C#]
using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.AustraliaPost, "59123456780123012301230123"))
{
    generator.Parameters.Barcode.AustralianPost.AustralianPostEncodingTable = CustomerInformationInterpretingType.Other;
    using (Bitmap image = generator.GenerateBarCodeImage())
    using (BarCodeReader reader = new BarCodeReader(image, DecodeType.AustraliaPost))
     {
        reader.BarcodeSettings.AustraliaPost.CustomerInformationInterpretingType = CustomerInformationInterpretingType.Other;
        foreach (BarCodeResult result in reader.ReadBarCodes())
        {
            Console.WriteLine("BarCode Type: " + result.CodeType);
            Console.WriteLine("BarCode CodeText: " + result.CodeText);
        }
    }
}
[VB.NET]
Using generator As New BarcodeGenerator(EncodeTypes.AustraliaPost, "59123456780123012301230123")
    generator.Parameters.Barcode.AustralianPost.AustralianPostEncodingTable = CustomerInformationInterpretingType.Other
    Using image As Bitmap = generator.GenerateBarCodeImage()
        Using reader As New BarCodeReader(image, DecodeType.AustraliaPost)
            reader.BarcodeSettings.AustraliaPost.CustomerInformationInterpretingType = CustomerInformationInterpretingType.Other
            For Each result As BarCodeResult In reader.ReadBarCodes()
                Console.WriteLine("BarCode Type: " + result.CodeTypeName)
                Console.WriteLine("BarCode CodeText: " + result.CodeText)
            Next
        End Using
    End Using
End Using
```

### Ayrıca Bakınız

* namespace [Aspose.BarCode](../../aspose.barcode/)
* assembly [Aspose.BarCode](../../)


