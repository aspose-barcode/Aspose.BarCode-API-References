---
title: "MaxiCodeCodetextMode2"
linktitle: "MaxiCodeCodetextMode2"
second_title: "Riferimento API di Aspose.BarCode per Node.js via Java"
description: "Classe per la codifica e decodifica del testo incorporato nel codice MaxiCode per le modalità 2."
type: docs
weight: 610
url: /it/nodejs/aspose.barcode/maxicodecodetextmode2/
---

## MaxiCodeCodetextMode2 class

Classe per la codifica e decodifica del testo incorporato nel codice MaxiCode per le modalità 2.

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

## Metodi

| Nome | Descrizione |
| --- | --- |
| [getMode()](#getmode) | Ottiene la modalità MaxiCode. |

### getMode() {#getmode}

Ottiene la modalità MaxiCode.

**Returns:** MaxiCode mode
