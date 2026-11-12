---
title: "DataMatrixExtendedParameters"
linktitle: "DataMatrixExtendedParameters"
second_title: "Αναφορά API του Aspose.BarCode για Node.js μέσω Java"
description: "Αποθηκεύει ειδικά δεδομένα του DataMatrix barcode που αναγνωρίστηκε Αυτό το παράδειγμα δείχνει πώς να λάβετε τις ακατέργαστες τιμές DataMatrix let generator = new BarcodeGenerator(EncodeTypes.DATA_MA"
type: docs
weight: 350
url: /el/nodejs/aspose.barcode/datamatrixextendedparameters/
---

## DataMatrixExtendedParameters class

Αποθηκεύει ειδικά δεδομένα του DataMatrix barcode που αναγνωρίστηκε Αυτό το παράδειγμα δείχνει πώς να λάβετε τις ακατέργαστες τιμές DataMatrix let generator = new BarcodeGenerator(EncodeTypes.DATA_MATRIX, "12345")) generator.save("test.png", BarcodeImageFormat.PNG); let reader = new BarCodeReader("test.png", null, DecodeType.DATA_MATRIX)) let results = reader.readBarCodes(); for(let i = 0; i < results.length; i++) { let result = results[i]; console.log("BarCode type: " + result.getCodeTypeName()); console.log("BarCode codetext: " + result.getCodeText()); console.log("DataMatrix barcode ID: " + result.getExtended().getDataMatrix().getStructuredAppendBarcodeId()); console.log("DataMatrix barcodes count: " + result.getExtended().getDataMatrix().getStructuredAppendBarcodesCount()); console.log("DataMatrix file ID: " + result.getExtended().getDataMatrix().getStructuredAppendFileId()); console.log("DataMatrix is reader programming: " + result.getExtended().getDataMatrix().isReaderProgramming()); }

```js
new DataMatrixExtendedParameters()
```

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [equals(obj)](#equals) | Επιστρέφει μια τιμή που υποδεικνύει εάν αυτή η παρουσία είναι ίση με μια καθορισμένη τιμή `DataMatrixExtendedParameters`. |
| [getStructuredAppendBarcodeId()](#getstructuredappendbarcodeid) | Λαμβάνει το ID του barcode DataMatrix σε λειτουργία structured append. Το ID ξεκινά από 1 και πρέπει να είναι μικρότερο ή ίσο με τον αριθμό των barcode cou |
| [getStructuredAppendBarcodesCount()](#getstructuredappendbarcodescount) | Λαμβάνει τον αριθμό των barcode DataMatrix σε λειτουργία structured append. Η προεπιλεγμένη τιμή είναι -1. Ο αριθμός πρέπει να είναι τιμή από 1 έως 35. Valu |
| [getStructuredAppendFileId()](#getstructuredappendfileid) | Λαμβάνει το ID του barcode DataMatrix σε λειτουργία structured append. Το ID ξεκινά από 1 και πρέπει να είναι μικρότερο ή ίσο με τον αριθμό των barcode cou |
| [hashCode()](#hashcode) | Επιστρέφει τον κωδικό κατακερματισμού για αυτήν την παρουσία. |
| [isReaderProgramming()](#isreaderprogramming) | Δείχνει εάν ο κώδικας χρησιμοποιείται για να καθοδηγήσει τον αναγνώστη να ερμηνεύσει τα παρακάτω δεδομένα ως οδηγίες για την αρχικοποίηση ή |
| [toString()](#tostring) | Επιστρέφει μια αναγνώσιμη από άνθρωπο συμβολοσειρά που αντιπροσωπεύει αυτό το `DataMatrixExtendedParameters`. |

### equals(obj) {#equals}

Επιστρέφει μια τιμή που υποδεικνύει εάν αυτή η παρουσία είναι ίση με μια καθορισμένη τιμή `DataMatrixExtendedParameters`.

| Παράμετρος | Περιγραφή |
| --- | --- |
| obj | Μια τιμή System.Object για σύγκριση με αυτήν την παρουσία. |

**Returns:** `true ` if obj has the same value as this instance; otherwise, `false `.

### getStructuredAppendBarcodeId() {#getstructuredappendbarcodeid}

Λαμβάνει το ID του barcode DataMatrix σε λειτουργία structured append. Το ID ξεκινά από 1 και πρέπει να είναι μικρότερο ή ίσο με τον αριθμό των barcode. Η προεπιλεγμένη τιμή είναι -1. Τιμή: Το ID του barcode DataMatrix σε λειτουργία structured append.

### getStructuredAppendBarcodesCount() {#getstructuredappendbarcodescount}

Λαμβάνει τον αριθμό των barcode σε λειτουργία δομημένης προσθήκης DataMatrix. Η προεπιλεγμένη τιμή είναι -1. Ο αριθμός πρέπει να είναι τιμή από 1 έως 35. Τιμή: Ο αριθμός των barcode σε λειτουργία δομημένης προσθήκης DataMatrix.

### getStructuredAppendFileId() {#getstructuredappendfileid}

Λαμβάνει το ID του barcode DataMatrix σε λειτουργία structured append. Το ID ξεκινά από 1 και πρέπει να είναι μικρότερο ή ίσο με τον αριθμό των barcode. Η προεπιλεγμένη τιμή είναι -1. Τιμή: Το ID του barcode DataMatrix σε λειτουργία structured append.

### hashCode() {#hashcode}

Επιστρέφει τον κωδικό κατακερματισμού για αυτήν την παρουσία.

**Returns:** A 32-bit signed integer hash code.

### isReaderProgramming() {#isreaderprogramming}

Δείχνει εάν ο κώδικας χρησιμοποιείται για να καθοδηγήσει τον αναγνώστη να ερμηνεύσει τα παρακάτω δεδομένα ως οδηγίες για την αρχικοποίηση ή την επαναπρογραμματισμό του αναγνώστη barcode. Η προεπιλεγμένη τιμή είναι false.

### toString() {#tostring}

Επιστρέφει μια αναγνώσιμη από άνθρωπο συμβολοσειρά που αντιπροσωπεύει αυτό το `DataMatrixExtendedParameters`.

**Returns:** A string that represents this `DataMatrixExtendedParameters`.
