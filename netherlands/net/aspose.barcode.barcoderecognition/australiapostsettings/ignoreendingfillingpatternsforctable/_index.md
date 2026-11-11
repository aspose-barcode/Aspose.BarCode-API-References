---
title: "AustraliaPostSettings.IgnoreEndingFillingPatternsForCTable"
second_title: "Aspose.BarCode voor .NET API‑referentie"
description: "AustraliaPostSettings‑eigenschap. De vlag die de AustraliaPost-decoder dwingt de laatste vullingspatronen in het klantinformatie‑veld te negeren tijdens decodering met de CTable‑methode. De CTable‑coderingmethode heeft geen gaten in de coderingstabel en de reeks 333 van vullingspatronen wordt gedecodeerd als de letter z."
type: docs
weight: 30
url: /nl/net/aspose.barcode.barcoderecognition/australiapostsettings/ignoreendingfillingpatternsforctable/
---
## AustraliaPostSettings.IgnoreEndingFillingPatternsForCTable property

De vlag die de AustraliaPost-decoder dwingt om de laatste vulpatronen in het Customer Information Field te negeren tijdens het decoderen volgens de CTable-methode. De CTable-coderingmethode heeft geen gaten in de coderingstabel en de reeks "333" van vulpatronen wordt gedecodeerd als de letter "z".

```csharp
public bool IgnoreEndingFillingPatternsForCTable { get; set; }
```

### Property Value

De vlag die de AustraliaPost-decoder dwingt de laatste vullingspatronen te negeren tijdens decodering met de CTable‑methode

## Voorbeelden

Dit voorbeeld toont hoe je een Australia Post-barcode kunt genereren en herkennen met CTable‑interpretatietype en het negeren van vullingspatronen.

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

### Zie ook

* class [AustraliaPostSettings](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)


