---
title: "ComplexBackgroundMode"
second_title: "Riferimento API di Aspose.BarCode per Java"
description: 
type: docs
weight: 50
url: /it/java/com.aspose.barcode.barcoderecognition/complexbackgroundmode/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum ComplexBackgroundMode extends Enum<ComplexBackgroundMode>
```

Modalità che abilita o disabilita il riconoscimento aggiuntivo di codici a barre a colori su immagini a colori.

--------------------

> ```
> This sample shows how to use ComplexBackground mode
>   
>   BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.CODE_39_EXTENDED, DecodeType.CODE_128);
>   reader.getQualitySettings().setComplexBackground(ComplexBackgroundMode.ENABLED);
>   for(BarCodeResult result : reader.readBarCodes())
>      System.out.println(result.getCodeText());
> ```
## Campi

| Campo | Descrizione |
| --- | --- |
| [AUTO](#AUTO) | Al momento è uguale a Disabilitato. |
| [DISABLED](#DISABLED) | Disabilita il riconoscimento aggiuntivo di codici a barre a colori su immagini a colori. |
| [ENABLED](#ENABLED) | Abilita il riconoscimento aggiuntivo di codici a barre a colori su immagini a colori. |
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
public static final ComplexBackgroundMode AUTO
```


Al momento è uguale a Disabilitato. Disabilita il riconoscimento aggiuntivo di codici a barre a colori su immagini a colori.

### DISABLED {#DISABLED}
```
public static final ComplexBackgroundMode DISABLED
```


Disabilita il riconoscimento aggiuntivo di codici a barre a colori su immagini a colori.

### ENABLED {#ENABLED}
```
public static final ComplexBackgroundMode ENABLED
```


Abilita il riconoscimento aggiuntivo di codici a barre a colori su immagini a colori.

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
public static ComplexBackgroundMode fromValue(int value)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

**Returns:**
[ComplexBackgroundMode](../../com.aspose.barcode.barcoderecognition/complexbackgroundmode)
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
public static ComplexBackgroundMode valueOf(String name)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| nome | java.lang.String |  |

**Returns:**
[ComplexBackgroundMode](../../com.aspose.barcode.barcoderecognition/complexbackgroundmode)
### values() {#values--}
```
public static ComplexBackgroundMode[] values()
```




**Returns:**
com.aspose.barcode.barcoderecognition.ComplexBackgroundMode[]
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

