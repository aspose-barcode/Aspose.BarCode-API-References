---
title: "HIBCLICPrimaryDataCodetext"
linktitle: "HIBCLICPrimaryDataCodetext"
second_title: "Aspose.BarCode for Node.js via Java API リファレンス"
description: "一次データを格納する HIBC LIC コードに埋め込まれたテキストのエンコードとデコードを行うクラスです。"
type: docs
weight: 460
url: /ja/nodejs/aspose.barcode/hibclicprimarydatacodetext/
---

## HIBCLICPrimaryDataCodetext class

一次データを格納する HIBC LIC コードに埋め込まれたテキストのエンコードとデコードを行うクラスです。このサンプルは HIBCLICPrimaryCodetext を使用して HIBC LIC をエンコードおよびデコードする方法を示しています。

```js
new HIBCLICPrimaryDataCodetext()
```

**Example:**

```js
let complexCodetext  = new HIBCLICPrimaryCodetext();
complexCodetext.setBarcodeType(EncodeTypes.HIBCQRLIC);
complexCodetext.setData(new PrimaryData());
complexCodetext.getData().setProductOrCatalogNumber("12345");
complexCodetext.getData().setLabelerIdentificationCode("A999");
complexCodetext.getData().setUnitOfMeasureID(1);
let generator = new ComplexBarcodeGenerator(complexCodetext);
let image = generator.generateBarCodeImage(BarCodeImageFormat.PNG);
let reader = new BarCodeReader(image, null, DecodeType.HIBCQRLIC);
reader.readBarCodes();
let codetext = reader.getFoundBarCodes()[0].getCodeText();
let result = ComplexCodetextReader.tryDecodeHIBCLIC(codetext) ;
print("Product or catalog number: " + result.getData().getProductOrCatalogNumber());
print("Labeler identification code: " + result.getData().getLabelerIdentificationCode());
print("Unit of measure ID: " + result.getData().getUnitOfMeasureID());
```

## メソッド

| 名前 | 説明 |
| --- | --- |
| [equals(obj)](#equals) | このインスタンスが指定された `HIBCLICPrimaryDataCodetext` 値と等しいかどうかを示す値を返します。 |
| [getConstructedCodetext()](#getconstructedcodetext) | codetext を構築します |
| [getData()](#getdata) | 一次データを識別します。 |
| [hashCode()](#hashcode) | このインスタンスのハッシュコードを返します。 |
| [initFromString(constructedCodetext)](#initfromstring) | 構築された codetext からインスタンスを初期化します。 |
| [setData()](#setdata) | 一次データを識別します。 |

### equals(obj) {#equals}

このインスタンスが指定された `HIBCLICPrimaryDataCodetext` 値と等しいかどうかを示す値を返します。

| パラメータ | 説明 |
| --- | --- |
| obj | このインスタンスと比較するための `HIBCLICPrimaryDataCodetext` 値です。 |

**Returns:** `true ` if obj has the same value as this instance; otherwise, `false `.

### getConstructedCodetext() {#getconstructedcodetext}

codetext を構築します

**Returns:** Constructed codetext

### getData() {#getdata}

一次データを識別します。

### hashCode() {#hashcode}

このインスタンスのハッシュコードを返します。

**Returns:** A 32-bit signed integer hash code.

### initFromString(constructedCodetext) {#initfromstring}

構築された codetext からインスタンスを初期化します。

| パラメータ | 説明 |
| --- | --- |
| constructedCodetext | 構築された codetext。 |

### setData() {#setdata}

一次データを識別します。
