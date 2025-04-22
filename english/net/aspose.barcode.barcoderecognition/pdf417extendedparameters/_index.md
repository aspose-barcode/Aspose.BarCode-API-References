---
title: Class Pdf417ExtendedParameters
second_title: Aspose.BarCode for .NET API Reference
description: Aspose.BarCode.BarCodeRecognition.Pdf417ExtendedParameters class. Stores a MacroPdf417 metadata information of recognized barcode
type: docs
weight: 310
url: /net/aspose.barcode.barcoderecognition/pdf417extendedparameters/
---
## Pdf417ExtendedParameters class

Stores a MacroPdf417 metadata information of recognized barcode

```csharp
public sealed class Pdf417ExtendedParameters : BaseExtendedParameters
```

## Properties

| Name | Description |
| --- | --- |
| [IsCode128Emulation](../../aspose.barcode.barcoderecognition/pdf417extendedparameters/iscode128emulation/) { get; } | Flag that indicates that the MicroPdf417 barcode encoded with 908, 909, 910 or 911 Code 128 emulation codewords. |
| [IsEmpty](../../aspose.barcode.barcoderecognition/baseextendedparameters/isempty/) { get; } | Tests whether all parameters has only default values |
| [IsLinked](../../aspose.barcode.barcoderecognition/pdf417extendedparameters/islinked/) { get; } | Flag that indicates that the barcode must be linked to 1D barcode. |
| [IsReaderInitialization](../../aspose.barcode.barcoderecognition/pdf417extendedparameters/isreaderinitialization/) { get; } | Used to instruct the reader to interpret the data contained within the symbol as programming for reader initialization. |
| [MacroPdf417Addressee](../../aspose.barcode.barcoderecognition/pdf417extendedparameters/macropdf417addressee/) { get; } | Macro PDF417 addressee name (optional). |
| [MacroPdf417Checksum](../../aspose.barcode.barcoderecognition/pdf417extendedparameters/macropdf417checksum/) { get; } | Macro PDF417 checksum (optional). |
| [MacroPdf417FileID](../../aspose.barcode.barcoderecognition/pdf417extendedparameters/macropdf417fileid/) { get; } | Gets the file ID of the barcode, only available with MacroPdf417. |
| [MacroPdf417FileName](../../aspose.barcode.barcoderecognition/pdf417extendedparameters/macropdf417filename/) { get; } | Macro PDF417 file name (optional). |
| [MacroPdf417FileSize](../../aspose.barcode.barcoderecognition/pdf417extendedparameters/macropdf417filesize/) { get; } | Macro PDF417 file size (optional). |
| [MacroPdf417SegmentID](../../aspose.barcode.barcoderecognition/pdf417extendedparameters/macropdf417segmentid/) { get; } | Gets the segment ID of the barcode,only available with MacroPdf417. |
| [MacroPdf417SegmentsCount](../../aspose.barcode.barcoderecognition/pdf417extendedparameters/macropdf417segmentscount/) { get; } | Gets macro pdf417 barcode segments count. Default value is -1. |
| [MacroPdf417Sender](../../aspose.barcode.barcoderecognition/pdf417extendedparameters/macropdf417sender/) { get; } | Macro PDF417 sender name (optional). |
| [MacroPdf417Terminator](../../aspose.barcode.barcoderecognition/pdf417extendedparameters/macropdf417terminator/) { get; } | Indicates whether the segment is the last segment of a Macro PDF417 file. |
| [MacroPdf417TimeStamp](../../aspose.barcode.barcoderecognition/pdf417extendedparameters/macropdf417timestamp/) { get; } | Macro PDF417 time stamp (optional). |

## Methods

| Name | Description |
| --- | --- |
| override [Equals](../../aspose.barcode.barcoderecognition/pdf417extendedparameters/equals/)(object) | Returns a value indicating whether this instance is equal to a specified `Pdf417ExtendedParameters` value. |
| override [GetHashCode](../../aspose.barcode.barcoderecognition/pdf417extendedparameters/gethashcode/)() | Returns the hash code for this instance. |
| override [ToString](../../aspose.barcode.barcoderecognition/pdf417extendedparameters/tostring/)() | Returns a human-readable string representation of this `Pdf417ExtendedParameters`. |
| [operator ==](../../aspose.barcode.barcoderecognition/pdf417extendedparameters/op_equality/) | Returns a value indicating whether the first `Pdf417ExtendedParameters` value is equal to the second. |
| [operator !=](../../aspose.barcode.barcoderecognition/pdf417extendedparameters/op_inequality/) | Returns a value indicating if the first `Pdf417ExtendedParameters` value is different from the second. |

## Examples

This sample shows how to get Macro Pdf417 metadata

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

### See Also

* class [BaseExtendedParameters](../baseextendedparameters/)
* namespace [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../)


