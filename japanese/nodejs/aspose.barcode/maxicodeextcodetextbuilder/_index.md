---
title: "MaxiCodeExtCodetextBuilder"
linktitle: "MaxiCodeExtCodetextBuilder"
second_title: "Aspose.BarCode for Node.js via Java API リファレンス"
description: "MaxiCodeEncodeMode の ExtendedCodetext モードで MaxiCode バーコード用の拡張コードテキストジェネレータ。BarcodeGenerator の TwoDDisplayText プロパティを使用して表示テキストを設定します"
type: docs
weight: 630
url: /ja/nodejs/aspose.barcode/maxicodeextcodetextbuilder/
---

## MaxiCodeExtCodetextBuilder class

MaxiCodeEncodeMode の ExtendedCodetext モードで MaxiCode バーコード用の拡張コードテキストジェネレータ。BarcodeGenerator の TwoDDisplayText プロパティを使用して、管理文字を除去した表示テキストを設定します。このサンプルは、Extended モードで MaxiCodeExtCodetextBuilder を使用する方法を示しています。

```js
new MaxiCodeExtCodetextBuilder()
```

**Example:**

```js
//create codetext
let textBuilder = new MaxiCodeExtCodetextBuilder();
textBuilder.addECICodetext(ECIEncodings.Win1251, "Will");
textBuilder.addECICodetext(ECIEncodings.UTF8, "犬Right狗");
textBuilder.addECICodetext(ECIEncodings.UTF16BE, "犬Power狗");
textBuilder.addPlainCodetext("Plain text");

//generate codetext
let codetext = textBuilder.getExtendedCodetext();

//generate
let generator = new BarcodeGenerator(EncodeTypes.MAXI_CODE, codetext);
generator.getParameters().getBarcode().getCodeTextParameters().setTwoDDisplayText("My Text");
generator.save("test.bmp", BarcodeImageFormat.BMP);
```

## メソッド

| 名前 | 説明 |
| --- | --- |
| [getExtendedCodetext()](#getextendedcodetext) | 拡張コードテキストリストから拡張コードテキストを生成します。 |

### getExtendedCodetext() {#getextendedcodetext}

拡張コードテキストリストから拡張コードテキストを生成します。

**Returns:** Extended codetext as string
