---
title: "AztecExtendedParameters"
linktitle: "AztecExtendedParameters"
second_title: "Aspose.BarCode for Node.js via Java API リファレンス"
description: "Aztec 認識バーコードの特殊データを格納します。このサンプルは Aztec の生データを取得する方法を示します。let generator = new BarcodeGenerator(EncodeTypes.AZTEC, \"12345\"); "
type: docs
weight: 60
url: /ja/nodejs/aspose.barcode/aztecextendedparameters/
---

## AztecExtendedParameters class

Aztec 認識バーコードの特殊データを格納します。このサンプルは Aztec の生データを取得する方法を示します。let generator = new BarcodeGenerator(EncodeTypes.AZTEC, "12345"); generator.save("test.png", BarcodeImageFormat.PNG);

```js
new AztecExtendedParameters()
```

**Example:**

```js
BarCodeReader reader = new BarCodeReader("test.png", null, DecodeType.AZTEC);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
    let result = results[i];
    console.log("BarCode type: " + result.getCodeTypeName());
    console.log("BarCode codetext: " + result.getCodeText());
    console.log("Aztec barcode ID: " + result.getExtended().getAztec().getStructuredAppendBarcodeId());
    console.log("Aztec barcodes count: " + result.getExtended().getAztec().getStructuredAppendBarcodesCount());
    console.log("Aztec file ID: " + result.getExtended().getAztec().getStructuredAppendFileId());
    console.log("Aztec is reader initialization: " + result.getExtended().getAztec().isReaderInitialization());
}
</pre>
</pre></blockquote></hr></p>
```

## メソッド

| 名前 | 説明 |
| --- | --- |
| [equals(obj)](#equals) | `AztecExtendedParameters` の指定された値とこのインスタンスが等しいかどうかを示す値を返します。 |
| [getStructuredAppendBarcodeId()](#getstructuredappendbarcodeid) | Aztec 構造化付加モードバーコードの ID を取得します。ID は 1 から始まり、バーコード数以下である必要があります。D |
| [getStructuredAppendBarcodesCount()](#getstructuredappendbarcodescount) | Aztec 構造化付加モードのバーコード数を取得します。デフォルト値は 0 です。カウントは 1 から 26 の範囲である必要があります。Value: The |
| [getStructuredAppendFileId()](#getstructuredappendfileid) | Aztec 構造化付加モードのファイル ID を取得します。デフォルト値は空文字列です。Value: The File ID of the Aztec stru |
| [hashCode()](#hashcode) | このインスタンスのハッシュコードを返します。 |
| [isReaderInitialization()](#isreaderinitialization) | コードがリーダーに対し、以下のデータを初期化の指示として解釈させるために使用されるかどうかを示します。 |
| [toString()](#tostring) | この `AztecExtendedParameters` の人間が読みやすい文字列表現を返します。 |

### equals(obj) {#equals}

`AztecExtendedParameters` の指定された値とこのインスタンスが等しいかどうかを示す値を返します。

| パラメータ | 説明 |
| --- | --- |
| obj | このインスタンスと比較するための System.Object の値です。 |

**Returns:** `true ` if obj has the same value as this instance; otherwise, `false `.

### getStructuredAppendBarcodeId() {#getstructuredappendbarcodeid}

Aztec 構造化付加モードバーコードの ID を取得します。ID は 1 から始まり、バーコード数以下である必要があります。デフォルト値は 0 です。Value: The barcode ID of the Aztec structured append mode.

### getStructuredAppendBarcodesCount() {#getstructuredappendbarcodescount}

Aztec 構造化付加モードのバーコード数を取得します。デフォルト値は 0 です。カウントは 1 から 26 の範囲である必要があります。Value: The barcodes count of the Aztec structured append mode.

### getStructuredAppendFileId() {#getstructuredappendfileid}

Aztec 構造化付加モードのファイル ID を取得します。デフォルト値は空文字列です。Value: The File ID of the Aztec structured append mode.

### hashCode() {#hashcode}

このインスタンスのハッシュコードを返します。

**Returns:** 32-bit signed integer hash code.

### isReaderInitialization() {#isreaderinitialization}

コードがバーコードリーダーに対し、以下のデータを初期化または再プログラミングの指示として解釈させるために使用されるかどうかを示します。デフォルト値は false です。

### toString() {#tostring}

この `AztecExtendedParameters` の人間が読みやすい文字列表現を返します。

**Returns:** A string that represents this `AztecExtendedParameters`.
