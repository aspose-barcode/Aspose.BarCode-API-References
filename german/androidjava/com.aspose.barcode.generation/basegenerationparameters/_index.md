---
title: "BaseGenerationParameters"
second_title: "Aspose.BarCode für Android via Java API-Referenz"
description: "Parameter zur Erzeugung von Barcode-Bildern."
type: docs
weight: 17
url: /de/androidjava/com.aspose.barcode.generation/basegenerationparameters/
---
**Inheritance:**
java.lang.Object
```
public class BaseGenerationParameters
```

Parameter zur Erzeugung von Barcode-Bildern.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAutoSizeMode()](#getAutoSizeMode--) | Gibt die verschiedenen Typen automatischer Größeneinstellungsmodi an. |
| [getBackColor()](#getBackColor--) | Hintergrundfarbe des Barcode-Bildes. |
| [getBarcode()](#getBarcode--) | Gibt die  BarcodeParameters  zurück, die alle Barcode-Eigenschaften enthält. |
| [getBorder()](#getBorder--) | Gibt die  BorderParameters  zurück, die alle Konfigurationseigenschaften für den Barcode-Rahmen enthält. |
| [getCaptionAbove()](#getCaptionAbove--) | Beschriftung über dem BarCode-Bild. |
| [getCaptionBelow()](#getCaptionBelow--) | Beschriftung unter dem BarCode-Bild. |
| [getClass()](#getClass--) |  |
| [getImage()](#getImage--) | Bild-Parameter. |
| [getImageHeight()](#getImageHeight--) | Barcode-Bildhöhe, wenn die Eigenschaft  AutoSizeMode  auf AutoSizeMode.NEAREST oder AutoSizeMode.INTERPOLATION gesetzt ist. |
| [getImageWidth()](#getImageWidth--) | Barcode-Bildbreite, wenn die Eigenschaft  AutoSizeMode  auf AutoSizeMode.NEAREST oder AutoSizeMode.INTERPOLATION gesetzt ist. |
| [getResolution()](#getResolution--) | Gibt die Auflösung des BarCode-Bildes zurück. |
| [getRotationAngle()](#getRotationAngle--) | BarCode-Bilddrehwinkel, gemessen in Grad, z. B. |
| [getUseAntiAlias()](#getUseAntiAlias--) | Gibt einen Wert zurück, der angibt, ob der Anti-Aliasing-Modus zum Rendern des Bildes verwendet wird |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAutoSizeMode(AutoSizeMode value)](#setAutoSizeMode-com.aspose.barcode.generation.AutoSizeMode-) | Gibt die verschiedenen Typen automatischer Größeneinstellungsmodi an. |
| [setBackColor(int value)](#setBackColor-int-) | Hintergrundfarbe des Barcode-Bildes. |
| [setImageHeight(Unit value)](#setImageHeight-com.aspose.barcode.generation.Unit-) | Barcode-Bildhöhe, wenn die Eigenschaft  AutoSizeMode  auf AutoSizeMode.NEAREST oder AutoSizeMode.INTERPOLATION gesetzt ist. |
| [setImageWidth(Unit value)](#setImageWidth-com.aspose.barcode.generation.Unit-) | Barcode-Bildbreite, wenn die Eigenschaft  AutoSizeMode  auf AutoSizeMode.NEAREST oder AutoSizeMode.INTERPOLATION gesetzt ist. |
| [setResolution(float value)](#setResolution-float-) | Legt die Auflösung des BarCode-Bildes fest. |
| [setRotationAngle(float value)](#setRotationAngle-float-) | BarCode-Bilddrehwinkel, gemessen in Grad, z. B. |
| [setUseAntiAlias(boolean value)](#setUseAntiAlias-boolean-) | Setzt einen Wert, der angibt, ob der Anti-Aliasing-Modus zum Rendern des Bildes verwendet wird |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getAutoSizeMode() {#getAutoSizeMode--}
```
public AutoSizeMode getAutoSizeMode()
```


Gibt die verschiedenen Typen von automatischen Größenanpassungsmodi an. Standardwert: AutoSizeMode.NONE.

**Returns:**
[AutoSizeMode](../../com.aspose.barcode.generation/autosizemode)
### getBackColor() {#getBackColor--}
```
public int getBackColor()
```


Hintergrundfarbe des Barcode-Bildes. Standardwert: Color.White. Siehe Color.

**Returns:**
int
### getBarcode() {#getBarcode--}
```
public BarcodeParameters getBarcode()
```


Gibt die  BarcodeParameters  zurück, die alle Barcode-Eigenschaften enthält.

**Returns:**
[BarcodeParameters](../../com.aspose.barcode.generation/barcodeparameters)
### getBorder() {#getBorder--}
```
public BorderParameters getBorder()
```


Gibt die  BorderParameters  zurück, die alle Konfigurationseigenschaften für den Barcode-Rahmen enthält.

**Returns:**
[BorderParameters](../../com.aspose.barcode.generation/borderparameters)
### getCaptionAbove() {#getCaptionAbove--}
```
public CaptionParameters getCaptionAbove()
```


Beschriftung über dem BarCode-Bild. Siehe CaptionParameters.

**Returns:**
[CaptionParameters](../../com.aspose.barcode.generation/captionparameters)
### getCaptionBelow() {#getCaptionBelow--}
```
public CaptionParameters getCaptionBelow()
```


Beschriftung unter dem BarCode-Bild. Siehe CaptionParameters.

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


Bildparameter. Siehe .

**Returns:**
[ImageParameters](../../com.aspose.barcode.generation/imageparameters) - 
### getImageHeight() {#getImageHeight--}
```
public Unit getImageHeight()
```


Barcode-Bildhöhe, wenn die Eigenschaft  AutoSizeMode  auf AutoSizeMode.NEAREST oder AutoSizeMode.INTERPOLATION gesetzt ist.

**Returns:**
[Unit](../../com.aspose.barcode.generation/unit)
### getImageWidth() {#getImageWidth--}
```
public Unit getImageWidth()
```


Barcode-Bildbreite, wenn die Eigenschaft  AutoSizeMode  auf AutoSizeMode.NEAREST oder AutoSizeMode.INTERPOLATION gesetzt ist.

**Returns:**
[Unit](../../com.aspose.barcode.generation/unit)
### getResolution() {#getResolution--}
```
public float getResolution()
```


Gibt die Auflösung des BarCode-Bildes zurück. Ein Wert für beide Dimensionen. Standardwert: 96 dpi.

**Returns:**
float
### getRotationAngle() {#getRotationAngle--}
```
public float getRotationAngle()
```


BarCode-Bilddrehwinkel, gemessen in Grad, z. B. RotationAngle = 0 oder RotationAngle = 360 bedeutet keine Drehung. Wenn RotationAngle NICHT gleich 90, 180, 270 oder 0 ist, kann dies die Schwierigkeit für den Scanner erhöhen, das Bild zu lesen. Standardwert: 0.

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


Gibt einen Wert zurück, der angibt, ob der Anti-Aliasing-Modus zum Rendern des Bildes verwendet wird

**Returns:**
boolean
### hashCode() {#hashCode--}
```
public int hashCode()
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


Gibt die verschiedenen Typen von automatischen Größenanpassungsmodi an. Standardwert: AutoSizeMode.NONE.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [AutoSizeMode](../../com.aspose.barcode.generation/autosizemode) |  |

### setBackColor(int value) {#setBackColor-int-}
```
public void setBackColor(int value)
```


Hintergrundfarbe des Barcode-Bildes. Standardwert: Color.White. Siehe Color.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setImageHeight(Unit value) {#setImageHeight-com.aspose.barcode.generation.Unit-}
```
public void setImageHeight(Unit value)
```


Barcode-Bildhöhe, wenn die Eigenschaft  AutoSizeMode  auf AutoSizeMode.NEAREST oder AutoSizeMode.INTERPOLATION gesetzt ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [Unit](../../com.aspose.barcode.generation/unit) |  |

### setImageWidth(Unit value) {#setImageWidth-com.aspose.barcode.generation.Unit-}
```
public void setImageWidth(Unit value)
```


Barcode-Bildbreite, wenn die Eigenschaft  AutoSizeMode  auf AutoSizeMode.NEAREST oder AutoSizeMode.INTERPOLATION gesetzt ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [Unit](../../com.aspose.barcode.generation/unit) |  |

### setResolution(float value) {#setResolution-float-}
```
public void setResolution(float value)
```


Legt die Auflösung des BarCode-Bildes fest. Ein Wert für beide Dimensionen. Standardwert: 96 dpi.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | float |  |

### setRotationAngle(float value) {#setRotationAngle-float-}
```
public void setRotationAngle(float value)
```


BarCode-Bilddrehwinkel, gemessen in Grad, z. B. RotationAngle = 0 oder RotationAngle = 360 bedeutet keine Drehung. Wenn RotationAngle NICHT gleich 90, 180, 270 oder 0 ist, kann dies die Schwierigkeit für den Scanner erhöhen, das Bild zu lesen. Standardwert: 0.

--------------------

> ```
> This sample shows how to create and save a BarCode image.
>   
>  	  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DATA_MATRIX);
>  	  generator.getParameters().setRotationAngle(7f);
>     generator.save("test.png");
> ```

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | float |  |

### setUseAntiAlias(boolean value) {#setUseAntiAlias-boolean-}
```
public void setUseAntiAlias(boolean value)
```


Setzt einen Wert, der angibt, ob der Anti-Aliasing-Modus zum Rendern des Bildes verwendet wird

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

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
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

