---
title: "MaxiCodeCodetextMode3"
linktitle: "MaxiCodeCodetextMode3"
second_title: "Aspose.BarCode för Node.js via Java API-referens"
description: "Klass för kodning och avkodning av text som är inbäddad i MaxiCode-koden för läge 3."
type: docs
weight: 620
url: /sv/nodejs/aspose.barcode/maxicodecodetextmode3/
---

## MaxiCodeCodetextMode3 class

Klass för kodning och avkodning av text som är inbäddad i MaxiCode-koden för läge 3. Detta exempel visar hur man kodar och avkodar MaxiCode-kodtext för läge 3.

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

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [getMode()](#getmode) | Hämtar MaxiCode-läge. |

### getMode() {#getmode}

Hämtar MaxiCode-läge.

**Returns:** MaxiCode mode
