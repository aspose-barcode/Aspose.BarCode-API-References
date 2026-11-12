---
title: "MaxiCodeSecondMessage"
linktitle: "MaxiCodeSecondMessage"
second_title: "Aspose.BarCode for Node.js via Java API リファレンス"
description: "モード 4、5、6 用の MaxiCode コードテキストをエンコードおよびデコードするクラスです。"
type: docs
weight: 660
url: /ja/nodejs/aspose.barcode/maxicodesecondmessage/
---

## MaxiCodeSecondMessage class

モード 4、5、6 用の MaxiCode コードテキストをエンコードおよびデコードするクラスです。

```js
new MaxiCodeSecondMessage()
```

**Example:**

```js
//Mode 4
let maxiCodeCodetext = new MaxiCodeStandardCodetext();
maxiCodeCodetext.setMode(MaxiCodeMode.MODE_4);
maxiCodeCodetext.setMessage("Test message");
let complexGenerator = new ComplexBarcodeGenerator(maxiCodeCodetext.getConstructedCodetext());
complexGenerator.generateBarCodeImage(BarcodeImageFormat.PNG);
```
