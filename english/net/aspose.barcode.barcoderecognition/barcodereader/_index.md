---
title: Class BarCodeReader
second_title: Aspose.BarCode for .NET API Reference
description: Aspose.BarCode.BarCodeRecognition.BarCodeReader class. BarCodeReader encapsulates an image which may contain one or several barcodes it then can perform ReadBarCodes operation to detect barcodes
type: docs
weight: 70
url: /net/aspose.barcode.barcoderecognition/barcodereader/
---
## BarCodeReader class

BarCodeReader encapsulates an image which may contain one or several barcodes, it then can perform ReadBarCodes operation to detect barcodes.

```csharp
public class BarCodeReader : Component
```

## Constructors

| Name | Description |
| --- | --- |
| [BarCodeReader](barcodereader/#constructor)() | Initializes a new instance of the `BarCodeReader` class with default values. Requires to set image (SetBitmapImage()) before to call ReadBarCodes() method. |
| [BarCodeReader](barcodereader/#constructor_1)(Bitmap) | Initializes a new instance of the `BarCodeReader` class from an image. |
| [BarCodeReader](barcodereader/#constructor_8)(Stream) | Initializes a new instance of the `BarCodeReader` class. |
| [BarCodeReader](barcodereader/#constructor_11)(string) | Initializes a new instance of the `BarCodeReader` class from file. |
| [BarCodeReader](barcodereader/#constructor_2)(Bitmap, BaseDecodeType) | Initializes a new instance of the `BarCodeReader` class. |
| [BarCodeReader](barcodereader/#constructor_3)(Bitmap, params BaseDecodeType[]) | Initializes a new instance of the `BarCodeReader` class. |
| [BarCodeReader](barcodereader/#constructor_9)(Stream, BaseDecodeType) | Initializes a new instance of the `BarCodeReader` class. |
| [BarCodeReader](barcodereader/#constructor_10)(Stream, params BaseDecodeType[]) | Initializes a new instance of the `BarCodeReader` class. |
| [BarCodeReader](barcodereader/#constructor_12)(string, BaseDecodeType) | Initializes a new instance of the `BarCodeReader` class. |
| [BarCodeReader](barcodereader/#constructor_13)(string, params BaseDecodeType[]) | Initializes a new instance of the `BarCodeReader` class. |
| [BarCodeReader](barcodereader/#constructor_4)(Bitmap, Rectangle, BaseDecodeType) | Initializes a new instance of the `BarCodeReader` class. |
| [BarCodeReader](barcodereader/#constructor_5)(Bitmap, Rectangle, params BaseDecodeType[]) | Initializes a new instance of the `BarCodeReader` class. |
| [BarCodeReader](barcodereader/#constructor_6)(Bitmap, Rectangle[], BaseDecodeType) | Initializes a new instance of the `BarCodeReader` class. |
| [BarCodeReader](barcodereader/#constructor_7)(Bitmap, Rectangle[], params BaseDecodeType[]) | Initializes a new instance of the `BarCodeReader` class. |

## Properties

| Name | Description |
| --- | --- |
| [BarcodeSettings](../../aspose.barcode.barcoderecognition/barcodereader/barcodesettings/) { get; } | The main BarCode decoding parameters. Contains parameters which make influence on recognized data. |
| [FoundBarCodes](../../aspose.barcode.barcoderecognition/barcodereader/foundbarcodes/) { get; } | Gets recognized [`BarCodeResult`](../barcoderesult/)s array |
| [FoundCount](../../aspose.barcode.barcoderecognition/barcodereader/foundcount/) { get; } | Gets recognized barcodes count |
| [QualitySettings](../../aspose.barcode.barcoderecognition/barcodereader/qualitysettings/) { get; set; } | QualitySettings allows to configure recognition quality and speed manually. You can quickly set up QualitySettings by embedded presets: HighPerformance, NormalQuality, HighQuality, MaxBarCodes or you can manually configure separate options. Default value of QualitySettings is NormalQuality. |
| [Timeout](../../aspose.barcode.barcoderecognition/barcodereader/timeout/) { get; set; } | Gets or sets the timeout of recognition process in milliseconds. |
| static [ProcessorSettings](../../aspose.barcode.barcoderecognition/barcodereader/processorsettings/) { get; } | Gets a settings of using processor cores. |

## Methods

| Name | Description |
| --- | --- |
| static [ImportFromXml](../../aspose.barcode.barcoderecognition/barcodereader/importfromxml/#importfromxml)(Stream) | Imports BarCode properties from the xml-stream specified and applies them to the current BarCodeReader instance. |
| static [ImportFromXml](../../aspose.barcode.barcoderecognition/barcodereader/importfromxml/#importfromxml_1)(string) | Imports BarCode properties from the xml-file specified and applies them to the current BarCodeReader instance. |
| [Abort](../../aspose.barcode.barcoderecognition/barcodereader/abort/)() | Function requests termination of current recognition session from other thread. Abort is unblockable method and returns control just after calling. The method should be used when recognition process is too long. |
| [ExportToXml](../../aspose.barcode.barcoderecognition/barcodereader/exporttoxml/#exporttoxml)(Stream) | Exports BarCode properties to the xml-stream specified |
| [ExportToXml](../../aspose.barcode.barcoderecognition/barcodereader/exporttoxml/#exporttoxml_1)(string) | Exports BarCode properties to the xml-file specified |
| [ReadBarCodes](../../aspose.barcode.barcoderecognition/barcodereader/readbarcodes/)() | Reads [`BarCodeResult`](../barcoderesult/)s from the image. |
| [SetBarCodeImage](../../aspose.barcode.barcoderecognition/barcodereader/setbarcodeimage/#setbarcodeimage)(Bitmap) | Sets bitmap image for recognition. Must be called before ReadBarCodes() method. |
| [SetBarCodeImage](../../aspose.barcode.barcoderecognition/barcodereader/setbarcodeimage/#setbarcodeimage_3)(Stream) | Sets image stream for recognition. Must be called before ReadBarCodes() method. |
| [SetBarCodeImage](../../aspose.barcode.barcoderecognition/barcodereader/setbarcodeimage/#setbarcodeimage_4)(string) | Sets image file for recognition. Must be called before ReadBarCodes() method. |
| [SetBarCodeImage](../../aspose.barcode.barcoderecognition/barcodereader/setbarcodeimage/#setbarcodeimage_1)(Bitmap, Rectangle) | Sets bitmap image and area for recognition. Must be called before ReadBarCodes() method. |
| [SetBarCodeImage](../../aspose.barcode.barcoderecognition/barcodereader/setbarcodeimage/#setbarcodeimage_2)(Bitmap, Rectangle[]) | Sets bitmap image and areas for recognition. Must be called before ReadBarCodes() method. |
| [SetBarCodeReadType](../../aspose.barcode.barcoderecognition/barcodereader/setbarcodereadtype/#setbarcodereadtype)(BaseDecodeType) | Sets decode type for recognition. Must be called before ReadBarCodes() method. |
| [SetBarCodeReadType](../../aspose.barcode.barcoderecognition/barcodereader/setbarcodereadtype/#setbarcodereadtype_1)(params SingleDecodeType[]) | Sets [`SingleDecodeType`](../singledecodetype/) type array for recognition. Must be called before ReadBarCodes() method. |

## Examples

This sample shows how to detect Code39 and Code128 barcodes.

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39, DecodeType.Code128))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
    }
}
[VB.NET]
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39, DecodeType.Code128)
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
    Next
End Using
```

### See Also

* namespace [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../)


