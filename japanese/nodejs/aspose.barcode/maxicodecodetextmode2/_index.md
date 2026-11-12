---
title: "MaxiCodeCodetextMode2"
linktitle: "MaxiCodeCodetextMode2"
second_title: "Aspose.BarCode for Node.js via Java API リファレンス"
description: "モード 2 用の MaxiCode コードに埋め込まれたテキストをエンコードおよびデコードするクラス。"
type: docs
weight: 610
url: /ja/nodejs/aspose.barcode/maxicodecodetextmode2/
---

## MaxiCodeCodetextMode2 class

モード 2 用の MaxiCode コードに埋め込まれたテキストをエンコードおよびデコードするクラス。

```js
new MaxiCodeCodetextMode2()
```

**Example:**

```js
This sample shows how to encode and decode MaxiCode codetext for mode 2.
 //Mode 2 with standart second message
 let maxiCodeCodetext = new MaxiCodeCodetextMode2();
 maxiCodeCodetext.setPostalCode("524032140");
 maxiCodeCodetext.setCountryCode(056);
 maxiCodeCodetext.setServiceCategory(999);
 let MaxiCodeStandardSecondMessage = new MaxiCodeStandardSecondMessage();
 MaxiCodeStandardSecondMessage.setMessage("Test message");
 maxiCodeCodetext.setSecondMessage(MaxiCodeStandardSecondMessage);
 let complexGenerator = new ComplexBarcodeGenerator(maxiCodeCodetext);
 complexGenerator.generateBarCodeImage(BarcodeImageFormat.PNG);
```

## メソッド

| 名前 | 説明 |
| --- | --- |
| [getMode()](#getmode) | MaxiCodeモードを取得します。 |

### getMode() {#getmode}

MaxiCodeモードを取得します。

**Returns:** MaxiCode mode
