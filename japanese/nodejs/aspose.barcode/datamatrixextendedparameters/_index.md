---
title: "DataMatrixExtendedParameters"
linktitle: "DataMatrixExtendedParameters"
second_title: "Aspose.BarCode for Node.js via Java API リファレンス"
description: "DataMatrix 認識バーコードの特別データを保存します このサンプルは DataMatrix の生データを取得する方法を示します let generator = new BarcodeGenerator(EncodeTypes.DATA_MA"
type: docs
weight: 350
url: /ja/nodejs/aspose.barcode/datamatrixextendedparameters/
---

## DataMatrixExtendedParameters class

DataMatrix 認識バーコードの特別データを保存します このサンプルは DataMatrix の生データを取得する方法を示します let generator = new BarcodeGenerator(EncodeTypes.DATA_MATRIX, "12345")) generator.save("test.png", BarcodeImageFormat.PNG); let reader = new BarCodeReader("test.png", null, DecodeType.DATA_MATRIX)) let results = reader.readBarCodes(); for(let i = 0; i < results.length; i++) { let result = results[i]; console.log("BarCode type: " + result.getCodeTypeName()); console.log("BarCode codetext: " + result.getCodeText()); console.log("DataMatrix barcode ID: " + result.getExtended().getDataMatrix().getStructuredAppendBarcodeId()); console.log("DataMatrix barcodes count: " + result.getExtended().getDataMatrix().getStructuredAppendBarcodesCount()); console.log("DataMatrix file ID: " + result.getExtended().getDataMatrix().getStructuredAppendFileId()); console.log("DataMatrix is reader programming: " + result.getExtended().getDataMatrix().isReaderProgramming()); }

```js
new DataMatrixExtendedParameters()
```

## メソッド

| 名前 | 説明 |
| --- | --- |
| [equals(obj)](#equals) | このインスタンスが指定された `DataMatrixExtendedParameters` の値と等しいかどうかを示す値を返します。 |
| [getStructuredAppendBarcodeId()](#getstructuredappendbarcodeid) | DataMatrix 構造付加モードバーコードの ID を取得します。ID は 1 から開始し、バーコードの数以下である必要があります |
| [getStructuredAppendBarcodesCount()](#getstructuredappendbarcodescount) | DataMatrix 構造付加モードのバーコード数を取得します。デフォルト値は -1 です。カウントは 1 から 35 の範囲である必要があります |
| [getStructuredAppendFileId()](#getstructuredappendfileid) | DataMatrix 構造付加モードバーコードの ID を取得します。ID は 1 から開始し、バーコードの数以下である必要があります |
| [hashCode()](#hashcode) | このインスタンスのハッシュコードを返します。 |
| [isReaderProgramming()](#isreaderprogramming) | コードがリーダーに対し、以下のデータを初期化の指示として解釈させるために使用されるかどうかを示します。 |
| [toString()](#tostring) | この `DataMatrixExtendedParameters` の人間が読みやすい文字列表現を返します。 |

### equals(obj) {#equals}

このインスタンスが指定された `DataMatrixExtendedParameters` の値と等しいかどうかを示す値を返します。

| パラメータ | 説明 |
| --- | --- |
| obj | このインスタンスと比較するための System.Object の値です。 |

**Returns:** `true ` if obj has the same value as this instance; otherwise, `false `.

### getStructuredAppendBarcodeId() {#getstructuredappendbarcodeid}

DataMatrix 構造付加モードバーコードの ID を取得します。ID は 1 から開始し、バーコード数以下である必要があります。デフォルト値は -1 です。値: DataMatrix 構造付加モードバーコードの ID。

### getStructuredAppendBarcodesCount() {#getstructuredappendbarcodescount}

DataMatrix 構造付加モードのバーコード数を取得します。デフォルト値は -1 です。カウントは 1 から 35 の範囲である必要があります。値: DataMatrix 構造付加モードバーコードの数。

### getStructuredAppendFileId() {#getstructuredappendfileid}

DataMatrix 構造付加モードバーコードの ID を取得します。ID は 1 から開始し、バーコード数以下である必要があります。デフォルト値は -1 です。値: DataMatrix 構造付加モードバーコードの ID。

### hashCode() {#hashcode}

このインスタンスのハッシュコードを返します。

**Returns:** A 32-bit signed integer hash code.

### isReaderProgramming() {#isreaderprogramming}

コードがバーコードリーダーに対し、以下のデータを初期化または再プログラミングの指示として解釈させるために使用されるかどうかを示します。デフォルト値は false です。

### toString() {#tostring}

この `DataMatrixExtendedParameters` の人間が読みやすい文字列表現を返します。

**Returns:** A string that represents this `DataMatrixExtendedParameters`.
