---
title: Aspose::BarCode::BarCodeRecognition::Pdf417ExtendedParameters class
linktitle: Pdf417ExtendedParameters
second_title: Aspose.BarCode for C++ API Reference
description: 'Aspose::BarCode::BarCodeRecognition::Pdf417ExtendedParameters class. Stores a MacroPdf417 metadata information of recognized barcode in C++.'
type: docs
weight: 2500
url: /cpp/aspose.barcode.barcoderecognition/pdf417extendedparameters/
---
## Pdf417ExtendedParameters class


Stores a MacroPdf417 metadata information of recognized barcode

```cpp
class Pdf417ExtendedParameters : public Aspose::BarCode::BarCodeRecognition::BaseExtendedParameters
```

## Methods

| Method | Description |
| --- | --- |
| [get_IsCode128Emulation](./get_iscode128emulation/)() | Flag that indicates that the MicroPdf417 barcode encoded with 908, 909, 910 or 911 Code 128 emulation codewords. |
| [get_IsEmpty](../baseextendedparameters/get_isempty/)() | **Tests** whether all parameters has only default values |
| [get_IsLinked](./get_islinked/)() | Flag that indicates that the barcode must be linked to 1D barcode. |
| [get_IsReaderInitialization](./get_isreaderinitialization/)() | Used to instruct the reader to interpret the data contained within the symbol as programming for reader initialization. |
| [get_MacroPdf417Addressee](./get_macropdf417addressee/)() const | Macro PDF417 addressee name (optional). |
| [get_MacroPdf417Checksum](./get_macropdf417checksum/)() const | Macro PDF417 checksum (optional). |
| [get_MacroPdf417FileID](./get_macropdf417fileid/)() | Gets the file ID of the barcode, only available with MacroPdf417. |
| [get_MacroPdf417FileName](./get_macropdf417filename/)() const | Macro PDF417 file name (optional). |
| [get_MacroPdf417FileSize](./get_macropdf417filesize/)() const | Macro PDF417 file size (optional). |
| [get_MacroPdf417SegmentID](./get_macropdf417segmentid/)() | Gets the segment ID of the barcode,only available with MacroPdf417. |
| [get_MacroPdf417SegmentsCount](./get_macropdf417segmentscount/)() | Gets macro pdf417 barcode segments count. Default value is -1. |
| [get_MacroPdf417Sender](./get_macropdf417sender/)() const | Macro PDF417 sender name (optional). |
| [get_MacroPdf417Terminator](./get_macropdf417terminator/)() const | Indicates whether the segment is the last segment of a Macro PDF417 file. |
| [get_MacroPdf417TimeStamp](./get_macropdf417timestamp/)() const | Macro PDF417 time stamp (optional). |
| [GetHashCode](./gethashcode/)() const override | Returns the hash code for this instance. |
| [ToString](./tostring/)() const override | Returns a human-readable string representation of this [Pdf417ExtendedParameters](./). |
## Remarks


This sample shows how to get Macro Pdf417 metadata 
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

## See Also

* Class [BaseExtendedParameters](../baseextendedparameters/)
* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
