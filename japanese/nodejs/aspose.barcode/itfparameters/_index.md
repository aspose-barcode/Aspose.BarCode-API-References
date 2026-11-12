---
title: "ITFParameters"
linktitle: "ITFParameters"
second_title: "Aspose.BarCode for Node.js via Java API リファレンス"
description: "ITF パラメータ。"
type: docs
weight: 540
url: /ja/nodejs/aspose.barcode/itfparameters/
---

## ITFParameters class

ITF パラメータ。

```js
new ITFParameters()
```

## メソッド

| 名前 | 説明 |
| --- | --- |
| [getBorderThickness()](#getborderthickness) | ITF のボーダー（ベアラーバー）の厚さを Unit 値で取得します。デフォルト値: 12pt。 |
| [getBorderType()](#getbordertype) | ITF バーコードのボーダータイプです。デフォルト値: ITF14BorderType.Bar。 |
| [getItfBorderThickness()](#getitfborderthickness) ~~(deprecated)~~ | ITF のボーダー（ベアラーバー）の厚さを Unit 値で取得します。デフォルト値: 12pt。 |
| [getItfBorderType()](#getitfbordertype) ~~(deprecated)~~ | ITF バーコードのボーダータイプです。デフォルト値: ITF14BorderType.BAR。 |
| [getQuietZoneCoef()](#getquietzonecoef) | xDimension におけるクワイエットゾーンのサイズです。デフォルト値: 10。つまり、xDimension が 2px の場合、クワイエントゾーンは 20px になります。 |
| [setBorderThickness(value)](#setborderthickness) | ITF のボーダー（ベアラーバー）の厚さを Unit 値で設定します。デフォルト値: 12pt。 |
| [setBorderType()](#setbordertype) | ITF バーコードのボーダータイプです。デフォルト値: ITF14BorderType.Bar。 |
| [setItfBorderThickness()](#setitfborderthickness) ~~(deprecated)~~ | ITF のボーダー（ベアラーバー）の厚さを Unit 値で設定します。デフォルト値: 12pt。 |
| [setItfBorderType()](#setitfbordertype) ~~(deprecated)~~ | ITF バーコードのボーダータイプです。デフォルト値: ITF14BorderType.BAR。 |
| [setQuietZoneCoef()](#setquietzonecoef) | xDimension におけるクワイエットゾーンのサイズです。デフォルト値: 10。つまり、xDimension が 2px の場合、クワイエントゾーンは 20px になります。 |
| [toString()](#tostring) | この ITFParameters の人間が読める文字列表現を返します。 |

### getBorderThickness() {#getborderthickness}

ITF のボーダー（ベアラーバー）の厚さを Unit 値で取得します。デフォルト値: 12pt。

**Returns:** an ITF border (bearer bar) thickness in Unit value.

### getBorderType() {#getbordertype}

ITF バーコードのボーダータイプです。デフォルト値: ITF14BorderType.Bar。

### getItfBorderThickness() {#getitfborderthickness}

> **Deprecated.** See method description for replacement.

ITF のボーダー（ベアラーバー）の厚さを Unit 値で取得します。デフォルト値: 12pt。

### getItfBorderType() {#getitfbordertype}

> **Deprecated.** See method description for replacement.

ITF バーコードのボーダータイプです。デフォルト値: ITF14BorderType.BAR。

### getQuietZoneCoef() {#getquietzonecoef}

xDimension におけるクワイエットゾーンのサイズです。デフォルト値: 10。つまり、xDimension が 2px の場合、クワイエントゾーンは 20px になります。

**Throws:** IllegalArgumentException
QuietZoneCoef パラメータの値が 10 未満です。

### setBorderThickness(value) {#setborderthickness}

ITF のボーダー（ベアラーバー）の厚さを Unit 値で設定します。デフォルト値: 12pt。

| パラメータ | 説明 |
| --- | --- |
| 値 | Unit 値で表した ITF ボーダー（ベアラーバー）の厚さ。 |

### setBorderType() {#setbordertype}

ITF バーコードのボーダータイプです。デフォルト値: ITF14BorderType.Bar。

### setItfBorderThickness() {#setitfborderthickness}

> **Deprecated.** See method description for replacement.

ITF のボーダー（ベアラーバー）の厚さを Unit 値で設定します。デフォルト値: 12pt。

### setItfBorderType() {#setitfbordertype}

> **Deprecated.** See method description for replacement.

ITF バーコードのボーダータイプです。デフォルト値: ITF14BorderType.BAR。

### setQuietZoneCoef() {#setquietzonecoef}

xDimension におけるクワイエットゾーンのサイズです。デフォルト値: 10。つまり、xDimension が 2px の場合、クワイエントゾーンは 20px になります。

**Throws:** IllegalArgumentException
QuietZoneCoef パラメータの値が 10 未満です。

### toString() {#tostring}

この ITFParameters の人間が読める文字列表現を返します。

**Returns:** A string that represents this ITFParameters.
