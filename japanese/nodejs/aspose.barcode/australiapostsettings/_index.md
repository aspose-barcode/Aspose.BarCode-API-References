---
title: "AustraliaPostSettings"
linktitle: "AustraliaPostSettings"
second_title: "Aspose.BarCode for Node.js via Java API リファレンス"
description: "AustraliaPost のデコードパラメータ。"
type: docs
weight: 30
url: /ja/nodejs/aspose.barcode/australiapostsettings/
---

## AustraliaPostSettings class

AustraliaPost のデコードパラメータです。AustraliaPost シンボロジーの認識データに影響を与えるパラメータを含みます。

```js
new AustraliaPostSettings()
```

AustraliaPostSettings コンストラクタ

## メソッド

| 名前 | 説明 |
| --- | --- |
| [getCustomerInformationInterpretingType()](#getcustomerinformationinterpretingtype) | AustralianPost BarCode の顧客情報の解釈タイプを取得します。DEFAULT は CustomerInformationInterpre です。 |
| [getIgnoreEndingFillingPatternsForCTable()](#getignoreendingfillingpatternsforctable) | デコード中に顧客情報フィールドの最後のフィリングパターンを無視するように AustraliaPost デコーダを強制するフラグ |
| [setCustomerInformationInterpretingType(value)](#setcustomerinformationinterpretingtype) | AustralianPost BarCode の顧客情報の解釈タイプを設定します。DEFAULT は CustomerInformationInterpre です。 |
| [setIgnoreEndingFillingPatternsForCTable()](#setignoreendingfillingpatternsforctable) | デコード中に顧客情報フィールドの最後のフィリングパターンを無視するように AustraliaPost デコーダを強制するフラグ |

### getCustomerInformationInterpretingType() {#getcustomerinformationinterpretingtype}

AustralianPost BarCode の顧客情報の解釈タイプを取得します。DEFAULT は CustomerInformationInterpretingType.OTHER です。

**Returns:** The interpreting type (CTable, NTable or Other) of customer information for AustralianPost BarCode

### getIgnoreEndingFillingPatternsForCTable() {#getignoreendingfillingpatternsforctable}

CTable メソッドとしてデコード中に顧客情報フィールドの最後のフィリングパターンを無視するように AustraliaPost デコーダを強制するフラグ。CTable エンコーディングメソッドはエンコーディングテーブルにギャップがなく、フィリングパターンのシーケンス "333" は文字 "z" としてデコードされます。

**Returns:** The flag which force AustraliaPost decoder to ignore last filling patterns during CTable method decoding

**Example:**

```js
let generator = new BarcodeGenerator(EncodeTypes.AUSTRALIA_POST, "5912345678AB");
generator.getParameters().getBarcode().getAustralianPost().setAustralianPostEncodingTable(CustomerInformationInterpretingType.C_TABLE);
let image = generator.generateBarCodeImage(BarcodeImageFormat.PNG);
let reader = new BarCodeReader(image, null, DecodeType.AUSTRALIA_POST);
reader.getBarcodeSettings().getAustraliaPost().setCustomerInformationInterpretingType(CustomerInformationInterpretingType.C_TABLE);
reader.getBarcodeSettings().getAustraliaPost().setIgnoreEndingFillingPatternsForCTable(true);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
    let result = results[i];
    console.log("BarCode Type: " + result.getCodeType());
    console.log("BarCode CodeText: " + result.getCodeText());
}
```

### setCustomerInformationInterpretingType(value) {#setcustomerinformationinterpretingtype}

AustralianPost BarCode の顧客情報の解釈タイプを設定します。DEFAULT は CustomerInformationInterpretingType.OTHER です。

| パラメータ | 説明 |
| --- | --- |
| 値 | AustralianPost BarCode の顧客情報の解釈タイプ（CTable、NTable、または Other） |

### setIgnoreEndingFillingPatternsForCTable() {#setignoreendingfillingpatternsforctable}

CTable メソッドとしてデコード中に顧客情報フィールドの最後のフィリングパターンを無視するように AustraliaPost デコーダを強制するフラグ。CTable エンコーディングメソッドはエンコーディングテーブルにギャップがなく、フィリングパターンのシーケンス "333" は文字 "z" としてデコードされます。

**Returns:** The flag which force AustraliaPost decoder to ignore last filling patterns during CTable method decoding

**Example:**

```js
let generator = new BarcodeGenerator(EncodeTypes.AUSTRALIA_POST, "5912345678AB");
generator.getParameters().getBarcode().getAustralianPost().setAustralianPostEncodingTable(CustomerInformationInterpretingType.C_TABLE);
let image = generator.generateBarCodeImage(BarcodeImageFormat.PNG);
let reader = new BarCodeReader(image, null, DecodeType.AUSTRALIA_POST);
reader.getBarcodeSettings().getAustraliaPost().setCustomerInformationInterpretingType(CustomerInformationInterpretingType.C_TABLE);
reader.getBarcodeSettings().getAustraliaPost().setIgnoreEndingFillingPatternsForCTable(true);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
    let result = results[i];
    console.log("BarCode Type: " + result.getCodeType());
    console.log("BarCode CodeText: " + result.getCodeText());
}
```
