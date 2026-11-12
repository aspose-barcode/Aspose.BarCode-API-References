---
title: "AztecExtCodetextBuilder"
linktitle: "AztecExtCodetextBuilder"
second_title: "Aspose.BarCode for Node.js via Java API リファレンス"
description: "AztecEncodeMode の ExtendedCodetext モード用の Aztec バーコード向け拡張コードテキストジェネレータ。BarcodeGenerator の TwoDDisplayText プロパティを使用して表示テキストを設定します。"
type: docs
weight: 50
url: /ja/nodejs/aspose.barcode/aztecextcodetextbuilder/
---

## AztecExtCodetextBuilder class

AztecEncodeMode の ExtendedCodetext モード用の Aztec バーコード向け拡張コードテキストジェネレータ。BarcodeGenerator の TwoDDisplayText プロパティを使用して表示テキストを設定し、管理文字を除去します。このサンプルは Extended モードで AztecExtCodetextBuilder を使用する方法を示しています。

```js
new AztecExtCodetextBuilder()
```

**Example:**

```js
//create codetext
     let textBuilder = new AztecExtCodetextBuilder();
     textBuilder.addECICodetext(ECIEncodings.Win1251, "Will");
     textBuilder.addECICodetext(ECIEncodings.UTF8, "犬Right狗");
     textBuilder.addECICodetext(ECIEncodings.UTF16BE, "犬Power狗");
     textBuilder.addPlainCodetext("Plain text");
     //generate codetext
     let codetext = textBuilder.getExtendedCodetext();
     //generate
     let generator = new BarcodeGenerator(EncodeTypes.AZTEC, codetext);
     generator.getParameters().getBarcode().getCodeTextParameters().setwoDDisplayText("My Text");
     generator.save("test.bmp", BarcodeImageFormat.BMP);
```

## メソッド

| 名前 | 説明 |
| --- | --- |
| [getExtendedCodetext()](#getextendedcodetext) | 拡張コードテキストリストから拡張コードテキストを生成します。 |

### getExtendedCodetext() {#getextendedcodetext}

拡張コードテキストリストから拡張コードテキストを生成します。

**Returns:** Extended codetext as string
