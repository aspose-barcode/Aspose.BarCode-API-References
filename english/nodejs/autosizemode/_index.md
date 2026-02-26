---
title: "AutoSizeMode Enum"
linktitle: "AutoSizeMode"
articleTitle: "AutoSizeMode"
second_title: "Aspose.BarCode for Node.js via Java"
description: "Specifies the different types of automatic sizing modes. Default value is AutoSizeMode.NONE."
type: docs
weight: 1020
url: /nodejs/autosizemode/
---
## AutoSizeMode enumeration

Specifies the different types of automatic sizing modes. Default value is AutoSizeMode.NONE.

```javascript
public enum AutoSizeMode
```

## Values

| Name | Value | Description |
| --- | :---: | --- |
| NONE | `0` | Automatic resizing is disabled. Default value. |
| NEAREST | `1` | Barcode resizes to nearest lowest possible size which are specified by BarCodeWidth and BarCodeHeight properties. |
| INTERPOLATION | `2` | Resizes barcode to specified size with little scaling but it can be little damaged in some cases because using interpolation for scaling. Size can be specified by BarcodeGenerator.BarCodeWidth and BarcodeGenerator.BarCodeHeight properties. This sample shows how to create and save a BarCode image in Scale mode. let generator = new BarcodeGenerator( EncodeTypes.DATA_MATRIX); generator.getParameters().getBarcode().setAutoSizeMode(AutoSizeMode.INTERPOLATION); generator.getParameters().getBarcode().getBarCodeWidth().setMillimeters(50); generator.getParameters().getBarcode().getBarCodeHeight().setInches(1.3); generator.save("test.png", BarcodeImageFormat.PNG); |

## Examples

```javascript
//This sample shows how to create and save a BarCode image:
let generator = new BarcodeGenerator(EncodeTypes.DATA_MATRIX);
generator.setAutoSizeMode(AutoSizeMode.NEAREST);
generator.getBarCodeWidth().setMillimeters(50);
generator.getBarCodeHeight().setInches(1.3f);
generator.save("test.png", BarcodeImageFormat.PNG);
```

### See Also

* assembly [Aspose.BarCode](../)

