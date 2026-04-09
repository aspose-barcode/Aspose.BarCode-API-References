---
title: Pdf417EncodeMode
second_title: Aspose.BarCode 适用于 Android 通过 Java API 参考
description: Pdf417 条形码的编码模式
type: docs
weight: 99
url: /zh/androidjava/com.aspose.barcode.generation/pdf417encodemode/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum Pdf417EncodeMode extends Enum<Pdf417EncodeMode>
```

Pdf417 条形码的编码模式
## 字段

| 字段 | 描述 |
| --- | --- |
| [AUTO](#AUTO) | 在 Auto 模式下，CodeText 以最大数据紧凑度进行编码。 |
| [BINARY](#BINARY) | 在 Binary 模式下，CodeText 以最大数据紧凑度进行编码。 |
| [ECI](#ECI) | 在 ECI 模式下，整个消息会使用 ECIEncoding 指定的编码重新编码，并插入 ECI 标识符。 |
| [EXTENDED](#EXTENDED) |  |
## Methods

| Method | 描述 |
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
public static final Pdf417EncodeMode AUTO
```


在 Auto 模式下，CodeText 以最高数据紧凑度进行编码。Unicode 字符会使用 ECIEncoding 指定的编码重新编码，并插入 ECI 标识符。如果发现字符不受所选 ECI 编码支持，则抛出异常。

### BINARY {#BINARY}
```
public static final Pdf417EncodeMode BINARY
```


在 Binary 模式下，CodeText 以最高数据紧凑度进行编码。如果发现 Unicode 字符，则抛出异常。

### ECI {#ECI}
```
public static final Pdf417EncodeMode ECI
```


在 ECI 模式下，整个消息会使用 ECIEncoding 指定的编码重新编码，并插入 ECI 标识符。如果发现字符不受所选 ECI 编码支持，则抛出异常。请注意，某些旧（2006 年之前）的扫描仪可能不支持此模式。

### EXTENDED {#EXTENDED}
```
public static final Pdf417EncodeMode EXTENDED
```


支持多 ECI 模式的扩展模式。

最好使用 Pdf417ExtCodetextBuilder 来生成扩展的 codetext。

使用 Display2DText 属性设置可见文本以去除管理字符。

ECI 标识符设置为单斜杠加六位数字标识符 \"\\\\000026\" —— UTF8 ECI 标识符

所有在 ECI 标识符之后的 Unicode 字符会自动编码为正确的字符集。

### <T>valueOf(Class<T> arg0, String arg1) {#-T-valueOf-java.lang.Class-T--java.lang.String-}
```
public static T <T>valueOf(Class<T> arg0, String arg1)
```




**Parameters:**
| Parameter | Type | 描述 |
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
| Parameter | Type | 描述 |
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
| Parameter | Type | 描述 |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### fromValue(int value) {#fromValue-int-}
```
public static Pdf417EncodeMode fromValue(int value)
```




**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int |  |

**Returns:**
[Pdf417EncodeMode](../../com.aspose.barcode.generation/pdf417encodemode)
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
public static Pdf417EncodeMode valueOf(String name)
```




**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 名称 | java.lang.String |  |

**Returns:**
[Pdf417EncodeMode](../../com.aspose.barcode.generation/pdf417encodemode)
### values() {#values--}
```
public static Pdf417EncodeMode[] values()
```




**Returns:**
com.aspose.barcode.generation.Pdf417EncodeMode[]
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

