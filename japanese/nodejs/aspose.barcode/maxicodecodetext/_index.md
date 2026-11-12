---
title: "MaxiCodeCodetext"
linktitle: "MaxiCodeCodetext"
second_title: "Aspose.BarCode for Node.js via Java API リファレンス"
description: "MaxiCode コードに埋め込まれたテキストをエンコードおよびデコードするための基底クラスです。"
type: docs
weight: 600
url: /ja/nodejs/aspose.barcode/maxicodecodetext/
---

## MaxiCodeCodetext class

MaxiCode コードに埋め込まれたテキストをエンコードおよびデコードするための基底クラスです。このサンプルは、生の MaxiCode コードテキストを MaxiCodeCodetext インスタンスにデコードする方法を示しています。

```js
new MaxiCodeCodetext()
```

**Example:**

```js
let reader = new BarCodeReader("c:\\test.png", null, DecodeType.MAXI_CODE);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
     let result = results[i];
     let resultMaxiCodeCodetext = ComplexCodetextReader.tryDecodeMaxiCode(result.getExtended().getMaxiCode().getMaxiCodeMode(), result.getCodeText());
     console.log("BarCode Type: " + resultMaxiCodeCodetext.getBarcodeType());
     console.log("MaxiCode mode: " + resultMaxiCodeCodetext.getMode());
     console.log("BarCode CodeText: " + resultMaxiCodeCodetext.getConstructedCodetext());
}
```

## メソッド

| 名前 | 説明 |
| --- | --- |
| [getBarcodeType()](#getbarcodetype) | バーコードのタイプを取得します。 |
| [getECIEncoding()](#geteciencoding) | ECI エンコーディングを取得します。MaxiCodeEncodeMode が AUTO の場合に使用されます。 |
| [getEncodeMode()](#getencodemode) | MaxiCode エンコードモードを取得します。デフォルト値: Auto。 |
| [getMaxiCodeEncodeMode()](#getmaxicodeencodemode) ~~(deprecated)~~ | MaxiCode エンコードモードを取得します。 |
| [getMode()](#getmode) | MaxiCodeモードを取得します。 |
| [setECIEncoding()](#seteciencoding) | ECI エンコーディングを設定します。MaxiCodeEncodeMode が AUTO の場合に使用されます。 |
| [setEncodeMode(value)](#setencodemode) | MaxiCode エンコードモードを設定します。デフォルト値: Auto. |
| [setMaxiCodeEncodeMode()](#setmaxicodeencodemode) ~~(deprecated)~~ | MaxiCode エンコードモードを設定します。 |

### getBarcodeType() {#getbarcodetype}

バーコードのタイプを取得します。

**Returns:** Barcode type

### getECIEncoding() {#geteciencoding}

ECI エンコーディングを取得します。MaxiCodeEncodeMode が AUTO の場合に使用されます。

### getEncodeMode() {#getencodemode}

MaxiCode エンコードモードを取得します。デフォルト値: Auto。

**Returns:** a MaxiCode encode mode.

### getMaxiCodeEncodeMode() {#getmaxicodeencodemode}

> **Deprecated.** See method description for replacement.

MaxiCode エンコードモードを取得します。

### getMode() {#getmode}

MaxiCodeモードを取得します。

**Returns:** MaxiCode mode

### setECIEncoding() {#seteciencoding}

ECI エンコーディングを設定します。MaxiCodeEncodeMode が AUTO の場合に使用されます。

### setEncodeMode(value) {#setencodemode}

MaxiCode エンコードモードを設定します。デフォルト値: Auto.

| パラメータ | 説明 |
| --- | --- |
| 値 | MaxiCode エンコードモード。 |

### setMaxiCodeEncodeMode() {#setmaxicodeencodemode}

> **Deprecated.** See method description for replacement.

MaxiCode エンコードモードを設定します。
