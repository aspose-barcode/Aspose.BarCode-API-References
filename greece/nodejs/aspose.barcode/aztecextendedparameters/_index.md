---
title: "AztecExtendedParameters"
linktitle: "AztecExtendedParameters"
second_title: "Αναφορά API του Aspose.BarCode για Node.js μέσω Java"
description: "Αποθηκεύει ειδικά δεδομένα του αναγνωρισμένου barcode Aztec. Αυτό το παράδειγμα δείχνει πώς να λάβετε τις ακατέργαστες τιμές Aztec let generator = new BarcodeGenerator(EncodeTypes.AZTEC, \"12345\"); "
type: docs
weight: 60
url: /el/nodejs/aspose.barcode/aztecextendedparameters/
---

## AztecExtendedParameters class

Αποθηκεύει ειδικά δεδομένα του αναγνωρισμένου barcode Aztec. Αυτό το παράδειγμα δείχνει πώς να λάβετε τις ακατέργαστες τιμές Aztec let generator = new BarcodeGenerator(EncodeTypes.AZTEC, "12345"); generator.save("test.png", BarcodeImageFormat.PNG);

```js
new AztecExtendedParameters()
```

**Example:**

```js
BarCodeReader reader = new BarCodeReader("test.png", null, DecodeType.AZTEC);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
    let result = results[i];
    console.log("BarCode type: " + result.getCodeTypeName());
    console.log("BarCode codetext: " + result.getCodeText());
    console.log("Aztec barcode ID: " + result.getExtended().getAztec().getStructuredAppendBarcodeId());
    console.log("Aztec barcodes count: " + result.getExtended().getAztec().getStructuredAppendBarcodesCount());
    console.log("Aztec file ID: " + result.getExtended().getAztec().getStructuredAppendFileId());
    console.log("Aztec is reader initialization: " + result.getExtended().getAztec().isReaderInitialization());
}
</pre>
</pre></blockquote></hr></p>
```

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [equals(obj)](#equals) | Επιστρέφει μια τιμή που υποδεικνύει αν αυτή η παρουσία είναι ίση με μια καθορισμένη τιμή `AztecExtendedParameters`. |
| [getStructuredAppendBarcodeId()](#getstructuredappendbarcodeid) | Αποκτά το ID του barcode σε λειτουργία δομημένης προσθήκης Aztec. Το ID ξεκινά από 1 και πρέπει να είναι μικρότερο ή ίσο με τον αριθμό των barcode. D |
| [getStructuredAppendBarcodesCount()](#getstructuredappendbarcodescount) | Αποκτά τον αριθμό των barcode σε λειτουργία δομημένης προσθήκης Aztec. Προεπιλεγμένη τιμή είναι 0. Ο αριθμός πρέπει να είναι τιμή από 1 έως 26. Value: The |
| [getStructuredAppendFileId()](#getstructuredappendfileid) | Αποκτά το αναγνωριστικό αρχείου (File ID) της λειτουργίας δομημένης προσθήκης Aztec. Προεπιλεγμένη τιμή είναι κενή συμβολοσειρά. Value: The File ID of the Aztec stru |
| [hashCode()](#hashcode) | Επιστρέφει τον κωδικό κατακερματισμού για αυτήν την παρουσία. |
| [isReaderInitialization()](#isreaderinitialization) | Δείχνει εάν ο κώδικας χρησιμοποιείται για να καθοδηγήσει τον αναγνώστη να ερμηνεύσει τα παρακάτω δεδομένα ως οδηγίες για την αρχικοποίηση ή |
| [toString()](#tostring) | Επιστρέφει μια αναγνώσιμη από άνθρωπο αναπαράσταση συμβολοσειράς αυτού του `AztecExtendedParameters`. |

### equals(obj) {#equals}

Επιστρέφει μια τιμή που υποδεικνύει αν αυτή η παρουσία είναι ίση με μια καθορισμένη τιμή `AztecExtendedParameters`.

| Παράμετρος | Περιγραφή |
| --- | --- |
| obj | Μια τιμή System.Object για σύγκριση με αυτήν την παρουσία. |

**Returns:** `true ` if obj has the same value as this instance; otherwise, `false `.

### getStructuredAppendBarcodeId() {#getstructuredappendbarcodeid}

Αποκτά το ID του barcode σε λειτουργία δομημένης προσθήκης Aztec. Το ID ξεκινά από 1 και πρέπει να είναι μικρότερο ή ίσο με τον αριθμό των barcode. Προεπιλεγμένη τιμή είναι 0. Τιμή: Το ID του barcode της λειτουργίας δομημένης προσθήκης Aztec.

### getStructuredAppendBarcodesCount() {#getstructuredappendbarcodescount}

Αποκτά τον αριθμό των barcode σε λειτουργία δομημένης προσθήκης Aztec. Προεπιλεγμένη τιμή είναι 0. Ο αριθμός πρέπει να είναι τιμή από 1 έως 26. Τιμή: Ο αριθμός των barcode της λειτουργίας δομημένης προσθήκης Aztec.

### getStructuredAppendFileId() {#getstructuredappendfileid}

Αποκτά το αναγνωριστικό αρχείου (File ID) της λειτουργίας δομημένης προσθήκης Aztec. Προεπιλεγμένη τιμή είναι κενή συμβολοσειρά. Τιμή: Το File ID της λειτουργίας δομημένης προσθήκης Aztec.

### hashCode() {#hashcode}

Επιστρέφει τον κωδικό κατακερματισμού για αυτήν την παρουσία.

**Returns:** 32-bit signed integer hash code.

### isReaderInitialization() {#isreaderinitialization}

Δείχνει εάν ο κώδικας χρησιμοποιείται για να καθοδηγήσει τον αναγνώστη να ερμηνεύσει τα παρακάτω δεδομένα ως οδηγίες για την αρχικοποίηση ή την επαναπρογραμματισμό του αναγνώστη barcode. Η προεπιλεγμένη τιμή είναι false.

### toString() {#tostring}

Επιστρέφει μια αναγνώσιμη από άνθρωπο αναπαράσταση συμβολοσειράς αυτού του `AztecExtendedParameters`.

**Returns:** A string that represents this `AztecExtendedParameters`.
