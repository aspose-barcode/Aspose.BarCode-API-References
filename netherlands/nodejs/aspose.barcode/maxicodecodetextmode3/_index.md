---
title: "MaxiCodeCodetextMode3"
linktitle: "MaxiCodeCodetextMode3"
second_title: "Aspose.BarCode voor Node.js via Java API-referentie"
description: "Klasse voor het coderen en decoderen van de in de MaxiCode-code ingebedde tekst voor modus 3."
type: docs
weight: 620
url: /nl/nodejs/aspose.barcode/maxicodecodetextmode3/
---

## MaxiCodeCodetextMode3 class

Klasse voor het coderen en decoderen van de tekst die is ingebed in de MaxiCode-code voor modus 3. Deze voorbeeld toont hoe MaxiCode-codetekst te coderen en decoderen voor modus 3.

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

| Naam | Beschrijving |
| --- | --- |
| [getMode()](#getmode) | Haalt de MaxiCode-modus op. |

### getMode() {#getmode}

Haalt de MaxiCode-modus op.

**Returns:** MaxiCode mode
