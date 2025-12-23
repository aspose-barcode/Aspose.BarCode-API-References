---
title: Class QualitySettings
second_title: Aspose.BarCode for .NET API Reference
description: Aspose.BarCode.BarCodeRecognition.QualitySettings class. QualitySettings allows to configure recognition quality and speed manually. You can quickly set up QualitySettings with embedded presets HighPerformance NormalQuality HighQuality MaxQuality or you can manually configure separate options. Default value of QualitySettings is NormalQuality
type: docs
weight: 340
url: /net/aspose.barcode.barcoderecognition/qualitysettings/
---
## QualitySettings class

QualitySettings allows to configure recognition quality and speed manually. You can quickly set up QualitySettings with embedded presets: HighPerformance, NormalQuality, HighQuality, MaxQuality or you can manually configure separate options. Default value of QualitySettings is NormalQuality.

```csharp
public sealed class QualitySettings
```

## Properties

| Name | Description |
| --- | --- |
| static [HighPerformance](../../aspose.barcode.barcoderecognition/qualitysettings/highperformance/) { get; } | HighPerformance recognition quality preset. High quality barcodes are recognized well in this mode. |
| static [HighQuality](../../aspose.barcode.barcoderecognition/qualitysettings/highquality/) { get; } | HighQuality recognition quality preset. This preset is developed for low quality barcodes. Allows to detect highly damaged barcodes. |
| static [MaxQuality](../../aspose.barcode.barcoderecognition/qualitysettings/maxquality/) { get; } | MaxQuality recognition quality preset. This preset is developed to recognize all possible barcodes, even incorrect barcodes. |
| static [NormalQuality](../../aspose.barcode.barcoderecognition/qualitysettings/normalquality/) { get; } | NormalQuality recognition quality preset. Suitable for the most of barcodes |
| [AllowIncorrectBarcodes](../../aspose.barcode.barcoderecognition/qualitysettings/allowincorrectbarcodes/) { get; set; } | Allows engine to recognize barcodes which has incorrect checksumm or incorrect values. Mode can be used to recognize damaged barcodes with incorrect text. |
| [BarcodeQuality](../../aspose.barcode.barcoderecognition/qualitysettings/barcodequality/) { get; set; } | Mode which enables methods to recognize barcode elements with the selected quality. Barcode element with lower quality requires more hard methods which slows the recognition. |
| [ComplexBackground](../../aspose.barcode.barcoderecognition/qualitysettings/complexbackground/) { get; set; } | Mode which enables or disables additional recognition of color barcodes on color images. |
| [Deconvolution](../../aspose.barcode.barcoderecognition/qualitysettings/deconvolution/) { get; set; } | Deconvolution (image restorations) mode which defines level of image degradation. Originally deconvolution is a function which can restore image degraded (convoluted) by any natural function like blur, during obtaining image by camera. Because we cannot detect image function which corrupt the image, we have to check most well know functions like sharp or mathematical morphology. |
| [InverseImage](../../aspose.barcode.barcoderecognition/qualitysettings/inverseimage/) { get; set; } | Mode which enables or disables additional recognition of barcodes on images with inverted colors (luminance). |
| [MinimalXDimension](../../aspose.barcode.barcoderecognition/qualitysettings/minimalxdimension/) { get; set; } | Minimal size of XDimension in pixels which is used with UseMinimalXDimension. |
| [XDimension](../../aspose.barcode.barcoderecognition/qualitysettings/xdimension/) { get; set; } | Recognition mode which sets size (from 1 to infinity) of barcode minimal element: matrix cell or bar. |

## Examples

This sample shows how to use QualitySettings with BarCodeReader

```csharp
[C#]
//set HighPerformance recogition mode
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings = QualitySettings.HighPerformance;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}

//set HighQuality recognition mode
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings = QualitySettings.HighQuality;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}

//set HighPerformance recogition mode for low sized barcodes
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings = QualitySettings.HighPerformance;
    reader.QualitySettings.XDimension = XDimensionMode.Small;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}

//set HighPerformance recogition mode for low quality barcodes
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings = QualitySettings.HighPerformance;
    reader.QualitySettings.BarcodeQuality = BarcodeQualityMode.Low;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}    
```

### See Also

* namespace [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../)


