---
title: "CodetextParameters"
linktitle: "CodetextParameters"
second_title: "Aspose.BarCode for Node.js via Java API リファレンス"
description: "Codetext パラメータ。"
type: docs
weight: 270
url: /ja/nodejs/aspose.barcode/codetextparameters/
---

## CodetextParameters class

Codetext パラメータ。

```js
new CodetextParameters()
```

## メソッド

| 名前 | 説明 |
| --- | --- |
| [getAlignment()](#getalignment) | コードテキストの配置を取得します。デフォルト値: TextAlignment.CENTER。 |
| [getColor()](#getcolor) | 表示する CodeText の色を指定します。デフォルト値: BLACK。 |
| [getFont()](#getfont) | 表示する CodeText のフォントを指定します。デフォルト値: Arial 5pt regular。FontMode が FontMode.AUTO に設定されている場合は無視されます。 |
| [getFontMode()](#getfontmode) | FontMode を指定します。FontMode が Auto に設定されている場合、フォントサイズは xDimension の値に基づいて自動的に計算されます。It i |
| [getLocation()](#getlocation) | 表示する CodeText の位置を指定します。CodeLocation.NONE に設定すると CodeText が非表示になります。デフォルト値: CodeLocation.BELOW。 |
| [getNoWrap()](#getnowrap) | テキスト内の改行（ワードラップ）を指定します。デフォルト値: false。 |
| [getSpace()](#getspace) | CodeText とバーコードの間のスペース（単位値）。デフォルト値: 2pt。EAN8、EAN13、UPCE、UPCA、ISBN には適用されません、 |
| [getTwoDDisplayText()](#gettwoddisplaytext) | 2D バーコードでコードテキストの代わりに表示されるテキスト。使用対象: Aztec、Pdf417、DataMatrix、QR、MaxiCode、DotCo |
| [setAlignment()](#setalignment) | コードテキストの配置を設定します。デフォルト値: TextAlignment.CENTER。 |
| [setColor()](#setcolor) | 表示する CodeText の色を指定します。デフォルト値: BLACK。 |
| [setFont()](#setfont) | 表示する CodeText のフォントを指定します。デフォルト値: Arial 5pt regular。FontMode が FontMode.AUTO に設定されている場合は無視されます。 |
| [setFontMode()](#setfontmode) | FontMode を指定します。FontMode が Auto に設定されている場合、フォントサイズは xDimension の値に基づいて自動的に計算されます。It i |
| [setLocation()](#setlocation) | 表示する CodeText の位置を指定します。CodeLocation.NONE に設定すると CodeText が非表示になります。デフォルト値: CodeLocation.NONE。 |
| [setNoWrap()](#setnowrap) | テキスト内の改行（ワードラップ）を指定します。デフォルト値: false。 |
| [setSpace()](#setspace) | CodeText とバーコードの間のスペース（単位値）。デフォルト値: 2pt。EAN8、EAN13、UPCE、UPCA、ISBN には適用されません、 |
| [setTwoDDisplayText()](#settwoddisplaytext) | 2D バーコードでコードテキストの代わりに表示されるテキスト。使用対象: Aztec、Pdf417、DataMatrix、QR、MaxiCode、DotCo |
| [toString()](#tostring) | この CodetextParameters の人間が読める文字列表現を返します。 |

### getAlignment() {#getalignment}

コードテキストの配置を取得します。デフォルト値: TextAlignment.CENTER。

### getColor() {#getcolor}

表示する CodeText の色を指定します。デフォルト値: BLACK。

### getFont() {#getfont}

表示する CodeText のフォントを指定します。デフォルト値: Arial 5pt regular。FontMode が FontMode.AUTO に設定されている場合は無視されます。

### getFontMode() {#getfontmode}

FontMode を指定します。FontMode が Auto に設定されている場合、フォントサイズは xDimension の値に基づいて自動的に計算されます。特に AutoSizeMode.NEAREST または AutoSizeMode.INTERPOLATION で FontMode.AUTO を使用することが推奨されます。デフォルト値: FontMode.AUTO。

### getLocation() {#getlocation}

表示する CodeText の位置を指定します。CodeLocation.NONE に設定すると CodeText が非表示になります。デフォルト値: CodeLocation.BELOW。

### getNoWrap() {#getnowrap}

テキスト内の改行（ワードラップ）を指定します。デフォルト値: false。

### getSpace() {#getspace}

CodeText とバーコードの間のスペース（単位値）。デフォルト値: 2pt。EAN8、EAN13、UPCE、UPCA、ISBN、ISMN、ISSN、UpcaGs1DatabarCoupon には適用されません。

### getTwoDDisplayText() {#gettwoddisplaytext}

2D バーコードでコードテキストの代わりに表示されるテキスト。使用対象: Aztec、Pdf417、DataMatrix、QR、MaxiCode、DotCode

### setAlignment() {#setalignment}

コードテキストの配置を設定します。デフォルト値: TextAlignment.CENTER。

### setColor() {#setcolor}

表示する CodeText の色を指定します。デフォルト値: BLACK。

### setFont() {#setfont}

表示する CodeText のフォントを指定します。デフォルト値: Arial 5pt regular。FontMode が FontMode.AUTO に設定されている場合は無視されます。

### setFontMode() {#setfontmode}

FontMode を指定します。FontMode が Auto に設定されている場合、フォントサイズは xDimension の値に基づいて自動的に計算されます。特に AutoSizeMode.NEAREST または AutoSizeMode.INTERPOLATION で FontMode.AUTO を使用することが推奨されます。デフォルト値: FontMode.AUTO。

### setLocation() {#setlocation}

表示する CodeText の位置を指定します。CodeLocation.NONE に設定すると CodeText が非表示になります。デフォルト値: CodeLocation.NONE。

### setNoWrap() {#setnowrap}

テキスト内の改行（ワードラップ）を指定します。デフォルト値: false。

### setSpace() {#setspace}

CodeText とバーコードの間のスペース（単位値）。デフォルト値: 2pt。EAN8、EAN13、UPCE、UPCA、ISBN、ISMN、ISSN、UpcaGs1DatabarCoupon には適用されません。

### setTwoDDisplayText() {#settwoddisplaytext}

2D バーコードでコードテキストの代わりに表示されるテキスト。使用対象: Aztec、Pdf417、DataMatrix、QR、MaxiCode、DotCode

### toString() {#tostring}

この CodetextParameters の人間が読める文字列表現を返します。

**Returns:** A string that represents this CodetextParameters.
