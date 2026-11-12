---
title: "MaxiCodeSecondMessage"
linktitle: "MaxiCodeSecondMessage"
second_title: "Αναφορά API του Aspose.BarCode για Node.js μέσω Java"
description: "Κλάση για κωδικοποίηση και αποκωδικοποίηση του κειμένου MaxiCode για τις λειτουργίες 4, 5 και 6."
type: docs
weight: 660
url: /el/nodejs/aspose.barcode/maxicodesecondmessage/
---

## MaxiCodeSecondMessage class

Κλάση για κωδικοποίηση και αποκωδικοποίηση του κειμένου MaxiCode για τις λειτουργίες 4, 5 και 6.

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
