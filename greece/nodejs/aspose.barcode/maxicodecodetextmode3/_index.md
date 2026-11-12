---
title: "MaxiCodeCodetextMode3"
linktitle: "MaxiCodeCodetextMode3"
second_title: "Αναφορά API του Aspose.BarCode για Node.js μέσω Java"
description: "Κλάση για κωδικοποίηση και αποκωδικοποίηση του κειμένου ενσωματωμένου στον κώδικα MaxiCode για τις λειτουργίες 3."
type: docs
weight: 620
url: /el/nodejs/aspose.barcode/maxicodecodetextmode3/
---

## MaxiCodeCodetextMode3 class

Κλάση για κωδικοποίηση και αποκωδικοποίηση του κειμένου ενσωματωμένου στον κώδικα MaxiCode για λειτουργίες 3. Αυτό το παράδειγμα δείχνει πώς να κωδικοποιήσετε και να αποκωδικοποιήσετε το MaxiCode codetext για τη λειτουργία 3.

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

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [getMode()](#getmode) | Λαμβάνει τη λειτουργία MaxiCode. |

### getMode() {#getmode}

Λαμβάνει τη λειτουργία MaxiCode.

**Returns:** MaxiCode mode
