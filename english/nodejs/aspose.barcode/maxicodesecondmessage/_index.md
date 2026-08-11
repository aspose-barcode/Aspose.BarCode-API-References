---
title: "MaxiCodeSecondMessage"
linktitle: "MaxiCodeSecondMessage"
second_title: "Aspose.BarCode for Node.js via Java API Reference"
description: "Class for encoding and decoding MaxiCode codetext for modes 4, 5 and 6."
type: docs
weight: 660
url: /nodejs/aspose.barcode/maxicodesecondmessage/
---

## MaxiCodeSecondMessage class

Class for encoding and decoding MaxiCode codetext for modes 4, 5 and 6.

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
