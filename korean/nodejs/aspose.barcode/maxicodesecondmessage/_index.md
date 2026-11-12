---
title: "MaxiCodeSecondMessage"
linktitle: "MaxiCodeSecondMessage"
second_title: "Aspose.BarCode for Node.js via Java API 레퍼런스"
description: "모드 4, 5 및 6에 대한 MaxiCode 코드텍스트를 인코딩 및 디코딩하기 위한 클래스."
type: docs
weight: 660
url: /ko/nodejs/aspose.barcode/maxicodesecondmessage/
---

## MaxiCodeSecondMessage class

모드 4, 5 및 6에 대한 MaxiCode 코드텍스트를 인코딩 및 디코딩하기 위한 클래스.

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
