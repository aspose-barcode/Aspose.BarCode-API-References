---
title: DeconvolutionMode Enum
linktitle: DeconvolutionMode
articleTitle: DeconvolutionMode
second_title: Aspose.BarCode for Node.js via Java
description: "Deconvolution (image restorations) mode which defines level of image degradation. Originally deconvolution is a function which can restore image degraded (convoluted) by any natural function like blur, during obtaining image by camera. Because we cannot detect image function which corrupt the..."
type: docs
weight: 1520
url: /nodejs/deconvolutionmode/
---
## DeconvolutionMode enumeration

Deconvolution (image restorations) mode which defines level of image degradation. Originally deconvolution is a function which can restore image degraded (convoluted) by any natural function like blur, during obtaining image by camera. Because we cannot detect image function which corrupt the image, we have to check most well know functions like sharp or mathematical morphology.

```javascript
public enum DeconvolutionMode
```

## Values

| Name | Value | Description |
| --- | :---: | --- |
| FAST | `0` | Enables fast deconvolution methods for high quality images. |
| NORMAL | `1` | Enables normal deconvolution methods for common images. |
| SLOW | `2` | Enables slow deconvolution methods for low quality images. |

### See Also

* assembly [Aspose.BarCode](../)

