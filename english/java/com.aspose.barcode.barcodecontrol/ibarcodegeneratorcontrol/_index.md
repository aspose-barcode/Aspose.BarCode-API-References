---
title: IBarCodeGeneratorControl
second_title: Aspose.BarCode for Java API Reference
description: Interface declares obligatory methods for classes intended  for use in UI with generating barcode
type: docs
weight: 19
url: /java/com.aspose.barcode.barcodecontrol/ibarcodegeneratorcontrol/
---```
public interface IBarCodeGeneratorControl
```

Interface declares obligatory methods for classes intended for use in UI with generating barcode
## Methods

| Method | Description |
| --- | --- |
| [getEncodeType()](#getEncodeType--) | BarCode's encode type (symbology). |
| [getRotationAngle()](#getRotationAngle--) | BarCode image rotation angle, measured in degree, e.g. |
| [setEncodeType(BaseEncodeType value)](#setEncodeType-com.aspose.barcode.generation.BaseEncodeType-) | BarCode's encode type (symbology). |
| [setRotationAngle(float value)](#setRotationAngle-float-) | BarCode image rotation angle, measured in degree, e.g. |
### getEncodeType() {#getEncodeType--}
```
public abstract BaseEncodeType getEncodeType()
```


BarCode's encode type (symbology).

**Returns:**
[BaseEncodeType](../../com.aspose.barcode.generation/baseencodetype)
### getRotationAngle() {#getRotationAngle--}
```
public abstract float getRotationAngle()
```


BarCode image rotation angle, measured in degree, e.g. RotationAngle = 0 or RotationAngle = 360 means no rotation. If RotationAngle NOT equal to 90, 180, 270 or 0, it may increase the difficulty for the scanner to read the image.

**Returns:**
float
### setEncodeType(BaseEncodeType value) {#setEncodeType-com.aspose.barcode.generation.BaseEncodeType-}
```
public abstract void setEncodeType(BaseEncodeType value)
```


BarCode's encode type (symbology).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [BaseEncodeType](../../com.aspose.barcode.generation/baseencodetype) |  |

### setRotationAngle(float value) {#setRotationAngle-float-}
```
public abstract void setRotationAngle(float value)
```


BarCode image rotation angle, measured in degree, e.g. RotationAngle = 0 or RotationAngle = 360 means no rotation. If RotationAngle NOT equal to 90, 180, 270 or 0, it may increase the difficulty for the scanner to read the image.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

