---
title: "MaxiCodeCodetextMode2"
linktitle: "MaxiCodeCodetextMode2"
second_title: "Aspose.BarCode voor Node.js via Java API-referentie"
description: "Klasse voor het coderen en decoderen van de tekst die is ingebed in de MaxiCode-code voor modus 2."
type: docs
weight: 610
url: /nl/nodejs/aspose.barcode/maxicodecodetextmode2/
---

## MaxiCodeCodetextMode2 class

Klasse voor het coderen en decoderen van de tekst die is ingebed in de MaxiCode-code voor modus 2.

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

| Naam | Beschrijving |
| --- | --- |
| [getMode()](#getmode) | Haalt de MaxiCode-modus op. |

### getMode() {#getmode}

Haalt de MaxiCode-modus op.

**Returns:** MaxiCode mode
