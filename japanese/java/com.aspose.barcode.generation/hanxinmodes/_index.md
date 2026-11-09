---
title: "HanXinModes"
second_title: "Aspose.BarCode for Java API リファレンス"
description: "Han Xin Code エンコーディングモード。"
type: docs
weight: 89
url: /ja/java/com.aspose.barcode.generation/hanxinmodes/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum HanXinModes extends Enum<HanXinModes>
```

Han Xin Code のエンコーディングモードです。ASCII / 中国語文字または Unicode 文字には Auto を使用することが推奨されます。
## フィールド

| フィールド | 説明 |
| --- | --- |
| [AUTO](#AUTO) | Numeric、Text、ECI、Binary Bytes、4 GB18030 モードのシーケンスが自動的に変化します。 |
| [BINARY](#BINARY) | Binary byte モードは、任意の形態のバイナリデータをバイナリバイトとしてエンコードします。 |
| [COMMON_CHINESE_REGION_ONE](#COMMON-CHINESE-REGION-ONE) | リージョン One のすべての一般的な漢字は 12 ビットで表現されます。 |
| [COMMON_CHINESE_REGION_TWO](#COMMON-CHINESE-REGION-TWO) | リージョン Two のすべての一般的な漢字は 12 ビットで表現されます。 |
| [ECI](#ECI) | 拡張チャネル解釈 (ECI) モード |
| [GB_18030_FOUR_BYTE](#GB-18030-FOUR-BYTE) | GB18030 の 4 バイト領域文字はすべて 21 ビットで表現されます。 |
| [GB_18030_TWO_BYTE](#GB-18030-TWO-BYTE) | GB18030 の 2 バイト領域文字はすべて 15 ビットで表現されます。 |
| [GS_1](#GS-1) | GS1 モードは、Han Xin Code で表現されるデータが GS1 General Specification によって定義された GS1 システムの GS1 データであることを示します。 |
| [NUMERIC](#NUMERIC) | Numeric モードは、10 進数字セット（数字 0-9、バイト値 30HEX から 39HEX）からデータをエンコードします。 |
| [TEXT](#TEXT) | テキストモードは ISO/IEC 646 で定義された一般的な記号からデータをエンコードします。すなわち、 |
| [UNICODE](#UNICODE) | Unicode モードは、Han Xin Code において UTF8 エンコーディング/文字セットへの参照として任意のテキストデータを表現する方法を設計します。 |
| [URI](#URI) | URI モードは、Han Xin Code で表現されたデータが RFC 3986 に定義された Uniform Resource Identifier (URI) 参照であることを示します。 |
## メソッド

| メソッド | 説明 |
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
### AUTO {#AUTO}
```
public static final HanXinModes AUTO
```


Numeric、Text、ECI、Binary Bytes、4 GB18030 モードのシーケンスが自動的に変化します。

### BINARY {#BINARY}
```
public static final HanXinModes BINARY
```


バイナリバイトモードは、任意の形式のバイナリデータをエンコードし、バイナリバイトとしてエンコードします。バイナリバイトモードの各バイトは 8 ビットで表されます。

### COMMON_CHINESE_REGION_ONE {#COMMON-CHINESE-REGION-ONE}
```
public static final HanXinModes COMMON_CHINESE_REGION_ONE
```


Region One のすべての一般的な漢字は 12 ビットで表されます。Region One の一般的な漢字には、最初のバイト値が B0HEX から D7HEX の範囲にあり、2 バイト目が A1HEX から FEHEX の範囲にある文字（3760 文字）と、最初のバイト値が A1HEX から A3HEX の範囲にあり、2 バイト目が A1HEX から FEHEX の範囲にある文字（282 文字）、およびバイト値が A8A1HEX から A8C0HEX の範囲にある文字（32 文字）が含まれます。

### COMMON_CHINESE_REGION_TWO {#COMMON-CHINESE-REGION-TWO}
```
public static final HanXinModes COMMON_CHINESE_REGION_TWO
```


Region Two のすべての一般的な漢字は 12 ビットで表されます。Region Two の一般的な漢字には、最初のバイト値が D8HEX から F7HEX の範囲にあり、2 バイト目が A1HEX から FEHEX の範囲にある文字が含まれます。

### ECI {#ECI}
```
public static final HanXinModes ECI
```


拡張チャネル解釈 (ECI) モード

### GB_18030_FOUR_BYTE {#GB-18030-FOUR-BYTE}
```
public static final HanXinModes GB_18030_FOUR_BYTE
```


すべての GB18030 4 バイト領域文字は 21 ビットで表されます。GB18030 4 バイト領域は、GB18030 の 4 バイト領域にあるすべての文字（すなわち、最初のバイト値が 81HEX から FEHEX、2 バイト目が 30HEX から 39HEX、3 バイト目が 81HEX から FEHEX、4 バイト目が 30HEX から 39HEX の範囲にある文字）からデータをエンコードします。

### GB_18030_TWO_BYTE {#GB-18030-TWO-BYTE}
```
public static final HanXinModes GB_18030_TWO_BYTE
```


すべての GB18030 2 バイト領域文字は 15 ビットで表されます。GB18030 2 バイト領域は、GB18030 のダブルバイト領域にあるすべての文字（Region One と Region Two の一般的な漢字を含む）からデータをエンコードします（すなわち、最初のバイト値が 81HEX から FEHEX、2 バイト目が 40HEX から 7EHEX または 80HEX から FEHEX の範囲にある漢字）。

### GS_1 {#GS-1}
```
public static final HanXinModes GS_1
```


GS1 モードは、Han Xin Code で表現されたデータが GS1 システムの GS1 General Specification によって定義された GS1 データであることを示します。入力文字列の例: \"(01)03453120000011(17)191125(10)ABCD1234(21)10\"。

### NUMERIC {#NUMERIC}
```
public static final HanXinModes NUMERIC
```


数値モードは、10 進数字セット（数字 0-9、バイト値 30HEX から 39HEX）からデータをエンコードします。通常、3 つのデータ文字は 10 ビットで表されます。

### TEXT {#TEXT}
```
public static final HanXinModes TEXT
```


テキストモードは、ISO/IEC 646 で定義された一般的な記号（バイト値 00 HEX から 1B HEX および 20 HEX から 7F HEX）からデータをエンコードします。

### UNICODE {#UNICODE}
```
public static final HanXinModes UNICODE
```


Unicode モードは、Han Xin Code において UTF8 エンコーディング/文字セットへの参照として任意のテキストデータを表現する方法を設計します。

### URI {#URI}
```
public static final HanXinModes URI
```


URI モードは、Han Xin Code で表現されたデータが RFC 3986 に定義された Uniform Resource Identifier (URI) 参照であることを示します。

### <T>valueOf(Class<T> arg0, String arg1) {#-T-valueOf-java.lang.Class-T--java.lang.String-}
```
public static T <T>valueOf(Class<T> arg0, String arg1)
```




**Parameters:**
| パラメータ | 型 | 説明 |
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
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| arg0 | E |  |

**Returns:**
int
### equals(Object arg0) {#equals-java.lang.Object-}
```
public final boolean equals(Object arg0)
```




**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### fromValue(int value) {#fromValue-int-}
```
public static HanXinModes fromValue(int value)
```




**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

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
| パラメータ | 型 | 説明 |
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
public final native void wait(long arg0)
```




**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

