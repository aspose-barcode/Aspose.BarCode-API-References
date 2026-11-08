---
title: "HanXinModes"
second_title: "Aspose.BarCode for Java API Reference"
description: "汉信码编码模式。"
type: docs
weight: 89
url: /zh/java/com.aspose.barcode.generation/hanxinmodes/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum HanXinModes extends Enum<HanXinModes>
```

Han Xin Code 编码模式。建议在使用 ASCII/中文字符或 Unicode 字符时使用 Auto。
## 字段

| 字段 | 描述 |
| --- | --- |
| [AUTO](#AUTO) | Numeric、Text、ECI、Binary Bytes 和 4 GB18030 模式的序列会自动切换。 |
| [BINARY](#BINARY) | Binary byte 模式以二进制字节的形式对任何形式的二进制数据进行编码。 |
| [COMMON_CHINESE_REGION_ONE](#COMMON-CHINESE-REGION-ONE) | 区域一的每个常用汉字使用 12 位表示。 |
| [COMMON_CHINESE_REGION_TWO](#COMMON-CHINESE-REGION-TWO) | 区域二的每个常用汉字使用 12 位表示。 |
| [ECI](#ECI) | 扩展信道解释 (ECI) 模式 |
| [GB_18030_FOUR_BYTE](#GB-18030-FOUR-BYTE) | 每个 GB18030 四字节区域字符使用 21 位表示。 |
| [GB_18030_TWO_BYTE](#GB-18030-TWO-BYTE) | 每个 GB18030 两字节区域字符使用 15 位表示。 |
| [GS_1](#GS-1) | GS1 模式表示 Han Xin Code 中表示的数据是由 GS1 通用规范定义的 GS1 系统的 GS1 数据。 |
| [NUMERIC](#NUMERIC) | Numeric 模式对十进制数字集（数字 0-9，字节值 30HEX 到 39HEX）的数据进行编码。 |
| [TEXT](#TEXT) | 文本模式对 ISO/IEC 646 中定义的常用符号进行编码，即 |
| [UNICODE](#UNICODE) | Unicode 模式设计了一种在 Han Xin Code 中表示任何文本数据并引用 UTF8 编码/字符集的方法。 |
| [URI](#URI) | URI 模式表示在 Han Xin Code 中表示的数据是符合 RFC 3986 的统一资源标识符 (URI) 引用。 |
## 方法

| 方法 | 描述 |
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


Numeric、Text、ECI、Binary Bytes 和 4 GB18030 模式的序列会自动切换。

### BINARY {#BINARY}
```
public static final HanXinModes BINARY
```


二进制字节模式以任何形式对二进制数据进行编码，并将其编码为二进制字节。二进制字节模式中的每个字节由 8 位表示。

### COMMON_CHINESE_REGION_ONE {#COMMON-CHINESE-REGION-ONE}
```
public static final HanXinModes COMMON_CHINESE_REGION_ONE
```


Region One 中的每个常用汉字使用 12 位表示。Region One 的常用汉字包括首字节值在 B0HEX 到 D7HEX 范围内且第二字节值在 A1HEX 到 FEHEX 范围内的字符（共 3760 个），以及首字节值在 A1HEX 到 A3HEX 范围且第二字节值在 A1HEX 到 FEHEX 范围内的字符（共 282 个），以及字节值在 A8A1HEX 到 A8C0HEX 范围内的字符（共 32 个）。

### COMMON_CHINESE_REGION_TWO {#COMMON-CHINESE-REGION-TWO}
```
public static final HanXinModes COMMON_CHINESE_REGION_TWO
```


Region Two 中的每个常用汉字使用 12 位表示。Region Two 的常用汉字包括首字节值在 D8HEX 到 F7HEX 范围且第二字节值在 A1HEX 到 FEHEX 范围内的字符。

### ECI {#ECI}
```
public static final HanXinModes ECI
```


扩展信道解释 (ECI) 模式

### GB_18030_FOUR_BYTE {#GB-18030-FOUR-BYTE}
```
public static final HanXinModes GB_18030_FOUR_BYTE
```


每个 GB18030 四字节区域字符使用 21 位表示。GB18030 四字节区域对 GB18030 四字节区域中的所有字符进行编码（即首字节值在 81HEX 到 FEHEX 范围，第二字节值在 30HEX 到 39HEX 范围，第三字节值在 81HEX 到 FEHEX 范围，第四字节值在 30HEX 到 39HEX 范围的字符）。

### GB_18030_TWO_BYTE {#GB-18030-TWO-BYTE}
```
public static final HanXinModes GB_18030_TWO_BYTE
```


每个 GB18030 双字节区域字符使用 15 位表示。GB18030 双字节区域对 GB18030 双字节区域中的所有字符（包括 Region One 和 Region Two 中的常用汉字）进行编码，即首字节值在 81HEX 到 FEHEX 范围，第二字节值在 40HEX 到 7EHEX 或 80HEX 到 FEHEX 范围的汉字。

### GS_1 {#GS-1}
```
public static final HanXinModes GS_1
```


GS1 模式表示在 Han Xin Code 中表示的数据是由 GS1 通用规范定义的 GS1 系统的 GS1 数据。例如输入字符串："(01)03453120000011(17)191125(10)ABCD1234(21)10"。

### NUMERIC {#NUMERIC}
```
public static final HanXinModes NUMERIC
```


数字模式对十进制数字集（数字 0-9，字节值 30HEX 到 39HEX）进行编码。通常，3 个数据字符使用 10 位表示。

### TEXT {#TEXT}
```
public static final HanXinModes TEXT
```


文本模式对 ISO/IEC 646 中定义的常用符号进行编码，即字节值 00 HEX 到 1B HEX 和 20 HEX 到 7F HEX。

### UNICODE {#UNICODE}
```
public static final HanXinModes UNICODE
```


Unicode 模式设计了一种在 Han Xin Code 中表示任何文本数据并引用 UTF8 编码/字符集的方法。

### URI {#URI}
```
public static final HanXinModes URI
```


URI 模式表示在 Han Xin Code 中表示的数据是符合 RFC 3986 的统一资源标识符 (URI) 引用。

### <T>valueOf(Class<T> arg0, String arg1) {#-T-valueOf-java.lang.Class-T--java.lang.String-}
```
public static T <T>valueOf(Class<T> arg0, String arg1)
```




**Parameters:**
| 参数 | 类型 | 描述 |
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
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | E |  |

**Returns:**
int
### equals(Object arg0) {#equals-java.lang.Object-}
```
public final boolean equals(Object arg0)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### fromValue(int value) {#fromValue-int-}
```
public static HanXinModes fromValue(int value)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

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
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 名称 | java.lang.String |  |

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
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

