---
title: "Quadrangle"
second_title: "Aspose.BarCode for Android via Java API Reference"
description: "Quadrangle 領域を表す4つの Point の集合を格納します。"
type: docs
weight: 41
url: /ja/androidjava/com.aspose.barcode.barcoderecognition/quadrangle/
---
**Inheritance:**
java.lang.Object
```
public class Quadrangle
```

四つの Point が Quadrangle 領域を表すセットを保存します
## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [Quadrangle()](#Quadrangle--) |  |
| [Quadrangle(Point leftTop, Point rightTop, Point rightBottom, Point leftBottom)](#Quadrangle-android.graphics.Point-android.graphics.Point-android.graphics.Point-android.graphics.Point-) | 記述ポイントで  Quadrangle  構造体の新しいインスタンスを初期化します。 |
## フィールド

| フィールド | 説明 |
| --- | --- |
| [EMPTY](#EMPTY) | プロパティが未初期化のままの  Quadrangle  クラスを表します。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [clone()](#clone--) |  |
| [contains(Point pt)](#contains-android.graphics.Point-) | 指定された  Point  がこの  Quadrangle  クラス内に含まれるかどうかを判断します。 |
| [contains(Rect rect)](#contains-android.graphics.Rect-) | 指定された  Rectangle  がこの  Quadrangle  クラスに含まれるか、交差するかを判断します。 |
| [contains(Quadrangle quad)](#contains-com.aspose.barcode.barcoderecognition.Quadrangle-) | 指定された  Quadrangle  がこの  Quadrangle  クラスに含まれるか、交差するかを判断します。 |
| [contains(int x, int y)](#contains-int-int-) | 指定されたポイントがこの  Quadrangle  クラス内に含まれるかどうかを判断します。 |
| [equals(Object obj)](#equals-java.lang.Object-) | このインスタンスが指定された  Quadrangle  の値と等しいかどうかを示す値を返します。 |
| [getBoundingRectangle()](#getBoundingRectangle--) | この  Quadrangle  を囲む  Rectangle  を作成します。 |
| [getClass()](#getClass--) |  |
| [getLeftBottom()](#getLeftBottom--) | Quadrangle 領域の左下隅の  Point  を取得します。 |
| [getLeftTop()](#getLeftTop--) | Quadrangle 領域の左上隅の  Point  を取得します。 |
| [getRightBottom()](#getRightBottom--) | Quadrangle 領域の右下隅の  Point  を取得します。 |
| [getRightTop()](#getRightTop--) | Quadrangle 領域の右上隅の  Point  を取得します。 |
| [hashCode()](#hashCode--) | このインスタンスのハッシュコードを返します。 |
| [isEmpty()](#isEmpty--) | この  Quadrangle  のすべての  Point s がゼロの値かどうかをテストします。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setLeftBottom(Point value)](#setLeftBottom-android.graphics.Point-) | Quadrangle 領域の左下隅の  Point  を取得します。 |
| [setLeftTop(Point value)](#setLeftTop-android.graphics.Point-) | Quadrangle 領域の左上隅の  Point  を取得します。 |
| [setRightBottom(Point value)](#setRightBottom-android.graphics.Point-) | Quadrangle 領域の右下隅の  Point  を取得します。 |
| [setRightTop(Point value)](#setRightTop-android.graphics.Point-) | Quadrangle 領域の右上隅の  Point  を取得します。 |
| [toString()](#toString--) | この  Quadrangle  の人間が読みやすい文字列表現を返します。 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Quadrangle() {#Quadrangle--}
```
public Quadrangle()
```


### Quadrangle(Point leftTop, Point rightTop, Point rightBottom, Point leftBottom) {#Quadrangle-android.graphics.Point-android.graphics.Point-android.graphics.Point-android.graphics.Point-}
```
public Quadrangle(Point leftTop, Point rightTop, Point rightBottom, Point leftBottom)
```


記述ポイントで  Quadrangle  構造体の新しいインスタンスを初期化します。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| leftTop | android.graphics.Point | Quadrangle の左上隅を表す  Point  です。 |
| rightTop | android.graphics.Point | Quadrangle の右上隅を表す Point です。 |
| rightBottom | android.graphics.Point | Quadrangle の右下隅を表す Point です。 |
| leftBottom | android.graphics.Point | Quadrangle の左下隅を表す Point です。 |

### EMPTY {#EMPTY}
```
public static final Quadrangle EMPTY
```


プロパティが未初期化のままの  Quadrangle  クラスを表します。

値: Quadrangle

### clone() {#clone--}
```
public Quadrangle clone()
```




**Returns:**
[Quadrangle](../../com.aspose.barcode.barcoderecognition/quadrangle)
### contains(Point pt) {#contains-android.graphics.Point-}
```
public boolean contains(Point pt)
```


指定された  Point  がこの  Quadrangle  クラス内に含まれるかどうかを判断します。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| pt | android.graphics.Point | テスト対象の Point。 |

**Returns:**
boolean - この Quadrangle クラスに Point が含まれる場合は **true** を返し、そうでない場合は **false** を返します。
### contains(Rect rect) {#contains-android.graphics.Rect-}
```
public boolean contains(Rect rect)
```


指定された  Rectangle  がこの  Quadrangle  クラスに含まれるか、交差するかを判断します。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| rect | android.graphics.Rect | テスト対象の Rectangle。 |

**Returns:**
boolean - この Quadrangle クラスに Rectangle が含まれるか交差する場合は **true** を返し、そうでない場合は **false** を返します。
### contains(Quadrangle quad) {#contains-com.aspose.barcode.barcoderecognition.Quadrangle-}
```
public boolean contains(Quadrangle quad)
```


指定された  Quadrangle  がこの  Quadrangle  クラスに含まれるか、交差するかを判断します。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| quad | [Quadrangle](../../com.aspose.barcode.barcoderecognition/quadrangle) | テスト対象の Quadrangle。 |

**Returns:**
boolean - この Quadrangle クラスに Quadrangle が含まれるか交差する場合は **true** を返し、そうでない場合は **false** を返します。
### contains(int x, int y) {#contains-int-int-}
```
public boolean contains(int x, int y)
```


指定されたポイントがこの  Quadrangle  クラス内に含まれるかどうかを判断します。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| x | int | x の座標です。 |
| y | int | y の座標です。 |

**Returns:**
boolean - この Quadrangle クラスに point が含まれる場合は **true** を返し、そうでない場合は **false** を返します。
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


このインスタンスが指定された  Quadrangle  の値と等しいかどうかを示す値を返します。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| obj | java.lang.Object | このインスタンスと比較する Quadrangle 値です。 |

**Returns:**
boolean -  **true**  obj がこのインスタンスと同じ値を持つ場合; それ以外の場合は、  **false** 。
### getBoundingRectangle() {#getBoundingRectangle--}
```
public Rect getBoundingRectangle()
```


この  Quadrangle  を囲む  Rectangle  を作成します。

**Returns:**
android.graphics.Rect - この Quadrangle を囲む Rectangle を返します。
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getLeftBottom() {#getLeftBottom--}
```
public Point getLeftBottom()
```


Quadrangle 領域の左下隅の  Point  を取得します。

値: Quadrangle 領域の左下隅の Point。

**Returns:**
android.graphics.Point
### getLeftTop() {#getLeftTop--}
```
public Point getLeftTop()
```


Quadrangle 領域の左上隅の  Point  を取得します。

値: Quadrangle 領域の左上隅の Point。

**Returns:**
android.graphics.Point
### getRightBottom() {#getRightBottom--}
```
public Point getRightBottom()
```


Quadrangle 領域の右下隅の  Point  を取得します。

値: Quadrangle 領域の右下隅の Point。

**Returns:**
android.graphics.Point
### getRightTop() {#getRightTop--}
```
public Point getRightTop()
```


Quadrangle 領域の右上隅の  Point  を取得します。

値: 四角形領域の右上隅の点

**Returns:**
android.graphics.Point
### hashCode() {#hashCode--}
```
public int hashCode()
```


このインスタンスのハッシュコードを返します。

**Returns:**
int - 32 ビット符号付き整数のハッシュコード。
### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


この  Quadrangle  のすべての  Point s がゼロの値かどうかをテストします。

値: この Quadrangle のすべての Point がゼロの値である場合は **true** を返し、そうでない場合は **false** を返します。

**Returns:**
boolean
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setLeftBottom(Point value) {#setLeftBottom-android.graphics.Point-}
```
public void setLeftBottom(Point value)
```


Quadrangle 領域の左下隅の  Point  を取得します。

値: Quadrangle 領域の左下隅の Point。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | android.graphics.Point |  |

### setLeftTop(Point value) {#setLeftTop-android.graphics.Point-}
```
public void setLeftTop(Point value)
```


Quadrangle 領域の左上隅の  Point  を取得します。

値: Quadrangle 領域の左上隅の Point。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | android.graphics.Point |  |

### setRightBottom(Point value) {#setRightBottom-android.graphics.Point-}
```
public void setRightBottom(Point value)
```


Quadrangle 領域の右下隅の  Point  を取得します。

値: Quadrangle 領域の右下隅の Point。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | android.graphics.Point |  |

### setRightTop(Point value) {#setRightTop-android.graphics.Point-}
```
public void setRightTop(Point value)
```


Quadrangle 領域の右上隅の  Point  を取得します。

値: 四角形領域の右上隅の点

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | android.graphics.Point |  |

### toString() {#toString--}
```
public String toString()
```


この  Quadrangle  の人間が読みやすい文字列表現を返します。

**Returns:**
java.lang.String - この Quadrangle を表す文字列。
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

