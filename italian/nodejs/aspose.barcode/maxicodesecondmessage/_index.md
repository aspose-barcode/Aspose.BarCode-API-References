---
title: "MaxiCodeSecondMessage"
linktitle: "MaxiCodeSecondMessage"
second_title: "Riferimento API di Aspose.BarCode per Node.js via Java"
description: "Classe per la codifica e decodifica del codetext MaxiCode per le modalità 4, 5 e 6."
type: docs
weight: 660
url: /it/nodejs/aspose.barcode/maxicodesecondmessage/
---

## MaxiCodeSecondMessage class

Classe per la codifica e decodifica del codetext MaxiCode per le modalità 4, 5 e 6.

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
