---
title: Aspose::BarCode::BarCodeRecognition::QualitySettings class
linktitle: QualitySettings
second_title: Aspose.BarCode for C++ API Reference
description: 'Aspose::BarCode::BarCodeRecognition::QualitySettings class. QualitySettings allows to configure recognition quality and speed manually. You can quickly set up QualitySettings with embedded presets: HighPerformance, NormalQuality, HighQuality, MaxQuality or you can manually configure separate options. Default value of QualitySettings is NormalQuality in C++.'
type: docs
weight: 2800
url: /cpp/aspose.barcode.barcoderecognition/qualitysettings/
---
## QualitySettings class


[QualitySettings](./) allows to configure recognition quality and speed manually. You can quickly set up [QualitySettings](./) with embedded presets: HighPerformance, NormalQuality, HighQuality, MaxQuality or you can manually configure separate options. Default value of [QualitySettings](./) is NormalQuality.

```cpp
class QualitySettings : public System::Object
```

## Methods

| Method | Description |
| --- | --- |
| [get_AllowIncorrectBarcodes](./get_allowincorrectbarcodes/)() const | Allows engine to recognize barcodes which has incorrect checksumm or incorrect values. Mode can be used to recognize damaged barcodes with incorrect text. |
| [get_BarcodeQuality](./get_barcodequality/)() const | Mode which enables methods to recognize barcode elements with the selected quality. Barcode element with lower quality requires more hard methods which slows the recognition. |
| [get_ComplexBackground](./get_complexbackground/)() const | Mode which enables or disables additional recognition of color barcodes on color images. |
| [get_Deconvolution](./get_deconvolution/)() const | Deconvolution (image restorations) mode which defines level of image degradation. Originally deconvolution is a function which can restore image degraded (convoluted) by any natural function like blur, during obtaining image by camera. Because we cannot detect image function which corrupt the image, we have to check most well know functions like sharp or mathematical morphology. |
| static [get_HighPerformance](./get_highperformance/)() | HighPerformance recognition quality preset. High quality barcodes are recognized well in this mode. |
| static [get_HighQuality](./get_highquality/)() | HighQuality recognition quality preset. This preset is developed for low quality barcodes. Allows to detect highly damaged barcodes. |
| [get_InverseImage](./get_inverseimage/)() const | Mode which enables or disables additional recognition of barcodes on images with inverted colors (luminance). |
| static [get_MaxQuality](./get_maxquality/)() | MaxQuality recognition quality preset. This preset is developed to recognize all possible barcodes, even incorrect barcodes. |
| [get_MinimalXDimension](./get_minimalxdimension/)() const | Minimal size of XDimension in pixels which is used with UseMinimalXDimension. |
| static [get_NormalQuality](./get_normalquality/)() | NormalQuality recognition quality preset. Suitable for the most of barcodes |
| [get_XDimension](./get_xdimension/)() const | Recognition mode which sets size (from 1 to infinity) of barcode minimal element: matrix cell or bar. |
| [set_AllowIncorrectBarcodes](./set_allowincorrectbarcodes/)(bool) | Allows engine to recognize barcodes which has incorrect checksumm or incorrect values. Mode can be used to recognize damaged barcodes with incorrect text. |
| [set_BarcodeQuality](./set_barcodequality/)(BarcodeQualityMode) | Mode which enables methods to recognize barcode elements with the selected quality. Barcode element with lower quality requires more hard methods which slows the recognition. |
| [set_ComplexBackground](./set_complexbackground/)(ComplexBackgroundMode) | Mode which enables or disables additional recognition of color barcodes on color images. |
| [set_Deconvolution](./set_deconvolution/)(DeconvolutionMode) | Deconvolution (image restorations) mode which defines level of image degradation. Originally deconvolution is a function which can restore image degraded (convoluted) by any natural function like blur, during obtaining image by camera. Because we cannot detect image function which corrupt the image, we have to check most well know functions like sharp or mathematical morphology. |
| [set_InverseImage](./set_inverseimage/)(InverseImageMode) | Mode which enables or disables additional recognition of barcodes on images with inverted colors (luminance). |
| [set_MinimalXDimension](./set_minimalxdimension/)(float) | Minimal size of XDimension in pixels which is used with UseMinimalXDimension. |
| [set_XDimension](./set_xdimension/)(XDimensionMode) | Recognition mode which sets size (from 1 to infinity) of barcode minimal element: matrix cell or bar. |
## Remarks


This sample shows how to use [QualitySettings](./) with [BarCodeReader](../barcodereader/)
```cpp
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
<br>
```

## See Also

* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
