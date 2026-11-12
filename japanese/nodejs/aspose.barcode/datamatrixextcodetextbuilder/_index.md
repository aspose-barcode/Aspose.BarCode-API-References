---
title: "DataMatrixExtCodetextBuilder"
linktitle: "DataMatrixExtCodetextBuilder"
second_title: "Aspose.BarCode for Node.js via Java API リファレンス"
description: "DataMatrixEncodeMode の ExtendedCodetext モード用の 2D DataMatrix バーコード向け拡張コードテキストジェネレータ //Extended codetext mode //create codetext let textBuil"
type: docs
weight: 340
url: /ja/nodejs/aspose.barcode/datamatrixextcodetextbuilder/
---

## DataMatrixExtCodetextBuilder class

DataMatrixEncodeMode の ExtendedCodetext モード用の 2D DataMatrix バーコード向け拡張コードテキストジェネレータ //Extended codetext mode //create codetext let textBuilder = new DataMatrixExtCodetextBuilder(); codetextBuilder.addECICodetextWithEncodeMode(ECIEncodings.Win1251, DataMatrixEncodeMode.BYTES, "World"); codetextBuilder.addPlainCodetext("Will"); codetextBuilder.addECICodetext(ECIEncodings.UTF_8, "犬Right狗"); codetextBuilder.addCodetextWithEncodeMode(DataMatrixEncodeMode.C_40, "ABCDE"); //generate codetext let codetext = textBuilder.getExtendedCodetext(); //generate let generator = new BarcodeGenerator(EncodeTypes.DATA_MATRIX, null, codetext); generator.getParameters().getBarcode().getDataMatrix().setDataMatrixEncodeMode(DataMatrixEncodeMode.EXTENDED_CODETEXT); generator.save("test.bmp", BarcodeImageFormat.BMP);

```js
new DataMatrixExtCodetextBuilder()
```

## メソッド

| 名前 | 説明 |
| --- | --- |
| [addCodetextWithEncodeMode(encodeMode, codetext)](#addcodetextwithencodemode) | 定義されたエンコードモードでコードテキストを拡張コードテキスト項目に追加します |
| [addECICodetextWithEncodeMode(ECIEncoding, encodeMode, codetext)](#addecicodetextwithencodemode) | 定義されたエンコードモードと拡張チャネル識別子でコードテキストを追加します |
| [getExtendedCodetext()](#getextendedcodetext) | 拡張コードテキストリストから拡張コードテキストを生成します。 |

### addCodetextWithEncodeMode(encodeMode, codetext) {#addcodetextwithencodemode}

定義されたエンコードモードでコードテキストを拡張コードテキスト項目に追加します

| パラメータ | 説明 |
| --- | --- |
| encodeMode | エンコードモードの値 |
| codetext | 拡張コードテキスト項目として追加する Unicode のコードテキスト |

### addECICodetextWithEncodeMode(ECIEncoding, encodeMode, codetext) {#addecicodetextwithencodemode}

定義されたエンコードモードと拡張チャネル識別子でコードテキストを追加します

| パラメータ | 説明 |
| --- | --- |
| ECIEncoding | 拡張チャネル識別子 |
| encodeMode | エンコードモードの値 |
| codetext | 定義されたエンコードモードと拡張チャネル識別子を使用して、拡張コードテキスト項目として追加する Unicode のコードテキスト |

### getExtendedCodetext() {#getextendedcodetext}

拡張コードテキストリストから拡張コードテキストを生成します。

**Returns:** Extended codetext as string
