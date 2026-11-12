---
title: "MaxiCodeExtCodetextBuilder"
linktitle: "MaxiCodeExtCodetextBuilder"
second_title: "Αναφορά API του Aspose.BarCode για Node.js μέσω Java"
description: "Εκτεταμένος δημιουργός κειμένου κωδικοποίησης για barcode MaxiCode για τη λειτουργία ExtendedCodetext του MaxiCodeEncodeMode. Χρησιμοποιήστε την ιδιότητα TwoDDisplayText του BarcodeGenerator για να ορίσετε την ορατότητα"
type: docs
weight: 630
url: /el/nodejs/aspose.barcode/maxicodeextcodetextbuilder/
---

## MaxiCodeExtCodetextBuilder class

Εκτεταμένος γεννήτρια κώδικα κειμένου για γραμμωτούς κώδικες MaxiCode για τη λειτουργία ExtendedCodetext του MaxiCodeEncodeMode. Χρησιμοποιήστε την ιδιότητα TwoDDisplayText του BarcodeGenerator για να ορίσετε το ορατό κείμενο αφαιρώντας διαχειριστικούς χαρακτήρες. Αυτό το παράδειγμα δείχνει πώς να χρησιμοποιήσετε το MaxiCodeExtCodetextBuilder σε Extended Mode.

```js
new MaxiCodeExtCodetextBuilder()
```

**Example:**

```js
//create codetext
let textBuilder = new MaxiCodeExtCodetextBuilder();
textBuilder.addECICodetext(ECIEncodings.Win1251, "Will");
textBuilder.addECICodetext(ECIEncodings.UTF8, "犬Right狗");
textBuilder.addECICodetext(ECIEncodings.UTF16BE, "犬Power狗");
textBuilder.addPlainCodetext("Plain text");

//generate codetext
let codetext = textBuilder.getExtendedCodetext();

//generate
let generator = new BarcodeGenerator(EncodeTypes.MAXI_CODE, codetext);
generator.getParameters().getBarcode().getCodeTextParameters().setTwoDDisplayText("My Text");
generator.save("test.bmp", BarcodeImageFormat.BMP);
```

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [getExtendedCodetext()](#getextendedcodetext) | Δημιουργεί Extended codetext από τη λίστα Extended codetext. |

### getExtendedCodetext() {#getextendedcodetext}

Δημιουργεί Extended codetext από τη λίστα Extended codetext.

**Returns:** Extended codetext as string
