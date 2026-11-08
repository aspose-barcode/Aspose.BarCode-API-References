---
title: "HslaColor"
second_title: "Aspose.BarCode for Java API Reference"
description: "用于表示 HSLA 颜色（色相、饱和度、亮度、透明度）的类"
type: docs
weight: 49
url: /zh/java/com.aspose.barcode.generation/hslacolor/
---
**Inheritance:**
java.lang.Object
```
public class HslaColor
```

表示 HSLA 颜色（色相、饱和度、亮度、透明度）的类
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [HslaColor(int h, int s, int l, float a)](#HslaColor-int-int-int-float-) | HslaColor 的构造函数 |
## 字段

| 字段 | 描述 |
| --- | --- |
| [A](#A) | Alpha（不透明度）[0.0f, 1.0f] |
| [H](#H) | 色相 [0, 360] |
| [L](#L) | 亮度 [0, 100] |
| [S](#S) | 饱和度 [0, 100] |
## 方法

| 方法 | 描述 |
| --- | --- |
| [convertHslaToRgba(HslaColor hslaColor)](#convertHslaToRgba-com.aspose.barcode.generation.HslaColor-) | 使用 https://en.wikipedia.org/wiki/HSL\_and\_HSV\#HSL\_to\_RGB |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### HslaColor(int h, int s, int l, float a) {#HslaColor-int-int-int-float-}
```
public HslaColor(int h, int s, int l, float a)
```


HslaColor 的构造函数

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| h | int | 色相 [0, 360] |
| s | int | 饱和度 [0, 100] |
| l | int | 亮度 [0, 100] |
| a | float | Alpha（不透明度）[0.0f, 1.0f] |

### A {#A}
```
public float A
```


Alpha（不透明度）[0.0f, 1.0f]

### H {#H}
```
public final int H
```


色相 [0, 360]

### L {#L}
```
public final int L
```


亮度 [0, 100]

### S {#S}
```
public final int S
```


饱和度 [0, 100]

### convertHslaToRgba(HslaColor hslaColor) {#convertHslaToRgba-com.aspose.barcode.generation.HslaColor-}
```
public static Color convertHslaToRgba(HslaColor hslaColor)
```


使用 https://en.wikipedia.org/wiki/HSL\_and\_HSV\#HSL\_to\_RGB

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| hslaColor | [HslaColor](../../com.aspose.barcode.generation/hslacolor) | 要转换的 HSLA 颜色 |

**Returns:**
java.awt.Color - 具有 RGBA 值的颜色
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

