---
title: IgnoreEndingFillingPatternsForCTable
second_title: Aspose.BarCode för .NET API-referens
description: Flaggan som tvingar AustraliaPost-avkodaren att ignorera senaste fyllningsmönster i kundinformationsfältet under avkodning som CTable-metod. CTable-kodningsmetoden har inga luckor i kodningstabellen och sekvens 333 av fyllningsmönster avkodas som bokstaven z.
type: docs
weight: 30
url: /sv/net/aspose.barcode.barcoderecognition/australiapostsettings/ignoreendingfillingpatternsforctable/
---
## AustraliaPostSettings.IgnoreEndingFillingPatternsForCTable property

Flaggan som tvingar AustraliaPost-avkodaren att ignorera senaste fyllningsmönster i kundinformationsfältet under avkodning som CTable-metod. CTable-kodningsmetoden har inga luckor i kodningstabellen och sekvens "333" av fyllningsmönster avkodas som bokstaven "z".

```csharp
public bool IgnoreEndingFillingPatternsForCTable { get; set; }
```

### Fastighetsvärde

Flaggan som tvingar AustraliaPost-avkodaren att ignorera de senaste fyllningsmönstren under CTable-metodens avkodning

### Exempel

Det här exemplet visar hur man genererar och känner igen streckkoden för Australia Post med CTable Interpreting Type och ignorerar fyllningsmönster.

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

### Se även

* class [AustraliaPostSettings](../../australiapostsettings)
* namnutrymme [Aspose.BarCode.BarCodeRecognition](../../australiapostsettings)
* hopsättning [Aspose.BarCode](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->
