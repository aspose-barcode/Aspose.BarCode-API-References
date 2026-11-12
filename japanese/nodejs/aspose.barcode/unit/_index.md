---
title: "Unit"
linktitle: "Unit"
second_title: "Aspose.BarCode for Node.js via Java API リファレンス"
description: "サイズ値をさまざまな単位（ピクセル、インチなど）で指定します。"
type: docs
weight: 960
url: /ja/nodejs/aspose.barcode/unit/
---

## Unit class

サイズ値をさまざまな単位（ピクセル、インチなど）で指定します。

```js
new Unit()
```

**Example:**

```js
//This sample shows how to create and save a BarCode image.
   let generator = new BarcodeGenerator(EncodeTypes.CODE_128);
   generator.getParameters().getBarcode().getBarHeight().setMillimeters(10);
   generator.save("test.png", BarcodeImageFormat.PNG);
```

## メソッド

| 名前 | 説明 |
| --- | --- |
| [equals(obj)](#equals) | このインスタンスと、Unit オブジェクトである必要がある指定されたオブジェクトが同じ値かどうかを判断します。 |
| [getDocument()](#getdocument) | 文書単位でサイズ値を取得します。 |
| [getInches()](#getinches) | インチでサイズ値を取得します。 |
| [getMillimeters()](#getmillimeters) | ミリメートルでサイズ値を取得します。 |
| [getPixels()](#getpixels) | ピクセルでサイズ値を取得します。 |
| [getPoint()](#getpoint) | ポイントでサイズ値を取得します。 |
| [setDocument()](#setdocument) | 文書単位でサイズ値を設定します。 |
| [setInches()](#setinches) | インチでサイズ値を設定します。 |
| [setMillimeters()](#setmillimeters) | ミリメートルでサイズ値を設定します。 |
| [setPixels()](#setpixels) | ピクセルでサイズ値を設定します。 |
| [setPoint()](#setpoint) | ポイントでサイズ値を設定します。 |
| [toString()](#tostring) | この Unit の人間が読める文字列表現を返します。 |

### equals(obj) {#equals}

このインスタンスと、Unit オブジェクトである必要がある指定されたオブジェクトが同じ値かどうかを判断します。

| パラメータ | 説明 |
| --- | --- |
| obj | このインスタンスと比較する Unit。 |

**Returns:** true if obj is a Unit and its value is the same as this instance; otherwise, false. If obj is null, the method returns false.

### getDocument() {#getdocument}

文書単位でサイズ値を取得します。

### getInches() {#getinches}

インチでサイズ値を取得します。

### getMillimeters() {#getmillimeters}

ミリメートルでサイズ値を取得します。

### getPixels() {#getpixels}

ピクセルでサイズ値を取得します。

### getPoint() {#getpoint}

ポイントでサイズ値を取得します。

### setDocument() {#setdocument}

文書単位でサイズ値を設定します。

### setInches() {#setinches}

インチでサイズ値を設定します。

### setMillimeters() {#setmillimeters}

ミリメートルでサイズ値を設定します。

### setPixels() {#setpixels}

ピクセルでサイズ値を設定します。

### setPoint() {#setpoint}

ポイントでサイズ値を設定します。

### toString() {#tostring}

この Unit の人間が読める文字列表現を返します。

**Returns:** A string that represents this Unit.
