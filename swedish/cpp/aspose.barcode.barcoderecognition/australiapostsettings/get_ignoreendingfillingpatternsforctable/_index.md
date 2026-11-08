---
title: "metod"
linktitle: "get_IgnoreEndingFillingPatternsForCTable"
second_title: "Aspose.BarCode for C++ API-referens"
description: "metod. Flaggan som tvingar AustraliaPost‑avkodaren att ignorera sista fyllningsmönstren i kundinformationsfältet under avkodning som CTable‑metod. CTable‑kodningsmetoden har inga luckor i kodningstabellen och sekvensen \"333\" av fyllningsmönster avkodas som bokstaven \"z\" i C++."
type: docs
weight: 300
url: /sv/cpp/aspose.barcode.barcoderecognition/australiapostsettings/get_ignoreendingfillingpatternsforctable/
---
## AustraliaPostSettings::get_IgnoreEndingFillingPatternsForCTable method


Flaggan som tvingar AustraliaPost-avkodaren att ignorera de sista fyllningsmönstren i Customer Information Field under avkodning som CTable-metod. CTable-kodningsmetoden har inga luckor i kodningstabellen och sekvensen "333" av fyllningsmönster avkodas som bokstaven "z".

```cpp
bool Aspose::BarCode::BarCodeRecognition::AustraliaPostSettings::get_IgnoreEndingFillingPatternsForCTable() const
```

## Anmärkningar


Flaggan som tvingar AustraliaPost‑avkodaren att ignorera sista fyllningsmönstren under CTable‑metodens avkodning

Detta exempel visar hur man genererar och läser av Australia Post‑streckkod med CTable‑tolkningstyp och ignorerar fyllningsmönster.
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

## Se även

* Class [AustraliaPostSettings](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
