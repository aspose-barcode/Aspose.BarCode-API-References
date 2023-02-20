---
title: IBarCodeGeneratorControl
second_title: Aspose.BarCode for Java API Reference
description: IBarCodeGeneratorControl for TypeConverters
type: docs
weight: 18
url: /java/com.aspose.barcode.component/ibarcodegeneratorcontrol/
---```
public interface IBarCodeGeneratorControl
```

IBarCodeGeneratorControl for TypeConverters
## Methods

| Method | Description |
| --- | --- |
| [getBarcodeType()](#getBarcodeType--) | BarCode's encode type (symbology). |
| [getRotationAngle()](#getRotationAngle--) | BarCode image rotation angle, measured in degree, e.g. |
| [setBarcodeType(BaseEncodeType value)](#setBarcodeType-com.aspose.barcode.generation.BaseEncodeType-) | BarCode's encode type (symbology). |
| [setRotationAngle(float value)](#setRotationAngle-float-) | BarCode image rotation angle, measured in degree, e.g. |
### getBarcodeType() {#getBarcodeType--}
```
public abstract BaseEncodeType getBarcodeType()
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
### setBarcodeType(BaseEncodeType value) {#setBarcodeType-com.aspose.barcode.generation.BaseEncodeType-}
```
public abstract void setBarcodeType(BaseEncodeType value)
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

