---
title: "AustraliaPostSettings"
linktitle: "AustraliaPostSettings"
second_title: "Αναφορά API του Aspose.BarCode για Node.js μέσω Java"
description: "Παράμετροι αποκωδικοποίησης AustraliaPost."
type: docs
weight: 30
url: /el/nodejs/aspose.barcode/australiapostsettings/
---

## AustraliaPostSettings class

Παράμετροι αποκωδικοποίησης AustraliaPost. Περιέχει παραμέτρους που επηρεάζουν τα αναγνωρισμένα δεδομένα της συμβολής AustraliaPost.

```js
new AustraliaPostSettings()
```

Κατασκευαστής AustraliaPostSettings

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [getCustomerInformationInterpretingType()](#getcustomerinformationinterpretingtype) | Λαμβάνει τον Τύπο Ερμηνείας για τις Πληροφορίες Πελάτη του AustralianPost BarCode. Η προεπιλογή είναι CustomerInformationInterpre |
| [getIgnoreEndingFillingPatternsForCTable()](#getignoreendingfillingpatternsforctable) | Η σημαία που αναγκάζει τον αποκωδικοποιητή AustraliaPost να αγνοεί τα τελευταία μοτίβα γεμίσματος στο πεδίο Πληροφορίες Πελάτη κατά την αποκωδικοποίηση |
| [setCustomerInformationInterpretingType(value)](#setcustomerinformationinterpretingtype) | Ορίζει τον Τύπο Ερμηνείας για τις Πληροφορίες Πελάτη του AustralianPost BarCode. Η προεπιλογή είναι CustomerInformationInterpre |
| [setIgnoreEndingFillingPatternsForCTable()](#setignoreendingfillingpatternsforctable) | Η σημαία που αναγκάζει τον αποκωδικοποιητή AustraliaPost να αγνοεί τα τελευταία μοτίβα γεμίσματος στο πεδίο Πληροφορίες Πελάτη κατά την αποκωδικοποίηση |

### getCustomerInformationInterpretingType() {#getcustomerinformationinterpretingtype}

Λαμβάνει τον Τύπο Ερμηνείας για τις Πληροφορίες Πελάτη του AustralianPost BarCode. Η προεπιλογή είναι CustomerInformationInterpretingType.OTHER.

**Returns:** The interpreting type (CTable, NTable or Other) of customer information for AustralianPost BarCode

### getIgnoreEndingFillingPatternsForCTable() {#getignoreendingfillingpatternsforctable}

Η σημαία που αναγκάζει τον αποκωδικοποιητή AustraliaPost να αγνοεί τα τελευταία μοτίβα γεμίσματος στο πεδίο Πληροφορίες Πελάτη κατά την αποκωδικοποίηση ως μέθοδο CTable. Η μέθοδος κωδικοποίησης CTable δεν έχει κενά στον πίνακα κωδικοποίησης και η ακολουθία \"333\" των μοτίβων γεμίσματος αποκωδικοποιείται ως το γράμμα \"z\".

**Returns:** The flag which force AustraliaPost decoder to ignore last filling patterns during CTable method decoding

**Example:**

```js
let generator = new BarcodeGenerator(EncodeTypes.AUSTRALIA_POST, "5912345678AB");
generator.getParameters().getBarcode().getAustralianPost().setAustralianPostEncodingTable(CustomerInformationInterpretingType.C_TABLE);
let image = generator.generateBarCodeImage(BarcodeImageFormat.PNG);
let reader = new BarCodeReader(image, null, DecodeType.AUSTRALIA_POST);
reader.getBarcodeSettings().getAustraliaPost().setCustomerInformationInterpretingType(CustomerInformationInterpretingType.C_TABLE);
reader.getBarcodeSettings().getAustraliaPost().setIgnoreEndingFillingPatternsForCTable(true);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
    let result = results[i];
    console.log("BarCode Type: " + result.getCodeType());
    console.log("BarCode CodeText: " + result.getCodeText());
}
```

### setCustomerInformationInterpretingType(value) {#setcustomerinformationinterpretingtype}

Ορίζει τον Τύπο Ερμηνείας για τις Πληροφορίες Πελάτη του AustralianPost BarCode. Η προεπιλογή είναι CustomerInformationInterpretingType.OTHER.

| Παράμετρος | Περιγραφή |
| --- | --- |
| τιμή | Ο τύπος ερμηνείας (CTable, NTable ή Other) των πληροφοριών πελάτη για το AustralianPost BarCode |

### setIgnoreEndingFillingPatternsForCTable() {#setignoreendingfillingpatternsforctable}

Η σημαία που αναγκάζει τον αποκωδικοποιητή AustraliaPost να αγνοεί τα τελευταία μοτίβα γεμίσματος στο πεδίο Πληροφορίες Πελάτη κατά την αποκωδικοποίηση ως μέθοδο CTable. Η μέθοδος κωδικοποίησης CTable δεν έχει κενά στον πίνακα κωδικοποίησης και η ακολουθία \"333\" των μοτίβων γεμίσματος αποκωδικοποιείται ως το γράμμα \"z\".

**Returns:** The flag which force AustraliaPost decoder to ignore last filling patterns during CTable method decoding

**Example:**

```js
let generator = new BarcodeGenerator(EncodeTypes.AUSTRALIA_POST, "5912345678AB");
generator.getParameters().getBarcode().getAustralianPost().setAustralianPostEncodingTable(CustomerInformationInterpretingType.C_TABLE);
let image = generator.generateBarCodeImage(BarcodeImageFormat.PNG);
let reader = new BarCodeReader(image, null, DecodeType.AUSTRALIA_POST);
reader.getBarcodeSettings().getAustraliaPost().setCustomerInformationInterpretingType(CustomerInformationInterpretingType.C_TABLE);
reader.getBarcodeSettings().getAustraliaPost().setIgnoreEndingFillingPatternsForCTable(true);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
    let result = results[i];
    console.log("BarCode Type: " + result.getCodeType());
    console.log("BarCode CodeText: " + result.getCodeText());
}
```
