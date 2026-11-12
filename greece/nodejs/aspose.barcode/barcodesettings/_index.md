---
title: "BarcodeSettings"
linktitle: "BarcodeSettings"
second_title: "Αναφορά API του Aspose.BarCode για Node.js μέσω Java"
description: "Κύριες παράμετροι αποκωδικοποίησης BarCode."
type: docs
weight: 150
url: /el/nodejs/aspose.barcode/barcodesettings/
---

## BarcodeSettings class

Οι κύριες παράμετροι αποκωδικοποίησης BarCode. Περιέχει παραμέτρους που επηρεάζουν τα αναγνωρισμένα δεδομένα.

```js
new BarcodeSettings(settings)
```

Κατασκευαστής αντιγραφής BarcodeSettings

| Παράμετρος | Περιγραφή |
| --- | --- |
| ρυθμίσεις | Η πηγή των δεδομένων |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [getAustraliaPost()](#getaustraliapost) | Λαμβάνει τις παραμέτρους αποκωδικοποίησης AustraliaPost |
| [getChecksumValidation()](#getchecksumvalidation) | Ενεργοποίηση επαλήθευσης αθροίσματος ελέγχου κατά την αναγνώριση για 1D και ταχυδρομικούς κωδικούς. Η προεπιλογή θεωρείται Ναι για τις συμβολές που |
| [getDetectEncoding()](#getdetectencoding) | Η σημαία που αναγκάζει τη μηχανή να ανιχνεύσει την κωδικοποίηση του κειμένου κώδικα για σύνολα χαρακτήρων Unicode. Η προεπιλεγμένη τιμή είναι true. |
| [getStripFNC()](#getstripfnc) | Αφαίρεση χαρακτήρων FNC1, FNC2, FNC3 από το κείμενο κώδικα. Η προεπιλεγμένη τιμή είναι false. |
| [isOnlyRequestedTypes()](#isonlyrequestedtypes) | Επιστρέφει μόνο τύπους barcode που έχουν καθοριστεί ρητά για αναγνώριση. Όταν είναι ενεργό, οι αναγνωρισμένοι κωδικοί άλλων συμβατών |
| [setChecksumValidation(value)](#setchecksumvalidation) | Ενεργοποίηση επαλήθευσης αθροίσματος ελέγχου κατά την αναγνώριση για 1D και ταχυδρομικούς κωδικούς. Η προεπιλογή θεωρείται Ναι για τις συμβολές που |
| [setDetectEncoding()](#setdetectencoding) | Η σημαία που αναγκάζει τη μηχανή να ανιχνεύσει την κωδικοποίηση του κειμένου κώδικα για σύνολα χαρακτήρων Unicode. Η προεπιλεγμένη τιμή είναι true. |
| [setOnlyRequestedTypes()](#setonlyrequestedtypes) | Επιστρέφει μόνο τύπους barcode που έχουν καθοριστεί ρητά για αναγνώριση. Όταν είναι ενεργό, οι αναγνωρισμένοι κωδικοί άλλων συμβατών |
| [setStripFNC(value)](#setstripfnc) | Αφαίρεση χαρακτήρων FNC1, FNC2, FNC3 από το κείμενο κώδικα. Η προεπιλεγμένη τιμή είναι false. |

### getAustraliaPost() {#getaustraliapost}

Λαμβάνει τις παραμέτρους αποκωδικοποίησης AustraliaPost

**Returns:** The AustraliaPost decoding parameters which make influence on recognized data of AustraliaPost symbology

### getChecksumValidation() {#getchecksumvalidation}

Ενεργοποίηση επαλήθευσης αθροίσματος ελέγχου κατά την αναγνώριση για 1D και ταχυδρομικούς κωδικούς. Η προεπιλογή θεωρείται Ναι για τις συμβολές που πρέπει να περιέχουν άθροισμα ελέγχου, και Όχι όπου το άθροισμα ελέγχου είναι μόνο δυνατό. Άθροισμα ελέγχου ποτέ δεν χρησιμοποιείται: Codabar, PatchCode, Pharmacode, DataLogic2of5. Άθροισμα ελέγχου είναι δυνατό: Code39 Standard/Extended, Standard2of5, Interleaved2of5, ItalianPost25, Matrix2of5, MSI, ItalianPost25, DeutschePostIdentcode, DeutschePostLeitcode, VIN. Άθροισμα ελέγχου πάντα χρησιμοποιείται: Οι υπόλοιπες συμβολές.

**Returns:** Enable checksum validation during recognition for 1D and Postal barcodes.

**Example:**

```js
let generator = new BarcodeGenerator(EncodeTypes.EAN_13, "1234567890128");
generator.save("c:/test.png", BarcodeImageFormat.PNG);
let reader = new BarCodeReader("c:/test.png", DecodeType.EAN_13);
//checksum disabled
reader.getBarcodeSettings().setChecksumValidation(ChecksumValidation.OFF);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
     let result = results[i];
     console.log ("BarCode CodeText: " + result.getCodeText());
     console.log ("BarCode Value: " + result.getExtended().getOneD().getValue());
     console.log ("BarCode Checksum: " + result.getExtended().getOneD().getCheckSum());
}
```

### getDetectEncoding() {#getdetectencoding}

Η σημαία που αναγκάζει τη μηχανή να ανιχνεύσει την κωδικοποίηση του κειμένου κώδικα για σύνολα χαρακτήρων Unicode. Η προεπιλεγμένη τιμή είναι true.

**Returns:** The flag which force engine to detect codetext encoding for Unicode codesets

**Example:**

```js
let generator = new BarcodeGenerator(EncodeTypes.QR, "Слово"))
im = generator.generateBarcodeImage(BarcodeImageFormat.PNG);

//detects encoding for Unicode codesets is enabled
let reader = new BarCodeReader(im, DecodeType.QR);
reader.getBarcodeSettings().setDetectEncoding(true);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
   let result = results[i];
   console.log ("BarCode CodeText: " + result.getCodeText());
}
```

### getStripFNC() {#getstripfnc}

Αφαίρεση χαρακτήρων FNC1, FNC2, FNC3 από το κείμενο κώδικα. Η προεπιλεγμένη τιμή είναι false.

**Returns:** Strip FNC1, FNC2, FNC3 characters from codetext. Default value is false.

**Example:**

```js
let generator = new BarcodeGenerator(EncodeTypes.GS_1_CODE_128, "(02)04006664241007(37)1(400)7019590754");
generator.save("c:/test.png", BarcodeImageFormat.PNG);
let reader = new BarCodeReader("c:/test.png", DecodeType.CODE_128);

//StripFNC disabled
reader.getBarcodeSettings().setStripFNC(false);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
   let result = results[i];
   console.log ("BarCode CodeText: " + result.getCodeText());
}
```

### isOnlyRequestedTypes() {#isonlyrequestedtypes}

Επιστρέφει μόνο τύπους barcode που έχουν καθοριστεί ρητά για αναγνώριση. Όταν είναι ενεργό, οι αναγνωρισμένοι κωδικοί άλλων συμβατών ή ισοδύναμων τύπων φιλτράρονται. Η προεπιλεγμένη τιμή είναι false. Παράδειγμα: // generate EAN13 barcode let generator = new BarcodeGenerator(EncodeTypes.EAN_13, "2383823482894"); generator.save("test.png"); // recognize only UPCA barcodes (no results, because source is EAN13) const reader = new BarCodeReader("test.png", null, DecodeType.UPCA); reader.getBarcodeSettings().setOnlyRequestedTypes(true); let results = reader.readBarCodes(); for (let i = 0; i < results.length; i++) { console.log("BarCode CodeText: " + results[i].getCodeText()); } // recognize compatible types: EAN13, UPCA, ISSN, ISMN, ISBN // (EAN13 will be returned as UPCA-equivalent) let reader2 = new BarCodeReader("test.png", null, DecodeType.UPCA); reader2.getBarcodeSettings().setOnlyRequestedTypes(false); let results2 = reader2.readBarCodes(); for (let i = 0; i < results2.length; i++) { console.log("BarCode CodeText: " + results2[i].getCodeText()); }

**Returns:** true if only explicitly requested barcode types are returned; otherwise false

### setChecksumValidation(value) {#setchecksumvalidation}

Ενεργοποίηση επαλήθευσης αθροίσματος ελέγχου κατά την αναγνώριση για 1D και ταχυδρομικούς κωδικούς. Η προεπιλογή θεωρείται Ναι για τις συμβολές που πρέπει να περιέχουν άθροισμα ελέγχου, και Όχι όπου το άθροισμα ελέγχου είναι μόνο δυνατό. Άθροισμα ελέγχου ποτέ δεν χρησιμοποιείται: Codabar, PatchCode, Pharmacode, DataLogic2of5. Άθροισμα ελέγχου είναι δυνατό: Code39 Standard/Extended, Standard2of5, Interleaved2of5, ItalianPost25, Matrix2of5, MSI, ItalianPost25, DeutschePostIdentcode, DeutschePostLeitcode, VIN. Άθροισμα ελέγχου πάντα χρησιμοποιείται: Οι υπόλοιπες συμβολές.

| Παράμετρος | Περιγραφή |
| --- | --- |
| τιμή | Ενεργοποίηση επαλήθευσης αθροίσματος ελέγχου κατά την αναγνώριση για 1D και ταχυδρομικούς κωδικούς. |

**Example:**

```js
let generator = new BarcodeGenerator(EncodeTypes.EAN_13, "1234567890128");
generator.save("c:/test.png", BarcodeImageFormat.PNG);
let reader = new BarCodeReader("c:/test.png", DecodeType.EAN_13);
//checksum disabled
reader.getBarcodeSettings().setChecksumValidation(ChecksumValidation.OFF);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
     let result = results[i];
     console.log ("BarCode CodeText: " + result.getCodeText());
     console.log ("BarCode Value: " + result.getExtended().getOneD().getValue());
     console.log ("BarCode Checksum: " + result.getExtended().getOneD().getCheckSum());
}
```

### setDetectEncoding() {#setdetectencoding}

Η σημαία που αναγκάζει τη μηχανή να ανιχνεύσει την κωδικοποίηση του κειμένου κώδικα για σύνολα χαρακτήρων Unicode. Η προεπιλεγμένη τιμή είναι true.

**Returns:** The flag which force engine to detect codetext encoding for Unicode codesets

**Example:**

```js
let generator = new BarcodeGenerator(EncodeTypes.QR, "Слово"))
im = generator.generateBarcodeImage(BarcodeImageFormat.PNG);

//detects encoding for Unicode codesets is enabled
let reader = new BarCodeReader(im, DecodeType.QR);
reader.getBarcodeSettings().setDetectEncoding(true);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
   let result = results[i];
   console.log ("BarCode CodeText: " + result.getCodeText());
}
```

### setOnlyRequestedTypes() {#setonlyrequestedtypes}

Επιστρέφει μόνο τύπους barcode που έχουν καθοριστεί ρητά για αναγνώριση. Όταν είναι ενεργό, οι αναγνωρισμένοι κωδικοί άλλων συμβατών ή ισοδύναμων τύπων φιλτράρονται. Η προεπιλεγμένη τιμή είναι false. Παράδειγμα: // generate EAN13 barcode let generator = new BarcodeGenerator(EncodeTypes.EAN_13, "2383823482894"); generator.save("test.png"); // recognize only UPCA barcodes (no results, because source is EAN13) const reader = new BarCodeReader("test.png", null, DecodeType.UPCA); reader.getBarcodeSettings().setOnlyRequestedTypes(true); let results = reader.readBarCodes(); for (let i = 0; i < results.length; i++) { console.log("BarCode CodeText: " + results[i].getCodeText()); } // recognize compatible types: EAN13, UPCA, ISSN, ISMN, ISBN // (EAN13 will be returned as UPCA-equivalent) let reader2 = new BarCodeReader("test.png", null, DecodeType.UPCA); reader2.getBarcodeSettings().setOnlyRequestedTypes(false); let results2 = reader2.readBarCodes(); for (let i = 0; i < results2.length; i++) { console.log("BarCode CodeText: " + results2[i].getCodeText()); }

**Returns:** true if only explicitly requested barcode types are returned; otherwise false

### setStripFNC(value) {#setstripfnc}

Αφαίρεση χαρακτήρων FNC1, FNC2, FNC3 από το κείμενο κώδικα. Η προεπιλεγμένη τιμή είναι false.

| Παράμετρος | Περιγραφή |
| --- | --- |
| τιμή | Αφαίρεση χαρακτήρων FNC1, FNC2, FNC3 από το κείμενο κώδικα. Η προεπιλεγμένη τιμή είναι false. |

**Example:**

```js
let generator = new BarcodeGenerator(EncodeTypes.GS_1_CODE_128, "(02)04006664241007(37)1(400)7019590754");
generator.save("c:/test.png", BarcodeImageFormat.PNG);
let reader = new BarCodeReader("c:/test.png", DecodeType.CODE_128);

//StripFNC disabled
reader.getBarcodeSettings().setStripFNC(false);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
   let result = results[i];
   console.log ("BarCode CodeText: " + result.getCodeText());
}
```
