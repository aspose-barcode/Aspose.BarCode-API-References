---
title: "DeconvolutionMode"
linktitle: "DeconvolutionMode"
second_title: "Aspose.BarCode for Python via Java"
description: "Deconvolution (image restorations) mode which defines level of image degradation. Originally deconvolution is a function which can restore image degraded (convo"
type: docs
weight: 10
url: /python-java/aspose_barcode.recognition/deconvolutionmode/
---

## DeconvolutionMode enum

**Module:** `aspose_barcode.recognition.deconvolution_mode`


Deconvolution (image restorations) mode which defines level of image degradation. Originally deconvolution is a function which can restore image degraded (convoluted) by any natural function like blur, during obtaining image by camera. Because we cannot detect image function which corrupt the image, we have to check most well know functions like sharp or mathematical morphology. This sample shows how to use Deconvolution mode


## Enum Values

| Name | Value | Description |
| --- | --- | --- |
| [FAST](#fast) | `0` | Enables fast deconvolution methods for high quality images. |
| [NORMAL](#normal) | `1` | Enables normal deconvolution methods for common images. |
| [SLOW](#slow) | `2` | Enables slow deconvolution methods for low quality images. |
### DeconvolutionMode.FAST {#fast}

**Type:** `int`

**Value:** `0`

Enables fast deconvolution methods for high quality images.

### DeconvolutionMode.NORMAL {#normal}

**Type:** `int`

**Value:** `1`

Enables normal deconvolution methods for common images.

### DeconvolutionMode.SLOW {#slow}

**Type:** `int`

**Value:** `2`

Enables slow deconvolution methods for low quality images.

