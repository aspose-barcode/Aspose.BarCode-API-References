---
title: "USADriveIdCodetext.SubfileProperties"
second_title: "Aspose.BarCode for Java API Reference"
description: "USA DL 子文件属性的偏移量和长度会自动设置。"
type: docs
weight: 12
url: /zh/java/com.aspose.barcode.complexbarcode/usadriveidcodetext.subfileproperties/
---
**Inheritance:**
java.lang.Object
```
public static class USADriveIdCodetext.SubfileProperties
```

美国驾驶执照子文件属性、偏移量和长度会自动设置。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [SubfileProperties(String type)](#SubfileProperties-java.lang.String-) |  |
| [SubfileProperties()](#SubfileProperties--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getLength()](#getLength--) | 4 这些字节包含一个 4 位数字值，指定 Subfile 的字节长度。计算子文件长度时必须包括段终止符。段终止符 = 1。 |
| [getOffset()](#getOffset--) | 4 位数字值，指定从文件头部（或开始）到特定子文件相关数据所在位置的字节数。文件中的第一个字节位于偏移量 0。 |
| [getType()](#getType--) | 2 字节的子文件类型，例如 "DL" |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setLength(int value)](#setLength-int-) | 4 这些字节包含一个 4 位数字值，指定 Subfile 的字节长度。计算子文件长度时必须包括段终止符。段终止符 = 1。 |
| [setOffset(int value)](#setOffset-int-) | 4 位数字值，指定从文件头部（或开始）到特定子文件相关数据所在位置的字节数。文件中的第一个字节位于偏移量 0。 |
| [setType(String value)](#setType-java.lang.String-) | 2 字节的子文件类型，例如 "DL" |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### SubfileProperties(String type) {#SubfileProperties-java.lang.String-}
```
public SubfileProperties(String type)
```


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 类型 | java.lang.String |  |

### SubfileProperties() {#SubfileProperties--}
```
public SubfileProperties()
```


### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| 参数 | 类型 | 描述 |
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
### getLength() {#getLength--}
```
public final int getLength()
```


4 这些字节包含一个 4 位数字值，指定 Subfile 的字节长度。计算子文件长度时必须包括段终止符。段终止符 = 1。每个子文件必须以两个字符的 Subfile 类型开头，这两个字符也必须计入长度。

**Returns:**
int
### getOffset() {#getOffset--}
```
public final int getOffset()
```


4 位数字值，指定从文件头部（或开始）到特定子文件相关数据所在位置的字节数。文件中的第一个字节位于偏移量 0。

**Returns:**
int
### getType() {#getType--}
```
public final String getType()
```


2 字节的子文件类型，例如 "DL"

**Returns:**
java.lang.String
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setLength(int value) {#setLength-int-}
```
public final void setLength(int value)
```


4 这些字节包含一个 4 位数字值，指定 Subfile 的字节长度。计算子文件长度时必须包括段终止符。段终止符 = 1。每个子文件必须以两个字符的 Subfile 类型开头，这两个字符也必须计入长度。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### setOffset(int value) {#setOffset-int-}
```
public final void setOffset(int value)
```


4 位数字值，指定从文件头部（或开始）到特定子文件相关数据所在位置的字节数。文件中的第一个字节位于偏移量 0。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### setType(String value) {#setType-java.lang.String-}
```
public final void setType(String value)
```


2 字节的子文件类型，例如 "DL"

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
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

