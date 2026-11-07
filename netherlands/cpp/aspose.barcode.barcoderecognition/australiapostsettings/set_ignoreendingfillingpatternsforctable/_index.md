---
title: "methode"
linktitle: "set_IgnoreEndingFillingPatternsForCTable"
second_title: "Aspose.BarCode for C++ API-referentie"
description: " methode. De vlag die de AustraliaPost-decoder dwingt de laatste vulpatronen in het klantinformatieveld te negeren tijdens het decoderen als CTable-methode. De CTable-coderingsmethode heeft geen gaten in de coderingtabel en de reeks \"333\" van vulpatronen wordt gedecodeerd als letter \"z\" in C++."
type: docs
weight: 400
url: /nl/cpp/aspose.barcode.barcoderecognition/australiapostsettings/set_ignoreendingfillingpatternsforctable/
---
## AustraliaPostSettings::set_IgnoreEndingFillingPatternsForCTable method


De vlag die de AustraliaPost-decoder dwingt om de laatste vulpatronen in het Customer Information Field te negeren tijdens decodering volgens de CTable-methode. De CTable-coderingsmethode heeft geen gaten in de coderingstabel en de reeks "333" van vulpatronen wordt gedecodeerd als de letter "z".

```cpp
void Aspose::BarCode::BarCodeRecognition::AustraliaPostSettings::set_IgnoreEndingFillingPatternsForCTable(bool value)
```

## Opmerkingen


De vlag die de AustraliaPost-decoder dwingt de laatste vulpatronen te negeren tijdens het decoderen met de CTable-methode

Dit voorbeeld toont hoe een Australia Post-barcode te genereren en te herkennen met CTable-interpretatietype en het negeren van vulpatronen.
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

## Zie ook

* Class [AustraliaPostSettings](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
