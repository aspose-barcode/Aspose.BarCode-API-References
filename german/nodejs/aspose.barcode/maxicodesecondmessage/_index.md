---
title: "MaxiCodeSecondMessage"
linktitle: "MaxiCodeSecondMessage"
second_title: "Aspose.BarCode für Node.js über Java API-Referenz"
description: "Klasse zum Kodieren und Dekodieren von MaxiCode-Codetext für die Modi 4, 5 und 6."
type: docs
weight: 660
url: /de/nodejs/aspose.barcode/maxicodesecondmessage/
---

## MaxiCodeSecondMessage class

Klasse zum Kodieren und Dekodieren von MaxiCode-Codetext für die Modi 4, 5 und 6.

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
