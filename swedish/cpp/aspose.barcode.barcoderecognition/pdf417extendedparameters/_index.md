---
title: "Aspose::BarCode::BarCodeRecognition::Pdf417ExtendedParameters klass"
linktitle: "Pdf417ExtendedParameters"
second_title: "Aspose.BarCode for C++ API-referens"
description: "Aspose::BarCode::BarCodeRecognition::Pdf417ExtendedParameters klass. Lagrar metadatainformation för MacroPdf417 för erkänd streckkod i C++."
type: docs
weight: 2800
url: /sv/cpp/aspose.barcode.barcoderecognition/pdf417extendedparameters/
---
## Pdf417ExtendedParameters class


Lagrar metadatainformation för MacroPdf417 för den igenkända streckkoden.

```cpp
class Pdf417ExtendedParameters : public Aspose::BarCode::BarCodeRecognition::BaseExtendedParameters
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [get_IsCode128Emulation](./get_iscode128emulation/)() const | Flagga som indikerar att MicroPdf417‑streckkoden är kodad med 908, 909, 910 eller 911 Code 128‑emuleringskodord. |
| [get_IsEmpty](../baseextendedparameters/get_isempty/)() const | **Testar** om alla parametrar endast har standardvärden |
| [get_IsLinked](./get_islinked/)() const | Flagga som indikerar att streckkoden måste länkas till 1D‑streckkod. |
| [get_IsReaderInitialization](./get_isreaderinitialization/)() const | Används för att instruera läsaren att tolka data som finns i symbolen som programmering för läsarinitialisering. |
| [get_MacroPdf417Addressee](./get_macropdf417addressee/)() const | Macro PDF417‑mottagarnamn (valfritt). |
| [get_MacroPdf417Checksum](./get_macropdf417checksum/)() const | Macro PDF417‑kontrollsumma (valfritt). |
| [get_MacroPdf417FileID](./get_macropdf417fileid/)() const | Hämtar fil‑ID för streckkoden, endast tillgängligt med MacroPdf417. |
| [get_MacroPdf417FileName](./get_macropdf417filename/)() const | Macro PDF417‑filnamn (valfritt). |
| [get_MacroPdf417FileSize](./get_macropdf417filesize/)() const | Macro PDF417‑filstorlek (valfritt). |
| [get_MacroPdf417SegmentID](./get_macropdf417segmentid/)() const | Hämtar segment‑ID för streckkoden, endast tillgängligt med MacroPdf417. |
| [get_MacroPdf417SegmentsCount](./get_macropdf417segmentscount/)() const | Hämtar antalet segment för macro pdf417‑streckkod. Standardvärdet är -1. |
| [get_MacroPdf417Sender](./get_macropdf417sender/)() const | Macro PDF417‑avsändarnamn (valfritt). |
| [get_MacroPdf417Terminator](./get_macropdf417terminator/)() const | Indikerar om segmentet är det sista segmentet i en Macro PDF417‑fil. |
| [get_MacroPdf417TimeStamp](./get_macropdf417timestamp/)() const | Macro PDF417‑tidsstämpel (valfritt). |
| [GetHashCode](./gethashcode/)() const override | Returnerar hash‑koden för detta objekt. |
| [ToString](./tostring/)() const override | Returnerar en människoläsbar strängrepresentation av detta [Pdf417ExtendedParameters](./). |
## Anmärkningar


Detta exempel visar hur man hämtar Macro Pdf417‑metadata
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

## Se även

* Class [BaseExtendedParameters](../baseextendedparameters/)
* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
