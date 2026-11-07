---
title: "Aspose::BarCode::BarCodeRecognition::Pdf417ExtendedParameters Klasse"
linktitle: "Pdf417ExtendedParameters"
second_title: "Aspose.BarCode für C++ API-Referenz"
description: "Aspose::BarCode::BarCodeRecognition::Pdf417ExtendedParameters Klasse. Speichert Metadateninformationen von MacroPdf417 des erkannten Barcodes in C++."
type: docs
weight: 2800
url: /de/cpp/aspose.barcode.barcoderecognition/pdf417extendedparameters/
---
## Pdf417ExtendedParameters class


Speichert Metadateninformationen von MacroPdf417 des erkannten Barcodes.

```cpp
class Pdf417ExtendedParameters : public Aspose::BarCode::BarCodeRecognition::BaseExtendedParameters
```

## Methods

| Method | Beschreibung |
| --- | --- |
| [get_IsCode128Emulation](./get_iscode128emulation/)() const | Flag, das anzeigt, dass der MicroPdf417‑Barcode mit den Emulationscodewörtern 908, 909, 910 oder 911 Code 128 codiert ist. |
| [get_IsEmpty](../baseextendedparameters/get_isempty/)() const | **Tests** ob alle Parameter nur Standardwerte haben |
| [get_IsLinked](./get_islinked/)() const | Flag, das anzeigt, dass der Barcode mit einem 1D‑Barcode verknüpft sein muss. |
| [get_IsReaderInitialization](./get_isreaderinitialization/)() const | Wird verwendet, um den Leser anzuweisen, die im Symbol enthaltenen Daten als Programmierung für die Leserinitialisierung zu interpretieren. |
| [get_MacroPdf417Addressee](./get_macropdf417addressee/)() const | Macro PDF417 Empfängername (optional). |
| [get_MacroPdf417Checksum](./get_macropdf417checksum/)() const | Macro PDF417 Prüfsumme (optional). |
| [get_MacroPdf417FileID](./get_macropdf417fileid/)() const | Liefert die Datei‑ID des Barcodes, nur verfügbar mit MacroPdf417. |
| [get_MacroPdf417FileName](./get_macropdf417filename/)() const | Macro PDF417 Dateiname (optional). |
| [get_MacroPdf417FileSize](./get_macropdf417filesize/)() const | Macro PDF417 Dateigröße (optional). |
| [get_MacroPdf417SegmentID](./get_macropdf417segmentid/)() const | Liefert die Segment‑ID des Barcodes, nur verfügbar mit MacroPdf417. |
| [get_MacroPdf417SegmentsCount](./get_macropdf417segmentscount/)() const | Liefert die Anzahl der Macro‑PDF417‑Barcode‑Segmente. Standardwert ist -1. |
| [get_MacroPdf417Sender](./get_macropdf417sender/)() const | Macro PDF417 Absendername (optional). |
| [get_MacroPdf417Terminator](./get_macropdf417terminator/)() const | Gibt an, ob das Segment das letzte Segment einer Macro‑PDF417‑Datei ist. |
| [get_MacroPdf417TimeStamp](./get_macropdf417timestamp/)() const | Macro PDF417 Zeitstempel (optional). |
| [GetHashCode](./gethashcode/)() const override | Gibt den Hashcode für diese Instanz zurück. |
| [ToString](./tostring/)() const override | Gibt eine menschenlesbare Zeichenkettenrepräsentation dieses [Pdf417ExtendedParameters](./) zurück. |
## Hinweise


Dieses Beispiel zeigt, wie man Macro Pdf417 Metadaten erhält
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

## Siehe auch

* Class [BaseExtendedParameters](../baseextendedparameters/)
* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
