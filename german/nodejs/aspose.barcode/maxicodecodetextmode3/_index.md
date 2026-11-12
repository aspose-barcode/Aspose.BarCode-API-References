---
title: "MaxiCodeCodetextMode3"
linktitle: "MaxiCodeCodetextMode3"
second_title: "Aspose.BarCode für Node.js über Java API-Referenz"
description: "Klasse zum Kodieren und Dekodieren des im MaxiCode‑Code eingebetteten Textes für Modus 3."
type: docs
weight: 620
url: /de/nodejs/aspose.barcode/maxicodecodetextmode3/
---

## MaxiCodeCodetextMode3 class

Klasse zum Kodieren und Dekodieren des im MaxiCode-Code eingebetteten Textes für Modus 3. Dieses Beispiel zeigt, wie man MaxiCode-Codetext für Modus 3 kodiert und dekodiert.

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

## Methoden

| Name | Beschreibung |
| --- | --- |
| [getMode()](#getmode) | Liefert den MaxiCode-Modus. |

### getMode() {#getmode}

Liefert den MaxiCode-Modus.

**Returns:** MaxiCode mode
