---
title: "BaseGenerationParameters"
second_title: "Riferimento API di Aspose.BarCode per Java"
description: "Parametri di generazione dell'immagine del codice a barre."
type: docs
weight: 17
url: /it/java/com.aspose.barcode.generation/basegenerationparameters/
---
**Inheritance:**
java.lang.Object
```
public class BaseGenerationParameters
```

Parametri di generazione dell'immagine del codice a barre.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAutoSizeMode()](#getAutoSizeMode--) | Specifica i diversi tipi di modalità di dimensionamento automatico. |
| [getBackColor()](#getBackColor--) | Colore di sfondo dell'immagine del codice a barre. |
| [getBarcode()](#getBarcode--) | Restituisce i  BarcodeParameters  che contengono tutte le proprietà del codice a barre. |
| [getBorder()](#getBorder--) | Restituisce i  BorderParameters  che contengono tutte le proprietà di configurazione per il bordo del codice a barre. |
| [getCaptionAbove()](#getCaptionAbove--) | Didascalia sopra l'immagine del codice a barre. |
| [getCaptionBelow()](#getCaptionBelow--) | Didascalia sotto l'immagine BarCode. |
| [getClass()](#getClass--) |  |
| [getImage()](#getImage--) | Parametri immagine. |
| [getImageHeight()](#getImageHeight--) | Altezza dell'immagine BarCode quando la proprietà  AutoSizeMode  è impostata su AutoSizeMode.NEAREST o AutoSizeMode.INTERPOLATION. |
| [getImageWidth()](#getImageWidth--) | Larghezza dell'immagine BarCode quando la proprietà  AutoSizeMode  è impostata su AutoSizeMode.NEAREST o AutoSizeMode.INTERPOLATION. |
| [getResolution()](#getResolution--) | Ottiene la risoluzione dell'immagine del codice a barre. |
| [getRotationAngle()](#getRotationAngle--) | Angolo di rotazione dell'immagine del codice a barre, misurato in gradi, ad es. |
| [getUseAntiAlias()](#getUseAntiAlias--) | Restituisce un valore che indica se è utilizzata la modalità anti-aliasing per renderizzare l'immagine. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAutoSizeMode(AutoSizeMode value)](#setAutoSizeMode-com.aspose.barcode.generation.AutoSizeMode-) | Specifica i diversi tipi di modalità di dimensionamento automatico. |
| [setBackColor(Color value)](#setBackColor-java.awt.Color-) | Colore di sfondo dell'immagine del codice a barre. |
| [setImageHeight(Unit value)](#setImageHeight-com.aspose.barcode.generation.Unit-) | Altezza dell'immagine BarCode quando la proprietà  AutoSizeMode  è impostata su AutoSizeMode.NEAREST o AutoSizeMode.INTERPOLATION. |
| [setImageWidth(Unit value)](#setImageWidth-com.aspose.barcode.generation.Unit-) | Larghezza dell'immagine BarCode quando la proprietà  AutoSizeMode  è impostata su AutoSizeMode.NEAREST o AutoSizeMode.INTERPOLATION. |
| [setResolution(float value)](#setResolution-float-) | Imposta la risoluzione dell'immagine del codice a barre. |
| [setRotationAngle(float value)](#setRotationAngle-float-) | Angolo di rotazione dell'immagine del codice a barre, misurato in gradi, ad es. |
| [setUseAntiAlias(boolean value)](#setUseAntiAlias-boolean-) | Imposta un valore che indica se è utilizzata la modalità anti-aliasing per renderizzare l'immagine |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
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
public Color getBackColor()
```


Colore di sfondo dell'immagine del codice a barre. Valore predefinito: Color.White. Vedi Color.

**Returns:**
java.awt.Color
### getBarcode() {#getBarcode--}
```
public BarcodeParameters getBarcode()
```


Restituisce i  BarcodeParameters  che contengono tutte le proprietà del codice a barre.

**Returns:**
[BarcodeParameters](../../com.aspose.barcode.generation/barcodeparameters)
### getBorder() {#getBorder--}
```
public BorderParameters getBorder()
```


Restituisce i  BorderParameters  che contengono tutte le proprietà di configurazione per il bordo del codice a barre.

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


Parametri dell'immagine. Vedi .

**Returns:**
[ImageParameters](../../com.aspose.barcode.generation/imageparameters) - 
### getImageHeight() {#getImageHeight--}
```
public Unit getImageHeight()
```


Altezza dell'immagine BarCode quando la proprietà  AutoSizeMode  è impostata su AutoSizeMode.NEAREST o AutoSizeMode.INTERPOLATION.

**Returns:**
[Unit](../../com.aspose.barcode.generation/unit)
### getImageWidth() {#getImageWidth--}
```
public Unit getImageWidth()
```


Larghezza dell'immagine BarCode quando la proprietà  AutoSizeMode  è impostata su AutoSizeMode.NEAREST o AutoSizeMode.INTERPOLATION.

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


Restituisce un valore che indica se è utilizzata la modalità anti-aliasing per renderizzare l'immagine.

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


Specifica i diversi tipi di modalità di dimensionamento automatico. Valore predefinito: AutoSizeMode.NONE.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [AutoSizeMode](../../com.aspose.barcode.generation/autosizemode) |  |

### setBackColor(Color value) {#setBackColor-java.awt.Color-}
```
public void setBackColor(Color value)
```


Colore di sfondo dell'immagine del codice a barre. Valore predefinito: Color.White. Vedi Color.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.awt.Color |  |

### setImageHeight(Unit value) {#setImageHeight-com.aspose.barcode.generation.Unit-}
```
public void setImageHeight(Unit value)
```


Altezza dell'immagine BarCode quando la proprietà  AutoSizeMode  è impostata su AutoSizeMode.NEAREST o AutoSizeMode.INTERPOLATION.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Unit](../../com.aspose.barcode.generation/unit) |  |

### setImageWidth(Unit value) {#setImageWidth-com.aspose.barcode.generation.Unit-}
```
public void setImageWidth(Unit value)
```


Larghezza dell'immagine BarCode quando la proprietà  AutoSizeMode  è impostata su AutoSizeMode.NEAREST o AutoSizeMode.INTERPOLATION.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Unit](../../com.aspose.barcode.generation/unit) |  |

### setResolution(float value) {#setResolution-float-}
```
public void setResolution(float value)
```


Imposta la risoluzione dell'immagine BarCode. Un unico valore per entrambe le dimensioni. Valore predefinito: 96 dpi.

**Parameters:**
| Parametro | Tipo | Descrizione |
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
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | float |  |

### setUseAntiAlias(boolean value) {#setUseAntiAlias-boolean-}
```
public void setUseAntiAlias(boolean value)
```


Imposta un valore che indica se è utilizzata la modalità anti-aliasing per renderizzare l'immagine

**Parameters:**
| Parametro | Tipo | Descrizione |
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
public final native void wait(long arg0)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

