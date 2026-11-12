---
title: "MaxiCodeStandardCodetext"
linktitle: "MaxiCodeStandardCodetext"
second_title: "Aspose.BarCode for Node.js via Java API リファレンス"
description: "モード 4、5、6 用の MaxiCode コードテキストをエンコードおよびデコードするクラスです。"
type: docs
weight: 670
url: /ja/nodejs/aspose.barcode/maxicodestandardcodetext/
---

## MaxiCodeStandardCodetext class

モード 4、5、6 用の MaxiCode コードテキストをエンコードおよびデコードするクラスです。

```js
new MaxiCodeStandardCodetext()
```

**Example:**

```js
//Mode 4
let maxiCodeCodetext = new MaxiCodeStandardCodetext();
maxiCodeCodetext.setMode(MaxiCodeMode.MODE_4);
maxiCodeCodetext.setMessage("Test message");
let complexGenerator = new ComplexBarcodeGenerator(maxiCodeCodetext.getConstructedCodetext());
complexGenerator.generateBarCodeImage(BarcodeImageFormat.PNG);
```

## メソッド

| 名前 | 説明 |
| --- | --- |
| [equals(obj)](#equals) | このインスタンスが指定された値と等しいかどうかを示す値を返します。 |
| [getConstructedCodetext()](#getconstructedcodetext) | codetext を構築します |
| [getHashCode()](#gethashcode) | このインスタンスのハッシュコードを返します。 |
| [getMessage()](#getmessage) | メッセージを取得します。 |
| [getMode()](#getmode) | MaxiCodeモードを取得します。 |
| [initFromString(constructedCodetext)](#initfromstring) | 構築された codetext からインスタンスを初期化します。 |
| [setMessage()](#setmessage) | メッセージを設定します。 |
| [setMode()](#setmode) | MaxiCode モードを設定します。標準のコードテキストはモード 4、5、6 のみで使用できます。 |

### equals(obj) {#equals}

このインスタンスが指定された値と等しいかどうかを示す値を返します。

| パラメータ | 説明 |
| --- | --- |
| obj | このインスタンスと比較する値です。 |

**Returns:** if obj has the same value as this instance; otherwise, false .

### getConstructedCodetext() {#getconstructedcodetext}

codetext を構築します

**Returns:** Constructed codetext

### getHashCode() {#gethashcode}

このインスタンスのハッシュコードを返します。

**Returns:** A 32-bit signed integer hash code

### getMessage() {#getmessage}

メッセージを取得します。

### getMode() {#getmode}

MaxiCodeモードを取得します。

**Returns:** MaxiCode mode

### initFromString(constructedCodetext) {#initfromstring}

構築された codetext からインスタンスを初期化します。

| パラメータ | 説明 |
| --- | --- |
| constructedCodetext | 構築された codetext。 |

### setMessage() {#setmessage}

メッセージを設定します。

### setMode() {#setmode}

MaxiCode モードを設定します。標準のコードテキストはモード 4、5、6 のみで使用できます。
