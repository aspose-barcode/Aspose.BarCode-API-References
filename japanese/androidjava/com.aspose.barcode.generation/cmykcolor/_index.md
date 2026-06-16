---
title: CMYKColor
second_title: Aspose.BarCode for Android via Java API Reference
description: Class for CMYK color.
type: docs
weight: 19
url: /ja/androidjava/com.aspose.barcode.generation/cmykcolor/
---
**Inheritance:**
java.lang.Object
```
public class CMYKColor
```

CMYK カラーのクラスです。Null は CMYK が使用されていないことを意味し、デフォルトの RGB カラーが使用されています。
## Constructors

| Constructor | Description |
| --- | --- |
| [CMYKColor(int c, int m, int y, int k)](#CMYKColor-int-int-int-int-) | CMYK の値から CMYKColor クラスの新しいインスタンスを初期化します。 |
## フィールド

| フィールド | Description |
| --- | --- |
| [C](#C) |  |
| [K](#K) |  |
| [M](#M) |  |
| [Y](#Y) |  |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | 色の値が同じかどうかを比較します |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) | CMYKColor のハッシュコード |
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


CMYK の値から CMYKColor クラスの新しいインスタンスを初期化します。CMYK の値は 0〜100 です。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| c | int | シアン値 [0, 100] |
| m | int | マゼンタ値 [0, 100] |
| y | int | イエロー値 [0, 100] |
| k | int | ブラック値 [0, 100] |

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


色の値が同じかどうかを比較します

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | 比較対象の CMYKColor |

**Returns:**
boolean - 値は同じか
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


CMYKColor のハッシュコード

**Returns:**
int - CMYKColor のハッシュコード
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

