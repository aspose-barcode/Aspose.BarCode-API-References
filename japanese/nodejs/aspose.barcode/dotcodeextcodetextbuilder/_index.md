---
title: "DotCodeExtCodetextBuilder"
linktitle: "DotCodeExtCodetextBuilder"
second_title: "Aspose.BarCode for Node.js via Java API リファレンス"
description: "Extended codetext ジェネレータは 2D DotCode バーコード用で、DotCodeEncodeMode の ExtendedCodetext モードに使用されます"
type: docs
weight: 370
url: /ja/nodejs/aspose.barcode/dotcodeextcodetextbuilder/
---

## DotCodeExtCodetextBuilder class

Extended codetext ジェネレータは 2D DotCode バーコード用で、DotCodeEncodeMode の ExtendedCodetext モードに使用されます

```js
new DotCodeExtCodetextBuilder()
```

**Example:**

```js
//Extended codetext mode
//create codetext
let textBuilder = new DotCodeExtCodetextBuilder();
textBuilder.addFNC1FormatIdentifier();
textBuilder.addECICodetext(ECIEncodings.Win1251, "Will");
textBuilder.addFNC1FormatIdentifier();
textBuilder.addECICodetext(ECIEncodings.UTF8, "犬Right狗");
textBuilder.addFNC1FormatIdentifier();
textBuilder.addECICodetext(ECIEncodings.UTF16BE, "犬Power狗");
textBuilder.addPlainCodetext("Plain text");
textBuilder.addFNC3SymbolSeparator();
textBuilder.addFNC3ReaderInitialization();
textBuilder.addPlainCodetext("Reader initialization info");
//generate codetext
let codetext = textBuilder.getExtendedCodetext();
//generate
let generator = new BarcodeGenerator(EncodeTypes.DOT_CODE, codetext);
generator.getParameters().getBarcode().getDotCode().setDotCodeEncodeMode(DotCodeEncodeMode.EXTENDED_CODETEXT);
generator.save("test.bmp", BarCodeImageFormat.BMP);
```

## メソッド

| 名前 | 説明 |
| --- | --- |
| [addFNC1FormatIdentifier()](#addfnc1formatidentifier) | 拡張コードテキスト項目に FNC1 フォーマット識別子を追加します。 |
| [addFNC3ReaderInitialization()](#addfnc3readerinitialization) | 拡張コードテキスト項目に FNC3 リーダー初期化を追加します。 |
| [addFNC3SymbolSeparator()](#addfnc3symbolseparator) | 拡張コードテキスト項目に FNC3 シンボル区切りを追加します。 |
| [addStructuredAppendMode(barcodeId, barcodesCount)](#addstructuredappendmode) | 拡張コードテキスト項目に構造化付加モードを追加します。 |
| [getExtendedCodetext()](#getextendedcodetext) | 拡張コードテキストリストから拡張コードテキストを生成します。 |

### addFNC1FormatIdentifier() {#addfnc1formatidentifier}

拡張コードテキスト項目に FNC1 フォーマット識別子を追加します。

### addFNC3ReaderInitialization() {#addfnc3readerinitialization}

拡張コードテキスト項目に FNC3 リーダー初期化を追加します。

### addFNC3SymbolSeparator() {#addfnc3symbolseparator}

拡張コードテキスト項目に FNC3 シンボル区切りを追加します。

### addStructuredAppendMode(barcodeId, barcodesCount) {#addstructuredappendmode}

拡張コードテキスト項目に構造化付加モードを追加します。

| パラメータ | 説明 |
| --- | --- |
| barcodeId | バーコードの ID |
| barcodesCount | バーコード数 |

### getExtendedCodetext() {#getextendedcodetext}

拡張コードテキストリストから拡張コードテキストを生成します。

**Returns:** Extended codetext as string
