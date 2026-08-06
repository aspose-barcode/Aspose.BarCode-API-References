---
title: HanXinModes
second_title: Aspose.BarCode for Android via Java API-referens
description: Han Xin Code kodningsläge.
type: docs
weight: 91
url: /sv/androidjava/com.aspose.barcode.generation/hanxinmodes/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum HanXinModes extends Enum<HanXinModes>
```

Han Xin Code-kodningsläge. Det rekommenderas att använda Auto med ASCII / kinesiska tecken eller Unicode för Unicode-tecken.
## Fält

| Fält | Beskrivning |
| --- | --- |
| [AUTO](#AUTO) | Sekvens av Numeriska, Text, ECI, Binära byte och 4 GB18030-lägen som ändras automatiskt. |
| [BINARY](#BINARY) | Binärt byte-läge kodar binär data i vilken form som helst och kodar dem i deras binära byte. |
| [COMMON_CHINESE_REGION_ONE](#COMMON-CHINESE-REGION-ONE) | Varje vanligt kinesiskt tecken i Region ett representeras med 12 bitar. |
| [COMMON_CHINESE_REGION_TWO](#COMMON-CHINESE-REGION-TWO) | Varje vanligt kinesiskt tecken i Region två representeras med 12 bitar. |
| [ECI](#ECI) | Extended Channel Interpretation (ECI)-läge |
| [GB_18030_FOUR_BYTE](#GB-18030-FOUR-BYTE) | Varje GB18030 4-byte region-tecken representeras med 21 bitar. |
| [GB_18030_TWO_BYTE](#GB-18030-TWO-BYTE) | Varje GB18030 2-byte region-tecken representeras med 15 bitar. |
| [GS_1](#GS-1) | GS1-läge indikerar att data som representeras i Han Xin Code är GS1-data från GS1-systemet definierat av GS1 General Specification. |
| [NUMERIC](#NUMERIC) | Numeriskt läge kodar data från decimalteckenset (siffror 0-9, bytevärden 30HEX till 39HEX). |
| [TEXT](#TEXT) | Textläge kodar data från vanliga symboler definierade i ISO/IEC 646, t.ex. |
| [UNICODE](#UNICODE) | Unicode-läge utformar ett sätt att representera all textdata med referens till UTF8-kodning/teckenuppsättning i Han Xin Code. |
| [URI](#URI) | URI-läge indikerar att data som representeras i Han Xin Code är Uniform Resource Identifier (URI)-referens till RFC 3986. |
## Methods

| Method | Beskrivning |
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


Sekvens av Numeriska, Text, ECI, Binära byte och 4 GB18030-lägen som ändras automatiskt.

### BINARY {#BINARY}
```
public static final HanXinModes BINARY
```


Binärt byte-läge kodar binär data i vilken form som helst och kodar dem i deras binära byte. Varje byte i Binärt byte-läge representeras med 8 bitar.

### COMMON_CHINESE_REGION_ONE {#COMMON-CHINESE-REGION-ONE}
```
public static final HanXinModes COMMON_CHINESE_REGION_ONE
```


Varje vanligt kinesiskt tecken i Region ett representeras med 12 bitar. Vanliga kinesiska tecken i Region ett inkluderar tecken vars första bytevärde ligger i intervallet B0HEX till D7HEX och andra bytevärde i intervallet A1HEX till FEHEX (3760 tecken), samt tecken vars första bytevärde ligger i intervallet A1HEX till A3HEX och andra bytevärde i intervallet A1HEX till FEHEX (282 tecken), samt tecken vars bytevärden ligger i intervallet A8A1HEX till A8C0HEX (32 tecken).

### COMMON_CHINESE_REGION_TWO {#COMMON-CHINESE-REGION-TWO}
```
public static final HanXinModes COMMON_CHINESE_REGION_TWO
```


Varje vanligt kinesiskt tecken i Region två representeras med 12 bitar. Vanliga kinesiska tecken i Region två inkluderar tecken vars första bytevärde ligger i intervallet D8HEX till F7HEX och andra bytevärde i intervallet A1HEX till FEHEX.

### ECI {#ECI}
```
public static final HanXinModes ECI
```


Extended Channel Interpretation (ECI)-läge

### GB_18030_FOUR_BYTE {#GB-18030-FOUR-BYTE}
```
public static final HanXinModes GB_18030_FOUR_BYTE
```


Varje GB18030 4-byte region-tecken representeras med 21 bitar. GB18030 4-byte region kodar data från alla tecken i GB18030:s fyrabyte-region (dvs. tecken vars första bytevärde ligger i intervallet 81HEX till FEHEX, andra bytevärde i intervallet 30HEX till 39HEX, tredje bytevärde i intervallet 81HEX till FEHEX och fjärde bytevärde i intervallet 30HEX till 39HEX).

### GB_18030_TWO_BYTE {#GB-18030-TWO-BYTE}
```
public static final HanXinModes GB_18030_TWO_BYTE
```


Varje GB18030 2-byte region-tecken representeras med 15 bitar. GB18030 2-byte region kodar data från alla tecken (inklusive vanliga kinesiska tecken i Region ett och två) i GB18030:s dubbelbyte-region, (dvs. kinesiska tecken vars första bytevärde ligger i intervallet 81HEX till FEHEX och andra bytevärde ligger i intervallet 40HEX till 7EHEX eller 80HEX till FEHEX).

### GS_1 {#GS-1}
```
public static final HanXinModes GS_1
```


GS1-läge indikerar att data som representeras i Han Xin Code är GS1-data från GS1-systemet definierat av GS1 General Specification. Exempel på inmatningssträng: "(01)03453120000011(17)191125(10)ABCD1234(21)10".

### NUMERIC {#NUMERIC}
```
public static final HanXinModes NUMERIC
```


Numeriskt läge kodar data från decimalteckenset (siffror 0-9, bytevärden 30HEX till 39HEX). Vanligtvis representeras 3 datatecken med 10 bitar.

### TEXT {#TEXT}
```
public static final HanXinModes TEXT
```


Textläge kodar data från vanliga symboler definierade i ISO/IEC 646, d.v.s. bytevärden 00 HEX till 1B HEX och 20 HEX till 7F HEX.

### UNICODE {#UNICODE}
```
public static final HanXinModes UNICODE
```


Unicode-läge utformar ett sätt att representera all textdata med referens till UTF8-kodning/teckenuppsättning i Han Xin Code.

### URI {#URI}
```
public static final HanXinModes URI
```


URI-läge indikerar att data som representeras i Han Xin Code är Uniform Resource Identifier (URI)-referens till RFC 3986.

### <T>valueOf(Class<T> arg0, String arg1) {#-T-valueOf-java.lang.Class-T--java.lang.String-}
```
public static T <T>valueOf(Class<T> arg0, String arg1)
```




**Parameters:**
| Parameter | Type | Beskrivning |
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
| Parameter | Type | Beskrivning |
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
| Parameter | Type | Beskrivning |
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
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| namn | java.lang.String |  |

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
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

