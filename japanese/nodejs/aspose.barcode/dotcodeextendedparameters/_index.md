---
title: "DotCodeExtendedParameters"
linktitle: "DotCodeExtendedParameters"
second_title: "Aspose.BarCode for Node.js via Java API リファレンス"
description: "認識された DotCode バーコードの特別なデータを格納します。このサンプルは DotCode の生データ値を取得する方法を示します"
type: docs
weight: 380
url: /ja/nodejs/aspose.barcode/dotcodeextendedparameters/
---

## DotCodeExtendedParameters class

認識された DotCode バーコードの特別なデータを格納します。このサンプルは DotCode の生データ値を取得する方法を示します

```js
new DotCodeExtendedParameters()
```

**Example:**

```js
let generator = new BarcodeGenerator(EncodeTypes.DOT_CODE, "12345");
generator.save("test.png", BarCodeImageFormat.PNG);

let reader = new BarCodeReader("test.png", null, DecodeType.DOT_CODE);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
    let result = results[i];
    print("BarCode type: " + result.getCodeTypeName());
    print("BarCode codetext: " + result.getCodeText());
    print("DotCode barcode ID: " + result.getExtended().getDotCode().getDotCodeStructuredAppendModeBarcodeId());
    print("DotCode barcodes count: " + result.getExtended().getDotCode().getDotCodeStructuredAppendModeBarcodesCount());
}
```

## メソッド

| 名前 | 説明 |
| --- | --- |
| [equals(obj)](#equals) | このインスタンスが指定された `DotCodeExtendedParameters` の値と等しいかどうかを示す値を返します。 |
| [getDotCodeIsReaderInitialization()](#getdotcodeisreaderinitialization) ~~(deprecated)~~ | コードがリーダーに対し、以下のデータを初期化の指示として解釈させるために使用されるかどうかを示します。 |
| [getDotCodeStructuredAppendModeBarcodeId()](#getdotcodestructuredappendmodebarcodeid) ~~(deprecated)~~ | DotCode 構造化付加モードバーコードの ID を取得します。ID は 1 から開始し、バーコードの数以下である必要があります。 |
| [getDotCodeStructuredAppendModeBarcodesCount()](#getdotcodestructuredappendmodebarcodescount) ~~(deprecated)~~ | DotCode 構造化付加モードのバーコード数を取得します。デフォルト値は -1 です。カウントは 1 から 35 の値である必要があります。値: |
| [getStructuredAppendModeBarcodeId()](#getstructuredappendmodebarcodeid) | DotCode 構造化付加モードバーコードの ID を取得します。ID は 1 から開始し、バーコードの数以下である必要があります。 |
| [getStructuredAppendModeBarcodesCount()](#getstructuredappendmodebarcodescount) | DotCode 構造化付加モードのバーコード数を取得します。デフォルト値は -1 です。カウントは 1 から 35 の値である必要があります。値: |
| [hashCode()](#hashcode) | このインスタンスのハッシュコードを返します。 |
| [isReaderInitialization()](#isreaderinitialization) | コードがリーダーに対し、以下のデータを初期化の指示として解釈させるために使用されるかどうかを示します。 |
| [toString()](#tostring) | この `DotCodeExtendedParameters` の人間が読みやすい文字列表現を返します。 |

### equals(obj) {#equals}

このインスタンスが指定された `DotCodeExtendedParameters` の値と等しいかどうかを示す値を返します。

| パラメータ | 説明 |
| --- | --- |
| obj | このインスタンスと比較するための System.Object の値です。 |

**Returns:** `true ` if obj has the same value as this instance; otherwise, `false `.

### getDotCodeIsReaderInitialization() {#getdotcodeisreaderinitialization}

> **Deprecated.** See method description for replacement.

コードがバーコードリーダーに対し、以下のデータを初期化または再プログラミングの指示として解釈させるために使用されるかどうかを示します。デフォルト値は false です。

### getDotCodeStructuredAppendModeBarcodeId() {#getdotcodestructuredappendmodebarcodeid}

> **Deprecated.** See method description for replacement.

DotCode 構造化付加モードバーコードの ID を取得します。ID は 1 から開始し、バーコードの数以下である必要があります。デフォルト値は -1 です。値: DotCode 構造化付加モードバーコードの ID。

### getDotCodeStructuredAppendModeBarcodesCount() {#getdotcodestructuredappendmodebarcodescount}

> **Deprecated.** See method description for replacement.

DotCode 構造化付加モードのバーコード数を取得します。デフォルト値は -1 です。カウントは 1 から 35 の値である必要があります。値: DotCode 構造化付加モードバーコードの数。

### getStructuredAppendModeBarcodeId() {#getstructuredappendmodebarcodeid}

DotCode 構造化付加モードバーコードの ID を取得します。ID は 1 から開始し、バーコードの数以下である必要があります。デフォルト値は -1 です。値: DotCode 構造化付加モードバーコードの ID。

**Returns:** the ID of the DotCode structured append mode barcode.

### getStructuredAppendModeBarcodesCount() {#getstructuredappendmodebarcodescount}

DotCode 構造化付加モードのバーコード数を取得します。デフォルト値は -1 です。カウントは 1 から 35 の値である必要があります。値: DotCode 構造化付加モードバーコードの数。

**Returns:** the DotCode structured append mode barcodes count.

### hashCode() {#hashcode}

このインスタンスのハッシュコードを返します。

**Returns:** A 32-bit signed integer hash code.

### isReaderInitialization() {#isreaderinitialization}

コードがバーコードリーダーに対し、以下のデータを初期化または再プログラミングの指示として解釈させるために使用されるかどうかを示します。デフォルト値は false です。

### toString() {#tostring}

この `DotCodeExtendedParameters` の人間が読みやすい文字列表現を返します。

**Returns:** A string that represents this `DotCodeExtendedParameters`.
