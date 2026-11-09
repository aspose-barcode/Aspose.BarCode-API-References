---
title: "HslaColor"
second_title: "Aspose.BarCode for Java API リファレンス"
description: "HSLA カラーの Hue、Saturation、Lightness、Alpha を表すクラス"
type: docs
weight: 49
url: /ja/java/com.aspose.barcode.generation/hslacolor/
---
**Inheritance:**
java.lang.Object
```
public class HslaColor
```

HSLA カラー（色相、彩度、明度、アルファ）を表すクラス
## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [HslaColor(int h, int s, int l, float a)](#HslaColor-int-int-int-float-) | HslaColor のコンストラクタ |
## フィールド

| フィールド | 説明 |
| --- | --- |
| [A](#A) | Alpha（不透明度）[0.0f, 1.0f] |
| [H](#H) | Hue [0, 360] |
| [L](#L) | Lightness [0, 100] |
| [S](#S) | Saturation [0, 100] |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [convertHslaToRgba(HslaColor hslaColor)](#convertHslaToRgba-com.aspose.barcode.generation.HslaColor-) | 使用します https://en.wikipedia.org/wiki/HSL\_and\_HSV\#HSL\_to\_RGB |
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


HslaColor のコンストラクタ

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| h | int | Hue [0, 360] |
| s | int | Saturation [0, 100] |
| l | int | Lightness [0, 100] |
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


Hue [0, 360]

### L {#L}
```
public final int L
```


Lightness [0, 100]

### S {#S}
```
public final int S
```


Saturation [0, 100]

### convertHslaToRgba(HslaColor hslaColor) {#convertHslaToRgba-com.aspose.barcode.generation.HslaColor-}
```
public static Color convertHslaToRgba(HslaColor hslaColor)
```


使用します https://en.wikipedia.org/wiki/HSL\_and\_HSV\#HSL\_to\_RGB

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| hslaColor | [HslaColor](../../com.aspose.barcode.generation/hslacolor) | 変換対象の HSLA カラー |

**Returns:**
java.awt.Color - RGBA 値を持つカラー
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| パラメータ | 型 | 説明 |
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

