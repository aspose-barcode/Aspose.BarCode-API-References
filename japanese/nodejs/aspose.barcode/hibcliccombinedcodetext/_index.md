---
title: "HIBCLICCombinedCodetext"
linktitle: "HIBCLICCombinedCodetext"
second_title: "Aspose.BarCode for Node.js via Java API リファレンス"
description: "一次データと二次データを格納する HIBC LIC コードに埋め込まれたテキストをエンコードおよびデコードするクラスです。"
type: docs
weight: 440
url: /ja/nodejs/aspose.barcode/hibcliccombinedcodetext/
---

## HIBCLICCombinedCodetext class

一次データと二次データを格納する HIBC LIC コードに埋め込まれたテキストをエンコードおよびデコードするクラスです。このサンプルは HIBCLICCombinedCodetext を使用して HIBC LIC をエンコードおよびデコードする方法を示しています。

```js
new HIBCLICCombinedCodetext()
```

**Example:**

```js
let combinedCodetext = new HIBCLICCombinedCodetext();
combinedCodetext.setBarcodeType(EncodeTypes.HIBCQRLIC);
combinedCodetext.setPrimaryData(new PrimaryData());
combinedCodetext.getPrimaryData().setProductOrCatalogNumber("12345");
combinedCodetext.getPrimaryData().setLabelerIdentificationCode("A999");
combinedCodetext.getPrimaryData().setUnitOfMeasureID(1);
combinedCodetext.setSecondaryAndAdditionalData(new SecondaryAndAdditionalData());
combinedCodetext.getSecondaryAndAdditionalData().setExpiryDate(new Date());
combinedCodetext.getSecondaryAndAdditionalData().setExpiryDateFormat(HIBCLICDateFormat.MMDDYY);
combinedCodetext.getSecondaryAndAdditionalData().setQuantity(30);
combinedCodetext.getSecondaryAndAdditionalData().setLotNumber("LOT123");
combinedCodetext.getSecondaryAndAdditionalData().setSerialNumber("SERIAL123");
combinedCodetext.getSecondaryAndAdditionalData().setDateOfManufacture(new Date());
ComplexBarcodeGenerator generator = new ComplexBarcodeGenerator(combinedCodetext);
let image = generator.generateBarCodeImage(BarCodeImageFormat.PNG);
let reader = new BarCodeReader(image, null, DecodeType.HIBCQRLIC);
reader.readBarCodes();
let codetext = reader.getFoundBarCodes()[0].getCodeText();
let result = ComplexCodetextReader.tryDecodeHIBCLIC(codetext) ;
print("Product or catalog number: " + result.getPrimaryData().getProductOrCatalogNumber());
print("Labeler identification code: " + result.getPrimaryData().getLabelerIdentificationCode());
print("Unit of measure ID: " + result.getPrimaryData().getUnitOfMeasureID());
print("Expiry date: " + result.getSecondaryAndAdditionalData().getExpiryDate());
print("Quantity: " + result.getSecondaryAndAdditionalData().getQuantity());
print("Lot number: " + result.getSecondaryAndAdditionalData().getLotNumber());
print("Serial number: " + result.getSecondaryAndAdditionalData().getSerialNumber());
print("Date of manufacture: " + result.getSecondaryAndAdditionalData().getDateOfManufacture());
```

## メソッド

| 名前 | 説明 |
| --- | --- |
| [equals(obj)](#equals) | このインスタンスが指定された `HIBCLICCombinedCodetext` 値と等しいかどうかを示す値を返します。 |
| [getConstructedCodetext()](#getconstructedcodetext) | codetext を構築します |
| [getPrimaryData()](#getprimarydata) | 一次データを識別します。 |
| [getSecondaryAndAdditionalData()](#getsecondaryandadditionaldata) | 二次データおよび追加の補足データを識別します。 |
| [hashCode()](#hashcode) | このインスタンスのハッシュコードを返します。 |
| [initFromString(constructedCodetext)](#initfromstring) | 構築された codetext からインスタンスを初期化します。 |
| [setPrimaryData()](#setprimarydata) | 一次データを識別します。 |
| [setSecondaryAndAdditionalData()](#setsecondaryandadditionaldata) | 二次データおよび追加の補足データを識別します。 |

### equals(obj) {#equals}

このインスタンスが指定された `HIBCLICCombinedCodetext` 値と等しいかどうかを示す値を返します。

| パラメータ | 説明 |
| --- | --- |
| obj | このインスタンスと比較するための `HIBCLICCombinedCodetext` 値です。 |

**Returns:** `true ` if obj has the same value as this instance; otherwise, `false `.

### getConstructedCodetext() {#getconstructedcodetext}

codetext を構築します

**Returns:** Constructed codetext

### getPrimaryData() {#getprimarydata}

一次データを識別します。

### getSecondaryAndAdditionalData() {#getsecondaryandadditionaldata}

二次データおよび追加の補足データを識別します。

### hashCode() {#hashcode}

このインスタンスのハッシュコードを返します。

**Returns:** A 32-bit signed integer hash code.

### initFromString(constructedCodetext) {#initfromstring}

構築された codetext からインスタンスを初期化します。

| パラメータ | 説明 |
| --- | --- |
| constructedCodetext | 構築された codetext。 |

### setPrimaryData() {#setprimarydata}

一次データを識別します。

### setSecondaryAndAdditionalData() {#setsecondaryandadditionaldata}

二次データおよび追加の補足データを識別します。
