---
title: "AutoSizeMode Enum"
linktitle: "AutoSizeMode"
articleTitle: "AutoSizeMode"
second_title: "Aspose.BarCode for PHP via Java"
description: "Specifies the different types of automatic sizing modes. Default value is AutoSizeMode::NONE. This sample shows how to create and save a BarCode image."
type: docs
weight: 10
url: /php/aspose/barcode/generation/autosizemode/
---

## AutoSizeMode enum

**Namespace:** `Aspose.Barcode.Generation`


Specifies the different types of automatic sizing modes. Default value is AutoSizeMode::NONE. This sample shows how to create and save a BarCode image.


## Enum Values

| Name | Value | Description |
| --- | --- | --- |
| [INTERPOLATION](/php/aspose/barcode/generation/autosizemode/interpolation/) | `'2'` | Resizes barcode to specified size with little scaling but it can be little damaged in some cases because using interpolation for scaling. Size can be specified by BarcodeGenerator.BarCodeWidth and BarcodeGenerator.BarCodeHeight properties. This sample shows how to create and save a BarCode image in Scale mode. |
| [NEAREST](/php/aspose/barcode/generation/autosizemode/nearest/) | `1` | Barcode resizes to nearest lowest possible size which are specified by BarCodeWidth and BarCodeHeight properties. |
| [NONE](/php/aspose/barcode/generation/autosizemode/none/) | `0` | Automatic resizing is disabled. Default value. |
