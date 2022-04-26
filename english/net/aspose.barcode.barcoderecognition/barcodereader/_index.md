---
title: BarCodeReader
second_title: Aspose.BarCode for .NET API Reference
description: 
type: docs
weight: 60
url: /net/aspose.barcode.barcoderecognition/barcodereader/
---
## BarCodeReader class

BarCodeReader encapsulates an image which may contain one or several barcodes, it then can perform ReadBarCodes operation to detect barcodes.

```csharp
public class BarCodeReader : IDisposable
```

## Constructors

| Name | Description |
| --- | --- |
| [BarCodeReader](barcodereader)() | Initializes a new instance of the [`BarCodeReader`](../barcodereader) class with default values. Requires to set image (SetBitmapImage()) before to call ReadBarCodes() method. |
| [BarCodeReader](barcodereader)(Bitmap) | Initializes a new instance of the [`BarCodeReader`](../barcodereader) class from an image. |
| [BarCodeReader](barcodereader)(Stream) | Initializes a new instance of the [`BarCodeReader`](../barcodereader) class. |
| [BarCodeReader](barcodereader)(string) | Initializes a new instance of the [`BarCodeReader`](../barcodereader) class from file. |
| [BarCodeReader](barcodereader)(Bitmap, BaseDecodeType) | Initializes a new instance of the [`BarCodeReader`](../barcodereader) class. |
| [BarCodeReader](barcodereader)(Bitmap, params BaseDecodeType[]) | Initializes a new instance of the [`BarCodeReader`](../barcodereader) class. |
| [BarCodeReader](barcodereader)(Stream, BaseDecodeType) | Initializes a new instance of the [`BarCodeReader`](../barcodereader) class. |
| [BarCodeReader](barcodereader)(Stream, params BaseDecodeType[]) | Initializes a new instance of the [`BarCodeReader`](../barcodereader) class. |
| [BarCodeReader](barcodereader)(string, BaseDecodeType) | Initializes a new instance of the [`BarCodeReader`](../barcodereader) class. |
| [BarCodeReader](barcodereader)(string, params BaseDecodeType[]) | Initializes a new instance of the [`BarCodeReader`](../barcodereader) class. |
| [BarCodeReader](barcodereader)(Bitmap, Rectangle, BaseDecodeType) | Initializes a new instance of the [`BarCodeReader`](../barcodereader) class. |
| [BarCodeReader](barcodereader)(Bitmap, Rectangle, params BaseDecodeType[]) | Initializes a new instance of the [`BarCodeReader`](../barcodereader) class. |
| [BarCodeReader](barcodereader)(Bitmap, Rectangle[], BaseDecodeType) | Initializes a new instance of the [`BarCodeReader`](../barcodereader) class. |
| [BarCodeReader](barcodereader)(Bitmap, Rectangle[], params BaseDecodeType[]) | Initializes a new instance of the [`BarCodeReader`](../barcodereader) class. |

## Properties

| Name | Description |
| --- | --- |
| [BarcodeSettings](barcodesettings) { get; } | The main BarCode decoding parameters. Contains parameters which make influence on recognized data. |
| [FoundBarCodes](foundbarcodes) { get; } | Gets recognized [`BarCodeResult`](../barcoderesult)s array |
| [FoundCount](foundcount) { get; } | Gets recognized barcodes count |
| [QualitySettings](qualitysettings) { get; set; } | QualitySettings allows to configure recognition quality and speed manually. You can quickly set up QualitySettings by embedded presets: HighPerformance, NormalQuality, HighQuality, MaxBarCodes or you can manually configure separate options. Default value of QualitySettings is NormalQuality. |
| [Timeout](timeout) { get; set; } | Gets or sets the timeout of recognition process in milliseconds. |
| static [ProcessorSettings](processorsettings) { get; } | Gets a settings of using processor cores. |

## Methods

| Name | Description |
| --- | --- |
| static [ImportFromXml](importfromxml)(Stream) | Imports BarCode properties from the xml-stream specified and applies them to the current BarCodeReader instance. |
| static [ImportFromXml](importfromxml)(string) | Imports BarCode properties from the xml-file specified and applies them to the current BarCodeReader instance. |
| [Abort](abort)() | Function requests termination of current recognition session from other thread. Abort is unblockable method and returns control just after calling. The method should be used when recognition process is too long. |
| [Dispose](dispose)() |  |
| [ExportToXml](exporttoxml)(Stream) | Exports BarCode properties to the xml-stream specified |
| [ExportToXml](exporttoxml)(string) | Exports BarCode properties to the xml-file specified |
| [ReadBarCodes](readbarcodes)() | Reads [`BarCodeResult`](../barcoderesult)s from the image. |
| [SetBarCodeImage](setbarcodeimage)(Bitmap) | Sets bitmap image for recognition. Must be called before ReadBarCodes() method. |
| [SetBarCodeImage](setbarcodeimage)(Stream) | Sets image stream for recognition. Must be called before ReadBarCodes() method. |
| [SetBarCodeImage](setbarcodeimage)(string) | Sets image file for recognition. Must be called before ReadBarCodes() method. |
| [SetBarCodeImage](setbarcodeimage)(Bitmap, Rectangle) | Sets bitmap image and area for recognition. Must be called before ReadBarCodes() method. |
| [SetBarCodeImage](setbarcodeimage)(Bitmap, Rectangle[]) | Sets bitmap image and areas for recognition. Must be called before ReadBarCodes() method. |
| [SetBarCodeReadType](setbarcodereadtype)(BaseDecodeType) | Sets decode type for recognition. Must be called before ReadBarCodes() method. |
| [SetBarCodeReadType](setbarcodereadtype)(params SingleDecodeType[]) | Sets [`SingleDecodeType`](../singledecodetype) type array for recognition. Must be called before ReadBarCodes() method. |

### Examples

This sample shows how to detect Code39 and Code128 barcodes.

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Standard, DecodeType.Code128))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
    }
}
[VB.NET]
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39Standard, DecodeType.Code128)
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
    Next
End Using
```

### See Also

* namespace [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition)
* assembly [Aspose.BarCode](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->
