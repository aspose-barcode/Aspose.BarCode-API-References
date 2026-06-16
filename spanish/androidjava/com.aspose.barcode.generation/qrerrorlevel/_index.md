---
title: QRErrorLevel
second_title: Referencia de API de Aspose.BarCode para Android mediante Java
description: Nivel de corrección de errores Reed-Solomon.
type: docs
weight: 104
url: /es/androidjava/com.aspose.barcode.generation/qrerrorlevel/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum QRErrorLevel extends Enum<QRErrorLevel>
```

Nivel de corrección de errores Reed-Solomon. De bajo a alto: LEVEL\_L, LEVEL\_M, LEVEL\_Q, LEVEL\_H.
## Campos

| Campo | Descripción |
| --- | --- |
| [LEVEL_H](#LEVEL-H) | El nivel de corrección de errores H puede aplicarse a códigos de barras QR y RectMicroQR. |
| [LEVEL_L](#LEVEL-L) | El nivel de corrección de errores L puede aplicarse a códigos de barras QR y MicroQR. |
| [LEVEL_M](#LEVEL-M) | El nivel de corrección de errores M puede aplicarse a códigos de barras QR, códigos de barras RectMicroQR y códigos de barras MicroQR con versiones de M2 a M4. |
| [LEVEL_Q](#LEVEL-Q) | El nivel de corrección de errores Q puede aplicarse a códigos de barras QR y códigos de barras MicroQR con versión M4. |
## Methods

| Method | Descripción |
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


El nivel de corrección de errores H puede aplicarse a códigos de barras QR y RectMicroQR. Permite recuperar el 30% del texto del código.

### LEVEL_L {#LEVEL-L}
```
public static final QRErrorLevel LEVEL_L
```


El nivel de corrección de errores L puede aplicarse a códigos de barras QR y MicroQR. Permite recuperar el 7% del texto del código.

### LEVEL_M {#LEVEL-M}
```
public static final QRErrorLevel LEVEL_M
```


El nivel de corrección de errores M puede aplicarse a códigos de barras QR, códigos de barras RectMicroQR y códigos de barras MicroQR con versiones de M2 a M4. Permite recuperar el 15% del texto del código.

### LEVEL_Q {#LEVEL-Q}
```
public static final QRErrorLevel LEVEL_Q
```


El nivel de corrección de errores Q puede aplicarse a códigos de barras QR y códigos de barras MicroQR con versión M4. Permite recuperar el 25% del texto del código.

### <T>valueOf(Class<T> arg0, String arg1) {#-T-valueOf-java.lang.Class-T--java.lang.String-}
```
public static T <T>valueOf(Class<T> arg0, String arg1)
```




**Parameters:**
| Parameter | Type | Descripción |
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
| Parameter | Type | Descripción |
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
| Parameter | Type | Descripción |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### fromValue(int value) {#fromValue-int-}
```
public static QRErrorLevel fromValue(int value)
```




**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| valor | int |  |

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
| Parameter | Type | Descripción |
| --- | --- | --- |
| nombre | java.lang.String |  |

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
| Parameter | Type | Descripción |
| --- | --- | --- |
| arg0 | largo |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| arg0 | largo |  |
| arg1 | int |  |

