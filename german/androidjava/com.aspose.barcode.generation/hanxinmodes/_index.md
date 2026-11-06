---
title: "HanXinModes"
second_title: "Aspose.BarCode für Android via Java API-Referenz"
description: "Kodierungsmodus für Han Xin Code."
type: docs
weight: 90
url: /de/androidjava/com.aspose.barcode.generation/hanxinmodes/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum HanXinModes extends Enum<HanXinModes>
```

Han Xin Code-Codierungsmodus. Es wird empfohlen, Auto mit ASCII-/Chinesischen Zeichen oder Unicode für Unicode-Zeichen zu verwenden.
## Felder

| Feld | Beschreibung |
| --- | --- |
| [AUTO](#AUTO) | Sequenz von Numeric-, Text-, ECI-, Binary-Bytes- und 4-GB18030-Modi, die sich automatisch ändern. |
| [BINARY](#BINARY) | Der Binary‑Byte‑Modus kodiert Binärdaten in beliebiger Form und kodiert sie in ihrem Binärbyte. |
| [COMMON_CHINESE_REGION_ONE](#COMMON-CHINESE-REGION-ONE) | Jedes gängige chinesische Zeichen in Region Eins wird durch 12 Bit dargestellt. |
| [COMMON_CHINESE_REGION_TWO](#COMMON-CHINESE-REGION-TWO) | Jedes gängige chinesische Zeichen in Region Zwei wird durch 12 Bit dargestellt. |
| [ECI](#ECI) | Extended Channel Interpretation (ECI)-Modus |
| [GB_18030_FOUR_BYTE](#GB-18030-FOUR-BYTE) | Jedes GB18030‑4‑Byte‑Region‑Zeichen wird durch 21 Bit dargestellt. |
| [GB_18030_TWO_BYTE](#GB-18030-TWO-BYTE) | Jedes GB18030‑2‑Byte‑Region‑Zeichen wird durch 15 Bit dargestellt. |
| [GS_1](#GS-1) | Der GS1‑Modus gibt an, dass die im Han‑Xin‑Code dargestellten Daten GS1‑Daten des GS1‑Systems sind, definiert durch die GS1 General Specification. |
| [NUMERIC](#NUMERIC) | Der Numerische Modus kodiert Daten aus dem Dezimalziffern‑Set (Ziffern 0‑9, Byte‑Werte 30HEX bis 39HEX). |
| [TEXT](#TEXT) | Der Textmodus kodiert Daten aus den in ISO/IEC 646 definierten gängigen Symbolen, d. h. |
| [UNICODE](#UNICODE) | Der Unicode‑Modus entwirft eine Methode, um beliebige Textdaten, die sich auf die UTF‑8‑Kodierung/Zeichensatz im Han‑Xin‑Code beziehen, darzustellen. |
| [URI](#URI) | Der URI‑Modus gibt an, dass die im Han‑Xin‑Code dargestellten Daten Uniform Resource Identifier (URI)-Referenzen gemäß RFC 3986 sind. |
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
### AUTO {#AUTO}
```
public static final HanXinModes AUTO
```


Sequenz von Numeric-, Text-, ECI-, Binary-Bytes- und 4-GB18030-Modi, die sich automatisch ändern.

### BINARY {#BINARY}
```
public static final HanXinModes BINARY
```


Der Binary‑Byte‑Modus kodiert Binärdaten in beliebiger Form und kodiert sie in ihrem Binärbyte. Jedes Byte im Binary‑Byte‑Modus wird durch 8 Bit dargestellt.

### COMMON_CHINESE_REGION_ONE {#COMMON-CHINESE-REGION-ONE}
```
public static final HanXinModes COMMON_CHINESE_REGION_ONE
```


Jedes gängige chinesische Zeichen in Region Eins wird durch 12 Bit dargestellt. Gängige chinesische Zeichen in Region Eins umfassen Zeichen, deren erstes Byte im Bereich B0HEX bis D7HEX liegt und deren zweites Byte im Bereich A1HEX bis FEHEX (3760 Zeichen), sowie Zeichen, deren erstes Byte im Bereich A1HEX bis A3HEX liegt und zweites Byte im Bereich A1HEX bis FEHEX (282 Zeichen), und Zeichen, deren Byte‑Werte im Bereich A8A1HEX bis A8C0HEX liegen (32 Zeichen).

### COMMON_CHINESE_REGION_TWO {#COMMON-CHINESE-REGION-TWO}
```
public static final HanXinModes COMMON_CHINESE_REGION_TWO
```


Jedes gängige chinesische Zeichen in Region Zwei wird durch 12 Bit dargestellt. Gängige chinesische Zeichen in Region Zwei umfassen Zeichen, deren erstes Byte im Bereich D8HEX bis F7HEX liegt und deren zweites Byte im Bereich A1HEX bis FEHEX.

### ECI {#ECI}
```
public static final HanXinModes ECI
```


Extended Channel Interpretation (ECI)-Modus

### GB_18030_FOUR_BYTE {#GB-18030-FOUR-BYTE}
```
public static final HanXinModes GB_18030_FOUR_BYTE
```


Jedes GB18030‑4‑Byte‑Region‑Zeichen wird durch 21 Bit dargestellt. Die GB18030‑4‑Byte‑Region kodiert Daten aus allen Zeichen im GB18030‑Vier‑Byte‑Bereich (d. h. Zeichen, deren erstes Byte im Bereich 81HEX bis FEHEX liegt, zweites Byte im Bereich 30HEX bis 39HEX, drittes Byte im Bereich 81HEX bis FEHEX und viertes Byte im Bereich 30HEX bis 39HEX).

### GB_18030_TWO_BYTE {#GB-18030-TWO-BYTE}
```
public static final HanXinModes GB_18030_TWO_BYTE
```


Jedes GB18030‑2‑Byte‑Region‑Zeichen wird durch 15 Bit dargestellt. Die GB18030‑2‑Byte‑Region kodiert Daten aus allen Zeichen (einschließlich der gängigen chinesischen Zeichen in den Regionen Eins und Zwei) im GB18030‑Doppel‑Byte‑Bereich, (d. h. chinesische Zeichen, deren erstes Byte im Bereich 81HEX bis FEHEX liegt und deren zweites Byte im Bereich 40HEX bis 7EHEX oder 80HEX bis FEHEX liegt).

### GS_1 {#GS-1}
```
public static final HanXinModes GS_1
```


Der GS1‑Modus gibt an, dass die im Han‑Xin‑Code dargestellten Daten GS1‑Daten des GS1‑Systems sind, definiert durch die GS1 General Specification. Beispiel für Eingabezeichenfolge: \"(01)03453120000011(17)191125(10)ABCD1234(21)10\".

### NUMERIC {#NUMERIC}
```
public static final HanXinModes NUMERIC
```


Der Numerische Modus kodiert Daten aus dem Dezimalziffern‑Set (Ziffern 0‑9, Byte‑Werte 30HEX bis 39HEX). Normalerweise werden 3 Datenzeichen durch 10 Bit dargestellt.

### TEXT {#TEXT}
```
public static final HanXinModes TEXT
```


Der Textmodus kodiert Daten aus gängigen Symbolen, die in ISO/IEC 646 definiert sind, d. h. Byte‑Werte 00 HEX bis 1B HEX und 20 HEX bis 7F HEX.

### UNICODE {#UNICODE}
```
public static final HanXinModes UNICODE
```


Der Unicode‑Modus entwirft eine Methode, um beliebige Textdaten, die sich auf die UTF‑8‑Kodierung/Zeichensatz im Han‑Xin‑Code beziehen, darzustellen.

### URI {#URI}
```
public static final HanXinModes URI
```


Der URI‑Modus gibt an, dass die im Han‑Xin‑Code dargestellten Daten Uniform Resource Identifier (URI)-Referenzen gemäß RFC 3986 sind.

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
public static HanXinModes fromValue(int value)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

**Returns:**
com.aspose.barcode.generation.HanXinModes
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
public static HanXinModes valueOf(String name)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Name | java.lang.String |  |

**Returns:**
com.aspose.barcode.generation.HanXinModes
### values() {#values--}
```
public static HanXinModes[] values()
```




**Returns:**
com.aspose.barcode.generation.HanXinModes[]
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

