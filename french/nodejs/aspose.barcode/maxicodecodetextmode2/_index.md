---
title: "MaxiCodeCodetextMode2"
linktitle: "MaxiCodeCodetextMode2"
second_title: "Référence de l'API Aspose.BarCode pour Node.js via Java"
description: "Classe pour l'encodage et le décodage du texte intégré dans le code MaxiCode pour le mode 2."
type: docs
weight: 610
url: /fr/nodejs/aspose.barcode/maxicodecodetextmode2/
---

## MaxiCodeCodetextMode2 class

Classe pour l'encodage et le décodage du texte intégré dans le code MaxiCode pour le mode 2.

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

## Méthodes

| Nom | Description |
| --- | --- |
| [getMode()](#getmode) | Obtient le mode MaxiCode. |

### getMode() {#getmode}

Obtient le mode MaxiCode.

**Returns:** MaxiCode mode
