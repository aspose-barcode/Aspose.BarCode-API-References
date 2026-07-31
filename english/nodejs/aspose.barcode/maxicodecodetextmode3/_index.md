---
title: "MaxiCodeCodetextMode3 Class"
linktitle: "MaxiCodeCodetextMode3"
articleTitle: "MaxiCodeCodetextMode3"
second_title: "Aspose.BarCode for Node.js via Java"
description: "Class for encoding and decoding the text embedded in the MaxiCode code for modes 3. This sample shows how to encode and decode MaxiCode codetext for mode 3."
type: docs
weight: 620
url: /nodejs/aspose.barcode/maxicodecodetextmode3/
---

## MaxiCodeCodetextMode3 class

Class for encoding and decoding the text embedded in the MaxiCode code for modes 3. This sample shows how to encode and decode MaxiCode codetext for mode 3.

```js
new MaxiCodeCodetextMode3()
```

**Example:**

```js
//Mode 3 with standart second message
 let maxiCodeCodetext = new MaxiCodeCodetextMode3();
 maxiCodeCodetext.setPostalCode("B1050");
 maxiCodeCodetext.setCountryCode(056);
 maxiCodeCodetext.setServiceCategory(999);
 let MaxiCodeStandardSecondMessage = new MaxiCodeStandardSecondMessage();
 MaxiCodeStandardSecondMessage.setMessage("Test message");
 maxiCodeCodetext.setSecondMessage(MaxiCodeStandardSecondMessage);
 let complexGenerator = new ComplexBarcodeGenerator(maxiCodeCodetext);
 complexGenerator.generateBarCodeImage(BarcodeImageFormat.PNG);
```

## Methods

| Name | Description |
| --- | --- |
| [getMode()](./getmode/) | Gets MaxiCode mode. |
