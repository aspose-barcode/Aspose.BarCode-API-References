---
title: "QRExtendedParameters"
linktitle: "QRExtendedParameters"
second_title: "Aspose.BarCode for Node.js via Java API リファレンス"
description: "認識されたバーコードの QR Structured Append 情報を保存します。"
type: docs
weight: 810
url: /ja/nodejs/aspose.barcode/qrextendedparameters/
---

## QRExtendedParameters class

認識されたバーコードの QR Structured Append 情報を保存します。

```js
new QRExtendedParameters()
```

**Example:**

```js
//This sample shows how to get QR Structured Append data

let reader = new BarCodeReader("test.png", null,  DecodeType.QR);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
   let result = results[i];
   console.log("BarCode Type: " + result.getCodeTypeName());
   console.log("BarCode CodeText: " + result.getCodeText());
   console.log("QR Structured Append Quantity: " + result.getExtended().getQR().getQRStructuredAppendModeBarCodesQuantity());
   console.log("QR Structured Append Index: " + result.getExtended().getQR().getQRStructuredAppendModeBarCodeIndex());
   console.log("QR Structured Append ParityData: " + result.getExtended().getQR().getQRStructuredAppendModeParityData());
}
```

## メソッド

| 名前 | 説明 |
| --- | --- |
| [equals(obj)](#equals) | このインスタンスが指定された QRExtendedParameters 値と等しいかどうかを示す値を返します。 |
| [getErrorLevel()](#geterrorlevel) | 認識されたバーコードのリード・ソロモン誤り訂正レベル。低から高へ: LevelL、LevelM、LevelQ、LevelH。 |
| [getMicroQRVersion()](#getmicroqrversion) | 認識された MicroQR コードのバージョン。M1 から M4 まで。 |
| [getQRErrorLevel()](#getqrerrorlevel) ~~(deprecated)~~ | 認識されたバーコードのリード・ソロモン誤り訂正レベル。低から高へ: LevelL、LevelM、LevelQ、LevelH。 |
| [getQRStructuredAppendModeBarCodeIndex()](#getqrstructuredappendmodebarcodeindex) ~~(deprecated)~~ | QR 構造付加モードバーコードのインデックスを取得します。インデックスは 0 から開始します。デフォルト値は -1 です。値: 数量の |
| [getQRStructuredAppendModeBarCodesQuantity()](#getqrstructuredappendmodebarcodesquantity) ~~(deprecated)~~ | QR 構造付加モードバーコードの数量を取得します。デフォルト値は -1 です。値: QR 構造付加モードの数量 |
| [getQRStructuredAppendModeParityData()](#getqrstructuredappendmodeparitydata) ~~(deprecated)~~ | QR 構造付加モードのパリティデータを取得します。デフォルト値は -1 です。値: QR 構造付加モードのインデックス |
| [getQRVersion()](#getqrversion) ~~(deprecated)~~ | 認識された QR コードのバージョン。Version1 から Version40 まで。 |
| [getRectMicroQRVersion()](#getrectmicroqrversion) | 認識された RectMicroQR コードのバージョン。R7x43 から R17x139 まで。 |
| [getStructuredAppendModeBarCodeIndex()](#getstructuredappendmodebarcodeindex) | QR 構造付加モードバーコードのインデックスを取得します。インデックスは 0 から開始します。デフォルト値は -1 です。値: 数量の |
| [getStructuredAppendModeBarCodesQuantity()](#getstructuredappendmodebarcodesquantity) | QR 構造付加モードバーコードの数量を取得します。デフォルト値は -1 です。値: QR 構造付加モードの数量 |
| [getStructuredAppendModeParityData()](#getstructuredappendmodeparitydata) | QR 構造付加モードのパリティデータを取得します。デフォルト値は -1 です。値: QR 構造付加モードのインデックス |
| [getVersion()](#getversion) | 認識された QR コードのバージョン。Version1 から Version40 まで。 |
| [hashCode()](#hashcode) | このインスタンスのハッシュコードを返します。 |
| [isEmpty()](#isempty) | すべてのパラメータがデフォルト値のみであるかどうかをテストします 値 |
| [toString()](#tostring) | この QRExtendedParameters の人間が読みやすい文字列表現を返します。 |

### equals(obj) {#equals}

このインスタンスが指定された QRExtendedParameters 値と等しいかどうかを示す値を返します。

| パラメータ | 説明 |
| --- | --- |
| obj | このインスタンスと比較するオブジェクト値。 |

**Returns:** true if obj has the same value as this instance; otherwise, false.

### getErrorLevel() {#geterrorlevel}

認識されたバーコードのリード・ソロモン誤り訂正レベル。低から高へ: LevelL、LevelM、LevelQ、LevelH。

### getMicroQRVersion() {#getmicroqrversion}

認識された MicroQR コードのバージョン。M1 から M4 まで。

**Returns:** Version of recognized MicroQR Code. From M1 to M4.

### getQRErrorLevel() {#getqrerrorlevel}

> **Deprecated.** See method description for replacement.

認識されたバーコードのリード・ソロモン誤り訂正レベル。低から高へ: LevelL、LevelM、LevelQ、LevelH。

**Returns:** Reed-Solomon error correction level of recognized barcode.

### getQRStructuredAppendModeBarCodeIndex() {#getqrstructuredappendmodebarcodeindex}

> **Deprecated.** See method description for replacement.

QR 構造付加モードバーコードのインデックスを取得します。インデックスは 0 から開始します。デフォルト値は -1 です。値: QR 構造付加モードバーコードの数量。

### getQRStructuredAppendModeBarCodesQuantity() {#getqrstructuredappendmodebarcodesquantity}

> **Deprecated.** See method description for replacement.

QR 構造付加モードバーコードの数量を取得します。デフォルト値は -1 です。値: QR 構造付加モードバーコードの数量。

### getQRStructuredAppendModeParityData() {#getqrstructuredappendmodeparitydata}

> **Deprecated.** See method description for replacement.

QR 構造付加モードのパリティデータを取得します。デフォルト値は -1 です。値: QR 構造付加モードバーコードのインデックス。

### getQRVersion() {#getqrversion}

> **Deprecated.** See method description for replacement.

認識された QR コードのバージョン。Version1 から Version40 まで。

**Returns:** Version of recognized QR Code

### getRectMicroQRVersion() {#getrectmicroqrversion}

認識された RectMicroQR コードのバージョン。R7x43 から R17x139 まで。

**Returns:** Version of recognized RectMicroQR Code

### getStructuredAppendModeBarCodeIndex() {#getstructuredappendmodebarcodeindex}

QR構造付加モードバーコードのインデックスを取得します。インデックスは0から開始します。デフォルト値は-1です。値: QR構造付加モードバーコードの数量。

**Returns:** the index of the QR structured append mode barcode.

### getStructuredAppendModeBarCodesQuantity() {#getstructuredappendmodebarcodesquantity}

QR構造付加モードバーコードの数量を取得します。デフォルト値は-1です。値: QR構造付加モードバーコードの数量。

**Returns:** the QR structured append mode barcodes quantity.

### getStructuredAppendModeParityData() {#getstructuredappendmodeparitydata}

QR構造付加モードのパリティデータを取得します。デフォルト値は-1です。値: QR構造付加モードバーコードのインデックス。

**Returns:** the QR structured append mode parity data.

### getVersion() {#getversion}

認識された QR コードのバージョン。Version1 から Version40 まで。

### hashCode() {#hashcode}

このインスタンスのハッシュコードを返します。

**Returns:** A 32-bit signed integer hash code.

### isEmpty() {#isempty}

すべてのパラメータがデフォルト値のみであるかどうかをテストします 値

**Returns:** true if all parameters has only default values; otherwise, `false `.

### toString() {#tostring}

この QRExtendedParameters の人間が読みやすい文字列表現を返します。

**Returns:** A string that represents this QRExtendedParameters.
