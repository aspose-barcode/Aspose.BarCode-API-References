---
title: HanXinModes
second_title: Aspose.BarCode for Android via Java API-referentie
description: Coderingsmodus voor Han Xin Code.
type: docs
weight: 91
url: /nl/androidjava/com.aspose.barcode.generation/hanxinmodes/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum HanXinModes extends Enum<HanXinModes>
```

Han Xin Code-coderingsmodus. Het wordt aanbevolen om Auto te gebruiken met ASCII / Chinese tekens of Unicode voor Unicode‑tekens.
## Velden

| Veld | Beschrijving |
| --- | --- |
| [AUTO](#AUTO) | Reeks van Numeriek, Tekst, ECI, Binaire Bytes en 4 GB18030‑modi die automatisch veranderen. |
| [BINARY](#BINARY) | Binaire byte‑modus codeert binaire gegevens in elke vorm en codeert ze in hun binaire byte. |
| [COMMON_CHINESE_REGION_ONE](#COMMON-CHINESE-REGION-ONE) | Elk veelvoorkomend Chinees teken in Regio één wordt weergegeven met 12 bits. |
| [COMMON_CHINESE_REGION_TWO](#COMMON-CHINESE-REGION-TWO) | Elk veelvoorkomend Chinees teken in Regio twee wordt weergegeven met 12 bits. |
| [ECI](#ECI) | Extended Channel Interpretation (ECI)-modus |
| [GB_18030_FOUR_BYTE](#GB-18030-FOUR-BYTE) | Elk GB18030‑4‑byte‑regioteken wordt weergegeven met 21 bits. |
| [GB_18030_TWO_BYTE](#GB-18030-TWO-BYTE) | Elk GB18030‑2‑byte‑regioteken wordt weergegeven met 15 bits. |
| [GS_1](#GS-1) | GS1‑modus geeft aan dat de gegevens die in Han Xin Code worden weergegeven GS1‑gegevens zijn van het GS1‑systeem, gedefinieerd door de GS1‑General Specification. |
| [NUMERIC](#NUMERIC) | Numerieke modus codeert gegevens uit de decimale cijferreeks (cijfers 0-9, byte‑waarden 30HEX tot 39HEX). |
| [TEXT](#TEXT) | Tekstmodus codeert gegevens uit de veelvoorkomende symbolen gedefinieerd in ISO/IEC 646, d.w.z. |
| [UNICODE](#UNICODE) | Unicode‑modus biedt een manier om elke tekstgegevensreferentie naar UTF‑8‑codering/tekenset in Han Xin Code weer te geven. |
| [URI](#URI) | URI‑modus geeft aan dat de gegevens die in Han Xin Code worden weergegeven een Uniform Resource Identifier (URI)-referentie volgens RFC 3986 zijn. |
## Methods

| Method | Beschrijving |
| --- | --- |
| [<T>valueOf(Class<T> arg0, String arg1)](#-T-valueOf-java.lang.Class-T--java.lang.String-) |  |
| [compareTo(E arg0)](#compareTo-E-) |  |
| [describeConstable()](#describeConstable--) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
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


Reeks van Numeriek, Tekst, ECI, Binaire Bytes en 4 GB18030‑modi die automatisch veranderen.

### BINARY {#BINARY}
```
public static final HanXinModes BINARY
```


Binaire byte‑modus codeert binaire gegevens in elke vorm en codeert ze in hun binaire byte. Elke byte in Binaire Byte‑modus wordt weergegeven met 8 bits.

### COMMON_CHINESE_REGION_ONE {#COMMON-CHINESE-REGION-ONE}
```
public static final HanXinModes COMMON_CHINESE_REGION_ONE
```


Elk veelvoorkomend Chinees teken in Regio één wordt weergegeven met 12 bits. Veelvoorkomende Chinese tekens in Regio één omvatten tekens waarvan de eerste byte‑waarde ligt tussen B0HEX en D7HEX en de tweede byte‑waarde tussen A1HEX en FEHEX (3760 tekens), en tekens waarvan de eerste byte‑waarde ligt tussen A1HEX en A3HEX en de tweede byte‑waarde tussen A1HEX en FEHEX (282 tekens), en tekens waarvan de byte‑waarden liggen tussen A8A1HEX en A8C0HEX (32 tekens).

### COMMON_CHINESE_REGION_TWO {#COMMON-CHINESE-REGION-TWO}
```
public static final HanXinModes COMMON_CHINESE_REGION_TWO
```


Elk veelvoorkomend Chinees teken in Regio twee wordt weergegeven met 12 bits. Veelvoorkomende Chinese tekens in Regio twee omvatten tekens waarvan de eerste byte‑waarde ligt tussen D8HEX en F7HEX en de tweede byte‑waarde tussen A1HEX en FEHEX.

### ECI {#ECI}
```
public static final HanXinModes ECI
```


Extended Channel Interpretation (ECI)-modus

### GB_18030_FOUR_BYTE {#GB-18030-FOUR-BYTE}
```
public static final HanXinModes GB_18030_FOUR_BYTE
```


Elk GB18030‑4‑byte‑regioteken wordt weergegeven met 21 bits. GB18030‑4‑byte‑Regio codeert gegevens van alle tekens in de GB18030‑vier‑byte‑regio (d.w.z. tekens waarvan de eerste byte‑waarde ligt tussen 81HEX en FEHEX, de tweede byte‑waarde tussen 30HEX en 39HEX, de derde byte‑waarde tussen 81HEX en FEHEX, en de vierde byte‑waarde tussen 30HEX en 39HEX).

### GB_18030_TWO_BYTE {#GB-18030-TWO-BYTE}
```
public static final HanXinModes GB_18030_TWO_BYTE
```


Elk GB18030‑2‑byte‑regioteken wordt weergegeven met 15 bits. De GB18030‑2‑byte‑Regio codeert gegevens van alle tekens (inclusief de veelvoorkomende Chinese tekens in Regio één en twee) in de GB18030‑dubbele‑byte‑regio, (d.w.z. Chinese tekens waarvan de eerste byte‑waarde ligt tussen 81HEX en FEHEX en de tweede byte‑waarde tussen 40HEX en 7EHEX of 80HEX en FEHEX).

### GS_1 {#GS-1}
```
public static final HanXinModes GS_1
```


GS1‑modus geeft aan dat de gegevens die in Han Xin Code worden weergegeven GS1‑gegevens zijn van het GS1‑systeem, gedefinieerd door de GS1‑General Specification. Voorbeeld van invoertekst: "(01)03453120000011(17)191125(10)ABCD1234(21)10".

### NUMERIC {#NUMERIC}
```
public static final HanXinModes NUMERIC
```


Numerieke modus codeert gegevens uit de decimale cijferreeks (cijfers 0-9, byte‑waarden 30HEX tot 39HEX). Normaal worden 3 gegevenskarakters weergegeven met 10 bits.

### TEXT {#TEXT}
```
public static final HanXinModes TEXT
```


Tekstmodus codeert gegevens uit de veelvoorkomende symbolen gedefinieerd in ISO/IEC 646, d.w.z. byte‑waarden 00HEX tot 1BHEX en 20HEX tot 7FHEX.

### UNICODE {#UNICODE}
```
public static final HanXinModes UNICODE
```


Unicode‑modus biedt een manier om elke tekstgegevensreferentie naar UTF‑8‑codering/tekenset in Han Xin Code weer te geven.

### URI {#URI}
```
public static final HanXinModes URI
```


URI‑modus geeft aan dat de gegevens die in Han Xin Code worden weergegeven een Uniform Resource Identifier (URI)-referentie volgens RFC 3986 zijn.

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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| naam | java.lang.String |  |

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

