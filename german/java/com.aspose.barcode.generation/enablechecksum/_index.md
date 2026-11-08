---
title: "EnableChecksum"
second_title: "Aspose.BarCode für Java API-Referenz"
description: "Prüfsumme während der Erzeugung für 1D-Barcodes aktivieren."
type: docs
weight: 84
url: /de/java/com.aspose.barcode.generation/enablechecksum/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum EnableChecksum extends Enum<EnableChecksum>
```

Prüfsumme während der Erzeugung für 1D-Barcodes aktivieren.

Standardmäßig wird Yes für Symbologien verwendet, die eine Prüfsumme enthalten müssen, und No, wo eine Prüfsumme nur möglich ist.

Prüfsumme wird nie verwendet: Codabar

Prüfsumme ist möglich: Code39 Standard/Extended, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, DeutschePostIdentcode, DeutschePostLeitcode, VIN

Prüfsumme wird immer verwendet: Restliche Symbologien
## Felder

| Feld | Beschreibung |
| --- | --- |
| [DEFAULT](#DEFAULT) | Falls die Prüfsumme gemäß der Spezifikation erforderlich ist, wird sie angehängt. |
| [NO](#NO) | Verwenden Sie keine Prüfsumme. |
| [YES](#YES) | Verwenden Sie immer die Prüfsumme, wenn möglich. |
## Methoden

| Methode | Beschreibung |
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
### DEFAULT {#DEFAULT}
```
public static final EnableChecksum DEFAULT
```


Falls die Prüfsumme gemäß der Spezifikation erforderlich ist, wird sie angehängt.

### NO {#NO}
```
public static final EnableChecksum NO
```


Verwenden Sie keine Prüfsumme.

### YES {#YES}
```
public static final EnableChecksum YES
```


Verwenden Sie immer die Prüfsumme, wenn möglich.

### <T>valueOf(Class<T> arg0, String arg1) {#-T-valueOf-java.lang.Class-T--java.lang.String-}
```
public static T <T>valueOf(Class<T> arg0, String arg1)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
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
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | E |  |

**Returns:**
int
### equals(Object arg0) {#equals-java.lang.Object-}
```
public final boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolesch
### fromValue(int value) {#fromValue-int-}
```
public static EnableChecksum fromValue(int value)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

**Returns:**
[EnableChecksum](../../com.aspose.barcode.generation/enablechecksum)
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
public static EnableChecksum valueOf(String name)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Name | java.lang.String |  |

**Returns:**
[EnableChecksum](../../com.aspose.barcode.generation/enablechecksum)
### values() {#values--}
```
public static EnableChecksum[] values()
```




**Returns:**
com.aspose.barcode.generation.EnableChecksum[]
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final native void wait(long arg0)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

