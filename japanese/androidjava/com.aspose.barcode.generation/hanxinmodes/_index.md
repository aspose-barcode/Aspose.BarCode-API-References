---
title: "HanXinModes"
second_title: "Aspose.BarCode for Android via Java API Reference"
description: "Han Xin Code のエンコーディングモード。"
type: docs
weight: 90
url: /ja/androidjava/com.aspose.barcode.generation/hanxinmodes/
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
| [AUTO](#AUTO) | Numeric、Text、ECI、Binary Bytes、4 GB18030 モードが自動的に切り替わるシーケンスです。 |
| [BINARY](#BINARY) | Binary byte モードは任意の形式のバイナリデータをエンコードし、バイナリバイトとしてエンコードします。 |
| [COMMON_CHINESE_REGION_ONE](#COMMON-CHINESE-REGION-ONE) | Region One のすべての一般的な漢字は 12 ビットで表現されます。 |
| [COMMON_CHINESE_REGION_TWO](#COMMON-CHINESE-REGION-TWO) | Region Two のすべての一般的な漢字は 12 ビットで表現されます。 |
| [ECI](#ECI) | 拡張チャネル解釈 (ECI) モード |
| [GB_18030_FOUR_BYTE](#GB-18030-FOUR-BYTE) | GB18030 の 4 バイト領域文字はすべて 21 ビットで表現されます。 |
| [GB_18030_TWO_BYTE](#GB-18030-TWO-BYTE) | GB18030 の 2 バイト領域文字はすべて 15 ビットで表現されます。 |
| [GS_1](#GS-1) | GS1 モードは、Han Xin Code で表現されるデータが GS1 General Specification によって定義された GS1 システムの GS1 データであることを示します。 |
| [NUMERIC](#NUMERIC) | Numeric モードは十進数字セット（0-9 の数字、バイト値 30HEX から 39HEX）からデータをエンコードします。 |
| [TEXT](#TEXT) | Text モードは ISO/IEC 646 で定義された一般的な記号からデータをエンコードします。i.e. |
| [UNICODE](#UNICODE) | Unicode モードは、Han Xin Code において UTF8 エンコーディング/文字セットを参照した任意のテキストデータを表現する方法を設計します。 |
| [URI](#URI) | URI モードは、Han Xin Code で表現されるデータが RFC 3986 に準拠した Uniform Resource Identifier (URI) 参照であることを示します。 |
## メソッド

| メソッド | 説明 |
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


Numeric、Text、ECI、Binary Bytes、4 GB18030 モードが自動的に切り替わるシーケンスです。

### BINARY {#BINARY}
```
public static final HanXinModes BINARY
```


Binary byte モードは任意の形式のバイナリデータをエンコードし、バイナリバイトとしてエンコードします。Binary Byte モードの各バイトは 8 ビットで表現されます。

### COMMON_CHINESE_REGION_ONE {#COMMON-CHINESE-REGION-ONE}
```
public static final HanXinModes COMMON_CHINESE_REGION_ONE
```


領域1のすべての共通漢字は12ビットで表されます。領域1の共通漢字には、最初のバイト値がB0HEXからD7HEXの範囲にあり、2番目のバイト値がA1HEXからFEHEXの範囲にある文字（3760文字）と、最初のバイト値がA1HEXからA3HEXの範囲にあり、2番目のバイト値がA1HEXからFEHEXの範囲にある文字（282文字）、およびバイト値がA8A1HEXからA8C0HEXの範囲にある文字（32文字）が含まれます。

### COMMON_CHINESE_REGION_TWO {#COMMON-CHINESE-REGION-TWO}
```
public static final HanXinModes COMMON_CHINESE_REGION_TWO
```


領域2のすべての共通漢字は12ビットで表されます。領域2の共通漢字には、最初のバイト値がD8HEXからF7HEXの範囲にあり、2番目のバイト値がA1HEXからFEHEXの範囲にある文字が含まれます。

### ECI {#ECI}
```
public static final HanXinModes ECI
```


拡張チャネル解釈 (ECI) モード

### GB_18030_FOUR_BYTE {#GB-18030-FOUR-BYTE}
```
public static final HanXinModes GB_18030_FOUR_BYTE
```


GB18030 4バイト領域のすべての文字は21ビットで表されます。GB18030 4バイト領域は、GB18030の4バイト領域に含まれるすべての文字からデータをエンコードします（例：最初のバイト値が81HEXからFEHEX、2番目のバイト値が30HEXから39HEX、3番目のバイト値が81HEXからFEHEX、4番目のバイト値が30HEXから39HEXの範囲にある文字）。

### GB_18030_TWO_BYTE {#GB-18030-TWO-BYTE}
```
public static final HanXinModes GB_18030_TWO_BYTE
```


GB18030 2バイト領域のすべての文字は15ビットで表されます。GB18030 2バイト領域は、GB18030のダブルバイト領域に含まれるすべての文字（領域1および領域2の共通漢字を含む）からデータをエンコードします（例：最初のバイト値が81HEXからFEHEX、2番目のバイト値が40HEXから7EHEXまたは80HEXからFEHEXの範囲にある漢字）。

### GS_1 {#GS-1}
```
public static final HanXinModes GS_1
```


GS1モードは、Han Xin Codeで表されるデータがGS1一般仕様で定義されたGS1システムのGS1データであることを示します。入力文字列の例: "(01)03453120000011(17)191125(10)ABCD1234(21)10"。

### NUMERIC {#NUMERIC}
```
public static final HanXinModes NUMERIC
```


数値モードは、10進数字セット（0〜9の数字、バイト値30HEXから39HEX）からデータをエンコードします。通常、3つのデータ文字は10ビットで表されます。

### TEXT {#TEXT}
```
public static final HanXinModes TEXT
```


テキストモードは、ISO/IEC 646で定義された共通記号（バイト値00HEXから1BHEX、20HEXから7FHEX）からデータをエンコードします。

### UNICODE {#UNICODE}
```
public static final HanXinModes UNICODE
```


Unicode モードは、Han Xin Code において UTF8 エンコーディング/文字セットを参照した任意のテキストデータを表現する方法を設計します。

### URI {#URI}
```
public static final HanXinModes URI
```


URI モードは、Han Xin Code で表現されるデータが RFC 3986 に準拠した Uniform Resource Identifier (URI) 参照であることを示します。

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

