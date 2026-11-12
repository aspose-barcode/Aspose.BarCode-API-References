---
title: "PrimaryData"
linktitle: "PrimaryData"
second_title: "Aspose.BarCode for Node.js via Java API リファレンス"
description: "HIBC LIC の一次データを保存するクラスです。"
type: docs
weight: 800
url: /ja/nodejs/aspose.barcode/primarydata/
---

## PrimaryData class

HIBC LIC の一次データを保存するクラスです。

```js
new PrimaryData()
```

## メソッド

| 名前 | 説明 |
| --- | --- |
| [equals(obj)](#equals) | このインスタンスが指定された `PrimaryData` の値と等しいかどうかを示す値を返します。 |
| [getLabelerIdentificationCode()](#getlabeleridentificationcode) | ラベラー識別コードの日付を識別します。ラベラー識別コードは、4文字の英数字文字列である必要があります、 |
| [getProductOrCatalogNumber()](#getproductorcatalognumber) | 製品またはカタログ番号を識別します。製品またはカタログ番号は、最大18文字の英数字文字列である必要があります。 |
| [getUnitOfMeasureID()](#getunitofmeasureid) | 測定単位IDを識別します。測定単位IDは0から9までの整数である必要があります。 |
| [hashCode()](#hashcode) | このインスタンスのハッシュコードを返します。 |
| [parseFromString(primaryDataCodetext)](#parsefromstring) | HIBC LIC 仕様に従って文字列形式からプライマリデータをインスタンス化します。 |
| [setLabelerIdentificationCode()](#setlabeleridentificationcode) | ラベラー識別コードの日付を識別します。ラベラー識別コードは、4文字の英数字文字列である必要があります、 |
| [setProductOrCatalogNumber()](#setproductorcatalognumber) | 製品またはカタログ番号を識別します。製品またはカタログ番号は、最大18文字の英数字文字列である必要があります。 |
| [setUnitOfMeasureID()](#setunitofmeasureid) | 測定単位IDを識別します。測定単位IDは0から9までの整数である必要があります。 |
| [toString()](#tostring) | HIBC LIC 仕様に従ってデータを文字列形式に変換します。 |

### equals(obj) {#equals}

このインスタンスが指定された `PrimaryData` の値と等しいかどうかを示す値を返します。

| パラメータ | 説明 |
| --- | --- |
| obj | `PrimaryData` 値をこのインスタンスと比較します。 |

**Returns:** `true ` if obj has the same value as this instance; otherwise, `false `.

### getLabelerIdentificationCode() {#getlabeleridentificationcode}

ラベラー識別コードの日付を識別します。ラベラー識別コードは、4文字の英数字文字列で、最初の文字は必ずアルファベットである必要があります。

### getProductOrCatalogNumber() {#getproductorcatalognumber}

製品またはカタログ番号を識別します。製品またはカタログ番号は、最大18文字の英数字文字列である必要があります。

### getUnitOfMeasureID() {#getunitofmeasureid}

測定単位IDを識別します。測定単位IDは0から9までの整数である必要があります。

### hashCode() {#hashcode}

このインスタンスのハッシュコードを返します。

**Returns:** A 32-bit signed integer hash code.

### parseFromString(primaryDataCodetext) {#parsefromstring}

HIBC LIC 仕様に従って文字列形式からプライマリデータをインスタンス化します。

| パラメータ | 説明 |
| --- | --- |
| primaryDataCodetext | フォーマットされた文字列。 |

### setLabelerIdentificationCode() {#setlabeleridentificationcode}

ラベラー識別コードの日付を識別します。ラベラー識別コードは、4文字の英数字文字列で、最初の文字は必ずアルファベットである必要があります。

### setProductOrCatalogNumber() {#setproductorcatalognumber}

製品またはカタログ番号を識別します。製品またはカタログ番号は、最大18文字の英数字文字列である必要があります。

### setUnitOfMeasureID() {#setunitofmeasureid}

測定単位IDを識別します。測定単位IDは0から9までの整数である必要があります。

### toString() {#tostring}

HIBC LIC 仕様に従ってデータを文字列形式に変換します。

**Returns:** Formatted string.
