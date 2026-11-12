---
title: "HIBCLICComplexCodetext"
linktitle: "HIBCLICComplexCodetext"
second_title: "Aspose.BarCode for Node.js via Java API リファレンス"
description: "HIBC LIC コードに埋め込まれたテキストのエンコードとデコードを行う基底クラスです。"
type: docs
weight: 450
url: /ja/nodejs/aspose.barcode/hibcliccomplexcodetext/
---

## HIBCLICComplexCodetext class

HIBC LIC コードに埋め込まれたテキストのエンコードとデコードを行う基底クラスです。このサンプルは、生の HIBC LIC codetext を HIBCLICComplexCodetext インスタンスにデコードする方法を示しています。

```js
new HIBCLICComplexCodetext()
```

**Example:**

```js
let reader = new BarCodeReader("c:\\test.png", null, DecodeType.HIBC_AZTEC_LIC);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
    let result = results[i];
   let resultHIBCLICComplexCodetext = ComplexCodetextReader.tryDecodeHIBCLIC(result.getCodeText());
   print("BarCode Type: " + resultMaxiCodeCodetext.getBarcodeType());
   print("BarCode CodeText: " + resultMaxiCodeCodetext.getConstructedCodetext());
}
```

## メソッド

| 名前 | 説明 |
| --- | --- |
| [getBarcodeType()](#getbarcodetype) | バーコードのタイプを取得または設定します。HIBC LIC codetext は HIBCCode39LIC、HIBCCode128LIC、HIBCAztecLIC、HIBCDataM を使用してエンコードできます。 |
| [getConstructedCodetext()](#getconstructedcodetext) | codetext を構築します |
| [initFromString(constructedCodetext)](#initfromstring) | 構築された codetext からインスタンスを初期化します。 |
| [setBarcodeType()](#setbarcodetype) | バーコードのタイプを取得または設定します。HIBC LIC codetext は HIBCCode39LIC、HIBCCode128LIC、HIBCAztecLIC、HIBCDataM を使用してエンコードできます。 |

### getBarcodeType() {#getbarcodetype}

バーコードのタイプを取得または設定します。HIBC LIC codetext は HIBCCode39LIC、HIBCCode128LIC、HIBCAztecLIC、HIBCDataMatrixLIC、HIBCQRLIC のエンコードタイプを使用してエンコードできます。デフォルト値: HIBCCode39LIC。

**Returns:** Barcode type.

### getConstructedCodetext() {#getconstructedcodetext}

codetext を構築します

**Returns:** Constructed codetext

### initFromString(constructedCodetext) {#initfromstring}

構築された codetext からインスタンスを初期化します。

| パラメータ | 説明 |
| --- | --- |
| constructedCodetext | 構築された codetext。 |

### setBarcodeType() {#setbarcodetype}

バーコードのタイプを取得または設定します。HIBC LIC codetext は HIBCCode39LIC、HIBCCode128LIC、HIBCAztecLIC、HIBCDataMatrixLIC、HIBCQRLIC のエンコードタイプを使用してエンコードできます。デフォルト値: HIBCCode39LIC。

**Returns:** Barcode type.
