---
title: "MaxiCodeCodetextMode3"
linktitle: "MaxiCodeCodetextMode3"
second_title: "Aspose.BarCode for Node.js via Java API リファレンス"
description: "モード 3 用の MaxiCode コードに埋め込まれたテキストをエンコードおよびデコードするクラス。"
type: docs
weight: 620
url: /ja/nodejs/aspose.barcode/maxicodecodetextmode3/
---

## MaxiCodeCodetextMode3 class

モード3のMaxiCodeコードに埋め込まれたテキストをエンコードおよびデコードするためのクラスです。このサンプルは、モード3のMaxiCodeコードテキストをエンコードおよびデコードする方法を示しています。

```js
new MaxiCodeCodetextMode3()
```

**Example:**

```js
//Mode 3 with standart second message
 let maxiCodeCodetext = new MaxiCodeCodetextMode3();
 maxiCodeCodetext.setPostalCode("B1050");
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
