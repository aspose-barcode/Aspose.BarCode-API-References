---
title: "HIBCLICComplexCodetext"
linktitle: "HIBCLICComplexCodetext"
second_title: "Αναφορά API του Aspose.BarCode για Node.js μέσω Java"
description: "Βασική κλάση για κωδικοποίηση και αποκωδικοποίηση του κειμένου που ενσωματώνεται στον κώδικα HIBC LIC."
type: docs
weight: 450
url: /el/nodejs/aspose.barcode/hibcliccomplexcodetext/
---

## HIBCLICComplexCodetext class

Βασική κλάση για κωδικοποίηση και αποκωδικοποίηση του κειμένου που ενσωματώνεται στον κώδικα HIBC LIC. Αυτό το παράδειγμα δείχνει πώς να αποκωδικοποιήσετε ακατέργαστο κείμενο HIBC LIC σε αντικείμενο HIBCLICComplexCodetext.

```js
new HIBCLICComplexCodetext()
```

**Example:**

```js
let reader = new BarCodeReader("c:\\test.png", null, DecodeType.HIBC_AZTEC_LIC);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
    let result = results[i];
   let resultHIBCLICComplexCodetext = ComplexCodetextReader.tryDecodeHIBCLIC(result.getCodeText());
   print("BarCode Type: " + resultMaxiCodeCodetext.getBarcodeType());
   print("BarCode CodeText: " + resultMaxiCodeCodetext.getConstructedCodetext());
}
```

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [getBarcodeType()](#getbarcodetype) | Λαμβάνει ή ορίζει τον τύπο barcode. Το κείμενο HIBC LIC μπορεί να κωδικοποιηθεί χρησιμοποιώντας HIBCCode39LIC, HIBCCode128LIC, HIBCAztecLIC, HIBCDataM |
| [getConstructedCodetext()](#getconstructedcodetext) | Δημιουργεί κείμενο κώδικα. |
| [initFromString(constructedCodetext)](#initfromstring) | Αρχικοποιεί την παρουσία από το δημιουργημένο κείμενο κώδικα. |
| [setBarcodeType()](#setbarcodetype) | Λαμβάνει ή ορίζει τον τύπο barcode. Το κείμενο HIBC LIC μπορεί να κωδικοποιηθεί χρησιμοποιώντας HIBCCode39LIC, HIBCCode128LIC, HIBCAztecLIC, HIBCDataM |

### getBarcodeType() {#getbarcodetype}

Λαμβάνει ή ορίζει τον τύπο barcode. Το κείμενο HIBC LIC μπορεί να κωδικοποιηθεί χρησιμοποιώντας τους τύπους κωδικοποίησης HIBCCode39LIC, HIBCCode128LIC, HIBCAztecLIC, HIBCDataMatrixLIC και HIBCQRLIC. Προεπιλεγμένη τιμή: HIBCCode39LIC.

**Returns:** Barcode type.

### getConstructedCodetext() {#getconstructedcodetext}

Δημιουργεί κείμενο κώδικα.

**Returns:** Constructed codetext

### initFromString(constructedCodetext) {#initfromstring}

Αρχικοποιεί την παρουσία από το δημιουργημένο κείμενο κώδικα.

| Παράμετρος | Περιγραφή |
| --- | --- |
| constructedCodetext | Δημιουργημένο κείμενο κώδικα. |

### setBarcodeType() {#setbarcodetype}

Λαμβάνει ή ορίζει τον τύπο barcode. Το κείμενο HIBC LIC μπορεί να κωδικοποιηθεί χρησιμοποιώντας τους τύπους κωδικοποίησης HIBCCode39LIC, HIBCCode128LIC, HIBCAztecLIC, HIBCDataMatrixLIC και HIBCQRLIC. Προεπιλεγμένη τιμή: HIBCCode39LIC.

**Returns:** Barcode type.
