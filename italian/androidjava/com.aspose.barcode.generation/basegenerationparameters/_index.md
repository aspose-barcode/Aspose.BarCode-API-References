---
title: BaseGenerationParameters
second_title: Aspose.BarCode per Android via Java API Reference
description: Parametri di generazione dell'immagine barcode.
type: docs
weight: 17
url: /it/androidjava/com.aspose.barcode.generation/basegenerationparameters/
---
**Inheritance:**
java.lang.Object
```
public class BaseGenerationParameters
```

Parametri di generazione dell'immagine barcode.
## Methods

| Method | Descrizione |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAutoSizeMode()](#getAutoSizeMode--) | Specifica i diversi tipi di modalità di dimensionamento automatico. |
| [getBackColor()](#getBackColor--) | Background color of the barcode image. |
| [getBarcode()](#getBarcode--) | Gets the  BarcodeParameters  that contains all barcode properties. |
| [getBorder()](#getBorder--) | Gets the  BorderParameters  that contains all configuration properties for barcode border. |
| [getCaptionAbove()](#getCaptionAbove--) | Didascalia sopra l'immagine BarCode. |
| [getCaptionBelow()](#getCaptionBelow--) | Didascalia sotto l'immagine BarCode. |
| [getClass()](#getClass--) |  |
| [getImage()](#getImage--) | Parametri immagine. |
| [getImageHeight()](#getImageHeight--) | Altezza dell'immagine BarCode quando la proprietà AutoSizeMode è impostata su AutoSizeMode.NEAREST o AutoSizeMode.INTERPOLATION. |
| [getImageWidth()](#getImageWidth--) | Larghezza dell'immagine BarCode quando la proprietà AutoSizeMode è impostata su AutoSizeMode.NEAREST o AutoSizeMode.INTERPOLATION. |
| [getResolution()](#getResolution--) | Ottiene la risoluzione dell'immagine BarCode. |
| [getRotationAngle()](#getRotationAngle--) | Angolo di rotazione dell'immagine BarCode, misurato in gradi, ad es. |
| [getUseAntiAlias()](#getUseAntiAlias--) | Ottiene un valore che indica se è utilizzata la modalità anti-aliasing per renderizzare l'immagine. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAutoSizeMode(AutoSizeMode value)](#setAutoSizeMode-com.aspose.barcode.generation.AutoSizeMode-) | Specifica i diversi tipi di modalità di dimensionamento automatico. |
| [setBackColor(int value)](#setBackColor-int-) | Background color of the barcode image. |
| [setImageHeight(Unit value)](#setImageHeight-com.aspose.barcode.generation.Unit-) | Altezza dell'immagine BarCode quando la proprietà AutoSizeMode è impostata su AutoSizeMode.NEAREST o AutoSizeMode.INTERPOLATION. |
| [setImageWidth(Unit value)](#setImageWidth-com.aspose.barcode.generation.Unit-) | Larghezza dell'immagine BarCode quando la proprietà AutoSizeMode è impostata su AutoSizeMode.NEAREST o AutoSizeMode.INTERPOLATION. |
| [setResolution(float value)](#setResolution-float-) | Imposta la risoluzione dell'immagine BarCode. |
| [setRotationAngle(float value)](#setRotationAngle-float-) | Angolo di rotazione dell'immagine BarCode, misurato in gradi, ad es. |
| [setUseAntiAlias(boolean value)](#setUseAntiAlias-boolean-) | Imposta un valore che indica se è utilizzata la modalità anti-aliasing per renderizzare l'immagine. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getAutoSizeMode() {#getAutoSizeMode--}
```
public AutoSizeMode getAutoSizeMode()
```


Specifica i diversi tipi di modalità di dimensionamento automatico. Valore predefinito: AutoSizeMode.NONE.

**Returns:**
[AutoSizeMode](../../com.aspose.barcode.generation/autosizemode)
### getBackColor() {#getBackColor--}
```
public int getBackColor()
```


Colore di sfondo dell'immagine del barcode. Valore predefinito: Color.White. Vedi Color.

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


Didascalia sopra l'immagine BarCode. Vedi CaptionParameters.

**Returns:**
[CaptionParameters](../../com.aspose.barcode.generation/captionparameters)
### getCaptionBelow() {#getCaptionBelow--}
```
public CaptionParameters getCaptionBelow()
```


Didascalia sotto l'immagine BarCode. Vedi CaptionParameters.

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


Parametri immagine. Vedi .

**Returns:**
[ImageParameters](../../com.aspose.barcode.generation/imageparameters) - 
### getImageHeight() {#getImageHeight--}
```
public Unit getImageHeight()
```


Altezza dell'immagine BarCode quando la proprietà AutoSizeMode è impostata su AutoSizeMode.NEAREST o AutoSizeMode.INTERPOLATION.

**Returns:**
[Unit](../../com.aspose.barcode.generation/unit)
### getImageWidth() {#getImageWidth--}
```
public Unit getImageWidth()
```


Larghezza dell'immagine BarCode quando la proprietà AutoSizeMode è impostata su AutoSizeMode.NEAREST o AutoSizeMode.INTERPOLATION.

**Returns:**
[Unit](../../com.aspose.barcode.generation/unit)
### getResolution() {#getResolution--}
```
public float getResolution()
```


Ottiene la risoluzione dell'immagine BarCode. Un valore per entrambe le dimensioni. Valore predefinito: 96 dpi.

**Returns:**
float
### getRotationAngle() {#getRotationAngle--}
```
public float getRotationAngle()
```


Angolo di rotazione dell'immagine BarCode, misurato in gradi, ad es. RotationAngle = 0 o RotationAngle = 360 significa nessuna rotazione. Se RotationAngle NON è uguale a 90, 180, 270 o 0, può aumentare la difficoltà per lo scanner nel leggere l'immagine. Valore predefinito: 0.

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


Ottiene un valore che indica se è utilizzata la modalità anti-aliasing per renderizzare l'immagine.

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


Specifica i diversi tipi di modalità di dimensionamento automatico. Valore predefinito: AutoSizeMode.NONE.

**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| value | [AutoSizeMode](../../com.aspose.barcode.generation/autosizemode) |  |

### setBackColor(int value) {#setBackColor-int-}
```
public void setBackColor(int value)
```


Colore di sfondo dell'immagine del barcode. Valore predefinito: Color.White. Vedi Color.

**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setImageHeight(Unit value) {#setImageHeight-com.aspose.barcode.generation.Unit-}
```
public void setImageHeight(Unit value)
```


Altezza dell'immagine BarCode quando la proprietà AutoSizeMode è impostata su AutoSizeMode.NEAREST o AutoSizeMode.INTERPOLATION.

**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| value | [Unit](../../com.aspose.barcode.generation/unit) |  |

### setImageWidth(Unit value) {#setImageWidth-com.aspose.barcode.generation.Unit-}
```
public void setImageWidth(Unit value)
```


Larghezza dell'immagine BarCode quando la proprietà AutoSizeMode è impostata su AutoSizeMode.NEAREST o AutoSizeMode.INTERPOLATION.

**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| value | [Unit](../../com.aspose.barcode.generation/unit) |  |

### setResolution(float value) {#setResolution-float-}
```
public void setResolution(float value)
```


Imposta la risoluzione dell'immagine BarCode. Un valore per entrambe le dimensioni. Valore predefinito: 96 dpi.

**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| valore | float |  |

### setRotationAngle(float value) {#setRotationAngle-float-}
```
public void setRotationAngle(float value)
```


Angolo di rotazione dell'immagine BarCode, misurato in gradi, ad es. RotationAngle = 0 o RotationAngle = 360 significa nessuna rotazione. Se RotationAngle NON è uguale a 90, 180, 270 o 0, può aumentare la difficoltà per lo scanner nel leggere l'immagine. Valore predefinito: 0.

--------------------

> ```
> This sample shows how to create and save a BarCode image.
>   
>  	  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DATA_MATRIX);
>  	  generator.getParameters().setRotationAngle(7f);
>     generator.save("test.png");
> ```

**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| valore | float |  |

### setUseAntiAlias(boolean value) {#setUseAntiAlias-boolean-}
```
public void setUseAntiAlias(boolean value)
```


Imposta un valore che indica se è utilizzata la modalità anti-aliasing per renderizzare l'immagine.

**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

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
| Parameter | Type | Descrizione |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

