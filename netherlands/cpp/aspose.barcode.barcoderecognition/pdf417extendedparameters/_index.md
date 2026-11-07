---
title: "Aspose::BarCode::BarCodeRecognition::Pdf417ExtendedParameters klasse"
linktitle: "Pdf417ExtendedParameters"
second_title: "Aspose.BarCode for C++ API-referentie"
description: "Aspose::BarCode::BarCodeRecognition::Pdf417ExtendedParameters klasse. Slaat een MacroPdf417-metadata-informatie op van een herkende barcode in C++."
type: docs
weight: 2800
url: /nl/cpp/aspose.barcode.barcoderecognition/pdf417extendedparameters/
---
## Pdf417ExtendedParameters class


Slaat macroPdf417-metadata-informatie van herkende barcode op

```cpp
class Pdf417ExtendedParameters : public Aspose::BarCode::BarCodeRecognition::BaseExtendedParameters
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| [get_IsCode128Emulation](./get_iscode128emulation/)() const | Vlag die aangeeft dat de MicroPdf417-barcode is gecodeerd met 908, 909, 910 of 911 Code 128-emulatiecodewoorden. |
| [get_IsEmpty](../baseextendedparameters/get_isempty/)() const | **Test** of alle parameters alleen standaardwaarden hebben |
| [get_IsLinked](./get_islinked/)() const | Vlag die aangeeft dat de barcode moet worden gekoppeld aan een 1D-barcode. |
| [get_IsReaderInitialization](./get_isreaderinitialization/)() const | Wordt gebruikt om de lezer te instrueren de gegevens in het symbool te interpreteren als programmering voor lezerinitialisatie. |
| [get_MacroPdf417Addressee](./get_macropdf417addressee/)() const | Macro PDF417-ontvangernaam (optioneel). |
| [get_MacroPdf417Checksum](./get_macropdf417checksum/)() const | Macro PDF417-checksum (optioneel). |
| [get_MacroPdf417FileID](./get_macropdf417fileid/)() const | Haalt de bestands-ID van de barcode op, alleen beschikbaar met MacroPdf417. |
| [get_MacroPdf417FileName](./get_macropdf417filename/)() const | Macro PDF417-bestandsnaam (optioneel). |
| [get_MacroPdf417FileSize](./get_macropdf417filesize/)() const | Macro PDF417-bestandsgrootte (optioneel). |
| [get_MacroPdf417SegmentID](./get_macropdf417segmentid/)() const | Haalt de segment-ID van de barcode op, alleen beschikbaar met MacroPdf417. |
| [get_MacroPdf417SegmentsCount](./get_macropdf417segmentscount/)() const | Haalt het aantal segmenten van de macro pdf417-barcode op. Standaardwaarde is -1. |
| [get_MacroPdf417Sender](./get_macropdf417sender/)() const | Macro PDF417-afzendernaam (optioneel). |
| [get_MacroPdf417Terminator](./get_macropdf417terminator/)() const | Geeft aan of het segment het laatste segment van een Macro PDF417-bestand is. |
| [get_MacroPdf417TimeStamp](./get_macropdf417timestamp/)() const | Macro PDF417-tijdstempel (optioneel). |
| [GetHashCode](./gethashcode/)() const override | Retourneert de hashcode voor deze instantie. |
| [ToString](./tostring/)() const override | Retourneert een menselijk leesbare tekenreeksrepresentatie van deze [Pdf417ExtendedParameters](./). |
## Opmerkingen


Dit voorbeeld toont hoe u Macro Pdf417-metadata kunt ophalen.
```cpp
[C#]
using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MacroPdf417, "12345"))
{
    generator.Parameters.Barcode.Pdf417.Pdf417MacroFileID = 10;
    generator.Parameters.Barcode.Pdf417.Pdf417MacroSegmentsCount = 2;
    generator.Parameters.Barcode.Pdf417.Pdf417MacroSegmentID = 1;
    generator.Save(@"c:\test.png");
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.MacroPdf417))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
        Console.WriteLine("Macro Pdf417 FileID: " + result.Extended.Pdf417.MacroPdf417FileID);
        Console.WriteLine("Macro Pdf417 Segments: " + result.Extended.Pdf417.MacroPdf417SegmentsCount);
        Console.WriteLine("Macro Pdf417 SegmentID: " + result.Extended.Pdf417.MacroPdf417SegmentID);
    }
}
[VB.NET]
Using generator As New BarcodeGenerator(EncodeTypes.MacroPdf417, "12345")
    generator.Parameters.Barcode.Pdf417.Pdf417MacroFileID = 10
    generator.Parameters.Barcode.Pdf417.Pdf417MacroSegmentsCount = 2
    generator.Parameters.Barcode.Pdf417.Pdf417MacroSegmentID = 1
    generator.Save("c:\test.png")
End Using
Using reader As New BarCodeReader("c:\test.png", DecodeType.MacroPdf417)
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
        Console.WriteLine("Macro Pdf417 FileID: " + result.Extended.Pdf417.MacroPdf417FileID)
        Console.WriteLine("Macro Pdf417 Segments: " + result.Extended.Pdf417.MacroPdf417SegmentsCount)
        Console.WriteLine("Macro Pdf417 SegmentID: " + result.Extended.Pdf417.MacroPdf417SegmentID)
    Next
End Using
```

## Zie ook

* Class [BaseExtendedParameters](../baseextendedparameters/)
* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
