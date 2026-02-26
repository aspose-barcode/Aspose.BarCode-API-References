---
title: XDimensionMode Enum
linktitle: XDimensionMode
articleTitle: XDimensionMode
second_title: Aspose.BarCode for Node.js via Java
description: Recognition mode which sets size (from 1 to infinity) of barcode minimal element: matrix cell or bar.
type: docs
weight: 1540
url: /nodejs/xdimensionmode/
---
## XDimensionMode enumeration

Recognition mode which sets size (from 1 to infinity) of barcode minimal element: matrix cell or bar.

```javascript
public enum XDimensionMode
```

## Values

| Name | Value | Description |
| --- | :---: | --- |
| AUTO | `0` | Value of XDimension is detected by AI (SVM). At this time the same as Normal |
| SMALL | `1` | Detects barcodes with small XDimension in 1 pixel or more with quality from BarcodeQuality |
| NORMAL | `2` | Detects barcodes with classic XDimension in 2 pixels or more with quality from BarcodeQuality or high quality barcodes. |
| LARGE | `3` | Detects barcodes with large XDimension with quality from BarcodeQuality captured with high-resolution cameras. |
| USE_MINIMAL_X_DIMENSION | `4` | Detects barcodes from size set in MinimalXDimension with quality from BarcodeQuality |

### See Also

* assembly [Aspose.BarCode](../)

