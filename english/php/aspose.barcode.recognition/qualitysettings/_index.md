---
title: "QualitySettings"
linktitle: "QualitySettings"
second_title: "Aspose.BarCode for PHP via Java"
description: "QualitySettings allows to configure recognition quality and speed manually. You can quickly set up QualitySettings by embedded presets: HighPerformance, NormalQuality, HighQuality, MaxBarCodes or you "
type: docs
weight: 10
url: /php/aspose.barcode.recognition/qualitysettings/
---

## QualitySettings class

**Namespace:** `Aspose.Barcode.Recognition`


QualitySettings allows to configure recognition quality and speed manually. You can quickly set up QualitySettings by embedded presets: HighPerformance, NormalQuality, HighQuality, MaxBarCodes or you can manually configure separate options. Default value of QualitySettings is NormalQuality. This sample shows how to use QualitySettings with BarCodeReader


## Constructors

| Name | Description |
| --- | --- |
| [__construct](#constructor) |  |

## Properties

| Name | Static | Read/Write | Description |
| --- | --- | --- | --- |
| [AllowIncorrectBarcodes](#allowincorrectbarcodes) | No | Read/Write | Allows engine to recognize barcodes which has incorrect checksumm or incorrect values. Mode can be used to recognize damaged barcodes with incorrect text. |
| [BarcodeQuality](#barcodequality) | No | Read/Write | Mode which enables methods to recognize barcode elements with the selected quality. Barcode element with lower quality requires more hard methods which slows the recognition. |
| [ComplexBackground](#complexbackground) | No | Read/Write | Mode which enables or disables additional recognition of color barcodes on color images. |
| [Deconvolution](#deconvolution) | No | Read/Write | Deconvolution (image restorations) mode which defines level of image degradation. Originally deconvolution is a function which can restore image degraded (convoluted) by any natural function like blur, during obtaining image by camera. Because we cannot detect image function which corrupt the image, we have to check most well know functions like sharp or mathematical morphology. |
| [HighPerformance](#highperformance) | Yes | Read-only | HighPerformance recognition quality preset. High quality barcodes are recognized well in this mode. |
| [HighQuality](#highquality) | Yes | Read-only | HighQuality recognition quality preset. This preset is developed for low quality barcodes. |
| [InverseImage](#inverseimage) | No | Read/Write | Mode which enables or disables additional recognition of barcodes on images with inverted colors (luminance). |
| [MaxQuality](#maxquality) | Yes | Read-only | MaxQuality recognition quality preset. This preset is developed to recognize all possible barcodes, even incorrect barcodes. Value: MaxQuality recognition quality preset. |
| [MinimalXDimension](#minimalxdimension) | No | Read/Write | Minimal size of XDimension in pixels which is used with UseMinimalXDimension. |
| [NormalQuality](#normalquality) | Yes | Read-only | NormalQuality recognition quality preset. Suitable for the most of barcodes |
| [XDimension](#xdimension) | No | Read/Write | Recognition mode which sets size (from 1 to infinity) of barcode minimal element: matrix cell or bar. |

### QualitySettings__construct(QualitySettingsDTO $qualitySettingsDTO) {#constructor}

| Parameter | Type | Description |
| --- | --- | --- |
| `$qualitySettingsDTO` | `QualitySettingsDTO` |  |

### AllowIncorrectBarcodes {#allowincorrectbarcodes}

**Access:** Read/Write

**Returns:** bool : Allows engine to recognize incorrect barcodes.

Allows engine to recognize barcodes which has incorrect checksumm or incorrect values. Mode can be used to recognize damaged barcodes with incorrect text.

Allows engine to recognize barcodes which has incorrect checksumm or incorrect values. Mode can be used to recognize damaged barcodes with incorrect text.

| Parameter | Type | Description |
| --- | --- | --- |
| `$value` | `bool` | : Allows engine to recognize incorrect barcodes. |

### BarcodeQuality {#barcodequality}

**Access:** Read/Write

**Returns:** int : Mode which enables methods to recognize barcode elements with the selected quality.

Mode which enables methods to recognize barcode elements with the selected quality. Barcode element with lower quality requires more hard methods which slows the recognition.

Mode which enables methods to recognize barcode elements with the selected quality. Barcode element with lower quality requires more hard methods which slows the recognition.

| Parameter | Type | Description |
| --- | --- | --- |
| `$value` | `int` | : Mode which enables methods to recognize barcode elements with the selected quality. |

### ComplexBackground {#complexbackground}

**Access:** Read/Write

**Returns:** int : Additional recognition of color barcodes on color images.

Mode which enables or disables additional recognition of color barcodes on color images.

Mode which enables or disables additional recognition of color barcodes on color images.

| Parameter | Type | Description |
| --- | --- | --- |
| `$value` | `int` | : Additional recognition of color barcodes on color images. |

### Deconvolution {#deconvolution}

**Access:** Read/Write

**Returns:** int : Deconvolution mode which defines level of image degradation.

Deconvolution (image restorations) mode which defines level of image degradation. Originally deconvolution is a function which can restore image degraded (convoluted) by any natural function like blur, during obtaining image by camera. Because we cannot detect image function which corrupt the image, we have to check most well know functions like sharp or mathematical morphology.

Deconvolution (image restorations) mode which defines level of image degradation. Originally deconvolution is a function which can restore image degraded (convoluted) by any natural function like blur, during obtaining image by camera. Because we cannot detect image function which corrupt the image, we have to check most well know functions like sharp or mathematical morphology.

| Parameter | Type | Description |
| --- | --- | --- |
| `$value` | `int` | : Deconvolution mode which defines level of image degradation. |

### HighPerformance {#highperformance}

**Access:** Read-only

**Static:** Yes

HighPerformance recognition quality preset. High quality barcodes are recognized well in this mode.

### HighQuality {#highquality}

**Access:** Read-only

**Static:** Yes

**Returns:** QualitySettings HighQuality recognition quality preset.

HighQuality recognition quality preset. This preset is developed for low quality barcodes.

### InverseImage {#inverseimage}

**Access:** Read/Write

**Returns:** int : Additional recognition of barcodes on images with inverse colors

Mode which enables or disables additional recognition of barcodes on images with inverted colors (luminance).

Mode which enables or disables additional recognition of barcodes on images with inverted colors (luminance).

| Parameter | Type | Description |
| --- | --- | --- |
| `$value` | `int` | : Additional recognition of barcodes on images with inverse colors |

### MaxQuality {#maxquality}

**Access:** Read-only

**Static:** Yes

MaxQuality recognition quality preset. This preset is developed to recognize all possible barcodes, even incorrect barcodes. Value: MaxQuality recognition quality preset.

### MinimalXDimension {#minimalxdimension}

**Access:** Read/Write

**Returns:** float : Minimal size of XDimension in pixels which is used with UseMinimalXDimension.

Minimal size of XDimension in pixels which is used with UseMinimalXDimension.

Minimal size of XDimension in pixels which is used with UseMinimalXDimension.

| Parameter | Type | Description |
| --- | --- | --- |
| `$value` | `float` | : Minimal size of XDimension in pixels which is used with UseMinimalXDimension. |

### NormalQuality {#normalquality}

**Access:** Read-only

**Static:** Yes

**Returns:** QualitySettings NormalQuality recognition quality preset.

NormalQuality recognition quality preset. Suitable for the most of barcodes

### XDimension {#xdimension}

**Access:** Read/Write

**Returns:** int : size (from 1 to infinity) of barcode minimal element: matrix cell or bar.

Recognition mode which sets size (from 1 to infinity) of barcode minimal element: matrix cell or bar.

Recognition mode which sets size (from 1 to infinity) of barcode minimal element: matrix cell or bar.

| Parameter | Type | Description |
| --- | --- | --- |
| `$value` | `int` |  |

