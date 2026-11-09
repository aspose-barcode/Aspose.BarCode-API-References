---
title: "InverseImageMode"
second_title: "Riferimento API di Aspose.BarCode per Java"
description: 
type: docs
weight: 53
url: /it/java/com.aspose.barcode.barcoderecognition/inverseimagemode/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum InverseImageMode extends Enum<InverseImageMode>
```

Modalità che abilita o disabilita il riconoscimento aggiuntivo di codici a barre su immagini con colori invertiti (luminanza).

--------------------

> ```
> This sample shows how to use InverseImage mode
>   
> 
>   BarCodeReader reader = new BarCodeReader("c:\\test.png", DecodeType.CODE_39_EXTENDED, DecodeType.CODE_128);
>   reader.getQualitySettings().setInverseImage(InverseImageMode.ENABLED);
>   for(BarCodeResult result : reader.readBarCodes())
>      System.out.println(result.getCodeText());
> ```
## Campi

| Campo | Descrizione |
| --- | --- |
| [AUTO](#AUTO) | Disabilita il riconoscimento aggiuntivo dei codici a barre su immagini inverse per tutti i tipi di codice a barre tranne QR Code |
| [DISABLED](#DISABLED) | Disabilita il riconoscimento aggiuntivo dei codici a barre su immagini inverse. |
| [ENABLED](#ENABLED) | Abilita il riconoscimento aggiuntivo dei codici a barre su immagini inverse |
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
public static final InverseImageMode AUTO
```


Disabilita il riconoscimento aggiuntivo dei codici a barre su immagini inverse per tutti i tipi di codice a barre tranne QR Code

### DISABLED {#DISABLED}
```
public static final InverseImageMode DISABLED
```


Disabilita il riconoscimento aggiuntivo dei codici a barre su immagini inverse.

### ENABLED {#ENABLED}
```
public static final InverseImageMode ENABLED
```


Abilita il riconoscimento aggiuntivo dei codici a barre su immagini inverse

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
public static InverseImageMode fromValue(int value)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

**Returns:**
[InverseImageMode](../../com.aspose.barcode.barcoderecognition/inverseimagemode)
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
public static InverseImageMode valueOf(String name)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| nome | java.lang.String |  |

**Returns:**
[InverseImageMode](../../com.aspose.barcode.barcoderecognition/inverseimagemode)
### values() {#values--}
```
public static InverseImageMode[] values()
```




**Returns:**
com.aspose.barcode.barcoderecognition.InverseImageMode[]
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

