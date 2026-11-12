---
title: "HIBCLICCombinedCodetext"
linktitle: "HIBCLICCombinedCodetext"
second_title: "Αναφορά API του Aspose.BarCode για Node.js μέσω Java"
description: "Κλάση για κωδικοποίηση και αποκωδικοποίηση του κειμένου που ενσωματώνεται στον κώδικα HIBC LIC, ο οποίος αποθηκεύει πρωτεύοντα και δευτερεύοντα δεδομένα."
type: docs
weight: 440
url: /el/nodejs/aspose.barcode/hibcliccombinedcodetext/
---

## HIBCLICCombinedCodetext class

Κλάση για κωδικοποίηση και αποκωδικοποίηση του κειμένου που ενσωματώνεται στον κώδικα HIBC LIC, ο οποίος αποθηκεύει πρωτεύοντα και δευτερεύοντα δεδομένα. Αυτό το παράδειγμα δείχνει πώς να κωδικοποιήσετε και να αποκωδικοποιήσετε HIBC LIC χρησιμοποιώντας HIBCLICCombinedCodetext.

```js
new HIBCLICCombinedCodetext()
```

**Example:**

```js
let combinedCodetext = new HIBCLICCombinedCodetext();
combinedCodetext.setBarcodeType(EncodeTypes.HIBCQRLIC);
combinedCodetext.setPrimaryData(new PrimaryData());
combinedCodetext.getPrimaryData().setProductOrCatalogNumber("12345");
combinedCodetext.getPrimaryData().setLabelerIdentificationCode("A999");
combinedCodetext.getPrimaryData().setUnitOfMeasureID(1);
combinedCodetext.setSecondaryAndAdditionalData(new SecondaryAndAdditionalData());
combinedCodetext.getSecondaryAndAdditionalData().setExpiryDate(new Date());
combinedCodetext.getSecondaryAndAdditionalData().setExpiryDateFormat(HIBCLICDateFormat.MMDDYY);
combinedCodetext.getSecondaryAndAdditionalData().setQuantity(30);
combinedCodetext.getSecondaryAndAdditionalData().setLotNumber("LOT123");
combinedCodetext.getSecondaryAndAdditionalData().setSerialNumber("SERIAL123");
combinedCodetext.getSecondaryAndAdditionalData().setDateOfManufacture(new Date());
ComplexBarcodeGenerator generator = new ComplexBarcodeGenerator(combinedCodetext);
let image = generator.generateBarCodeImage(BarCodeImageFormat.PNG);
let reader = new BarCodeReader(image, null, DecodeType.HIBCQRLIC);
reader.readBarCodes();
let codetext = reader.getFoundBarCodes()[0].getCodeText();
let result = ComplexCodetextReader.tryDecodeHIBCLIC(codetext) ;
print("Product or catalog number: " + result.getPrimaryData().getProductOrCatalogNumber());
print("Labeler identification code: " + result.getPrimaryData().getLabelerIdentificationCode());
print("Unit of measure ID: " + result.getPrimaryData().getUnitOfMeasureID());
print("Expiry date: " + result.getSecondaryAndAdditionalData().getExpiryDate());
print("Quantity: " + result.getSecondaryAndAdditionalData().getQuantity());
print("Lot number: " + result.getSecondaryAndAdditionalData().getLotNumber());
print("Serial number: " + result.getSecondaryAndAdditionalData().getSerialNumber());
print("Date of manufacture: " + result.getSecondaryAndAdditionalData().getDateOfManufacture());
```

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [equals(obj)](#equals) | Επιστρέφει μια τιμή που υποδεικνύει εάν αυτή η παρουσία είναι ίση με μια καθορισμένη τιμή `HIBCLICCombinedCodetext`. |
| [getConstructedCodetext()](#getconstructedcodetext) | Δημιουργεί κείμενο κώδικα. |
| [getPrimaryData()](#getprimarydata) | Αναγνωρίζει τα πρωτεύοντα δεδομένα. |
| [getSecondaryAndAdditionalData()](#getsecondaryandadditionaldata) | Αναγνωρίζει τα δευτερεύοντα και πρόσθετα συμπληρωματικά δεδομένα. |
| [hashCode()](#hashcode) | Επιστρέφει τον κωδικό κατακερματισμού για αυτήν την παρουσία. |
| [initFromString(constructedCodetext)](#initfromstring) | Αρχικοποιεί την παρουσία από το δημιουργημένο κείμενο κώδικα. |
| [setPrimaryData()](#setprimarydata) | Αναγνωρίζει τα πρωτεύοντα δεδομένα. |
| [setSecondaryAndAdditionalData()](#setsecondaryandadditionaldata) | Αναγνωρίζει τα δευτερεύοντα και πρόσθετα συμπληρωματικά δεδομένα. |

### equals(obj) {#equals}

Επιστρέφει μια τιμή που υποδεικνύει εάν αυτή η παρουσία είναι ίση με μια καθορισμένη τιμή `HIBCLICCombinedCodetext`.

| Παράμετρος | Περιγραφή |
| --- | --- |
| obj | Μια τιμή `HIBCLICCombinedCodetext` για σύγκριση με αυτήν την παρουσία. |

**Returns:** `true ` if obj has the same value as this instance; otherwise, `false `.

### getConstructedCodetext() {#getconstructedcodetext}

Δημιουργεί κείμενο κώδικα.

**Returns:** Constructed codetext

### getPrimaryData() {#getprimarydata}

Αναγνωρίζει τα πρωτεύοντα δεδομένα.

### getSecondaryAndAdditionalData() {#getsecondaryandadditionaldata}

Αναγνωρίζει τα δευτερεύοντα και πρόσθετα συμπληρωματικά δεδομένα.

### hashCode() {#hashcode}

Επιστρέφει τον κωδικό κατακερματισμού για αυτήν την παρουσία.

**Returns:** A 32-bit signed integer hash code.

### initFromString(constructedCodetext) {#initfromstring}

Αρχικοποιεί την παρουσία από το δημιουργημένο κείμενο κώδικα.

| Παράμετρος | Περιγραφή |
| --- | --- |
| constructedCodetext | Δημιουργημένο κείμενο κώδικα. |

### setPrimaryData() {#setprimarydata}

Αναγνωρίζει τα πρωτεύοντα δεδομένα.

### setSecondaryAndAdditionalData() {#setsecondaryandadditionaldata}

Αναγνωρίζει τα δευτερεύοντα και πρόσθετα συμπληρωματικά δεδομένα.
