---
title: QRErrorLevel
second_title: Référence d'API Aspose.BarCode pour Android via Java
description: Niveau de correction d'erreurs Reed-Solomon.
type: docs
weight: 104
url: /fr/androidjava/com.aspose.barcode.generation/qrerrorlevel/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum QRErrorLevel extends Enum<QRErrorLevel>
```

Niveau de correction d'erreurs Reed-Solomon. Du plus bas au plus haut : LEVEL\_L, LEVEL\_M, LEVEL\_Q, LEVEL\_H.
## Champs

| Champ | Description |
| --- | --- |
| [LEVEL_H](#LEVEL-H) | Le niveau de correction d'erreurs H peut être appliqué aux codes-barres QR et RectMicroQR. |
| [LEVEL_L](#LEVEL-L) | Le niveau de correction d'erreurs L peut être appliqué aux codes-barres QR et MicroQR. |
| [LEVEL_M](#LEVEL-M) | Le niveau de correction d'erreurs M peut être appliqué aux codes-barres QR, aux codes-barres RectMicroQR et aux codes-barres MicroQR avec des versions de M2 à M4. |
| [LEVEL_Q](#LEVEL-Q) | Le niveau de correction d'erreurs Q peut être appliqué aux codes-barres QR et aux codes-barres MicroQR avec la version M4. |
## Méthodes

| Méthode | Description |
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


Le niveau de correction d'erreurs H peut être appliqué aux codes-barres QR et RectMicroQR. Permet de récupérer 30 % du texte du code.

### LEVEL_L {#LEVEL-L}
```
public static final QRErrorLevel LEVEL_L
```


Le niveau de correction d'erreurs L peut être appliqué aux codes-barres QR et MicroQR. Permet de récupérer 7 % du texte du code.

### LEVEL_M {#LEVEL-M}
```
public static final QRErrorLevel LEVEL_M
```


Le niveau de correction d'erreurs M peut être appliqué aux codes-barres QR, aux codes-barres RectMicroQR et aux codes-barres MicroQR avec des versions de M2 à M4. Permet de récupérer 15 % du texte du code.

### LEVEL_Q {#LEVEL-Q}
```
public static final QRErrorLevel LEVEL_Q
```


Le niveau de correction d'erreurs Q peut être appliqué aux codes-barres QR et aux codes-barres MicroQR avec la version M4. Permet de récupérer 25 % du texte du code.

### <T>valueOf(Class<T> arg0, String arg1) {#-T-valueOf-java.lang.Class-T--java.lang.String-}
```
public static T <T>valueOf(Class<T> arg0, String arg1)
```




**Parameters:**
| Paramètre | Type | Description |
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
| Paramètre | Type | Description |
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
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### fromValue(int value) {#fromValue-int-}
```
public static QRErrorLevel fromValue(int value)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

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
| Paramètre | Type | Description |
| --- | --- | --- |
| nom | java.lang.String |  |

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
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

