---
title: QRErrorLevel
second_title: Aspose.BarCode für Android via Java API-Referenz
description: Stufe der Reed‑Solomon-Fehlerkorrektur.
type: docs
weight: 104
url: /de/androidjava/com.aspose.barcode.generation/qrerrorlevel/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum QRErrorLevel extends Enum<QRErrorLevel>
```

Stufe der Reed-Solomon-Fehlerkorrektur. Von niedrig bis hoch: LEVEL\_L, LEVEL\_M, LEVEL\_Q, LEVEL\_H.
## Felder

| Feld | Beschreibung |
| --- | --- |
| [LEVEL_H](#LEVEL-H) | Fehlerkorrektur Stufe H kann auf QR- und RectMicroQR-Barcodes angewendet werden. |
| [LEVEL_L](#LEVEL-L) | Fehlerkorrektur Stufe L kann auf QR- und MicroQR-Barcodes angewendet werden. |
| [LEVEL_M](#LEVEL-M) | Fehlerkorrektur Stufe M kann auf QR-Barcodes, RectMicroQR-Barcodes und MicroQR-Barcodes mit Versionen von M2 bis M4 angewendet werden. |
| [LEVEL_Q](#LEVEL-Q) | Fehlerkorrektur Stufe Q kann auf QR-Barcodes und MicroQR-Barcodes mit Version M4 angewendet werden. |
## Methods

| Method | Beschreibung |
| --- | --- |
| [<T>valueOf(Class<T> arg0, String arg1)](#-T-valueOf-java.lang.Class-T--java.lang.String-) |  |
| [compareTo(E arg0)](#compareTo-E-) |  |
| [describeConstable()](#describeConstable--) |  |
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
### LEVEL_H {#LEVEL-H}
```
public static final QRErrorLevel LEVEL_H
```


Fehlerkorrektur Stufe H kann auf QR- und RectMicroQR-Barcodes angewendet werden. Ermöglicht die Wiederherstellung von 30 % des Code-Texts.

### LEVEL_L {#LEVEL-L}
```
public static final QRErrorLevel LEVEL_L
```


Fehlerkorrektur Stufe L kann auf QR- und MicroQR-Barcodes angewendet werden. Ermöglicht die Wiederherstellung von 7 % des Code-Texts.

### LEVEL_M {#LEVEL-M}
```
public static final QRErrorLevel LEVEL_M
```


Fehlerkorrektur Stufe M kann auf QR-Barcodes, RectMicroQR-Barcodes und MicroQR-Barcodes mit Versionen von M2 bis M4 angewendet werden. Ermöglicht die Wiederherstellung von 15 % des Code-Texts.

### LEVEL_Q {#LEVEL-Q}
```
public static final QRErrorLevel LEVEL_Q
```


Fehlerkorrektur Stufe Q kann auf QR-Barcodes und MicroQR-Barcodes mit Version M4 angewendet werden. Ermöglicht die Wiederherstellung von 25 % des Code-Texts.

### <T>valueOf(Class<T> arg0, String arg1) {#-T-valueOf-java.lang.Class-T--java.lang.String-}
```
public static T <T>valueOf(Class<T> arg0, String arg1)
```




**Parameters:**
| Parameter | Type | Beschreibung |
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
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| arg0 | E |  |

**Returns:**
int
### describeConstable() {#describeConstable--}
```
public final Optional<Enum.EnumDesc<E>> describeConstable()
```




**Returns:**
java.util.Optional<java.lang.Enum.EnumDesc<E>>
### equals(Object arg0) {#equals-java.lang.Object-}
```
public final boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### fromValue(int value) {#fromValue-int-}
```
public static QRErrorLevel fromValue(int value)
```




**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

**Returns:**
[QRErrorLevel](../../com.aspose.barcode.generation/qrerrorlevel)
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
public static QRErrorLevel valueOf(String name)
```




**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| Name | java.lang.String |  |

**Returns:**
[QRErrorLevel](../../com.aspose.barcode.generation/qrerrorlevel)
### values() {#values--}
```
public static QRErrorLevel[] values()
```




**Returns:**
com.aspose.barcode.generation.QRErrorLevel[]
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

