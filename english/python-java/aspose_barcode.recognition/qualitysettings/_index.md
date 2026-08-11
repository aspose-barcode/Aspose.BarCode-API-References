---
title: "QualitySettings"
linktitle: "QualitySettings"
second_title: "Aspose.BarCode for Python via Java"
description: "QualitySettings allows to configure recognition quality and speed manually. You can quickly set up QualitySettings by embedded presets: HighPerformance, NormalQ"
type: docs
weight: 10
url: /python-java/aspose_barcode.recognition/qualitysettings/
---

## QualitySettings class

**Module:** `aspose_barcode.recognition.quality_settings`


QualitySettings allows to configure recognition quality and speed manually. You can quickly set up QualitySettings by embedded presets: HighPerformance, NormalQuality, HighQuality, MaxBarCodes or you can manually configure separate options. Default value of QualitySettings is NormalQuality. This sample shows how to use QualitySettings with BarCodeReader


## Constructors

| Name | Description |
| --- | --- |
| [__init__](#constructor) |  |

## Methods

| Name | Return Type | Static | Description |
| --- | --- | --- | --- |
| [high_performance](#high_performance) | `QualitySettings` | Yes |  |
| [high_quality](#high_quality) | `QualitySettings` | Yes |  |
| [max_quality](#max_quality) | `QualitySettings` | Yes |  |
| [normal_quality](#normal_quality) | `QualitySettings` | Yes |  |

## Properties

| Name | Type | Description |
| --- | --- | --- |
| [allow_incorrect_barcodes](#allow_incorrect_barcodes) | `bool` |  |
| [barcode_quality](#barcode_quality) | `BarcodeQualityMode` |  |
| [complex_background](#complex_background) | `ComplexBackgroundMode` |  |
| [deconvolution](#deconvolution) | `DeconvolutionMode` |  |
| [inverse_image](#inverse_image) | `InverseImageMode` |  |
| [minimal_x_dimension](#minimal_x_dimension) | `int` |  |
| [x_dimension](#x_dimension) | `XDimensionMode` |  |

### QualitySettings Constructor {#constructor}

```python
__init__(self, _java_class) -> def
```

| Parameter | Type | Description |
| --- | --- | --- |
| `_java_class` | `` |  |

### QualitySettings.high_performance (static) {#high_performance}

```python
high_performance() -> QualitySettings
```

**Return Type:** `QualitySettings`

### QualitySettings.high_quality (static) {#high_quality}

```python
high_quality() -> QualitySettings
```

**Return Type:** `QualitySettings`

### QualitySettings.max_quality (static) {#max_quality}

```python
max_quality() -> QualitySettings
```

**Return Type:** `QualitySettings`

### QualitySettings.normal_quality (static) {#normal_quality}

```python
normal_quality() -> QualitySettings
```

**Return Type:** `QualitySettings`

### QualitySettings.allow_incorrect_barcodes {#allow_incorrect_barcodes}

**Type:** `bool`

| Parameter | Type | Description |
| --- | --- | --- |
| `value` | `bool` |  |

### QualitySettings.barcode_quality {#barcode_quality}

**Type:** `BarcodeQualityMode`

| Parameter | Type | Description |
| --- | --- | --- |
| `value` | `BarcodeQualityMode` |  |

### QualitySettings.complex_background {#complex_background}

**Type:** `ComplexBackgroundMode`

| Parameter | Type | Description |
| --- | --- | --- |
| `value` | `ComplexBackgroundMode` |  |

### QualitySettings.deconvolution {#deconvolution}

**Type:** `DeconvolutionMode`

| Parameter | Type | Description |
| --- | --- | --- |
| `value` | `DeconvolutionMode` |  |

### QualitySettings.inverse_image {#inverse_image}

**Type:** `InverseImageMode`

| Parameter | Type | Description |
| --- | --- | --- |
| `value` | `InverseImageMode` |  |

### QualitySettings.minimal_x_dimension {#minimal_x_dimension}

**Type:** `int`

| Parameter | Type | Description |
| --- | --- | --- |
| `value` | `int` |  |

### QualitySettings.x_dimension {#x_dimension}

**Type:** `XDimensionMode`

| Parameter | Type | Description |
| --- | --- | --- |
| `value` | `XDimensionMode` |  |

