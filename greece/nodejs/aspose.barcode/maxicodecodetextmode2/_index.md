---
title: "MaxiCodeCodetextMode2"
linktitle: "MaxiCodeCodetextMode2"
second_title: "Αναφορά API του Aspose.BarCode για Node.js μέσω Java"
description: "Κλάση για κωδικοποίηση και αποκωδικοποίηση του κειμένου ενσωματωμένου στον κώδικα MaxiCode για λειτουργίες 2."
type: docs
weight: 610
url: /el/nodejs/aspose.barcode/maxicodecodetextmode2/
---

## MaxiCodeCodetextMode2 class

Κλάση για κωδικοποίηση και αποκωδικοποίηση του κειμένου ενσωματωμένου στον κώδικα MaxiCode για λειτουργίες 2.

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

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [getMode()](#getmode) | Λαμβάνει τη λειτουργία MaxiCode. |

### getMode() {#getmode}

Λαμβάνει τη λειτουργία MaxiCode.

**Returns:** MaxiCode mode
