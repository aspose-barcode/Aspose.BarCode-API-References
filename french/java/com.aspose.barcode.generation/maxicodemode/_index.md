---
title: "MaxiCodeMode"
second_title: "Référence API d'Aspose.BarCode pour Java"
description: "Contient les modes d'encodage MaxiCode."
type: docs
weight: 94
url: /fr/java/com.aspose.barcode.generation/maxicodemode/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum MaxiCodeMode extends Enum<MaxiCodeMode>
```

Contient les modes d'encodage MaxiCode.
## Champs

| Champ | Description |
| --- | --- |
| [MODE_2](#MODE-2) | Le mode 2 encode les informations postales dans le premier message et les données dans le deuxième message. |
| [MODE_3](#MODE-3) | Le mode 3 encode les informations postales dans le premier message et les données dans le deuxième message. |
| [MODE_4](#MODE-4) | Le mode 4 encode les données dans le premier et le deuxième messages avec une correction ECC courte. |
| [MODE_5](#MODE-5) | Le mode 5 encode les données dans le premier et le deuxième messages avec une correction ECC longue. |
| [MODE_6](#MODE-6) | Le mode 6 encode les données dans le premier et le deuxième messages avec une correction ECC courte. |
## Méthodes

| Méthode | Description |
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
### MODE_2 {#MODE-2}
```
public static final MaxiCodeMode MODE_2
```


Le mode 2 encode les informations postales dans le premier message et les données dans le deuxième message. Il possède un code postal à 9 chiffres et n'est utilisé qu'aux États‑Unis.

### MODE_3 {#MODE-3}
```
public static final MaxiCodeMode MODE_3
```


Le mode 3 encode les informations postales dans le premier message et les données dans le deuxième message. Il possède un code postal alphanumérique de 6 caractères et est utilisé dans le monde entier.

### MODE_4 {#MODE-4}
```
public static final MaxiCodeMode MODE_4
```


Le mode 4 encode les données dans le premier et le deuxième messages avec une correction ECC courte.

### MODE_5 {#MODE-5}
```
public static final MaxiCodeMode MODE_5
```


Le mode 5 encode les données dans le premier et le deuxième messages avec une correction ECC longue.

### MODE_6 {#MODE-6}
```
public static final MaxiCodeMode MODE_6
```


Le mode 6 encode les données dans le premier et le deuxième messages avec une correction ECC courte. Utilisé pour encoder des appareils.

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
public static MaxiCodeMode fromValue(int value)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

**Returns:**
[MaxiCodeMode](../../com.aspose.barcode.generation/maxicodemode)
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
public static MaxiCodeMode valueOf(String name)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| nom | java.lang.String |  |

**Returns:**
[MaxiCodeMode](../../com.aspose.barcode.generation/maxicodemode)
### values() {#values--}
```
public static MaxiCodeMode[] values()
```




**Returns:**
com.aspose.barcode.generation.MaxiCodeMode[]
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final native void wait(long arg0)
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

