---
title: "MaxiCodeSecondMessage"
linktitle: "MaxiCodeSecondMessage"
second_title: "Aspose.BarCode voor Node.js via Java API-referentie"
description: "Klasse voor het coderen en decoderen van MaxiCode-codetekst voor modus 4, 5 en 6."
type: docs
weight: 660
url: /nl/nodejs/aspose.barcode/maxicodesecondmessage/
---

## MaxiCodeSecondMessage class

Klasse voor het coderen en decoderen van MaxiCode-codetekst voor modus 4, 5 en 6.

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
