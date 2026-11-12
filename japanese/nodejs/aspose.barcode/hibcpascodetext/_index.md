---
title: "HIBCPASCodetext"
linktitle: "HIBCPASCodetext"
second_title: "Aspose.BarCode for Node.js via Java API リファレンス"
description: "HIBC PAS コードに埋め込まれたテキストをエンコードおよびデコードするクラス。"
type: docs
weight: 480
url: /ja/nodejs/aspose.barcode/hibcpascodetext/
---

## HIBCPASCodetext class

HIBC PAS コードに埋め込まれたテキストをエンコードおよびデコードするクラス。

```js
new HIBCPASCodetext()
```

**Example:**

```js
This sample shows how to encode and decode HIBC PAS using HIBCPASCodetext.

 let complexCodetext = new HIBCPASComplexCodetext();
 complexCodetext.setDataLocation(HIBCPASDataLocation.PATIENT);
 complexCodetext.addRecord(HIBCPASDataType.LABELER_IDENTIFICATION_CODE, "A123");
 complexCodetext.addRecord(HIBCPASDataType.MANUFACTURER_SERIAL_NUMBER, "SERIAL123");
 complexCodetext.setBarcodeType(EncodeTypes.HIBC_DATA_MATRIX_PAS);
 let generator = new ComplexBarcodeGenerator(complexCodetext);
 BarCodeReader reader = new BarCodeReader(generator.generateBarCodeImage(BarCodeImageFormat.PNG), null, DecodeType.HIBC_DATA_MATRIX_PAS);
 reader.readBarCodes();
 let codetext = reader.getFoundBarCodes()[0].getCodeText();
	let readCodetext = ComplexCodetextReader.tryDecodeHIBCPAS(codetext);
 print("Data location: " + readCodetext.getDataLocation());
 print("Data type: " + readCodetext.getRecords()[0].getDataType());
 print("Data: " + readCodetext.getRecords()[0].getData());
 print("Data type: " + readCodetext.getRecords()[1].getDataType());
 print("Data: " + readCodetext.getRecords()[1].getData());
```

## メソッド

| 名前 | 説明 |
| --- | --- |
| [_fromMwObject()](#-frommwobject) *(static)* | HIBCPASRecord コンストラクタ |
| [addHIBCPASRecord(record)](#addhibcpasrecord) | 新しいレコードを追加します |
| [addRecord(dataType, data)](#addrecord) | 新しいレコードを追加します |
| [clear()](#clear) | レコード一覧をクリアします |
| [equals(obj)](#equals) | このインスタンスが指定された `HIBCPASCodetext` 値と等しいかどうかを示す値を返します。 |
| [getBarcodeType()](#getbarcodetype) | バーコードのタイプを取得します。 |
| [getConstructedCodetext()](#getconstructedcodetext) | codetext を構築します |
| [getDataLocation()](#getdatalocation) | データの場所を特定します。 |
| [getRecords()](#getrecords) | レコード一覧を取得します |
| [hashCode()](#hashcode) | このインスタンスのハッシュコードを返します。 |
| [initFromString(constructedCodetext)](#initfromstring) | 構築された codetext からインスタンスを初期化します。 |
| [setBarcodeType()](#setbarcodetype) | バーコードタイプを取得または設定します。HIBC PAS コードテキストは HIBCCode39PAS、HIBCCode128PAS、HIBCAztec:PAS、HIBCData を使用してエンコードできます。 |
| [setDataLocation()](#setdatalocation) | データの場所を特定します。 |

### _fromMwObject() (static) {#-frommwobject}

HIBCPASRecord コンストラクタ

### addHIBCPASRecord(record) {#addhibcpasrecord}

新しいレコードを追加します

| パラメータ | 説明 |
| --- | --- |
| レコード | 追加するレコード |

### addRecord(dataType, data) {#addrecord}

新しいレコードを追加します

| パラメータ | 説明 |
| --- | --- |
| データ型 | データの種類 |
| データ | データ文字列 |

### clear() {#clear}

レコード一覧をクリアします

### equals(obj) {#equals}

このインスタンスが指定された `HIBCPASCodetext` 値と等しいかどうかを示す値を返します。

| パラメータ | 説明 |
| --- | --- |
| obj | このインスタンスと比較するための `HIBCPASCodetext` 値です。 |

**Returns:** `true ` if obj has the same value as this instance; otherwise, `false `.

### getBarcodeType() {#getbarcodetype}

バーコードのタイプを取得します。

**Returns:** Barcode type.

### getConstructedCodetext() {#getconstructedcodetext}

codetext を構築します

**Returns:** Constructed codetext

### getDataLocation() {#getdatalocation}

データの場所を特定します。

### getRecords() {#getrecords}

レコード一覧を取得します

**Returns:** List of records

### hashCode() {#hashcode}

このインスタンスのハッシュコードを返します。

**Returns:** A 32-bit signed integer hash code.

### initFromString(constructedCodetext) {#initfromstring}

構築された codetext からインスタンスを初期化します。

| パラメータ | 説明 |
| --- | --- |
| constructedCodetext | 構築された codetext。 |

### setBarcodeType() {#setbarcodetype}

バーコードタイプを取得または設定します。HIBC PAS コードテキストは HIBCCode39PAS、HIBCCode128PAS、HIBCAztec:PAS、HIBCDataMatrixPAS、HIBCQRPAS のエンコードタイプを使用してエンコードできます。既定値: HIBCCode39PAS。

**Returns:** Barcode type.

### setDataLocation() {#setdatalocation}

データの場所を特定します。
