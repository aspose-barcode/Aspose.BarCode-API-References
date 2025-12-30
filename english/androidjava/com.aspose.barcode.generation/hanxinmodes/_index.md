---
title: HanXinModes
second_title: Aspose.BarCode for Android via Java API Reference
description: Han Xin Code encoding mode.
type: docs
weight: 91
url: /androidjava/com.aspose.barcode.generation/hanxinmodes/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum HanXinModes extends Enum<HanXinModes>
```

Han Xin Code encoding mode. It is recommended to use Auto with ASCII / Chinese characters or Unicode for Unicode characters.
## Fields

| Field | Description |
| --- | --- |
| [AUTO](#AUTO) | Sequence of Numeric, Text, ECI, Binary Bytes and 4 GB18030 modes changing automatically. |
| [BINARY](#BINARY) | Binary byte mode encodes binary data in any form and encodes them in their binary byte. |
| [COMMON_CHINESE_REGION_ONE](#COMMON-CHINESE-REGION-ONE) | Every common Chinese Character in Region One is represented by 12 bits. |
| [COMMON_CHINESE_REGION_TWO](#COMMON-CHINESE-REGION-TWO) | Every common Chinese Character in Region Two is represented by 12 bits. |
| [ECI](#ECI) | Extended Channel Interpretation (ECI) mode |
| [GB_18030_FOUR_BYTE](#GB-18030-FOUR-BYTE) | Every GB18030 4-byte Region character is represented by 21 bits. |
| [GB_18030_TWO_BYTE](#GB-18030-TWO-BYTE) | Every GB18030 2-byte Region character is represented by 15 bits. |
| [GS_1](#GS-1) | GS1 mode indicates the data represented in Han Xin Code is GS1 data of GS1 system defined by GS1 General Specification. |
| [NUMERIC](#NUMERIC) | Numeric mode encodes data from decimal digit set (digits 0-9, byte values 30HEX to 39HEX). |
| [TEXT](#TEXT) | Text mode encodes data from common symbols defined in ISO/IEC 646, i.e. |
| [UNICODE](#UNICODE) | Unicode mode designs a way to represent any text data reference to UTF8 encoding/charset in Han Xin Code. |
| [URI](#URI) | URI mode indicates the data represented in Han Xin Code is Uniform Resource Identifier (URI) reference to RFC 3986. |
## Methods

| Method | Description |
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


Sequence of Numeric, Text, ECI, Binary Bytes and 4 GB18030 modes changing automatically.

### BINARY {#BINARY}
```
public static final HanXinModes BINARY
```


Binary byte mode encodes binary data in any form and encodes them in their binary byte. Every byte in Binary Byte mode is represented by 8 bits.

### COMMON_CHINESE_REGION_ONE {#COMMON-CHINESE-REGION-ONE}
```
public static final HanXinModes COMMON_CHINESE_REGION_ONE
```


Every common Chinese Character in Region One is represented by 12 bits. Common Chinese Characters in Region one includes characters whose first byte value is in the range of B0HEX to D7HEX and second byte value is in the range of A1HEX to FEHEX (3760 characters), and characters whose first byte value is in the range of A1HEX to A3HEX, and second byte value is in the range of A1HEX to FEHEX (282 characters), and characters whose byte values are in the range of A8A1HEX to A8C0HEX (32 characters).

### COMMON_CHINESE_REGION_TWO {#COMMON-CHINESE-REGION-TWO}
```
public static final HanXinModes COMMON_CHINESE_REGION_TWO
```


Every common Chinese Character in Region Two is represented by 12 bits. Common Chinese Characters in Region Two which includes character whose first byte value is in the range of D8HEX to F7HEX, and second byte value is in the range of A1HEX to FEHEX.

### ECI {#ECI}
```
public static final HanXinModes ECI
```


Extended Channel Interpretation (ECI) mode

### GB_18030_FOUR_BYTE {#GB-18030-FOUR-BYTE}
```
public static final HanXinModes GB_18030_FOUR_BYTE
```


Every GB18030 4-byte Region character is represented by 21 bits. GB18030 4-byte Region encodes data from all characters in GB18030 four-byte region (i.e., characters whose first byte value is in the range of 81HEX to FEHEX, and second byte value is in the range of 30HEX to 39HEX, and third byte value is in the range of 81HEX to FEHEX, and fourth byte value is in the range of 30HEXto 39HEX).

### GB_18030_TWO_BYTE {#GB-18030-TWO-BYTE}
```
public static final HanXinModes GB_18030_TWO_BYTE
```


Every GB18030 2-byte Region character is represented by 15 bits. The GB18030 2-byte Region encodes data from all characters (including the common Chinese Characters in Regions One and Two) in GB18030 double-byte region, (i.e., Chinese characters whose first byte value is in the range of 81HEX to FEHEX and second byte value is in the range of 40HEX to 7EHEX or 80HEX to FEHEX).

### GS_1 {#GS-1}
```
public static final HanXinModes GS_1
```


GS1 mode indicates the data represented in Han Xin Code is GS1 data of GS1 system defined by GS1 General Specification. Example of input string: "(01)03453120000011(17)191125(10)ABCD1234(21)10".

### NUMERIC {#NUMERIC}
```
public static final HanXinModes NUMERIC
```


Numeric mode encodes data from decimal digit set (digits 0-9, byte values 30HEX to 39HEX). Normally, 3 data characters are represented by 10 bit.

### TEXT {#TEXT}
```
public static final HanXinModes TEXT
```


Text mode encodes data from common symbols defined in ISO/IEC 646, i.e. byte values 00 HEX to 1B HEX and 20 HEX to 7F HEX.

### UNICODE {#UNICODE}
```
public static final HanXinModes UNICODE
```


Unicode mode designs a way to represent any text data reference to UTF8 encoding/charset in Han Xin Code.

### URI {#URI}
```
public static final HanXinModes URI
```


URI mode indicates the data represented in Han Xin Code is Uniform Resource Identifier (URI) reference to RFC 3986.

### <T>valueOf(Class<T> arg0, String arg1) {#-T-valueOf-java.lang.Class-T--java.lang.String-}
```
public static T <T>valueOf(Class<T> arg0, String arg1)
```




**Parameters:**
| Parameter | Type | Description |
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
| Parameter | Type | Description |
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
| Parameter | Type | Description |
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
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String |  |

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
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

