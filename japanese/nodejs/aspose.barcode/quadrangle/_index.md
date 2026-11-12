---
title: "Quadrangle"
linktitle: "Quadrangle"
second_title: "Aspose.BarCode for Node.js via Java API リファレンス"
description: "四つのポイントのセットで、Quadrangle 領域を表すものを保存します。"
type: docs
weight: 850
url: /ja/nodejs/aspose.barcode/quadrangle/
---

## Quadrangle class

四つのポイントのセットで、Quadrangle 領域を表すものを保存します。

```js
new Quadrangle(leftTop, rightTop, rightBottom, leftBottom)
```

記述ポイントを使用してQuadrangle構造体の新しいインスタンスを初期化します。

| パラメータ | 説明 |
| --- | --- |
| leftTop | Quadrangleの左上隅を表すポイントです。 |
| rightTop | Quadrangleの右上隅を表すポイントです。 |
| rightBottom | Quadrangleの右下隅を表すポイントです。 |
| leftBottom | Quadrangleの左下隅を表すポイントです。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [contains(pt)](#contains) | 指定されたポイントがこのQuadrangle構造体に含まれているかどうかを判断します。 |
| [containsPoint(x, y)](#containspoint) | 指定されたポイントがこのQuadrangle構造体に含まれているかどうかを判断します。 |
| [containsQuadrangle(quad)](#containsquadrangle) | 指定されたQuadrangleがこのQuadrangle構造体に含まれるか、交差するかどうかを判断します。 |
| [containsRectangle(rect)](#containsrectangle) | 指定されたRectangleがこのQuadrangle構造体に含まれるか、交差するかどうかを判断します。 |
| [equals(other)](#equals) | このインスタンスが指定されたQuadrangleの値と等しいかどうかを示す値を返します。 |
| [getBoundingRectangle()](#getboundingrectangle) | このQuadrangleを囲むRectangleを作成します |
| [getLeftBottom()](#getleftbottom) | Quadrangle領域の左下隅ポイントを取得します。Value: Quadrangle領域の左下隅ポイントです。 |
| [getLeftTop()](#getlefttop) | Quadrangle領域の左上隅ポイントを取得します。Value: Quadrangle領域の左上隅ポイントです。 |
| [getRightBottom()](#getrightbottom) | Quadrangle領域の右下隅ポイントを取得します。Value: Quadrangle領域の右下隅ポイントです。 |
| [getRightTop()](#getrighttop) | Quadrangle領域の右上隅ポイントを取得します。Value: Quadrangle領域の右上隅ポイントです。 |
| [hashCode()](#hashcode) | このインスタンスのハッシュコードを返します。 |
| [isEmpty()](#isempty) | この四辺形のすべてのポイントがゼロの値かどうかをテストします。値: すべてのポイントがゼロの値である場合は true を返します。 |
| [setLeftBottom()](#setleftbottom) | 四辺形領域の左下隅ポイントを設定します。値: 四辺形領域の左下隅ポイント。 |
| [setLeftTop()](#setlefttop) | 四辺形領域の左上隅ポイントを設定します。値: 四辺形領域の左上隅ポイント。 |
| [setRightBottom()](#setrightbottom) | 四辺形領域の右下隅ポイントを設定します。値: 四辺形領域の右下隅ポイント。 |
| [setRightTop()](#setrighttop) | 四辺形領域の右上隅ポイントを設定します。値: 四辺形領域の右上隅ポイント。 |
| [toString()](#tostring) | この四辺形の人間が読みやすい文字列表現を返します。 |

### contains(pt) {#contains}

指定されたポイントがこのQuadrangle構造体に含まれているかどうかを判断します。

| パラメータ | 説明 |
| --- | --- |
| pt | テスト対象のポイントです。 |

**Returns:** true if Point is contained within this Quadrangle structure; otherwise, false.

### containsPoint(x, y) {#containspoint}

指定されたポイントがこのQuadrangle構造体に含まれているかどうかを判断します。

| パラメータ | 説明 |
| --- | --- |
| x | x 点の座標です。 |
| y | y 点の座標です。 |

**Returns:** Returns true if point is contained within this Quadrangle structure; otherwise, false.

### containsQuadrangle(quad) {#containsquadrangle}

指定されたQuadrangleがこのQuadrangle構造体に含まれるか、交差するかどうかを判断します。

| パラメータ | 説明 |
| --- | --- |
| quad | テスト対象の四辺形です。 |

**Returns:** Returns true if Quadrangle is contained or intersect this Quadrangle structure; otherwise, false.

### containsRectangle(rect) {#containsrectangle}

指定されたRectangleがこのQuadrangle構造体に含まれるか、交差するかどうかを判断します。

| パラメータ | 説明 |
| --- | --- |
| rect | テスト対象の矩形です。 |

**Returns:** Returns true if Rectangle is contained or intersect this Quadrangle structure; otherwise, false.

### equals(other) {#equals}

このインスタンスが指定されたQuadrangleの値と等しいかどうかを示す値を返します。

| パラメータ | 説明 |
| --- | --- |
| その他 | このインスタンスと比較するための四辺形値です。 |

**Returns:** true if obj has the same value as this instance; otherwise, false.

### getBoundingRectangle() {#getboundingrectangle}

このQuadrangleを囲むRectangleを作成します

**Returns:** returns Rectangle bounding this Quadrangle

### getLeftBottom() {#getleftbottom}

Quadrangle領域の左下隅ポイントを取得します。Value: Quadrangle領域の左下隅ポイントです。

### getLeftTop() {#getlefttop}

Quadrangle領域の左上隅ポイントを取得します。Value: Quadrangle領域の左上隅ポイントです。

### getRightBottom() {#getrightbottom}

Quadrangle領域の右下隅ポイントを取得します。Value: Quadrangle領域の右下隅ポイントです。

### getRightTop() {#getrighttop}

Quadrangle領域の右上隅ポイントを取得します。Value: Quadrangle領域の右上隅ポイントです。

### hashCode() {#hashcode}

このインスタンスのハッシュコードを返します。

**Returns:** A 32-bit signed integer hash code.

### isEmpty() {#isempty}

この四辺形のすべてのポイントがゼロの値かどうかをテストします。値: すべてのポイントがゼロの値である場合は true を返し、そうでない場合は false を返します。

### setLeftBottom() {#setleftbottom}

四辺形領域の左下隅ポイントを設定します。値: 四辺形領域の左下隅ポイント。

### setLeftTop() {#setlefttop}

四辺形領域の左上隅ポイントを設定します。値: 四辺形領域の左上隅ポイント。

### setRightBottom() {#setrightbottom}

四辺形領域の右下隅ポイントを設定します。値: 四辺形領域の右下隅ポイント。

### setRightTop() {#setrighttop}

四辺形領域の右上隅ポイントを設定します。値: 四辺形領域の右上隅ポイント。

### toString() {#tostring}

この四辺形の人間が読みやすい文字列表現を返します。

**Returns:** A string that represents this Quadrangle.
