---
title: "BaseGenerationParameters"
linktitle: "BaseGenerationParameters"
second_title: "Aspose.BarCode for Python via Java"
description: "Barcode image generation parameters."
type: docs
weight: 10
url: /python-java/aspose_barcode.generation/basegenerationparameters/
---

## BaseGenerationParameters class

**Module:** `aspose_barcode.generation.base_generation_parameters`


Barcode image generation parameters.


## Constructors

| Name | Description |
| --- | --- |
| [__init__](#constructor) |  |

## Methods

| Name | Return Type | Static | Description |
| --- | --- | --- | --- |
| [barcode](#barcode) | `BarcodeParameters` | No | Gets the BarcodeParameters that contains all barcode properties. |
| [border](#border) | `BorderParameters` | No | Gets the BorderParameters that contains all configuration properties for barcode border. |
| [caption_above](#caption_above) | `CaptionParameters` | No | Caption Above the BarCode image. See CaptionParameters. |
| [caption_below](#caption_below) | `CaptionParameters` | No | Caption Below the BarCode image. See CaptionParameters. |
| [image](#image) | `ImageParameters` | No |  |

## Properties

| Name | Type | Description |
| --- | --- | --- |
| [auto_size_mode](#auto_size_mode) | `AutoSizeMode` | Specifies the different types of automatic sizing modes. Default value: AutoSizeMode.NONE. |
| [back_color](#back_color) | `Tuple[int, int, int]` |  |
| [image_height](#image_height) | `Unit` | BarCode image height when AutoSizeMode property is set to AutoSizeMode.NEAREST or AutoSizeMode.INTERPOLATION. |
| [image_width](#image_width) | `Unit` | BarCode image width when AutoSizeMode property is set to AutoSizeMode.NEAREST or AutoSizeMode.INTERPOLATION. |
| [resolution](#resolution) | `float` | Gets the resolution of the BarCode image. One value for both dimensions. Default value: 96 dpi. The Resolution parameter value is less than or equal to 0. |
| [rotation_angle](#rotation_angle) | `float` | BarCode image rotation angle, measured in degree, e.g. RotationAngle = 0 or RotationAngle = 360 means no rotation. If RotationAngle NOT equal to 90, 180, 270 or 0, it may increase the difficulty for the scanner to read the image. Default value: 0. This sample shows how to create and save a BarCode image. |
| [use_anti_alias](#use_anti_alias) | `bool` |  |

### BaseGenerationParameters Constructor {#constructor}

```python
__init__(self, _java_class) -> def
```

| Parameter | Type | Description |
| --- | --- | --- |
| `_java_class` | `` |  |

### BaseGenerationParameters.barcode {#barcode}

```python
barcode(self) -> BarcodeParameters
```

Gets the BarcodeParameters that contains all barcode properties.

**Return Type:** `BarcodeParameters`

### BaseGenerationParameters.border {#border}

```python
border(self) -> BorderParameters
```

Gets the BorderParameters that contains all configuration properties for barcode border.

**Return Type:** `BorderParameters`

### BaseGenerationParameters.caption_above {#caption_above}

```python
caption_above(self) -> CaptionParameters
```

Caption Above the BarCode image. See CaptionParameters.

**Return Type:** `CaptionParameters`

### BaseGenerationParameters.caption_below {#caption_below}

```python
caption_below(self) -> CaptionParameters
```

Caption Below the BarCode image. See CaptionParameters.

**Return Type:** `CaptionParameters`

### BaseGenerationParameters.image {#image}

```python
image(self) -> ImageParameters
```

**Return Type:** `ImageParameters`

### BaseGenerationParameters.auto_size_mode {#auto_size_mode}

**Type:** `AutoSizeMode`

Specifies the different types of automatic sizing modes. Default value: AutoSizeMode.NONE.

Specifies the different types of automatic sizing modes. Default value: AutoSizeMode.NONE.

| Parameter | Type | Description |
| --- | --- | --- |
| `value` | `AutoSizeMode` |  |

### BaseGenerationParameters.back_color {#back_color}

**Type:** `Tuple[int, int, int]`

| Parameter | Type | Description |
| --- | --- | --- |
| `value` | `Tuple[int, int, int]` |  |

### BaseGenerationParameters.image_height {#image_height}

**Type:** `Unit`

BarCode image height when AutoSizeMode property is set to AutoSizeMode.NEAREST or AutoSizeMode.INTERPOLATION.

BarCode image height when AutoSizeMode property is set to AutoSizeMode.NEAREST or AutoSizeMode.INTERPOLATION.

| Parameter | Type | Description |
| --- | --- | --- |
| `value` | `Unit` |  |

### BaseGenerationParameters.image_width {#image_width}

**Type:** `Unit`

BarCode image width when AutoSizeMode property is set to AutoSizeMode.NEAREST or AutoSizeMode.INTERPOLATION.

BarCode image width when AutoSizeMode property is set to AutoSizeMode.NEAREST or AutoSizeMode.INTERPOLATION.

| Parameter | Type | Description |
| --- | --- | --- |
| `value` | `Unit` |  |

### BaseGenerationParameters.resolution {#resolution}

**Type:** `float`

Gets the resolution of the BarCode image. One value for both dimensions. Default value: 96 dpi. The Resolution parameter value is less than or equal to 0.

Sets the resolution of the BarCode image. One value for both dimensions. Default value: 96 dpi. The Resolution parameter value is less than or equal to 0.

| Parameter | Type | Description |
| --- | --- | --- |
| `value` | `float` |  |

### BaseGenerationParameters.rotation_angle {#rotation_angle}

**Type:** `float`

BarCode image rotation angle, measured in degree, e.g. RotationAngle = 0 or RotationAngle = 360 means no rotation. If RotationAngle NOT equal to 90, 180, 270 or 0, it may increase the difficulty for the scanner to read the image. Default value: 0. This sample shows how to create and save a BarCode image.

BarCode image rotation angle, measured in degree, e.g. RotationAngle = 0 or RotationAngle = 360 means no rotation. If RotationAngle NOT equal to 90, 180, 270 or 0, it may increase the difficulty for the scanner to read the image. Default value: 0. This sample shows how to create and save a BarCode image.

| Parameter | Type | Description |
| --- | --- | --- |
| `value` | `float` |  |

### BaseGenerationParameters.use_anti_alias {#use_anti_alias}

**Type:** `bool`

| Parameter | Type | Description |
| --- | --- | --- |
| `value` | `bool` |  |

