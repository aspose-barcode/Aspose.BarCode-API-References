---
title: "SecondaryAndAdditionalData"
linktitle: "SecondaryAndAdditionalData"
second_title: "Aspose.BarCode for Node.js via Java API リファレンス"
description: "HIBC LIC の二次および追加データを保存するクラスです。"
type: docs
weight: 880
url: /ja/nodejs/aspose.barcode/secondaryandadditionaldata/
---

## SecondaryAndAdditionalData class

HIBC LIC の二次および追加データを保存するクラスです。

```js
new SecondaryAndAdditionalData()
```

## メソッド

| 名前 | 説明 |
| --- | --- |
| [equals(obj)](#equals) | このインスタンスが指定された `SecondaryAndAdditionalData` 値と等しいかどうかを示す値を返します。 |
| [getDateOfManufacture()](#getdateofmanufacture) | 製造日を識別します。製造日はこのフィールドを使用しないようにするために DateTime.MinValue に設定できます。Defa |
| [getExpiryDate()](#getexpirydate) | 有効期限日を識別します。ExpiryDateFormat が None に設定されていない場合に使用されます。 |
| [getExpiryDateFormat()](#getexpirydateformat) | 有効期限の日付形式を識別します。 |
| [getLotNumber()](#getlotnumber) | ロットまたはバッチ番号を識別します。ロット/バッチ番号は最大 18 文字の英数字文字列である必要があります。 |
| [getQuantity()](#getquantity) | 数量を識別します。0 から 500 の整数値である必要があります。数量はこのフィールドを使用しないようにするために -1 に設定できます。Defa |
| [getSerialNumber()](#getserialnumber) | シリアル番号を識別します。シリアル番号は最大 18 文字の英数字文字列である必要があります。 |
| [hashCode()](#hashcode) | このインスタンスのハッシュコードを返します。 |
| [parseFromString(secondaryDataCodetext)](#parsefromstring) | HIBC LIC 仕様に従って文字列形式から二次および追加の補足データをインスタンス化します。 |
| [setDateOfManufacture()](#setdateofmanufacture) | 製造日を識別します。製造日はこのフィールドを使用しないようにするために DateTime.MinValue に設定できます。Defa |
| [setExpiryDate()](#setexpirydate) | 有効期限日を識別します。ExpiryDateFormat が None に設定されていない場合に使用されます。 |
| [setExpiryDateFormat()](#setexpirydateformat) | 有効期限の日付形式を識別します。 |
| [setLotNumber()](#setlotnumber) | ロットまたはバッチ番号を識別します。ロット/バッチ番号は最大 18 文字の英数字文字列である必要があります。 |
| [setQuantity()](#setquantity) | 数量を識別します。0 から 500 の整数値である必要があります。数量はこのフィールドを使用しないようにするために -1 に設定できます。Defa |
| [setSerialNumber()](#setserialnumber) | シリアル番号を識別します。シリアル番号は最大 18 文字の英数字文字列である必要があります。 |
| [toString()](#tostring) | HIBC LIC 仕様に従ってデータを文字列形式に変換します。 |

### equals(obj) {#equals}

このインスタンスが指定された `SecondaryAndAdditionalData` 値と等しいかどうかを示す値を返します。

| パラメータ | 説明 |
| --- | --- |
| obj | `SecondaryAndAdditionalData` の値をこのインスタンスと比較します。 |

**Returns:** `true ` if obj has the same value as this instance; otherwise, `false `.

### getDateOfManufacture() {#getdateofmanufacture}

製造日を識別します。製造日はこのフィールドを使用しないようにするために DateTime.MinValue に設定できます。デフォルト値: DateTime.MinValue

### getExpiryDate() {#getexpirydate}

有効期限日を識別します。ExpiryDateFormat が None に設定されていない場合に使用されます。

### getExpiryDateFormat() {#getexpirydateformat}

有効期限の日付形式を識別します。

### getLotNumber() {#getlotnumber}

ロットまたはバッチ番号を識別します。ロット/バッチ番号は最大 18 文字の英数字文字列である必要があります。

### getQuantity() {#getquantity}

数量を識別します。0 から 500 の整数値である必要があります。数量はこのフィールドを使用しないようにするために -1 に設定できます。デフォルト値: -1

### getSerialNumber() {#getserialnumber}

シリアル番号を識別します。シリアル番号は最大 18 文字の英数字文字列である必要があります。

### hashCode() {#hashcode}

このインスタンスのハッシュコードを返します。

**Returns:** A 32-bit signed integer hash code.

### parseFromString(secondaryDataCodetext) {#parsefromstring}

HIBC LIC 仕様に従って文字列形式から二次および追加の補足データをインスタンス化します。

| パラメータ | 説明 |
| --- | --- |
| secondaryDataCodetext | フォーマットされた文字列。 |

### setDateOfManufacture() {#setdateofmanufacture}

製造日を識別します。製造日はこのフィールドを使用しないようにするために DateTime.MinValue に設定できます。デフォルト値: DateTime.MinValue

### setExpiryDate() {#setexpirydate}

有効期限日を識別します。ExpiryDateFormat が None に設定されていない場合に使用されます。

### setExpiryDateFormat() {#setexpirydateformat}

有効期限の日付形式を識別します。

### setLotNumber() {#setlotnumber}

ロットまたはバッチ番号を識別します。ロット/バッチ番号は最大 18 文字の英数字文字列である必要があります。

### setQuantity() {#setquantity}

数量を識別します。0 から 500 の整数値である必要があります。数量はこのフィールドを使用しないようにするために -1 に設定できます。デフォルト値: -1

### setSerialNumber() {#setserialnumber}

シリアル番号を識別します。シリアル番号は最大 18 文字の英数字文字列である必要があります。

### toString() {#tostring}

HIBC LIC 仕様に従ってデータを文字列形式に変換します。

**Returns:** Formatted string.
