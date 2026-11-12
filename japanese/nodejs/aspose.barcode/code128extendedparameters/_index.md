---
title: "Code128ExtendedParameters"
linktitle: "Code128ExtendedParameters"
second_title: "Aspose.BarCode for Node.js via Java API リファレンス"
description: "認識された Code128 バーコードの特別なデータを格納します。認識されたバーコードの領域とバーコードの角度を表します"
type: docs
weight: 240
url: /ja/nodejs/aspose.barcode/code128extendedparameters/
---

## Code128ExtendedParameters class

認識された Code128 バーコードの特別なデータを格納します。認識されたバーコードの領域とバーコードの角度を表します

```js
new Code128ExtendedParameters()
```

**Example:**

```js
//This sample shows how to get code128 raw values
let generator = new BarcodeGenerator(EncodeTypes.Code128, "12345");
generator.save("test.png");
let reader = new BarCodeReader("test.png", null,  DecodeType.CODE_128);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
   let result = results[i];
   console.log("BarCode Type: " + result.getCodeTypeName());
   console.log("BarCode CodeText: " + result.getCodeText());
   console.log("Code128 Data Portions: " + result.getExtended().getCode128());
}
```

## メソッド

| 名前 | 説明 |
| --- | --- |
| [equals(obj)](#equals) | このインスタンスが指定された Code128ExtendedParameters の値と等しいかどうかを示す値を返します。 |
| [getCode128DataPortions()](#getcode128dataportions) | 認識された Code128 バーコードの Code128DataPortion 配列を取得します。Code128DataPortion の値。 |
| [hashCode()](#hashcode) | このインスタンスのハッシュコードを返します。 |
| [toString()](#tostring) | この Code128ExtendedParameters の人間が読める文字列表現を返します。 |

### equals(obj) {#equals}

このインスタンスが指定された Code128ExtendedParameters の値と等しいかどうかを示す値を返します。

| パラメータ | 説明 |
| --- | --- |
| obj | このインスタンスと比較するための System.Object の値です。 |

**Returns:** true if obj has the same value as this instance; otherwise, false.

### getCode128DataPortions() {#getcode128dataportions}

認識された Code128 バーコードの Code128DataPortion 配列を取得します。Code128DataPortion の値。

### hashCode() {#hashcode}

このインスタンスのハッシュコードを返します。

**Returns:** A 32-bit signed integer hash code.

### toString() {#tostring}

この Code128ExtendedParameters の人間が読める文字列表現を返します。

**Returns:** A string that represents this Code128ExtendedParameters.
