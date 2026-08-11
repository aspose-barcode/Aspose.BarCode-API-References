---
title: "AutoSizeMode"
linktitle: "AutoSizeMode"
second_title: "Aspose.BarCode for Python via Java"
description: "Specifies the different types of automatic sizing modes. Default value is AutoSizeMode.NONE. This sample shows how to create and save a BarCode image."
type: docs
weight: 10
url: /python-java/aspose_barcode.generation/autosizemode/
---

## AutoSizeMode enum

**Module:** `aspose_barcode.generation.auto_size_mode`


Specifies the different types of automatic sizing modes. Default value is AutoSizeMode.NONE. This sample shows how to create and save a BarCode image.


## Enum Values

| Name | Value | Description |
| --- | --- | --- |
| [INTERPOLATION](#interpolation) | `2` |  |
| [NEAREST](#nearest) | `1` | Barcode resizes to nearest lowest possible size which are specified by BarCodeWidth and BarCodeHeight properties. Resizes barcode to specified size with little scaling but it can be little damaged in some cases because using interpolation for scaling. Size can be specified by BarcodeGenerator.BarCodeWidth and BarcodeGenerator.BarCodeHeight properties. This sample shows how to create and save a BarCode image in Scale mode. |
| [NONE](#none) | `0` | Automatic resizing is disabled. Default value. |
### AutoSizeMode.INTERPOLATION {#interpolation}

**Type:** `int`

**Value:** `2`

### AutoSizeMode.NEAREST {#nearest}

**Type:** `int`

**Value:** `1`

Barcode resizes to nearest lowest possible size which are specified by BarCodeWidth and BarCodeHeight properties. Resizes barcode to specified size with little scaling but it can be little damaged in some cases because using interpolation for scaling. Size can be specified by BarcodeGenerator.BarCodeWidth and BarcodeGenerator.BarCodeHeight properties. This sample shows how to create and save a BarCode image in Scale mode.

### AutoSizeMode.NONE {#none}

**Type:** `int`

**Value:** `0`

Automatic resizing is disabled. Default value.

