---
title: "QualitySettings Class"
linktitle: "QualitySettings"
articleTitle: "QualitySettings"
second_title: "Aspose.BarCode for PHP via Java"
description: "QualitySettings allows to configure recognition quality and speed manually. You can quickly set up QualitySettings by embedded presets: HighPerformance, NormalQuality, HighQuality, MaxBarCodes or you "
type: docs
weight: 10
url: /php/aspose/barcode/recognition/qualitysettings/
---

## QualitySettings class

**Namespace:** `Aspose.Barcode.Recognition`


QualitySettings allows to configure recognition quality and speed manually. You can quickly set up QualitySettings by embedded presets: HighPerformance, NormalQuality, HighQuality, MaxBarCodes or you can manually configure separate options. Default value of QualitySettings is NormalQuality. This sample shows how to use QualitySettings with BarCodeReader


## Constructors

| Name | Description |
| --- | --- |
| [__construct](/php/aspose/barcode/recognition/qualitysettings/qualitysettings/) |  |

## Properties

| Name | Read/Write | Description |
| --- | --- | --- |
| [AllowIncorrectBarcodes](/php/aspose/barcode/recognition/qualitysettings/allowincorrectbarcodes/) | Read/Write | Allows engine to recognize barcodes which has incorrect checksumm or incorrect values. Mode can be used to recognize damaged barcodes with incorrect text. |
| [BarcodeQuality](/php/aspose/barcode/recognition/qualitysettings/barcodequality/) | Read/Write | Mode which enables methods to recognize barcode elements with the selected quality. Barcode element with lower quality requires more hard methods which slows the recognition. |
| [ComplexBackground](/php/aspose/barcode/recognition/qualitysettings/complexbackground/) | Read/Write | Mode which enables or disables additional recognition of color barcodes on color images. |
| [Deconvolution](/php/aspose/barcode/recognition/qualitysettings/deconvolution/) | Read/Write | Deconvolution (image restorations) mode which defines level of image degradation. Originally deconvolution is a function which can restore image degraded (convoluted) by any natural function like blur, during obtaining image by camera. Because we cannot detect image function which corrupt the image, we have to check most well know functions like sharp or mathematical morphology. |
| [HighPerformance](/php/aspose/barcode/recognition/qualitysettings/highperformance/) | Read-only | HighPerformance recognition quality preset. High quality barcodes are recognized well in this mode. |
| [HighQuality](/php/aspose/barcode/recognition/qualitysettings/highquality/) | Read-only | HighQuality recognition quality preset. This preset is developed for low quality barcodes. |
| [InverseImage](/php/aspose/barcode/recognition/qualitysettings/inverseimage/) | Read/Write | Mode which enables or disables additional recognition of barcodes on images with inverted colors (luminance). |
| [MaxQuality](/php/aspose/barcode/recognition/qualitysettings/maxquality/) | Read-only | MaxQuality recognition quality preset. This preset is developed to recognize all possible barcodes, even incorrect barcodes. Value: MaxQuality recognition quality preset. |
| [MinimalXDimension](/php/aspose/barcode/recognition/qualitysettings/minimalxdimension/) | Read/Write | Minimal size of XDimension in pixels which is used with UseMinimalXDimension. |
| [NormalQuality](/php/aspose/barcode/recognition/qualitysettings/normalquality/) | Read-only | NormalQuality recognition quality preset. Suitable for the most of barcodes |
| [XDimension](/php/aspose/barcode/recognition/qualitysettings/xdimension/) | Read/Write | Recognition mode which sets size (from 1 to infinity) of barcode minimal element: matrix cell or bar. |
