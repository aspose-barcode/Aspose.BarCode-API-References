---
title: "MaxiCodeSecondMessage"
linktitle: "MaxiCodeSecondMessage"
second_title: "Aspose.BarCode för Node.js via Java API-referens"
description: "Klass för kodning och avkodning av MaxiCode‑kodtext för lägena 4, 5 och 6."
type: docs
weight: 660
url: /sv/nodejs/aspose.barcode/maxicodesecondmessage/
---

## MaxiCodeSecondMessage class

Klass för kodning och avkodning av MaxiCode‑kodtext för lägena 4, 5 och 6.

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
