---
title: "CMYKColor"
second_title: "Aspose.BarCode for Java API Reference"
description: "CMYK 颜色的类。"
type: docs
weight: 19
url: /zh/java/com.aspose.barcode.generation/cmykcolor/
---
**Inheritance:**
java.lang.Object
```
public class CMYKColor
```

CMYK 颜色的类。Null 表示未使用 CMYK，默认使用 RGB 颜色。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [CMYKColor(int c, int m, int y, int k)](#CMYKColor-int-int-int-int-) | 从 CMYK 值初始化 CMYKColor 类的新实例。 |
## 字段

| 字段 | 描述 |
| --- | --- |
| [C](#C) |  |
| [K](#K) |  |
| [M](#M) |  |
| [Y](#Y) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | 比较颜色值是否相同 |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) | CMYKColor 的哈希码 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### CMYKColor(int c, int m, int y, int k) {#CMYKColor-int-int-int-int-}
```
public CMYKColor(int c, int m, int y, int k)
```


从 CMYK 值初始化 CMYKColor 类的新实例。CMYK 值范围为 0-100。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| c | int | 青色值 [0, 100] |
| m | int | 品红值 [0, 100] |
| y | int | 黄色值 [0, 100] |
| k | int | 黑色值 [0, 100] |

### C {#C}
```
public float C
```


### K {#K}
```
public float K
```


### M {#M}
```
public float M
```


### Y {#Y}
```
public float Y
```


### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


比较颜色值是否相同

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| obj | java.lang.Object | 用于比较的 CMYKColor |

**Returns:**
boolean - 值是否相同
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### hashCode() {#hashCode--}
```
public int hashCode()
```


CMYKColor 的哈希码

**Returns:**
int - CMYKColor 的哈希码
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




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

