---
title: "OneDExtendedParameters"
linktitle: "OneDExtendedParameters"
second_title: "Aspose.BarCode for Node.js via Java API リファレンス"
description: "認識された 1D バーコードの別個のコードテキストやチェックサムなどの特殊データを保存します。"
type: docs
weight: 720
url: /ja/nodejs/aspose.barcode/onedextendedparameters/
---

## OneDExtendedParameters class

認識された 1D バーコードの別個のコードテキストやチェックサムなどの特殊データを保存します。

```js
new OneDExtendedParameters()
```

**Example:**

```js
//This sample shows how to get 1D barcode value and checksum
let generator = new BarcodeGenerator(EncodeTypes.EAN_13, "1234567890128");
generator.save("test.png");
let reader = new BarCodeReader("test.png", null,  DecodeType.EAN_13);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
   let result = results[i];
   console.log("BarCode Type: " + result.getCodeTypeName());
   console.log("BarCode CodeText: " + result.getCodeText());
   console.log("BarCode Value: " + result.getExtended().getOneD().getValue());
   console.log("BarCode Checksum: " + result.getExtended().getOneD().getCheckSum());
}
```

## メソッド

| 名前 | 説明 |
| --- | --- |
| [equals(obj)](#equals) | このインスタンスが指定された OneDExtendedParameters 値と等しいかどうかを示す値を返します。 |
| [getCheckSum()](#getchecksum) | 1D バーコードのチェックサムを取得します。値: 1D バーコードのチェックサムです。 |
| [getValue()](#getvalue) | チェックサムなしの 1D バーコードのコードテキストを取得します。値: チェックサムなしの 1D バーコードのコードテキストです。 |
| [hashCode()](#hashcode) | このインスタンスのハッシュコードを返します。 |
| [isEmpty()](#isempty) | すべてのパラメーターがデフォルト値のみであるかテストします。値: すべてのパラメーターがデフォルト値のみの場合は `true ` を返します; o |
| [toString()](#tostring) | この OneDExtendedParameters の人間が読みやすい文字列表現を返します。 |

### equals(obj) {#equals}

このインスタンスが指定された OneDExtendedParameters 値と等しいかどうかを示す値を返します。

| パラメータ | 説明 |
| --- | --- |
| obj | このインスタンスと比較するための System.Object の値です。 |

**Returns:** true if obj has the same value as this instance; otherwise, false.

### getCheckSum() {#getchecksum}

1D バーコードのチェックサムを取得します。値: 1D バーコードのチェックサムです。

### getValue() {#getvalue}

チェックサムなしの 1D バーコードのコードテキストを取得します。値: チェックサムなしの 1D バーコードのコードテキストです。

### hashCode() {#hashcode}

このインスタンスのハッシュコードを返します。

**Returns:** A 32-bit signed integer hash code.

### isEmpty() {#isempty}

すべてのパラメーターがデフォルト値のみであるかテストします。値: すべてのパラメーターがデフォルト値のみの場合は `true ` を返し、そうでない場合は `false ` を返します。

### toString() {#tostring}

この OneDExtendedParameters の人間が読みやすい文字列表現を返します。

**Returns:** A string that represents this OneDExtendedParameters.
