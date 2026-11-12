---
title: "MaxiCodeSecondMessage"
linktitle: "MaxiCodeSecondMessage"
second_title: "Referensi API Aspose.BarCode untuk Node.js via Java"
description: "Kelas untuk mengenkode dan mendekode teks kode MaxiCode untuk mode 4, 5, dan 6."
type: docs
weight: 660
url: /id/nodejs/aspose.barcode/maxicodesecondmessage/
---

## MaxiCodeSecondMessage class

Kelas untuk mengenkode dan mendekode teks kode MaxiCode untuk mode 4, 5, dan 6.

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
