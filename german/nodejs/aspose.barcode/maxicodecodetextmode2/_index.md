---
title: "MaxiCodeCodetextMode2"
linktitle: "MaxiCodeCodetextMode2"
second_title: "Aspose.BarCode für Node.js über Java API-Referenz"
description: "Klasse zum Kodieren und Dekodieren des in den MaxiCode‑Code eingebetteten Textes für Modus 2."
type: docs
weight: 610
url: /de/nodejs/aspose.barcode/maxicodecodetextmode2/
---

## MaxiCodeCodetextMode2 class

Klasse zum Kodieren und Dekodieren des in den MaxiCode‑Code eingebetteten Textes für Modus 2.

```js
new MaxiCodeCodetextMode2()
```

**Example:**

```js
This sample shows how to encode and decode MaxiCode codetext for mode 2.
 //Mode 2 with standart second message
 let maxiCodeCodetext = new MaxiCodeCodetextMode2();
 maxiCodeCodetext.setPostalCode("524032140");
 maxiCodeCodetext.setCountryCode(056);
 maxiCodeCodetext.setServiceCategory(999);
 let MaxiCodeStandardSecondMessage = new MaxiCodeStandardSecondMessage();
 MaxiCodeStandardSecondMessage.setMessage("Test message");
 maxiCodeCodetext.setSecondMessage(MaxiCodeStandardSecondMessage);
 let complexGenerator = new ComplexBarcodeGenerator(maxiCodeCodetext);
 complexGenerator.generateBarCodeImage(BarcodeImageFormat.PNG);
```

## Methoden

| Name | Beschreibung |
| --- | --- |
| [getMode()](#getmode) | Liefert den MaxiCode-Modus. |

### getMode() {#getmode}

Liefert den MaxiCode-Modus.

**Returns:** MaxiCode mode
