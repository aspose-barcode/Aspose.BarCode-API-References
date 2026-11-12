---
title: "MaxiCodeCodetextMode3"
linktitle: "MaxiCodeCodetextMode3"
second_title: "Riferimento API di Aspose.BarCode per Node.js via Java"
description: "Classe per la codifica e decodifica del testo incorporato nel codice MaxiCode per la modalità 3."
type: docs
weight: 620
url: /it/nodejs/aspose.barcode/maxicodecodetextmode3/
---

## MaxiCodeCodetextMode3 class

Classe per la codifica e la decodifica del testo incorporato nel codice MaxiCode per le modalità 3. Questo esempio mostra come codificare e decodificare il codetext MaxiCode per la modalità 3.

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

## Metodi

| Nome | Descrizione |
| --- | --- |
| [getMode()](#getmode) | Ottiene la modalità MaxiCode. |

### getMode() {#getmode}

Ottiene la modalità MaxiCode.

**Returns:** MaxiCode mode
