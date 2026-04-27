---
title: BaseGenerationParameters
second_title: Aspose.BarCode for Android via Java API-referens
description: Parametrar för generering av streckkodsbilder.
type: docs
weight: 17
url: /sv/androidjava/com.aspose.barcode.generation/basegenerationparameters/
---
**Inheritance:**
java.lang.Object
```
public class BaseGenerationParameters
```

Parametrar för generering av streckkodsbilder.
## Methods

| Method | Beskrivning |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAutoSizeMode()](#getAutoSizeMode--) | Anger de olika typerna av automatiska storleksinställningslägen. |
| [getBackColor()](#getBackColor--) | Background color of the barcode image. |
| [getBarcode()](#getBarcode--) | Gets the  BarcodeParameters  that contains all barcode properties. |
| [getBorder()](#getBorder--) | Gets the  BorderParameters  that contains all configuration properties for barcode border. |
| [getCaptionAbove()](#getCaptionAbove--) | Rubrik ovanför BarCode-bilden. |
| [getCaptionBelow()](#getCaptionBelow--) | Rubrik under BarCode-bilden. |
| [getClass()](#getClass--) |  |
| [getImage()](#getImage--) | Bildparametrar. |
| [getImageHeight()](#getImageHeight--) | BarCode-bildens höjd när egenskapen AutoSizeMode är inställd på AutoSizeMode.NEAREST eller AutoSizeMode.INTERPOLATION. |
| [getImageWidth()](#getImageWidth--) | BarCode-bildens bredd när egenskapen AutoSizeMode är inställd på AutoSizeMode.NEAREST eller AutoSizeMode.INTERPOLATION. |
| [getResolution()](#getResolution--) | Hämtar upplösningen för BarCode-bilden. |
| [getRotationAngle()](#getRotationAngle--) | BarCode-bildens rotationsvinkel, mätt i grader, t.ex. |
| [getUseAntiAlias()](#getUseAntiAlias--) | Hämtar ett värde som indikerar om anti-aliasing-läge används för att rendera bilden. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAutoSizeMode(AutoSizeMode value)](#setAutoSizeMode-com.aspose.barcode.generation.AutoSizeMode-) | Anger de olika typerna av automatiska storleksinställningslägen. |
| [setBackColor(int value)](#setBackColor-int-) | Background color of the barcode image. |
| [setImageHeight(Unit value)](#setImageHeight-com.aspose.barcode.generation.Unit-) | BarCode-bildens höjd när egenskapen AutoSizeMode är inställd på AutoSizeMode.NEAREST eller AutoSizeMode.INTERPOLATION. |
| [setImageWidth(Unit value)](#setImageWidth-com.aspose.barcode.generation.Unit-) | BarCode-bildens bredd när egenskapen AutoSizeMode är inställd på AutoSizeMode.NEAREST eller AutoSizeMode.INTERPOLATION. |
| [setResolution(float value)](#setResolution-float-) | Ställer in upplösningen för BarCode-bilden. |
| [setRotationAngle(float value)](#setRotationAngle-float-) | BarCode-bildens rotationsvinkel, mätt i grader, t.ex. |
| [setUseAntiAlias(boolean value)](#setUseAntiAlias-boolean-) | Ställer in ett värde som indikerar om anti-aliasing-läge används för att rendera bilden. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getAutoSizeMode() {#getAutoSizeMode--}
```
public AutoSizeMode getAutoSizeMode()
```


Anger de olika typerna av automatiska storleksinställningslägen. Standardvärde: AutoSizeMode.NONE.

**Returns:**
[AutoSizeMode](../../com.aspose.barcode.generation/autosizemode)
### getBackColor() {#getBackColor--}
```
public int getBackColor()
```


Bakgrundsfärg för streckkodsbilden. Standardvärde: Color.White. Se Color.

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


Rubrik ovanför BarCode-bilden. Se CaptionParameters.

**Returns:**
[CaptionParameters](../../com.aspose.barcode.generation/captionparameters)
### getCaptionBelow() {#getCaptionBelow--}
```
public CaptionParameters getCaptionBelow()
```


Rubrik under BarCode-bilden. Se CaptionParameters.

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


Bildparametrar. Se .

**Returns:**
[ImageParameters](../../com.aspose.barcode.generation/imageparameters) - 
### getImageHeight() {#getImageHeight--}
```
public Unit getImageHeight()
```


BarCode-bildens höjd när egenskapen AutoSizeMode är inställd på AutoSizeMode.NEAREST eller AutoSizeMode.INTERPOLATION.

**Returns:**
[Unit](../../com.aspose.barcode.generation/unit)
### getImageWidth() {#getImageWidth--}
```
public Unit getImageWidth()
```


BarCode-bildens bredd när egenskapen AutoSizeMode är inställd på AutoSizeMode.NEAREST eller AutoSizeMode.INTERPOLATION.

**Returns:**
[Unit](../../com.aspose.barcode.generation/unit)
### getResolution() {#getResolution--}
```
public float getResolution()
```


Hämtar upplösningen för BarCode-bilden. Ett värde för båda dimensionerna. Standardvärde: 96 dpi.

**Returns:**
float
### getRotationAngle() {#getRotationAngle--}
```
public float getRotationAngle()
```


BarCode-bildens rotationsvinkel, mätt i grader, t.ex. RotationAngle = 0 eller RotationAngle = 360 betyder ingen rotation. Om RotationAngle INTE är lika med 90, 180, 270 eller 0 kan det öka svårigheten för skannern att läsa bilden. Standardvärde: 0.

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


Hämtar ett värde som indikerar om anti-aliasing-läge används för att rendera bilden.

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


Anger de olika typerna av automatiska storleksinställningslägen. Standardvärde: AutoSizeMode.NONE.

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| value | [AutoSizeMode](../../com.aspose.barcode.generation/autosizemode) |  |

### setBackColor(int value) {#setBackColor-int-}
```
public void setBackColor(int value)
```


Bakgrundsfärg för streckkodsbilden. Standardvärde: Color.White. Se Color.

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setImageHeight(Unit value) {#setImageHeight-com.aspose.barcode.generation.Unit-}
```
public void setImageHeight(Unit value)
```


BarCode-bildens höjd när egenskapen AutoSizeMode är inställd på AutoSizeMode.NEAREST eller AutoSizeMode.INTERPOLATION.

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| value | [Unit](../../com.aspose.barcode.generation/unit) |  |

### setImageWidth(Unit value) {#setImageWidth-com.aspose.barcode.generation.Unit-}
```
public void setImageWidth(Unit value)
```


BarCode-bildens bredd när egenskapen AutoSizeMode är inställd på AutoSizeMode.NEAREST eller AutoSizeMode.INTERPOLATION.

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| value | [Unit](../../com.aspose.barcode.generation/unit) |  |

### setResolution(float value) {#setResolution-float-}
```
public void setResolution(float value)
```


Ställer in upplösningen för BarCode-bilden. Ett värde för båda dimensionerna. Standardvärde: 96 dpi.

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| värde | float |  |

### setRotationAngle(float value) {#setRotationAngle-float-}
```
public void setRotationAngle(float value)
```


BarCode-bildens rotationsvinkel, mätt i grader, t.ex. RotationAngle = 0 eller RotationAngle = 360 betyder ingen rotation. Om RotationAngle INTE är lika med 90, 180, 270 eller 0 kan det öka svårigheten för skannern att läsa bilden. Standardvärde: 0.

--------------------

> ```
> This sample shows how to create and save a BarCode image.
>   
>  	  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DATA_MATRIX);
>  	  generator.getParameters().setRotationAngle(7f);
>     generator.save("test.png");
> ```

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| värde | float |  |

### setUseAntiAlias(boolean value) {#setUseAntiAlias-boolean-}
```
public void setUseAntiAlias(boolean value)
```


Ställer in ett värde som indikerar om anti-aliasing-läge används för att rendera bilden.

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

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
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

