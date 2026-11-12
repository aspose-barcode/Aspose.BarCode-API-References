---
title: "HIBCPASCodetext"
linktitle: "HIBCPASCodetext"
second_title: "Αναφορά API του Aspose.BarCode για Node.js μέσω Java"
description: "Κλάση για κωδικοποίηση και αποκωδικοποίηση του κειμένου ενσωματωμένου στον κώδικα HIBC PAS."
type: docs
weight: 480
url: /el/nodejs/aspose.barcode/hibcpascodetext/
---

## HIBCPASCodetext class

Κλάση για κωδικοποίηση και αποκωδικοποίηση του κειμένου ενσωματωμένου στον κώδικα HIBC PAS.

```js
new HIBCPASCodetext()
```

**Example:**

```js
This sample shows how to encode and decode HIBC PAS using HIBCPASCodetext.

 let complexCodetext = new HIBCPASComplexCodetext();
 complexCodetext.setDataLocation(HIBCPASDataLocation.PATIENT);
 complexCodetext.addRecord(HIBCPASDataType.LABELER_IDENTIFICATION_CODE, "A123");
 complexCodetext.addRecord(HIBCPASDataType.MANUFACTURER_SERIAL_NUMBER, "SERIAL123");
 complexCodetext.setBarcodeType(EncodeTypes.HIBC_DATA_MATRIX_PAS);
 let generator = new ComplexBarcodeGenerator(complexCodetext);
 BarCodeReader reader = new BarCodeReader(generator.generateBarCodeImage(BarCodeImageFormat.PNG), null, DecodeType.HIBC_DATA_MATRIX_PAS);
 reader.readBarCodes();
 let codetext = reader.getFoundBarCodes()[0].getCodeText();
	let readCodetext = ComplexCodetextReader.tryDecodeHIBCPAS(codetext);
 print("Data location: " + readCodetext.getDataLocation());
 print("Data type: " + readCodetext.getRecords()[0].getDataType());
 print("Data: " + readCodetext.getRecords()[0].getData());
 print("Data type: " + readCodetext.getRecords()[1].getDataType());
 print("Data: " + readCodetext.getRecords()[1].getData());
```

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [_fromMwObject()](#-frommwobject) *(static)* | Κατασκευαστής HIBCPASRecord |
| [addHIBCPASRecord(record)](#addhibcpasrecord) | Προσθέτει νέα εγγραφή |
| [addRecord(dataType, data)](#addrecord) | Προσθέτει νέα εγγραφή |
| [clear()](#clear) | Καθαρίζει τη λίστα εγγραφών |
| [equals(obj)](#equals) | Επιστρέφει μια τιμή που υποδεικνύει εάν αυτή η παρουσία είναι ίση με μια καθορισμένη τιμή `HIBCPASCodetext`. |
| [getBarcodeType()](#getbarcodetype) | Λαμβάνει τον τύπο barcode. |
| [getConstructedCodetext()](#getconstructedcodetext) | Δημιουργεί κείμενο κώδικα. |
| [getDataLocation()](#getdatalocation) | Καθορίζει τη θέση των δεδομένων. |
| [getRecords()](#getrecords) | Αποκτά τη λίστα εγγραφών |
| [hashCode()](#hashcode) | Επιστρέφει τον κωδικό κατακερματισμού για αυτήν την παρουσία. |
| [initFromString(constructedCodetext)](#initfromstring) | Αρχικοποιεί την παρουσία από το δημιουργημένο κείμενο κώδικα. |
| [setBarcodeType()](#setbarcodetype) | Αποκτά ή ορίζει τον τύπο του barcode. Το κείμενο κωδικοποίησης HIBC PAS μπορεί να κωδικοποιηθεί χρησιμοποιώντας HIBCCode39PAS, HIBCCode128PAS, HIBCAztec:PAS, HIBCData |
| [setDataLocation()](#setdatalocation) | Καθορίζει τη θέση των δεδομένων. |

### _fromMwObject() (static) {#-frommwobject}

Κατασκευαστής HIBCPASRecord

### addHIBCPASRecord(record) {#addhibcpasrecord}

Προσθέτει νέα εγγραφή

| Παράμετρος | Περιγραφή |
| --- | --- |
| εγγραφή | Εγγραφή προς προσθήκη |

### addRecord(dataType, data) {#addrecord}

Προσθέτει νέα εγγραφή

| Παράμετρος | Περιγραφή |
| --- | --- |
| dataType | Τύπος δεδομένων |
| data | Συμβολοσειρά δεδομένων |

### clear() {#clear}

Καθαρίζει τη λίστα εγγραφών

### equals(obj) {#equals}

Επιστρέφει μια τιμή που υποδεικνύει εάν αυτή η παρουσία είναι ίση με μια καθορισμένη τιμή `HIBCPASCodetext`.

| Παράμετρος | Περιγραφή |
| --- | --- |
| obj | Μια τιμή `HIBCPASCodetext` για σύγκριση με αυτή την παρουσία. |

**Returns:** `true ` if obj has the same value as this instance; otherwise, `false `.

### getBarcodeType() {#getbarcodetype}

Λαμβάνει τον τύπο barcode.

**Returns:** Barcode type.

### getConstructedCodetext() {#getconstructedcodetext}

Δημιουργεί κείμενο κώδικα.

**Returns:** Constructed codetext

### getDataLocation() {#getdatalocation}

Καθορίζει τη θέση των δεδομένων.

### getRecords() {#getrecords}

Αποκτά τη λίστα εγγραφών

**Returns:** List of records

### hashCode() {#hashcode}

Επιστρέφει τον κωδικό κατακερματισμού για αυτήν την παρουσία.

**Returns:** A 32-bit signed integer hash code.

### initFromString(constructedCodetext) {#initfromstring}

Αρχικοποιεί την παρουσία από το δημιουργημένο κείμενο κώδικα.

| Παράμετρος | Περιγραφή |
| --- | --- |
| constructedCodetext | Δημιουργημένο κείμενο κώδικα. |

### setBarcodeType() {#setbarcodetype}

Αποκτά ή ορίζει τον τύπο του barcode. Το κείμενο κωδικοποίησης HIBC PAS μπορεί να κωδικοποιηθεί χρησιμοποιώντας τους τύπους κωδικοποίησης HIBCCode39PAS, HIBCCode128PAS, HIBCAztec:PAS, HIBCDataMatrixPAS και HIBCQRPAS. Προεπιλεγμένη τιμή: HIBCCode39PAS.

**Returns:** Barcode type.

### setDataLocation() {#setdatalocation}

Καθορίζει τη θέση των δεδομένων.
