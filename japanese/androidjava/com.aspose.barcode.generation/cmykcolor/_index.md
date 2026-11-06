---
title: "CMYKColor"
second_title: "Aspose.BarCode for Android via Java API Reference"
description: "CMYK カラーのクラス。"
type: docs
weight: 19
url: /ja/androidjava/com.aspose.barcode.generation/cmykcolor/
---
**Inheritance:**
java.lang.Object
```
public class CMYKColor
```

CMYKカラー用のクラスです。null はCMYKが使用されていないことを意味し、デフォルトのRGBカラーが使用されます。
## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [CMYKColor(int c, int m, int y, int k)](#CMYKColor-int-int-int-int-) | CMYK値から  CMYKColor  クラスの新しいインスタンスを初期化します。 |
## フィールド

| フィールド | 説明 |
| --- | --- |
| [C](#C) |  |
| [K](#K) |  |
| [M](#M) |  |
| [Y](#Y) |  |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | カラーの値が同じかどうかを比較します |
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


CMYK値から  CMYKColor  クラスの新しいインスタンスを初期化します。CMYK値は0〜100です。

**Parameters:**
| パラメータ | 型 | 説明 |
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


カラーの値が同じかどうかを比較します

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| obj | java.lang.Object | 比較対象のCMYKColor |

**Returns:**
boolean - 値は同じですか
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
int - CMYKColorのハッシュコード
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

