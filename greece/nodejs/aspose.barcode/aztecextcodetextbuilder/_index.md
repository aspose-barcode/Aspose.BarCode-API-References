---
title: "AztecExtCodetextBuilder"
linktitle: "AztecExtCodetextBuilder"
second_title: "Αναφορά API του Aspose.BarCode για Node.js μέσω Java"
description: "Εκτεταμένος δημιουργός κωδικού κειμένου για γραμμωτούς κώδικες Aztec σε λειτουργία ExtendedCodetext του AztecEncodeMode. Χρησιμοποιήστε την ιδιότητα TwoDDisplayText του BarcodeGenerator για ορισμό του ορατού κειμένου."
type: docs
weight: 50
url: /el/nodejs/aspose.barcode/aztecextcodetextbuilder/
---

## AztecExtCodetextBuilder class

Εκτεταμένος δημιουργός κωδικού κειμένου για γραμμωτούς κώδικες Aztec σε λειτουργία ExtendedCodetext του AztecEncodeMode. Χρησιμοποιήστε την ιδιότητα TwoDDisplayText του BarcodeGenerator για ορισμό του ορατού κειμένου αφαιρώντας διαχειριστικούς χαρακτήρες. Αυτό το παράδειγμα δείχνει πώς να χρησιμοποιήσετε το AztecExtCodetextBuilder σε Εκτεταμένη Λειτουργία.

```js
new AztecExtCodetextBuilder()
```

**Example:**

```js
//create codetext
     let textBuilder = new AztecExtCodetextBuilder();
     textBuilder.addECICodetext(ECIEncodings.Win1251, "Will");
     textBuilder.addECICodetext(ECIEncodings.UTF8, "犬Right狗");
     textBuilder.addECICodetext(ECIEncodings.UTF16BE, "犬Power狗");
     textBuilder.addPlainCodetext("Plain text");
     //generate codetext
     let codetext = textBuilder.getExtendedCodetext();
     //generate
     let generator = new BarcodeGenerator(EncodeTypes.AZTEC, codetext);
     generator.getParameters().getBarcode().getCodeTextParameters().setwoDDisplayText("My Text");
     generator.save("test.bmp", BarcodeImageFormat.BMP);
```

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [getExtendedCodetext()](#getextendedcodetext) | Δημιουργεί Extended codetext από τη λίστα Extended codetext. |

### getExtendedCodetext() {#getextendedcodetext}

Δημιουργεί Extended codetext από τη λίστα Extended codetext.

**Returns:** Extended codetext as string
