---
title: "BarCodeRegionParameters"
linktitle: "BarCodeRegionParameters"
second_title: "Aspose.BarCode for Node.js via Java API リファレンス"
description: "認識されたバーコードの領域と角度を表します"
type: docs
weight: 100
url: /ja/nodejs/aspose.barcode/barcoderegionparameters/
---

## BarCodeRegionParameters class

認識されたバーコードの領域と角度を表します

```js
new BarCodeRegionParameters()
```

**Example:**

```js
//This sample shows how to get barcode Angle and bounding quadrangle values
let generator = new BarcodeGenerator(EncodeTypes.Code128, "12345");
generator.save("test.png");
let reader = new BarCodeReader("test.png", null,  [ DecodeType.CODE_39, DecodeType.CODE_128 ]);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
   let result = results[i];
   console.log("BarCode CodeText: " + result.getCodeText());
   console.log("BarCode Angle: " + result.getRegion().getAngle());
   console.log("BarCode Quadrangle: " + result.getRegion().getQuadrangle());
}
```

## メソッド

| 名前 | 説明 |
| --- | --- |
| [equals(obj)](#equals) | このインスタンスが指定された BarCodeRegionParameters 値と等しいかどうかを示す値を返します。 |
| [getAngle()](#getangle) | バーコードの角度 (0-360) を取得します。値: バーコードの角度 (0-360)。 |
| [getPoints()](#getpoints) | バーコード領域を囲む Points 配列を取得します 値: バーコード領域を囲む Points 配列を返します |
| [getQuadrangle()](#getquadrangle) | バーコード領域を囲む Quadrangle を取得します 値: バーコード領域を囲む Quadrangle を返します |
| [getRectangle()](#getrectangle) | バーコード領域を囲む Rectangle を取得します 値: バーコード領域を囲む Rectangle を返します |
| [hashCode()](#hashcode) | このインスタンスのハッシュコードを返します。 |
| [toString()](#tostring) | この BarCodeRegionParameters の人間が読みやすい文字列表現を返します。 |

### equals(obj) {#equals}

このインスタンスが指定された BarCodeRegionParameters 値と等しいかどうかを示す値を返します。

| パラメータ | 説明 |
| --- | --- |
| obj | このインスタンスと比較するための System.Object の値です。 |

**Returns:** true if obj has the same value as this instance; otherwise, false.

### getAngle() {#getangle}

バーコードの角度 (0-360) を取得します。値: バーコードの角度 (0-360)。

### getPoints() {#getpoints}

バーコード領域を囲む Points 配列を取得します 値: バーコード領域を囲む Points 配列を返します

### getQuadrangle() {#getquadrangle}

バーコード領域を囲む Quadrangle を取得します 値: バーコード領域を囲む Quadrangle を返します

### getRectangle() {#getrectangle}

バーコード領域を囲む Rectangle を取得します 値: バーコード領域を囲む Rectangle を返します

### hashCode() {#hashcode}

このインスタンスのハッシュコードを返します。

**Returns:** A 32-bit signed integer hash code.

### toString() {#tostring}

この BarCodeRegionParameters の人間が読みやすい文字列表現を返します。

**Returns:** A string that represents this BarCodeRegionParameters.
