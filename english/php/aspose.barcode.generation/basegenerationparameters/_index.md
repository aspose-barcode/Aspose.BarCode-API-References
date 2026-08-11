---
title: "BaseGenerationParameters"
linktitle: "BaseGenerationParameters"
second_title: "Aspose.BarCode for PHP via Java"
description: "Barcode image generation parameters."
type: docs
weight: 10
url: /php/aspose.barcode.generation/basegenerationparameters/
---

## BaseGenerationParameters class

**Namespace:** `Aspose.Barcode.Generation`


Barcode image generation parameters.


## Constructors

| Name | Description |
| --- | --- |
| [__construct](#constructor) |  |

## Properties

| Name | Read/Write | Description |
| --- | --- | --- |
| [AutoSizeMode](#autosizemode) | Read/Write | Specifies the different types of automatic sizing modes. Default value: AutoSizeMode::NONE. |
| [BackColor](#backcolor) | Read/Write | Background color of the barcode image. Default value: #FFFFFF |
| [Barcode](#barcode) | Read/Write | Gets the BarcodeParameters that contains all barcode properties. |
| [Border](#border) | Read-only | Gets the BorderParameters that contains all configuration properties for barcode border. |
| [CaptionAbove](#captionabove) | Read/Write | Caption Above the BarCode image. |
| [CaptionBelow](#captionbelow) | Read/Write | Caption Below the BarCode image. |
| [Image](#image) | Read-only | Image parameters. See ImageParameters. |
| [ImageHeight](#imageheight) | Read/Write | BarCode image height when AutoSizeMode property is set to AutoSizeMode::NEAREST or AutoSizeMode::INTERPOLATION. |
| [ImageWidth](#imagewidth) | Read/Write | BarCode image width when AutoSizeMode property is set to AutoSizeMode.NEAREST or AutoSizeMode::INTERPOLATION. |
| [Resolution](#resolution) | Read/Write | Gets the resolution of the BarCode image. One value for both dimensions. Default value: 96 dpi. |
| [RotationAngle](#rotationangle) | Read/Write | BarCode image rotation angle, measured in degree, e.g. RotationAngle = 0 or RotationAngle = 360 means no rotation. If RotationAngle NOT equal to 90, 180, 270 or 0, it may increase the difficulty for the scanner to read the image. Default value: 0. This sample shows how to create and save a BarCode image. |
| [UseAntiAlias](#useantialias) | Read/Write | Gets a value indicating whether is used anti-aliasing mode to render image |

### BaseGenerationParameters__construct(BaseGenerationParametersDTO $baseGenerationParametersDto) {#constructor}

| Parameter | Type | Description |
| --- | --- | --- |
| `$baseGenerationParametersDto` | `BaseGenerationParametersDTO` |  |

### AutoSizeMode {#autosizemode}

**Access:** Read/Write

Specifies the different types of automatic sizing modes. Default value: AutoSizeMode::NONE.

Specifies the different types of automatic sizing modes. Default value: AutoSizeMode::NONE.

| Parameter | Type | Description |
| --- | --- | --- |
| `$value` | `int` |  |

### BackColor {#backcolor}

**Access:** Read/Write

**Returns:** string value of background color.

Background color of the barcode image. Default value: #FFFFFF

Background color of the barcode image. Default value: #FFFFFF

| Parameter | Type | Description |
| --- | --- | --- |
| `$hexValue` | `string` |  |

### Barcode {#barcode}

**Access:** Read/Write

Gets the BarcodeParameters that contains all barcode properties.

Gets the BarcodeParameters that contains all barcode properties.

| Parameter | Type | Description |
| --- | --- | --- |
| `$value` | `BarcodeParameters` |  |

### Border {#border}

**Access:** Read-only

Gets the BorderParameters that contains all configuration properties for barcode border.

### CaptionAbove {#captionabove}

**Access:** Read/Write

Caption Above the BarCode image.

Caption Above the BarCode image.

| Parameter | Type | Description |
| --- | --- | --- |
| `$value` | `CaptionParameters` |  |

### CaptionBelow {#captionbelow}

**Access:** Read/Write

Caption Below the BarCode image.

Caption Below the BarCode image.

| Parameter | Type | Description |
| --- | --- | --- |
| `$value` | `CaptionParameters` |  |

### Image {#image}

**Access:** Read-only

Image parameters. See ImageParameters.

### ImageHeight {#imageheight}

**Access:** Read/Write

BarCode image height when AutoSizeMode property is set to AutoSizeMode::NEAREST or AutoSizeMode::INTERPOLATION.

BarCode image height when AutoSizeMode property is set to AutoSizeMode.NEAREST or AutoSizeMode::INTERPOLATION.

| Parameter | Type | Description |
| --- | --- | --- |
| `$value` | `Unit` |  |

### ImageWidth {#imagewidth}

**Access:** Read/Write

BarCode image width when AutoSizeMode property is set to AutoSizeMode.NEAREST or AutoSizeMode::INTERPOLATION.

BarCode image width when AutoSizeMode property is set to AutoSizeMode.NEAREST or AutoSizeMode::INTERPOLATION.

| Parameter | Type | Description |
| --- | --- | --- |
| `$value` | `Unit` |  |

### Resolution {#resolution}

**Access:** Read/Write

**Returns:** float The Resolution parameter value is less than or equal to 0.

Gets the resolution of the BarCode image. One value for both dimensions. Default value: 96 dpi.

Sets the resolution of the BarCode image. One value for both dimensions. Default value: 96 dpi.

| Parameter | Type | Description |
| --- | --- | --- |
| `$value` | `float` |  |

### RotationAngle {#rotationangle}

**Access:** Read/Write

BarCode image rotation angle, measured in degree, e.g. RotationAngle = 0 or RotationAngle = 360 means no rotation. If RotationAngle NOT equal to 90, 180, 270 or 0, it may increase the difficulty for the scanner to read the image. Default value: 0. This sample shows how to create and save a BarCode image.

BarCode image rotation angle, measured in degree, e.g. RotationAngle = 0 or RotationAngle = 360 means no rotation. If RotationAngle NOT equal to 90, 180, 270 or 0, it may increase the difficulty for the scanner to read the image. Default value: 0. This sample shows how to create and save a BarCode image.

| Parameter | Type | Description |
| --- | --- | --- |
| `$value` | `float` |  |

### UseAntiAlias {#useantialias}

**Access:** Read/Write

Gets a value indicating whether is used anti-aliasing mode to render image

Sets a value indicating whether is used anti-aliasing mode to render image

| Parameter | Type | Description |
| --- | --- | --- |
| `$value` | `bool` |  |

