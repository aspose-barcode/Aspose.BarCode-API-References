---
title: "enum"
linktitle: "CustomerInformationInterpretingType"
second_title: "Aspose.BarCode for C++ API-referentie"
description: " enum. Definieert het interpretatietype (CTable, NTable of Other) van klantinformatie voor AustralianPost BarCode in C++."
type: docs
weight: 700
url: /nl/cpp/aspose.barcode/customerinformationinterpretingtype/
---
## CustomerInformationInterpretingType enum


Definieert het interpretatietype (CTable, NTable of Other) van klantinformatie voor AustralianPost [BarCode](../).

```cpp
enum class CustomerInformationInterpretingType
```

### Waarden

| Naam | Waarde | Beschrijving |
| --- | --- | --- |
| CTable | 0 | Gebruik CTable om de klantinformatie te interpreteren. Staat A..Z, a..z, 1..9, spatie en # teken toe. |
| NTable | 1 | Gebruik NTable om de klantinformatie te interpreteren. Staat cijfers toe. |
| Other | 2 | Interpreteer de klantinformatie niet. Staat alleen het symbool 0, 1, 2 of 3 toe. |

## Opmerkingen


Deze voorbeelden tonen hoe je een Australia Post barcode kunt genereren en herkennen
```cpp
    [C#]
//Dit voorbeeld toont hoe je een Australia Post barcode kunt genereren en herkennen met CTable Interpreting Type.
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
//Dit voorbeeld laat zien hoe u een Australia Post barcode kunt genereren en herkennen zonder Customer Interpreting Type.
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

## Zie ook

* Namespace [Aspose::BarCode](../)
* Library [Aspose.BarCode for C++](../../)
