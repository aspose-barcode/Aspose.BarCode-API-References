---
title: "BarCodeResult"
linktitle: "BarCodeResult"
second_title: "Aspose.BarCode for Node.js via Java API リファレンス"
description: "認識されたバーコードデータを保存します。例: SingleDecodeType 型、`string` codetext、BarCodeRegionParameters region、その他のパラメーター"
type: docs
weight: 110
url: /ja/nodejs/aspose.barcode/barcoderesult/
---

## BarCodeResult class

認識されたバーコードデータを保存します。例: SingleDecodeType 型、`string` codetext、BarCodeRegionParameters region、その他のパラメーター

```js
new BarCodeResult()
```

**Example:**

```js
//This sample shows how to obtain BarCodeResult.
let generator = new BarcodeGenerator(EncodeTypes.Code128, "12345");
generator.save("test.png");
let reader = new BarCodeReader("test.png", null,  [ DecodeType.CODE_39, DecodeType.CODE_128 ]);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
   let result = results[i];
    console.log("BarCode Type: " + result.getCodeTypeName());
    console.log("BarCode CodeText: " + result.getCodeText());
    console.log("BarCode Confidence: " + result.getConfidence());
    console.log("BarCode ReadingQuality: " + result.getReadingQuality());
    console.log("BarCode Angle: " + result.getRegion().getAngle());
}
```

## メソッド

| 名前 | 説明 |
| --- | --- |
| [deepClone()](#deepclone) | BarCodeResult クラスのコピーを作成します。 |
| [equals(other)](#equals) | このインスタンスが指定された BarCodeResult の値と等しいかどうかを示す値を返します。 |
| [getCodeBytes()](#getcodebytes) | エンコードされたコードバイトを取得します。値: バーコードのコードバイト |
| [getCodeText(encoding)](#getcodetext) | エンコーディングされたコードテキストを取得します。この例は `getCodeText` の使用方法を示しています: let gen = new BarcodeGenerator(EncodeType |
| [getCodeType()](#getcodetype) | バーコードのタイプを取得します。値: 認識されたバーコードのタイプ情報 |
| [getCodeTypeName()](#getcodetypename) | バーコードタイプの名前を取得します。値: 認識されたバーコードのタイプ名 |
| [getConfidence()](#getconfidence) | 認識されたバーコードの信頼度レベルを取得します。値: BarCodeConfidence.Strong は偽造や誤認識がありません。 |
| [getExtended()](#getextended) | 認識されたバーコードの拡張パラメーターを取得します。値: 認識されたバーコードの拡張パラメーター |
| [getReadingQuality()](#getreadingquality) | 読み取り品質を取得します。1D および郵便バーコードで機能します。値: 読み取り品質のパーセンテージ |
| [getRegion()](#getregion) | バーコードの領域を取得します。値: 認識されたバーコードの領域 |
| [hashCode()](#hashcode) | このインスタンスのハッシュコードを返します。 |
| [toString()](#tostring) | この BarCodeResult の人間が読みやすい文字列表現を返します。 |

### deepClone() {#deepclone}

BarCodeResult クラスのコピーを作成します。

**Returns:** Returns copy of BarCodeResult class.

### equals(other) {#equals}

このインスタンスが指定された BarCodeResult の値と等しいかどうかを示す値を返します。

| パラメータ | 説明 |
| --- | --- |
| その他 | このインスタンスと比較するための BarCodeResult 値。 |

**Returns:** true if obj has the same value as this instance; otherwise, false.

### getCodeBytes() {#getcodebytes}

エンコードされたコードバイトを取得します。値: バーコードのコードバイト

### getCodeText(encoding) {#getcodetext}

エンコーディングされたコードテキストを取得します。この例は `getCodeText` の使用方法を示しています: let gen = new BarcodeGenerator(EncodeTypes.DATA_MATRIX, null); gen.setCodeText("車種名", "932"); gen.save("barcode.png", BarCodeImageFormat.PNG); let reader = new BarCodeReader("barcode.png", null, DecodeType.DATA_MATRIX); let results = reader.readBarCodes(); for(let i = 0; i < results.length; i++) { let result = results[i]; console.log("BarCode CodeText: " + result.getCodeText("932")); }

| パラメータ | 説明 |
| --- | --- |
| エンコーディング | codetext のエンコーディング。 |

**Returns:** A string containing recognized code text.

### getCodeType() {#getcodetype}

バーコードのタイプを取得します。値: 認識されたバーコードのタイプ情報

### getCodeTypeName() {#getcodetypename}

バーコードタイプの名前を取得します。値: 認識されたバーコードのタイプ名

### getConfidence() {#getconfidence}

認識されたバーコードの信頼度レベルを取得します。値: BarCodeConfidence.Strong は偽造や誤認識がありません。BarCodeConfidence.Moderate は、チェックサムが弱い、またはなしのバーコードの場合、偽造や誤った codetext が時々発生する可能性があります。BarCodeConfidence.NONE は常に誤った codetext を持ち、偽の認識である可能性があります。

### getExtended() {#getextended}

認識されたバーコードの拡張パラメーターを取得します。値: 認識されたバーコードの拡張パラメーター

### getReadingQuality() {#getreadingquality}

読み取り品質を取得します。1D および郵便バーコードで機能します。値: 読み取り品質のパーセンテージ

### getRegion() {#getregion}

バーコードの領域を取得します。値: 認識されたバーコードの領域

### hashCode() {#hashcode}

このインスタンスのハッシュコードを返します。

**Returns:** A 32-bit signed integer hash code.

### toString() {#tostring}

この BarCodeResult の人間が読みやすい文字列表現を返します。

**Returns:** A string that represents this BarCodeResult.
