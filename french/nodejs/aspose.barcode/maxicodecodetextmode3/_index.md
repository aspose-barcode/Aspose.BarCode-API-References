---
title: "MaxiCodeCodetextMode3"
linktitle: "MaxiCodeCodetextMode3"
second_title: "Référence de l'API Aspose.BarCode pour Node.js via Java"
description: "Classe pour l'encodage et le décodage du texte intégré dans le code MaxiCode pour le mode 3."
type: docs
weight: 620
url: /fr/nodejs/aspose.barcode/maxicodecodetextmode3/
---

## MaxiCodeCodetextMode3 class

Classe pour encoder et décoder le texte intégré dans le code MaxiCode pour le mode 3. Cet exemple montre comment encoder et décoder le codetext MaxiCode pour le mode 3.

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

## Méthodes

| Nom | Description |
| --- | --- |
| [getMode()](#getmode) | Obtient le mode MaxiCode. |

### getMode() {#getmode}

Obtient le mode MaxiCode.

**Returns:** MaxiCode mode
