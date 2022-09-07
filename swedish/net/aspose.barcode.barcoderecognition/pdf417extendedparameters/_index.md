---
title: Pdf417ExtendedParameters
second_title: Aspose.BarCode för .NET API-referens
description: Lagrar en MacroPdf417-metadatainformation av erkänd streckkod
type: docs
weight: 220
url: /sv/net/aspose.barcode.barcoderecognition/pdf417extendedparameters/
---
## Pdf417ExtendedParameters class

Lagrar en MacroPdf417-metadatainformation av erkänd streckkod

```csharp
public sealed class Pdf417ExtendedParameters : BaseExtendedParameters
```

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [IsEmpty](../../aspose.barcode.barcoderecognition/baseextendedparameters/isempty) { get; } | Testar om alla parametrar bara har standardvärden |
| [MacroPdf417Addressee](../../aspose.barcode.barcoderecognition/pdf417extendedparameters/macropdf417addressee) { get; } | Makro PDF417 adressatens namn (valfritt). |
| [MacroPdf417Checksum](../../aspose.barcode.barcoderecognition/pdf417extendedparameters/macropdf417checksum) { get; } | Makro PDF417 kontrollsumma (valfritt). |
| [MacroPdf417FileID](../../aspose.barcode.barcoderecognition/pdf417extendedparameters/macropdf417fileid) { get; } | Hämtar fil-ID för streckkoden, endast tillgänglig med MacroPdf417. |
| [MacroPdf417FileName](../../aspose.barcode.barcoderecognition/pdf417extendedparameters/macropdf417filename) { get; } | Makro PDF417 filnamn (valfritt). |
| [MacroPdf417FileSize](../../aspose.barcode.barcoderecognition/pdf417extendedparameters/macropdf417filesize) { get; } | Makro PDF417 filstorlek (valfritt). |
| [MacroPdf417SegmentID](../../aspose.barcode.barcoderecognition/pdf417extendedparameters/macropdf417segmentid) { get; } | Hämtar streckkodens segment-ID, endast tillgängligt med MacroPdf417. |
| [MacroPdf417SegmentsCount](../../aspose.barcode.barcoderecognition/pdf417extendedparameters/macropdf417segmentscount) { get; } | Får makro pdf417 streckkod segment räknas. Standardvärdet är -1. |
| [MacroPdf417Sender](../../aspose.barcode.barcoderecognition/pdf417extendedparameters/macropdf417sender) { get; } | Makro PDF417 avsändarnamn (valfritt). |
| [MacroPdf417TimeStamp](../../aspose.barcode.barcoderecognition/pdf417extendedparameters/macropdf417timestamp) { get; } | Makro PDF417 tidsstämpel (valfritt). |

## Metoder

| namn | Beskrivning |
| --- | --- |
| override [Equals](../../aspose.barcode.barcoderecognition/pdf417extendedparameters/equals)(object) | Returnerar ett värde som anger om denna instans är lika med en specificerad[`Pdf417ExtendedParameters`](../pdf417extendedparameters) värde. |
| override [GetHashCode](../../aspose.barcode.barcoderecognition/pdf417extendedparameters/gethashcode)() | Returnerar hashkoden för denna instans. |
| override [ToString](../../aspose.barcode.barcoderecognition/pdf417extendedparameters/tostring)() | Returnerar en mänsklig läsbar strängrepresentation av detta[`Pdf417ExtendedParameters`](../pdf417extendedparameters) . |
| [operator ==](../../aspose.barcode.barcoderecognition/pdf417extendedparameters/op_equality) | Returnerar ett värde som anger om det första[`Pdf417ExtendedParameters`](../pdf417extendedparameters) värdet är lika med sekunden. |
| [operator !=](../../aspose.barcode.barcoderecognition/pdf417extendedparameters/op_inequality) | Returnerar ett värde som anger om det första[`Pdf417ExtendedParameters`](../pdf417extendedparameters) värdet skiljer sig från det andra. |

### Exempel

Detta exempel visar hur man får Macro Pdf417 metadata

```csharp
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

### Se även

* class [BaseExtendedParameters](../baseextendedparameters)
* namnutrymme [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition)
* hopsättning [Aspose.BarCode](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->
