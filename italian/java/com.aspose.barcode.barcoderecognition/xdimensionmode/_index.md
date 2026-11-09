---
title: "XDimensionMode"
second_title: "Riferimento API di Aspose.BarCode per Java"
description: 
type: docs
weight: 54
url: /it/java/com.aspose.barcode.barcoderecognition/xdimensionmode/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum XDimensionMode extends Enum<XDimensionMode>
```

Modalità di riconoscimento che imposta la dimensione (da 1 a infinito) dell'elemento minimo del codice a barre: cella della matrice o barra.

--------------------

> ```
> This sample shows how to use XDimension mode
>   
>   BarCodeReader reader = new BarCodeReader("c:\\test.png", DecodeType.CODE_39_EXTENDED, DecodeType.CODE_128);
>   reader.getQualitySettings().setXDimension(XDimensionMode.SMALL);
>   for(BarCodeResult result : reader.readBarCodes())
>      System.out.println(result.getCodeText());
> ```
## Campi

| Campo | Descrizione |
| --- | --- |
| [AUTO](#AUTO) | Il valore di XDimension è rilevato dall'IA (SVM). |
| [LARGE](#LARGE) | Rileva i codici a barre con XDimension grande con qualità da BarcodeQuality catturata con fotocamere ad alta risoluzione. |
| [NORMAL](#NORMAL) | Rileva i codici a barre con XDimension classico di 2 pixel o più con qualità da BarcodeQuality o codici a barre di alta qualità. |
| [SMALL](#SMALL) | Rileva i codici a barre con XDimension piccolo di 1 pixel o più con qualità da BarcodeQuality. |
| [USE_MINIMAL_X_DIMENSION](#USE-MINIMAL-X-DIMENSION) | Rileva i codici a barre dalla dimensione impostata in MinimalXDimension con qualità da BarcodeQuality. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [<T>valueOf(Class<T> arg0, String arg1)](#-T-valueOf-java.lang.Class-T--java.lang.String-) |  |
| [compareTo(E arg0)](#compareTo-E-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [fromValue(int value)](#fromValue-int-) |  |
| [getClass()](#getClass--) |  |
| [getDeclaringClass()](#getDeclaringClass--) |  |
| [getValue()](#getValue--) |  |
| [hashCode()](#hashCode--) |  |
| [name()](#name--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [ordinal()](#ordinal--) |  |
| [toString()](#toString--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
| [values()](#values--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### AUTO {#AUTO}
```
public static final XDimensionMode AUTO
```


Il valore di XDimension è rilevato dall'IA (SVM). Al momento è lo stesso di Normal.

### LARGE {#LARGE}
```
public static final XDimensionMode LARGE
```


Rileva i codici a barre con XDimension grande con qualità da BarcodeQuality catturata con fotocamere ad alta risoluzione.

### NORMAL {#NORMAL}
```
public static final XDimensionMode NORMAL
```


Rileva i codici a barre con XDimension classico di 2 pixel o più con qualità da BarcodeQuality o codici a barre di alta qualità.

### SMALL {#SMALL}
```
public static final XDimensionMode SMALL
```


Rileva i codici a barre con XDimension piccolo di 1 pixel o più con qualità da BarcodeQuality.

### USE_MINIMAL_X_DIMENSION {#USE-MINIMAL-X-DIMENSION}
```
public static final XDimensionMode USE_MINIMAL_X_DIMENSION
```


Rileva i codici a barre dalla dimensione impostata in MinimalXDimension con qualità da BarcodeQuality.

### <T>valueOf(Class<T> arg0, String arg1) {#-T-valueOf-java.lang.Class-T--java.lang.String-}
```
public static T <T>valueOf(Class<T> arg0, String arg1)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | java.lang.Class<T> |  |
| arg1 | java.lang.String |  |

**Returns:**
T
### compareTo(E arg0) {#compareTo-E-}
```
public final int compareTo(E arg0)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | E |  |

**Returns:**
int
### equals(Object arg0) {#equals-java.lang.Object-}
```
public final boolean equals(Object arg0)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### fromValue(int value) {#fromValue-int-}
```
public static XDimensionMode fromValue(int value)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

**Returns:**
[XDimensionMode](../../com.aspose.barcode.barcoderecognition/xdimensionmode)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDeclaringClass() {#getDeclaringClass--}
```
public final Class<E> getDeclaringClass()
```




**Returns:**
java.lang.Class<E>
### getValue() {#getValue--}
```
public int getValue()
```




**Returns:**
int
### hashCode() {#hashCode--}
```
public final int hashCode()
```




**Returns:**
int
### name() {#name--}
```
public final String name()
```




**Returns:**
java.lang.String
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### ordinal() {#ordinal--}
```
public final int ordinal()
```




**Returns:**
int
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static XDimensionMode valueOf(String name)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| nome | java.lang.String |  |

**Returns:**
[XDimensionMode](../../com.aspose.barcode.barcoderecognition/xdimensionmode)
### values() {#values--}
```
public static XDimensionMode[] values()
```




**Returns:**
com.aspose.barcode.barcoderecognition.XDimensionMode[]
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

