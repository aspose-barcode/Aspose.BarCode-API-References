---
title: "Unit"
second_title: "Riferimento API di Aspose.BarCode per Android via Java"
description: "Specifica il valore di dimensione in diverse unità Pixel, Inches, ecc.."
type: docs
weight: 67
url: /it/androidjava/com.aspose.barcode.generation/unit/
---
**Inheritance:**
java.lang.Object
```
public final class Unit
```

Specifica il valore di dimensione in diverse unità (Pixel, Pollici, ecc.).

--------------------

> ```
> This sample shows how to create and save a BarCode image.
>   
>  	  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.CODE_128);
>  	  generator.getParameters().getBarcode().getBarHeight().setMillimeters(10);
>     generator.save("test.png");
> ```
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [Unit(Unit source)](#Unit-com.aspose.barcode.generation.Unit-) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | Determina se questa istanza e un oggetto specificato, che deve essere anche un oggetto  Unit , hanno lo stesso valore. |
| [getClass()](#getClass--) |  |
| [getDocument()](#getDocument--) | Ottiene il valore della dimensione in unità di documento. |
| [getInches()](#getInches--) | Ottiene il valore della dimensione in pollici. |
| [getMillimeters()](#getMillimeters--) | Ottiene il valore della dimensione in millimetri. |
| [getPixels()](#getPixels--) | Ottiene il valore della dimensione in pixel. |
| [getPoint()](#getPoint--) | Ottiene il valore della dimensione in punti. |
| [getResolution()](#getResolution--) |  |
| [hashCode()](#hashCode--) | Restituisce il codice hash per questo oggetto. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDocument(float value)](#setDocument-float-) | Imposta il valore della dimensione in unità di documento. |
| [setInches(float value)](#setInches-float-) | Imposta il valore della dimensione in pollici. |
| [setMillimeters(float value)](#setMillimeters-float-) | Imposta il valore della dimensione in millimetri. |
| [setPixels(float value)](#setPixels-float-) | Imposta il valore della dimensione in pixel. |
| [setPoint(float value)](#setPoint-float-) | Imposta il valore della dimensione in punti. |
| [toString()](#toString--) | Restituisce una rappresentazione stringa leggibile dall'uomo di questo  Unit . |
| [updateResolution(float dpi)](#updateResolution-float-) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Unit(Unit source) {#Unit-com.aspose.barcode.generation.Unit-}
```
public Unit(Unit source)
```


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| source | [Unit](../../com.aspose.barcode.generation/unit) |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Determina se questa istanza e un oggetto specificato, che deve essere anche un oggetto  Unit , hanno lo stesso valore.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| obj | java.lang.Object | L'  Unit  da confrontare con questa istanza. |

**Returns:**
boolean - true se obj è un  Unit  e il suo valore è lo stesso di questa istanza; altrimenti, false. Se obj è null, il metodo restituisce false.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDocument() {#getDocument--}
```
public float getDocument()
```


Ottiene il valore della dimensione in unità di documento.

**Returns:**
float
### getInches() {#getInches--}
```
public float getInches()
```


Ottiene il valore della dimensione in pollici.

**Returns:**
float
### getMillimeters() {#getMillimeters--}
```
public float getMillimeters()
```


Ottiene il valore della dimensione in millimetri.

**Returns:**
float
### getPixels() {#getPixels--}
```
public float getPixels()
```


Ottiene il valore della dimensione in pixel.

**Returns:**
float
### getPoint() {#getPoint--}
```
public float getPoint()
```


Ottiene il valore della dimensione in punti.

**Returns:**
float
### getResolution() {#getResolution--}
```
public float getResolution()
```




**Returns:**
float
### hashCode() {#hashCode--}
```
public int hashCode()
```


Restituisce il codice hash per questo oggetto.

**Returns:**
int - Un codice hash intero con segno a 32 bit.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setDocument(float value) {#setDocument-float-}
```
public void setDocument(float value)
```


Imposta il valore della dimensione in unità di documento.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | float |  |

### setInches(float value) {#setInches-float-}
```
public void setInches(float value)
```


Imposta il valore della dimensione in pollici.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | float |  |

### setMillimeters(float value) {#setMillimeters-float-}
```
public void setMillimeters(float value)
```


Imposta il valore della dimensione in millimetri.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | float |  |

### setPixels(float value) {#setPixels-float-}
```
public void setPixels(float value)
```


Imposta il valore della dimensione in pixel.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | float |  |

### setPoint(float value) {#setPoint-float-}
```
public void setPoint(float value)
```


Imposta il valore della dimensione in punti.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | float |  |

### toString() {#toString--}
```
public String toString()
```


Restituisce una rappresentazione stringa leggibile dall'uomo di questo  Unit .

**Returns:**
java.lang.String - Una stringa che rappresenta questo  Unit .
### updateResolution(float dpi) {#updateResolution-float-}
```
public void updateResolution(float dpi)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| dpi | float |  |

### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
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

