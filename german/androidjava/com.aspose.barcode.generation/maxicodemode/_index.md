---
title: "MaxiCodeMode"
second_title: "Aspose.BarCode für Android via Java API-Referenz"
description: "Enthält MaxiCode-Kodierungsmodi."
type: docs
weight: 95
url: /de/androidjava/com.aspose.barcode.generation/maxicodemode/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum MaxiCodeMode extends Enum<MaxiCodeMode>
```

Enthält MaxiCode-Kodierungsmodi.
## Felder

| Feld | Beschreibung |
| --- | --- |
| [MODE_2](#MODE-2) | Modus 2 kodiert Postinformationen in der ersten Nachricht und Daten in der zweiten Nachricht. |
| [MODE_3](#MODE-3) | Modus 3 kodiert Postinformationen in der ersten Nachricht und Daten in der zweiten Nachricht. |
| [MODE_4](#MODE-4) | Modus 4 kodiert Daten in der ersten und zweiten Nachricht mit kurzer ECC‑Korrektur. |
| [MODE_5](#MODE-5) | Modus 5 kodiert Daten in der ersten und zweiten Nachricht mit langer ECC‑Korrektur. |
| [MODE_6](#MODE-6) | Modus 6 kodiert Daten in der ersten und zweiten Nachricht mit kurzer ECC‑Korrektur. |
## Methoden

| Methode | Beschreibung |
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
### MODE_2 {#MODE-2}
```
public static final MaxiCodeMode MODE_2
```


Modus 2 kodiert Postinformationen in der ersten Nachricht und Daten in der zweiten Nachricht. Hat eine 9‑stellige Postleitzahl und wird nur in den USA verwendet.

### MODE_3 {#MODE-3}
```
public static final MaxiCodeMode MODE_3
```


Modus 3 kodiert Postinformationen in der ersten Nachricht und Daten in der zweiten Nachricht. Hat eine 6‑stellige alphanumerische Postleitzahl und wird weltweit verwendet.

### MODE_4 {#MODE-4}
```
public static final MaxiCodeMode MODE_4
```


Modus 4 kodiert Daten in der ersten und zweiten Nachricht mit kurzer ECC‑Korrektur.

### MODE_5 {#MODE-5}
```
public static final MaxiCodeMode MODE_5
```


Modus 5 kodiert Daten in der ersten und zweiten Nachricht mit langer ECC‑Korrektur.

### MODE_6 {#MODE-6}
```
public static final MaxiCodeMode MODE_6
```


Modus 6 kodiert Daten in der ersten und zweiten Nachricht mit kurzer ECC‑Korrektur. Wird zum Kodieren von Geräten verwendet.

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
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### fromValue(int value) {#fromValue-int-}
```
public static MaxiCodeMode fromValue(int value)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

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
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Name | java.lang.String |  |

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
public final void wait(long arg0)
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

