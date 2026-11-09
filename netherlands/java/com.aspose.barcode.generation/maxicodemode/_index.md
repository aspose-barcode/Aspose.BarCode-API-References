---
title: "MaxiCodeMode"
second_title: "Aspose.BarCode for Java API-referentie"
description: "Bevat MaxiCode-coderingsmodi."
type: docs
weight: 94
url: /nl/java/com.aspose.barcode.generation/maxicodemode/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum MaxiCodeMode extends Enum<MaxiCodeMode>
```

Bevat MaxiCode-coderingsmodi.
## Velden

| Veld | Beschrijving |
| --- | --- |
| [MODE_2](#MODE-2) | Modus 2 codeert postinformatie in het eerste bericht en gegevens in het tweede bericht. |
| [MODE_3](#MODE-3) | Modus 3 codeert postinformatie in het eerste bericht en gegevens in het tweede bericht. |
| [MODE_4](#MODE-4) | Modus 4 codeert gegevens in het eerste en tweede bericht met korte ECC-correctie. |
| [MODE_5](#MODE-5) | Modus 5 codeert gegevens in het eerste en tweede bericht met lange ECC-correctie. |
| [MODE_6](#MODE-6) | Modus 6 codeert gegevens in het eerste en tweede bericht met korte ECC-correctie. |
## Methoden

| Methode | Beschrijving |
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


Modus 2 codeert postinformatie in het eerste bericht en gegevens in het tweede bericht. Heeft een 9-cijferige postcode en wordt alleen in de VS gebruikt.

### MODE_3 {#MODE-3}
```
public static final MaxiCodeMode MODE_3
```


Modus 3 codeert postinformatie in het eerste bericht en gegevens in het tweede bericht. Heeft een 6‑karakter alfanumerieke postcode en wordt wereldwijd gebruikt.

### MODE_4 {#MODE-4}
```
public static final MaxiCodeMode MODE_4
```


Modus 4 codeert gegevens in het eerste en tweede bericht met korte ECC-correctie.

### MODE_5 {#MODE-5}
```
public static final MaxiCodeMode MODE_5
```


Modus 5 codeert gegevens in het eerste en tweede bericht met lange ECC-correctie.

### MODE_6 {#MODE-6}
```
public static final MaxiCodeMode MODE_6
```


Modus 6 codeert gegevens in het eerste en tweede bericht met korte ECC-correctie. Wordt gebruikt om apparaten te coderen.

### <T>valueOf(Class<T> arg0, String arg1) {#-T-valueOf-java.lang.Class-T--java.lang.String-}
```
public static T <T>valueOf(Class<T> arg0, String arg1)
```




**Parameters:**
| Parameter | Type | Beschrijving |
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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | E |  |

**Returns:**
int
### equals(Object arg0) {#equals-java.lang.Object-}
```
public final boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### fromValue(int value) {#fromValue-int-}
```
public static MaxiCodeMode fromValue(int value)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| naam | java.lang.String |  |

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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

