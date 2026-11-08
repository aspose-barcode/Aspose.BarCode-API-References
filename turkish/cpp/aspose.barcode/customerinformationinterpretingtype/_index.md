---
title: "enum"
linktitle: "CustomerInformationInterpretingType"
second_title: "Aspose.BarCode for C++ API Referansı"
description: " enum. AustralianPost BarCode için müşteri bilgilerinin yorumlama tipini (CTable, NTable veya Other) C++'da tanımlar."
type: docs
weight: 700
url: /tr/cpp/aspose.barcode/customerinformationinterpretingtype/
---
## CustomerInformationInterpretingType enum


AustralianPost [BarCode](../) için müşteri bilgilerinin yorumlama tipini (CTable, NTable veya Other) tanımlar.

```cpp
enum class CustomerInformationInterpretingType
```

### Değerler

| Ad | Değer | Açıklama |
| --- | --- | --- |
| CTable | 0 | Müşteri bilgisini yorumlamak için CTable kullanın. A..Z, a..z, 1..9, boşluk ve # işaretine izin verir. |
| NTable | 1 | Müşteri bilgisini yorumlamak için NTable kullanın. Rakamları içerir. |
| Other | 2 | Müşteri bilgisini yorumlamayın. Yalnızca 0, 1, 2 veya 3 sembolüne izin verir. |

## Açıklamalar


Bu örnekler, Australia Post barkodunun nasıl oluşturulup tanınacağını gösterir.
```cpp
    [C#]
//Bu örnek, Australia Post barkodunun CTable Yorumlama Tipi ile nasıl oluşturulup tanınacağını gösterir.
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
//Bu örnek, Müşteri Yorumlama Türü olmadan Australia Post barkodunu nasıl oluşturup tanıyacağını gösterir.
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

## Ayrıca Bakınız

* Namespace [Aspose::BarCode](../)
* Library [Aspose.BarCode for C++](../../)
