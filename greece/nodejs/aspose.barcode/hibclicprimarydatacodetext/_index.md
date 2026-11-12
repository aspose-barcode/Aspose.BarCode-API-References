---
title: "HIBCLICPrimaryDataCodetext"
linktitle: "HIBCLICPrimaryDataCodetext"
second_title: "Αναφορά API του Aspose.BarCode για Node.js μέσω Java"
description: "Κλάση για κωδικοποίηση και αποκωδικοποίηση του κειμένου ενσωματωμένου στον κώδικα HIBC LIC που αποθηκεύει τα πρωτεύοντα δεδομένα."
type: docs
weight: 460
url: /el/nodejs/aspose.barcode/hibclicprimarydatacodetext/
---

## HIBCLICPrimaryDataCodetext class

Κλάση για κωδικοποίηση και αποκωδικοποίηση του κειμένου ενσωματωμένου στον κώδικα HIBC LIC που αποθηκεύει τα πρωτεύοντα δεδομένα. Αυτό το παράδειγμα δείχνει πώς να κωδικοποιήσετε και να αποκωδικοποιήσετε HIBC LIC χρησιμοποιώντας HIBCLICPrimaryCodetext.

```js
new HIBCLICPrimaryDataCodetext()
```

**Example:**

```js
let complexCodetext  = new HIBCLICPrimaryCodetext();
complexCodetext.setBarcodeType(EncodeTypes.HIBCQRLIC);
complexCodetext.setData(new PrimaryData());
complexCodetext.getData().setProductOrCatalogNumber("12345");
complexCodetext.getData().setLabelerIdentificationCode("A999");
complexCodetext.getData().setUnitOfMeasureID(1);
let generator = new ComplexBarcodeGenerator(complexCodetext);
let image = generator.generateBarCodeImage(BarCodeImageFormat.PNG);
let reader = new BarCodeReader(image, null, DecodeType.HIBCQRLIC);
reader.readBarCodes();
let codetext = reader.getFoundBarCodes()[0].getCodeText();
let result = ComplexCodetextReader.tryDecodeHIBCLIC(codetext) ;
print("Product or catalog number: " + result.getData().getProductOrCatalogNumber());
print("Labeler identification code: " + result.getData().getLabelerIdentificationCode());
print("Unit of measure ID: " + result.getData().getUnitOfMeasureID());
```

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [equals(obj)](#equals) | Επιστρέφει μια τιμή που υποδεικνύει εάν αυτή η περίπτωση είναι ίση με μια καθορισμένη τιμή `HIBCLICPrimaryDataCodetext`. |
| [getConstructedCodetext()](#getconstructedcodetext) | Δημιουργεί κείμενο κώδικα. |
| [getData()](#getdata) | Αναγνωρίζει τα πρωτεύοντα δεδομένα. |
| [hashCode()](#hashcode) | Επιστρέφει τον κωδικό κατακερματισμού για αυτήν την παρουσία. |
| [initFromString(constructedCodetext)](#initfromstring) | Αρχικοποιεί την παρουσία από το δημιουργημένο κείμενο κώδικα. |
| [setData()](#setdata) | Αναγνωρίζει τα πρωτεύοντα δεδομένα. |

### equals(obj) {#equals}

Επιστρέφει μια τιμή που υποδεικνύει εάν αυτή η περίπτωση είναι ίση με μια καθορισμένη τιμή `HIBCLICPrimaryDataCodetext`.

| Παράμετρος | Περιγραφή |
| --- | --- |
| obj | Μια τιμή `HIBCLICPrimaryDataCodetext` για σύγκριση με αυτήν την περίπτωση. |

**Returns:** `true ` if obj has the same value as this instance; otherwise, `false `.

### getConstructedCodetext() {#getconstructedcodetext}

Δημιουργεί κείμενο κώδικα.

**Returns:** Constructed codetext

### getData() {#getdata}

Αναγνωρίζει τα πρωτεύοντα δεδομένα.

### hashCode() {#hashcode}

Επιστρέφει τον κωδικό κατακερματισμού για αυτήν την παρουσία.

**Returns:** A 32-bit signed integer hash code.

### initFromString(constructedCodetext) {#initfromstring}

Αρχικοποιεί την παρουσία από το δημιουργημένο κείμενο κώδικα.

| Παράμετρος | Περιγραφή |
| --- | --- |
| constructedCodetext | Δημιουργημένο κείμενο κώδικα. |

### setData() {#setdata}

Αναγνωρίζει τα πρωτεύοντα δεδομένα.
