---
title: "BaseGenerationParameters Class"
linktitle: "BaseGenerationParameters"
articleTitle: "BaseGenerationParameters"
second_title: "Aspose.BarCode for Python via Java"
description: "Barcode image generation parameters."
type: docs
weight: 10
url: /python-java/aspose_barcode.generation.base_generation_parameters/basegenerationparameters/
---

## BaseGenerationParameters class

**Module:** `aspose_barcode.generation.base_generation_parameters`


Barcode image generation parameters.


## Constructors

| Name | Description |
| --- | --- |
| [__init__](./basegenerationparameters/) |  |

## Methods

| Name | Return Type | Static | Description |
| --- | --- | --- | --- |
| [barcode](./barcode/) | `BarcodeParameters` | No | Gets the BarcodeParameters that contains all barcode properties. |
| [border](./border/) | `BorderParameters` | No | Gets the BorderParameters that contains all configuration properties for barcode border. |
| [caption_above](./caption_above/) | `CaptionParameters` | No | Caption Above the BarCode image. See CaptionParameters. |
| [caption_below](./caption_below/) | `CaptionParameters` | No | Caption Below the BarCode image. See CaptionParameters. |
| [image](./image/) | `ImageParameters` | No |  |

## Properties

| Name | Type | Description |
| --- | --- | --- |
| [auto_size_mode](./auto_size_mode/) | `AutoSizeMode` | Specifies the different types of automatic sizing modes. Default value: AutoSizeMode.NONE. |
| [back_color](./back_color/) | `Tuple[int, int, int]` |  |
| [image_height](./image_height/) | `Unit` | BarCode image height when AutoSizeMode property is set to AutoSizeMode.NEAREST or AutoSizeMode.INTERPOLATION. |
| [image_width](./image_width/) | `Unit` | BarCode image width when AutoSizeMode property is set to AutoSizeMode.NEAREST or AutoSizeMode.INTERPOLATION. |
| [resolution](./resolution/) | `float` | Gets the resolution of the BarCode image. One value for both dimensions. Default value: 96 dpi. The Resolution parameter value is less than or equal to 0. |
| [rotation_angle](./rotation_angle/) | `float` | BarCode image rotation angle, measured in degree, e.g. RotationAngle = 0 or RotationAngle = 360 means no rotation. If RotationAngle NOT equal to 90, 180, 270 or 0, it may increase the difficulty for the scanner to read the image. Default value: 0. This sample shows how to create and save a BarCode image. |
| [use_anti_alias](./use_anti_alias/) | `bool` |  |
