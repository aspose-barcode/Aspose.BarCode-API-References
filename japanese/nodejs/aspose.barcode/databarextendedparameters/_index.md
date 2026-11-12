---
title: "DataBarExtendedParameters"
linktitle: "DataBarExtendedParameters"
second_title: "Aspose.BarCode for Node.js via Java API リファレンス"
description: "認識されたバーコードの DataBar 追加情報を格納します"
type: docs
weight: 310
url: /ja/nodejs/aspose.barcode/databarextendedparameters/
---

## DataBarExtendedParameters class

認識されたバーコードの DataBar 追加情報を格納します

```js
new DataBarExtendedParameters()
```

**Example:**

```js
let reader = new BarCodeReader("test.png", DecodeType.DATABAR_OMNI_DIRECTIONAL);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
   let result = results[i];
   console.log("BarCode Type: " + result.getCodeTypeName());
   console.log("BarCode CodeText: " + result.getCodeText());
   console.log("QR Structured Append Quantity: " + result.getExtended().getQR().getQRStructuredAppendModeBarCodesQuantity());
}
```

## メソッド

| 名前 | 説明 |
| --- | --- |
| [equals(obj)](#equals) | このインスタンスが指定された DataBarExtendedParameters の値と等しいかどうかを示す値を返します。 |
| [hashCode()](#hashcode) | このインスタンスのハッシュコードを返します。 |
| [is2DCompositeComponent()](#is2dcompositecomponent) | DataBar 2D 複合コンポーネントフラグを取得します。デフォルト値は false です。 |
| [toString()](#tostring) | このオブジェクトの人間が読める文字列表現を返します。 |

### equals(obj) {#equals}

このインスタンスが指定された DataBarExtendedParameters の値と等しいかどうかを示す値を返します。

| パラメータ | 説明 |
| --- | --- |
| obj | このインスタンスと比較する DataBarExtendedParameters の値。 |

**Returns:** true if obj has the same value as this instance; otherwise, false .

### hashCode() {#hashcode}

このインスタンスのハッシュコードを返します。

**Returns:** A 32-bit signed integer hash code.

### is2DCompositeComponent() {#is2dcompositecomponent}

DataBar 2D 複合コンポーネントフラグを取得します。デフォルト値は false です。

**Returns:** The DataBar 2D composite component flag.

### toString() {#tostring}

このオブジェクトの人間が読める文字列表現を返します。

**Returns:** A string that represents this .
