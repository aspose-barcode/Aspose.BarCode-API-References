---
title: HanXinModes
second_title: Aspose.BarCode for Android via Java API Reference
description: Han Xin Code のエンコーディングモード。
type: docs
weight: 91
url: /ja/androidjava/com.aspose.barcode.generation/hanxinmodes/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum HanXinModes extends Enum<HanXinModes>
```

Han Xin Code のエンコードモードです。ASCII / 中国語文字または Unicode を使用する場合は、Auto を使用することを推奨します。
## フィールド

| フィールド | Description |
| --- | --- |
| [AUTO](#AUTO) | Numeric、Text、ECI、Binary Bytes、4 GB18030 モードのシーケンスが自動的に切り替わります。 |
| [BINARY](#BINARY) | Binary byte モードは、任意の形式のバイナリデータをエンコードし、そのバイナリバイトとして符号化します。 |
| [COMMON_CHINESE_REGION_ONE](#COMMON-CHINESE-REGION-ONE) | リージョン1のすべての一般的な中国文字は 12 ビットで表されます。 |
| [COMMON_CHINESE_REGION_TWO](#COMMON-CHINESE-REGION-TWO) | リージョン2のすべての一般的な中国文字は 12 ビットで表されます。 |
| [ECI](#ECI) | Extended Channel Interpretation (ECI) モード |
| [GB_18030_FOUR_BYTE](#GB-18030-FOUR-BYTE) | GB18030 4 バイト領域の文字はすべて 21 ビットで表されます。 |
| [GB_18030_TWO_BYTE](#GB-18030-TWO-BYTE) | GB18030 2 バイト領域の文字はすべて 15 ビットで表されます。 |
| [GS_1](#GS-1) | GS1 モードは、Han Xin Code で表されるデータが GS1 General Specification によって定義された GS1 システムの GS1 データであることを示します。 |
| [NUMERIC](#NUMERIC) | Numeric モードは、10 進数字セット（数字 0-9、バイト値 30HEX から 39HEX）からデータをエンコードします。 |
| [TEXT](#TEXT) | Text モードは、ISO/IEC 646 で定義された一般的な記号からデータをエンコードします。 |
| [UNICODE](#UNICODE) | Unicode モードは、Han Xin Code において UTF8 エンコーディング/文字セットへの参照として任意のテキストデータを表現する方法を設計します。 |
| [URI](#URI) | URI モードは、Han Xin Code で表されるデータが RFC 3986 に準拠した Uniform Resource Identifier (URI) 参照であることを示します。 |
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


Numeric、Text、ECI、Binary Bytes、4 GB18030 モードのシーケンスが自動的に切り替わります。

### BINARY {#BINARY}
```
public static final HanXinModes BINARY
```


Binary byte モードは、任意の形式のバイナリデータをエンコードし、そのバイナリバイトとして符号化します。Binary Byte モードの各バイトは 8 ビットで表されます。

### COMMON_CHINESE_REGION_ONE {#COMMON-CHINESE-REGION-ONE}
```
public static final HanXinModes COMMON_CHINESE_REGION_ONE
```


リージョン1のすべての一般的な中国文字は 12 ビットで表されます。リージョン1の一般的な中国文字には、最初のバイト値が B0HEX から D7HEX、2 番目のバイト値が A1HEX から FEHEX の範囲にある文字（3760 文字）、最初のバイト値が A1HEX から A3HEX、2 番目のバイト値が A1HEX から FEHEX の範囲にある文字（282 文字）、およびバイト値が A8A1HEX から A8C0HEX の範囲にある文字（32 文字）が含まれます。

### COMMON_CHINESE_REGION_TWO {#COMMON-CHINESE-REGION-TWO}
```
public static final HanXinModes COMMON_CHINESE_REGION_TWO
```


リージョン2のすべての一般的な中国文字は 12 ビットで表されます。リージョン2の一般的な中国文字には、最初のバイト値が D8HEX から F7HEX、2 番目のバイト値が A1HEX から FEHEX の範囲にある文字が含まれます。

### ECI {#ECI}
```
public static final HanXinModes ECI
```


Extended Channel Interpretation (ECI) モード

### GB_18030_FOUR_BYTE {#GB-18030-FOUR-BYTE}
```
public static final HanXinModes GB_18030_FOUR_BYTE
```


GB18030 4 バイト領域の文字はすべて 21 ビットで表されます。GB18030 4 バイト領域は、GB18030 の 4 バイト領域にあるすべての文字からデータをエンコードします（すなわち、最初のバイト値が 81HEX から FEHEX、2 番目のバイト値が 30HEX から 39HEX、3 番目のバイト値が 81HEX から FEHEX、4 番目のバイト値が 30HEX から 39HEX の範囲にある文字）。

### GB_18030_TWO_BYTE {#GB-18030-TWO-BYTE}
```
public static final HanXinModes GB_18030_TWO_BYTE
```


GB18030 2 バイト領域の文字はすべて 15 ビットで表されます。GB18030 2 バイト領域は、GB18030 のダブルバイト領域にあるすべての文字（リージョン1およびリージョン2の一般的な中国文字を含む）からデータをエンコードします（すなわち、最初のバイト値が 81HEX から FEHEX、2 番目のバイト値が 40HEX から 7EHEX または 80HEX から FEHEX の範囲にある中国文字）。

### GS_1 {#GS-1}
```
public static final HanXinModes GS_1
```


GS1 モードは、Han Xin Code で表されるデータが GS1 General Specification によって定義された GS1 システムの GS1 データであることを示します。入力文字列の例: "(01)03453120000011(17)191125(10)ABCD1234(21)10"。

### NUMERIC {#NUMERIC}
```
public static final HanXinModes NUMERIC
```


Numeric モードは、10 進数字セット（数字 0-9、バイト値 30HEX から 39HEX）からデータをエンコードします。通常、3 文字のデータは 10 ビットで表されます。

### TEXT {#TEXT}
```
public static final HanXinModes TEXT
```


Text モードは、ISO/IEC 646 で定義された一般的な記号（バイト値 00 HEX から 1B HEX および 20 HEX から 7F HEX）からデータをエンコードします。

### UNICODE {#UNICODE}
```
public static final HanXinModes UNICODE
```


Unicode モードは、Han Xin Code において UTF8 エンコーディング/文字セットへの参照として任意のテキストデータを表現する方法を設計します。

### URI {#URI}
```
public static final HanXinModes URI
```


URI モードは、Han Xin Code で表されるデータが RFC 3986 に準拠した Uniform Resource Identifier (URI) 参照であることを示します。

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
| 名前 | java.lang.String |  |

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

