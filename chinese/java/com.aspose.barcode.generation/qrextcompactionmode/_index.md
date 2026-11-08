---
title: "QrExtCompactionMode"
second_title: "Aspose.BarCode for Java API Reference"
description: "指定由 QrExtCodetextBuilder 添加的代码文本的 QR 紧凑模式。"
type: docs
weight: 103
url: /zh/java/com.aspose.barcode.generation/qrextcompactionmode/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum QrExtCompactionMode extends Enum<QrExtCompactionMode>
```

指定由 QrExtCodetextBuilder 添加的代码文本的 QR 紧凑模式。
## 字段

| 字段 | 描述 |
| --- | --- |
| [ALPHA_NUMERIC](#ALPHA-NUMERIC) | 以 QR 字母数字模式编码代码文本。 |
| [AUTO](#AUTO) | 编码器会自动选择最高效的 QR 压缩模式。 |
| [BYTES](#BYTES) | 以 QR 字节模式编码代码文本。 |
| [KANJI](#KANJI) | 以 QR 汉字模式编码代码文本。 |
| [NUMERIC](#NUMERIC) | 以 QR 数字模式编码代码文本。 |
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
### ALPHA_NUMERIC {#ALPHA-NUMERIC}
```
public static final QrExtCompactionMode ALPHA_NUMERIC
```


以 QR 字母数字模式编码代码文本。

### AUTO {#AUTO}
```
public static final QrExtCompactionMode AUTO
```


编码器会自动选择最高效的 QR 压缩模式。

### BYTES {#BYTES}
```
public static final QrExtCompactionMode BYTES
```


以 QR 字节模式编码代码文本。

### KANJI {#KANJI}
```
public static final QrExtCompactionMode KANJI
```


以 QR 汉字模式编码代码文本。

### NUMERIC {#NUMERIC}
```
public static final QrExtCompactionMode NUMERIC
```


以 QR 数字模式编码代码文本。仅允许数字 0-9。

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
public static QrExtCompactionMode fromValue(int value)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

**Returns:**
[QrExtCompactionMode](../../com.aspose.barcode.generation/qrextcompactionmode)
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
public static QrExtCompactionMode valueOf(String name)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 名称 | java.lang.String |  |

**Returns:**
[QrExtCompactionMode](../../com.aspose.barcode.generation/qrextcompactionmode)
### values() {#values--}
```
public static QrExtCompactionMode[] values()
```




**Returns:**
com.aspose.barcode.generation.QrExtCompactionMode[]
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

