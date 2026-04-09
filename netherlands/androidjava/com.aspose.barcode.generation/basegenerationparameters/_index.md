---
title: BasisGeneratieParameters
second_title: Aspose.BarCode for Android via Java API-referentie
description: Barcode-afbeeldingsgeneratieparameters.
type: docs
weight: 17
url: /nl/androidjava/com.aspose.barcode.generation/basegenerationparameters/
---
**Inheritance:**
java.lang.Object
```
public class BaseGenerationParameters
```

Barcode-afbeeldingsgeneratieparameters.
## Methods

| Method | Beschrijving |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAutoSizeMode()](#getAutoSizeMode--) | Specificeert de verschillende typen automatische formaatmodi. |
| [getBackColor()](#getBackColor--) | Achtergrondkleur van de barcode-afbeelding. |
| [getBarcode()](#getBarcode--) | Haalt de  BarcodeParameters  op die alle barcode-eigenschappen bevat. |
| [getBorder()](#getBorder--) | Haalt de  BorderParameters  op die alle configuratie-eigenschappen voor de barcode-rand bevat. |
| [getCaptionAbove()](#getCaptionAbove--) | Bijschrift boven de BarCode-afbeelding. |
| [getCaptionBelow()](#getCaptionBelow--) | Bijschrift onder de BarCode-afbeelding. |
| [getClass()](#getClass--) |  |
| [getImage()](#getImage--) | Afbeeldingsparameters. |
| [getImageHeight()](#getImageHeight--) | BarCode-afbeeldingshoogte wanneer de AutoSizeMode-eigenschap is ingesteld op AutoSizeMode.NEAREST of AutoSizeMode.INTERPOLATION. |
| [getImageWidth()](#getImageWidth--) | BarCode-afbeeldingsbreedte wanneer de AutoSizeMode-eigenschap is ingesteld op AutoSizeMode.NEAREST of AutoSizeMode.INTERPOLATION. |
| [getResolution()](#getResolution--) | Haalt de resolutie van de BarCode-afbeelding op. |
| [getRotationAngle()](#getRotationAngle--) | Rotatiehoek van de BarCode-afbeelding, gemeten in graden, bijv. |
| [getUseAntiAlias()](#getUseAntiAlias--) | Haalt een waarde op die aangeeft of anti-aliasing-modus wordt gebruikt om de afbeelding weer te geven. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAutoSizeMode(AutoSizeMode value)](#setAutoSizeMode-com.aspose.barcode.generation.AutoSizeMode-) | Specificeert de verschillende typen automatische formaatmodi. |
| [setBackColor(int value)](#setBackColor-int-) | Achtergrondkleur van de barcode-afbeelding. |
| [setImageHeight(Unit value)](#setImageHeight-com.aspose.barcode.generation.Unit-) | BarCode-afbeeldingshoogte wanneer de AutoSizeMode-eigenschap is ingesteld op AutoSizeMode.NEAREST of AutoSizeMode.INTERPOLATION. |
| [setImageWidth(Unit value)](#setImageWidth-com.aspose.barcode.generation.Unit-) | BarCode-afbeeldingsbreedte wanneer de AutoSizeMode-eigenschap is ingesteld op AutoSizeMode.NEAREST of AutoSizeMode.INTERPOLATION. |
| [setResolution(float value)](#setResolution-float-) | Stelt de resolutie van de BarCode-afbeelding in. |
| [setRotationAngle(float value)](#setRotationAngle-float-) | Rotatiehoek van de BarCode-afbeelding, gemeten in graden, bijv. |
| [setUseAntiAlias(boolean value)](#setUseAntiAlias-boolean-) | Stelt een waarde in die aangeeft of anti-aliasing-modus wordt gebruikt om de afbeelding weer te geven. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getAutoSizeMode() {#getAutoSizeMode--}
```
public AutoSizeMode getAutoSizeMode()
```


Specificeert de verschillende typen automatische formaatmodi. Standaardwaarde: AutoSizeMode.NONE.

**Returns:**
[AutoSizeMode](../../com.aspose.barcode.generation/autosizemode)
### getBackColor() {#getBackColor--}
```
public int getBackColor()
```


Achtergrondkleur van de barcode-afbeelding. Standaardwaarde: Color.White. Zie Color.

**Returns:**
int
### getBarcode() {#getBarcode--}
```
public BarcodeParameters getBarcode()
```


Haalt de  BarcodeParameters  op die alle barcode-eigenschappen bevat.

**Returns:**
[BarcodeParameters](../../com.aspose.barcode.generation/barcodeparameters)
### getBorder() {#getBorder--}
```
public BorderParameters getBorder()
```


Haalt de  BorderParameters  op die alle configuratie-eigenschappen voor de barcode-rand bevat.

**Returns:**
[BorderParameters](../../com.aspose.barcode.generation/borderparameters)
### getCaptionAbove() {#getCaptionAbove--}
```
public CaptionParameters getCaptionAbove()
```


Bijschrift boven de BarCode-afbeelding. Zie CaptionParameters.

**Returns:**
[CaptionParameters](../../com.aspose.barcode.generation/captionparameters)
### getCaptionBelow() {#getCaptionBelow--}
```
public CaptionParameters getCaptionBelow()
```


Bijschrift onder de BarCode-afbeelding. Zie CaptionParameters.

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


Afbeeldingsparameters. Zie .

**Returns:**
[ImageParameters](../../com.aspose.barcode.generation/imageparameters) - 
### getImageHeight() {#getImageHeight--}
```
public Unit getImageHeight()
```


BarCode-afbeeldingshoogte wanneer de AutoSizeMode-eigenschap is ingesteld op AutoSizeMode.NEAREST of AutoSizeMode.INTERPOLATION.

**Returns:**
[Unit](../../com.aspose.barcode.generation/unit)
### getImageWidth() {#getImageWidth--}
```
public Unit getImageWidth()
```


BarCode-afbeeldingsbreedte wanneer de AutoSizeMode-eigenschap is ingesteld op AutoSizeMode.NEAREST of AutoSizeMode.INTERPOLATION.

**Returns:**
[Unit](../../com.aspose.barcode.generation/unit)
### getResolution() {#getResolution--}
```
public float getResolution()
```


Haalt de resolutie van de BarCode-afbeelding op. Eén waarde voor beide dimensies. Standaardwaarde: 96 dpi.

**Returns:**
float
### getRotationAngle() {#getRotationAngle--}
```
public float getRotationAngle()
```


Rotatiehoek van de BarCode-afbeelding, gemeten in graden, bijv. RotationAngle = 0 of RotationAngle = 360 betekent geen rotatie. Als RotationAngle NIET gelijk is aan 90, 180, 270 of 0, kan dit de moeilijkheid voor de scanner om de afbeelding te lezen verhogen. Standaardwaarde: 0.

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


Haalt een waarde op die aangeeft of anti-aliasing-modus wordt gebruikt om de afbeelding weer te geven.

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


Specificeert de verschillende typen automatische formaatmodi. Standaardwaarde: AutoSizeMode.NONE.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [AutoSizeMode](../../com.aspose.barcode.generation/autosizemode) |  |

### setBackColor(int value) {#setBackColor-int-}
```
public void setBackColor(int value)
```


Achtergrondkleur van de barcode-afbeelding. Standaardwaarde: Color.White. Zie Color.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setImageHeight(Unit value) {#setImageHeight-com.aspose.barcode.generation.Unit-}
```
public void setImageHeight(Unit value)
```


BarCode-afbeeldingshoogte wanneer de AutoSizeMode-eigenschap is ingesteld op AutoSizeMode.NEAREST of AutoSizeMode.INTERPOLATION.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [Unit](../../com.aspose.barcode.generation/unit) |  |

### setImageWidth(Unit value) {#setImageWidth-com.aspose.barcode.generation.Unit-}
```
public void setImageWidth(Unit value)
```


BarCode-afbeeldingsbreedte wanneer de AutoSizeMode-eigenschap is ingesteld op AutoSizeMode.NEAREST of AutoSizeMode.INTERPOLATION.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [Unit](../../com.aspose.barcode.generation/unit) |  |

### setResolution(float value) {#setResolution-float-}
```
public void setResolution(float value)
```


Stelt de resolutie van de BarCode-afbeelding in. Eén waarde voor beide dimensies. Standaardwaarde: 96 dpi.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | float |  |

### setRotationAngle(float value) {#setRotationAngle-float-}
```
public void setRotationAngle(float value)
```


Rotatiehoek van de BarCode-afbeelding, gemeten in graden, bijv. RotationAngle = 0 of RotationAngle = 360 betekent geen rotatie. Als RotationAngle NIET gelijk is aan 90, 180, 270 of 0, kan dit de moeilijkheid voor de scanner om de afbeelding te lezen verhogen. Standaardwaarde: 0.

--------------------

> ```
> This sample shows how to create and save a BarCode image.
>   
>  	  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DATA_MATRIX);
>  	  generator.getParameters().setRotationAngle(7f);
>     generator.save("test.png");
> ```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | float |  |

### setUseAntiAlias(boolean value) {#setUseAntiAlias-boolean-}
```
public void setUseAntiAlias(boolean value)
```


Stelt een waarde in die aangeeft of anti-aliasing-modus wordt gebruikt om de afbeelding weer te geven.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean |  |

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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

