---
title: BaseGenerationParameters
second_title: Aspose.BarCode for Android via Java API Reference
description: Barcode image generation parameters.
type: docs
weight: 17
url: /androidjava/com.aspose.barcode.generation/basegenerationparameters/
---
**Inheritance:**
java.lang.Object
```
public class BaseGenerationParameters
```

Barcode image generation parameters.
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAutoSizeMode()](#getAutoSizeMode--) | Specifies the different types of automatic sizing modes. |
| [getBackColor()](#getBackColor--) | Background color of the barcode image. |
| [getBarcode()](#getBarcode--) | Gets the  BarcodeParameters  that contains all barcode properties. |
| [getBorder()](#getBorder--) | Gets the  BorderParameters  that contains all configuration properties for barcode border. |
| [getCaptionAbove()](#getCaptionAbove--) | Caption Above the BarCode image. |
| [getCaptionBelow()](#getCaptionBelow--) | Caption Below the BarCode image. |
| [getClass()](#getClass--) |  |
| [getImage()](#getImage--) | Image parameters. |
| [getImageHeight()](#getImageHeight--) | BarCode image height when  AutoSizeMode  property is set to AutoSizeMode.NEAREST or AutoSizeMode.INTERPOLATION. |
| [getImageWidth()](#getImageWidth--) | BarCode image width when  AutoSizeMode  property is set to AutoSizeMode.NEAREST or AutoSizeMode.INTERPOLATION. |
| [getResolution()](#getResolution--) | Gets the resolution of the BarCode image. |
| [getRotationAngle()](#getRotationAngle--) | BarCode image rotation angle, measured in degree, e.g. |
| [getUseAntiAlias()](#getUseAntiAlias--) | Gets a value indicating whether is used anti-aliasing mode to render image |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAutoSizeMode(AutoSizeMode value)](#setAutoSizeMode-com.aspose.barcode.generation.AutoSizeMode-) | Specifies the different types of automatic sizing modes. |
| [setBackColor(int value)](#setBackColor-int-) | Background color of the barcode image. |
| [setImageHeight(Unit value)](#setImageHeight-com.aspose.barcode.generation.Unit-) | BarCode image height when  AutoSizeMode  property is set to AutoSizeMode.NEAREST or AutoSizeMode.INTERPOLATION. |
| [setImageWidth(Unit value)](#setImageWidth-com.aspose.barcode.generation.Unit-) | BarCode image width when  AutoSizeMode  property is set to AutoSizeMode.NEAREST or AutoSizeMode.INTERPOLATION. |
| [setResolution(float value)](#setResolution-float-) | Sets the resolution of the BarCode image. |
| [setRotationAngle(float value)](#setRotationAngle-float-) | BarCode image rotation angle, measured in degree, e.g. |
| [setUseAntiAlias(boolean value)](#setUseAntiAlias-boolean-) | Sets a value indicating whether is used anti-aliasing mode to render image |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getAutoSizeMode() {#getAutoSizeMode--}
```
public AutoSizeMode getAutoSizeMode()
```


Specifies the different types of automatic sizing modes. Default value: AutoSizeMode.NONE.

**Returns:**
[AutoSizeMode](../../com.aspose.barcode.generation/autosizemode)
### getBackColor() {#getBackColor--}
```
public int getBackColor()
```


Background color of the barcode image. Default value: Color.White. See  Color .

**Returns:**
int
### getBarcode() {#getBarcode--}
```
public BarcodeParameters getBarcode()
```


Gets the  BarcodeParameters  that contains all barcode properties.

**Returns:**
[BarcodeParameters](../../com.aspose.barcode.generation/barcodeparameters)
### getBorder() {#getBorder--}
```
public BorderParameters getBorder()
```


Gets the  BorderParameters  that contains all configuration properties for barcode border.

**Returns:**
[BorderParameters](../../com.aspose.barcode.generation/borderparameters)
### getCaptionAbove() {#getCaptionAbove--}
```
public CaptionParameters getCaptionAbove()
```


Caption Above the BarCode image. See  CaptionParameters .

**Returns:**
[CaptionParameters](../../com.aspose.barcode.generation/captionparameters)
### getCaptionBelow() {#getCaptionBelow--}
```
public CaptionParameters getCaptionBelow()
```


Caption Below the BarCode image. See  CaptionParameters .

**Returns:**
[CaptionParameters](../../com.aspose.barcode.generation/captionparameters)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getImage() {#getImage--}
```
public ImageParameters getImage()
```


Image parameters. See .

**Returns:**
[ImageParameters](../../com.aspose.barcode.generation/imageparameters) - 
### getImageHeight() {#getImageHeight--}
```
public Unit getImageHeight()
```


BarCode image height when  AutoSizeMode  property is set to AutoSizeMode.NEAREST or AutoSizeMode.INTERPOLATION.

**Returns:**
[Unit](../../com.aspose.barcode.generation/unit)
### getImageWidth() {#getImageWidth--}
```
public Unit getImageWidth()
```


BarCode image width when  AutoSizeMode  property is set to AutoSizeMode.NEAREST or AutoSizeMode.INTERPOLATION.

**Returns:**
[Unit](../../com.aspose.barcode.generation/unit)
### getResolution() {#getResolution--}
```
public float getResolution()
```


Gets the resolution of the BarCode image. One value for both dimensions. Default value: 96 dpi.

**Returns:**
float
### getRotationAngle() {#getRotationAngle--}
```
public float getRotationAngle()
```


BarCode image rotation angle, measured in degree, e.g. RotationAngle = 0 or RotationAngle = 360 means no rotation. If RotationAngle NOT equal to 90, 180, 270 or 0, it may increase the difficulty for the scanner to read the image. Default value: 0.

--------------------

> ```
> This sample shows how to create and save a BarCode image.
>   
>  	  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DATA_MATRIX);
>  	  generator.getParameters().setRotationAngle(7f);
>     generator.save("test.png");
> ```

**Returns:**
float
### getUseAntiAlias() {#getUseAntiAlias--}
```
public boolean getUseAntiAlias()
```


Gets a value indicating whether is used anti-aliasing mode to render image

**Returns:**
boolean
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setAutoSizeMode(AutoSizeMode value) {#setAutoSizeMode-com.aspose.barcode.generation.AutoSizeMode-}
```
public void setAutoSizeMode(AutoSizeMode value)
```


Specifies the different types of automatic sizing modes. Default value: AutoSizeMode.NONE.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [AutoSizeMode](../../com.aspose.barcode.generation/autosizemode) |  |

### setBackColor(int value) {#setBackColor-int-}
```
public void setBackColor(int value)
```


Background color of the barcode image. Default value: Color.White. See  Color .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setImageHeight(Unit value) {#setImageHeight-com.aspose.barcode.generation.Unit-}
```
public void setImageHeight(Unit value)
```


BarCode image height when  AutoSizeMode  property is set to AutoSizeMode.NEAREST or AutoSizeMode.INTERPOLATION.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Unit](../../com.aspose.barcode.generation/unit) |  |

### setImageWidth(Unit value) {#setImageWidth-com.aspose.barcode.generation.Unit-}
```
public void setImageWidth(Unit value)
```


BarCode image width when  AutoSizeMode  property is set to AutoSizeMode.NEAREST or AutoSizeMode.INTERPOLATION.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Unit](../../com.aspose.barcode.generation/unit) |  |

### setResolution(float value) {#setResolution-float-}
```
public void setResolution(float value)
```


Sets the resolution of the BarCode image. One value for both dimensions. Default value: 96 dpi.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### setRotationAngle(float value) {#setRotationAngle-float-}
```
public void setRotationAngle(float value)
```


BarCode image rotation angle, measured in degree, e.g. RotationAngle = 0 or RotationAngle = 360 means no rotation. If RotationAngle NOT equal to 90, 180, 270 or 0, it may increase the difficulty for the scanner to read the image. Default value: 0.

--------------------

> ```
> This sample shows how to create and save a BarCode image.
>   
>  	  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DATA_MATRIX);
>  	  generator.getParameters().setRotationAngle(7f);
>     generator.save("test.png");
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### setUseAntiAlias(boolean value) {#setUseAntiAlias-boolean-}
```
public void setUseAntiAlias(boolean value)
```


Sets a value indicating whether is used anti-aliasing mode to render image

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

