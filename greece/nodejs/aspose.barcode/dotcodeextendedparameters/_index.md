---
title: "DotCodeExtendedParameters"
linktitle: "DotCodeExtendedParameters"
second_title: "Αναφορά API του Aspose.BarCode για Node.js μέσω Java"
description: "Αποθηκεύει ειδικά δεδομένα του αναγνωρισμένου barcode DotCode. Αυτό το παράδειγμα δείχνει πώς να λάβετε τις ακατέργαστες τιμές DotCode"
type: docs
weight: 380
url: /el/nodejs/aspose.barcode/dotcodeextendedparameters/
---

## DotCodeExtendedParameters class

Αποθηκεύει ειδικά δεδομένα του αναγνωρισμένου barcode DotCode. Αυτό το παράδειγμα δείχνει πώς να λάβετε τις ακατέργαστες τιμές DotCode

```js
new DotCodeExtendedParameters()
```

**Example:**

```js
let generator = new BarcodeGenerator(EncodeTypes.DOT_CODE, "12345");
generator.save("test.png", BarCodeImageFormat.PNG);

let reader = new BarCodeReader("test.png", null, DecodeType.DOT_CODE);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
    let result = results[i];
    print("BarCode type: " + result.getCodeTypeName());
    print("BarCode codetext: " + result.getCodeText());
    print("DotCode barcode ID: " + result.getExtended().getDotCode().getDotCodeStructuredAppendModeBarcodeId());
    print("DotCode barcodes count: " + result.getExtended().getDotCode().getDotCodeStructuredAppendModeBarcodesCount());
}
```

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [equals(obj)](#equals) | Επιστρέφει μια τιμή που υποδεικνύει εάν αυτή η παρουσία είναι ίση με μια καθορισμένη τιμή `DotCodeExtendedParameters`. |
| [getDotCodeIsReaderInitialization()](#getdotcodeisreaderinitialization) ~~(deprecated)~~ | Δείχνει εάν ο κώδικας χρησιμοποιείται για να καθοδηγήσει τον αναγνώστη να ερμηνεύσει τα παρακάτω δεδομένα ως οδηγίες για την αρχικοποίηση ή |
| [getDotCodeStructuredAppendModeBarcodeId()](#getdotcodestructuredappendmodebarcodeid) ~~(deprecated)~~ | Αποκτά το ID του barcode DotCode σε δομημένη λειτουργία προσάρτησης. Το ID ξεκινά από 1 και πρέπει να είναι μικρότερο ή ίσο με τον αριθμό των barcode. |
| [getDotCodeStructuredAppendModeBarcodesCount()](#getdotcodestructuredappendmodebarcodescount) ~~(deprecated)~~ | Αποκτά τον αριθμό των barcode DotCode σε δομημένη λειτουργία προσάρτησης. Η προεπιλεγμένη τιμή είναι -1. Ο αριθμός πρέπει να είναι τιμή από 1 έως 35. Τιμή: |
| [getStructuredAppendModeBarcodeId()](#getstructuredappendmodebarcodeid) | Αποκτά το ID του barcode DotCode σε δομημένη λειτουργία προσάρτησης. Το ID ξεκινά από 1 και πρέπει να είναι μικρότερο ή ίσο με τον αριθμό των barcode. |
| [getStructuredAppendModeBarcodesCount()](#getstructuredappendmodebarcodescount) | Αποκτά τον αριθμό των barcode DotCode σε δομημένη λειτουργία προσάρτησης. Η προεπιλεγμένη τιμή είναι -1. Ο αριθμός πρέπει να είναι τιμή από 1 έως 35. Τιμή: |
| [hashCode()](#hashcode) | Επιστρέφει τον κωδικό κατακερματισμού για αυτήν την παρουσία. |
| [isReaderInitialization()](#isreaderinitialization) | Δείχνει εάν ο κώδικας χρησιμοποιείται για να καθοδηγήσει τον αναγνώστη να ερμηνεύσει τα παρακάτω δεδομένα ως οδηγίες για την αρχικοποίηση ή |
| [toString()](#tostring) | Επιστρέφει μια αναγνώσιμη από άνθρωπο αναπαράσταση συμβολοσειράς αυτού του `DotCodeExtendedParameters`. |

### equals(obj) {#equals}

Επιστρέφει μια τιμή που υποδεικνύει εάν αυτή η παρουσία είναι ίση με μια καθορισμένη τιμή `DotCodeExtendedParameters`.

| Παράμετρος | Περιγραφή |
| --- | --- |
| obj | Μια τιμή System.Object για σύγκριση με αυτήν την παρουσία. |

**Returns:** `true ` if obj has the same value as this instance; otherwise, `false `.

### getDotCodeIsReaderInitialization() {#getdotcodeisreaderinitialization}

> **Deprecated.** See method description for replacement.

Δείχνει εάν ο κώδικας χρησιμοποιείται για να καθοδηγήσει τον αναγνώστη να ερμηνεύσει τα παρακάτω δεδομένα ως οδηγίες για την αρχικοποίηση ή την επαναπρογραμματισμό του αναγνώστη barcode. Η προεπιλεγμένη τιμή είναι false.

### getDotCodeStructuredAppendModeBarcodeId() {#getdotcodestructuredappendmodebarcodeid}

> **Deprecated.** See method description for replacement.

Αποκτά το ID του barcode DotCode σε δομημένη λειτουργία προσάρτησης. Το ID ξεκινά από 1 και πρέπει να είναι μικρότερο ή ίσο με τον αριθμό των barcode. Η προεπιλεγμένη τιμή είναι -1. Τιμή: Το ID του barcode DotCode σε δομημένη λειτουργία προσάρτησης.

### getDotCodeStructuredAppendModeBarcodesCount() {#getdotcodestructuredappendmodebarcodescount}

> **Deprecated.** See method description for replacement.

Αποκτά τον αριθμό των barcode DotCode σε δομημένη λειτουργία προσάρτησης. Η προεπιλεγμένη τιμή είναι -1. Ο αριθμός πρέπει να είναι τιμή από 1 έως 35. Τιμή: Ο αριθμός των barcode DotCode σε δομημένη λειτουργία προσάρτησης.

### getStructuredAppendModeBarcodeId() {#getstructuredappendmodebarcodeid}

Αποκτά το ID του barcode DotCode σε δομημένη λειτουργία προσάρτησης. Το ID ξεκινά από 1 και πρέπει να είναι μικρότερο ή ίσο με τον αριθμό των barcode. Η προεπιλεγμένη τιμή είναι -1. Τιμή: Το ID του barcode DotCode σε δομημένη λειτουργία προσάρτησης.

**Returns:** the ID of the DotCode structured append mode barcode.

### getStructuredAppendModeBarcodesCount() {#getstructuredappendmodebarcodescount}

Αποκτά τον αριθμό των barcode DotCode σε δομημένη λειτουργία προσάρτησης. Η προεπιλεγμένη τιμή είναι -1. Ο αριθμός πρέπει να είναι τιμή από 1 έως 35. Τιμή: Ο αριθμός των barcode DotCode σε δομημένη λειτουργία προσάρτησης.

**Returns:** the DotCode structured append mode barcodes count.

### hashCode() {#hashcode}

Επιστρέφει τον κωδικό κατακερματισμού για αυτήν την παρουσία.

**Returns:** A 32-bit signed integer hash code.

### isReaderInitialization() {#isreaderinitialization}

Δείχνει εάν ο κώδικας χρησιμοποιείται για να καθοδηγήσει τον αναγνώστη να ερμηνεύσει τα παρακάτω δεδομένα ως οδηγίες για την αρχικοποίηση ή την επαναπρογραμματισμό του αναγνώστη barcode. Η προεπιλεγμένη τιμή είναι false.

### toString() {#tostring}

Επιστρέφει μια αναγνώσιμη από άνθρωπο αναπαράσταση συμβολοσειράς αυτού του `DotCodeExtendedParameters`.

**Returns:** A string that represents this `DotCodeExtendedParameters`.
