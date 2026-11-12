---
title: "MaxiCodeSecondMessage"
linktitle: "MaxiCodeSecondMessage"
second_title: "Aspose.BarCode के लिए Node.js via Java API संदर्भ"
description: "मोड 4, 5 और 6 के लिए MaxiCode कोडटेक्स्ट को एन्कोड और डिकोड करने वाली क्लास।"
type: docs
weight: 660
url: /hi/nodejs/aspose.barcode/maxicodesecondmessage/
---

## MaxiCodeSecondMessage class

मोड 4, 5 और 6 के लिए MaxiCode कोडटेक्स्ट को एन्कोड और डिकोड करने वाली क्लास।

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
