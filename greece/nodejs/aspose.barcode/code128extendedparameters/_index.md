---
title: "Code128ExtendedParameters"
linktitle: "Code128ExtendedParameters"
second_title: "Αναφορά API του Aspose.BarCode για Node.js μέσω Java"
description: "Αποθηκεύει ειδικά δεδομένα του αναγνωρισμένου barcode Code128. Αντιπροσωπεύει την περιοχή του αναγνωρισμένου barcode και τη γωνία του barcode."
type: docs
weight: 240
url: /el/nodejs/aspose.barcode/code128extendedparameters/
---

## Code128ExtendedParameters class

Αποθηκεύει ειδικά δεδομένα του αναγνωρισμένου barcode Code128. Αντιπροσωπεύει την περιοχή του αναγνωρισμένου barcode και τη γωνία του barcode.

```js
new Code128ExtendedParameters()
```

**Example:**

```js
//This sample shows how to get code128 raw values
let generator = new BarcodeGenerator(EncodeTypes.Code128, "12345");
generator.save("test.png");
let reader = new BarCodeReader("test.png", null,  DecodeType.CODE_128);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
   let result = results[i];
   console.log("BarCode Type: " + result.getCodeTypeName());
   console.log("BarCode CodeText: " + result.getCodeText());
   console.log("Code128 Data Portions: " + result.getExtended().getCode128());
}
```

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [equals(obj)](#equals) | Επιστρέφει μια τιμή που υποδεικνύει εάν αυτή η παρουσία είναι ίση με μια καθορισμένη τιμή Code128ExtendedParameters. |
| [getCode128DataPortions()](#getcode128dataportions) | Λαμβάνει τον πίνακα Code128DataPortion των αναγνωρισμένων barcode Code128. Τιμή του Code128DataPortion. |
| [hashCode()](#hashcode) | Επιστρέφει τον κωδικό κατακερματισμού για αυτήν την παρουσία. |
| [toString()](#tostring) | Επιστρέφει μια αναγνώσιμη από άνθρωπο αναπαράσταση συμβολοσειράς αυτού του Code128ExtendedParameters. |

### equals(obj) {#equals}

Επιστρέφει μια τιμή που υποδεικνύει εάν αυτή η παρουσία είναι ίση με μια καθορισμένη τιμή Code128ExtendedParameters.

| Παράμετρος | Περιγραφή |
| --- | --- |
| obj | Μια τιμή System.Object για σύγκριση με αυτήν την παρουσία. |

**Returns:** true if obj has the same value as this instance; otherwise, false.

### getCode128DataPortions() {#getcode128dataportions}

Λαμβάνει τον πίνακα Code128DataPortion των αναγνωρισμένων barcode Code128. Τιμή του Code128DataPortion.

### hashCode() {#hashcode}

Επιστρέφει τον κωδικό κατακερματισμού για αυτήν την παρουσία.

**Returns:** A 32-bit signed integer hash code.

### toString() {#tostring}

Επιστρέφει μια αναγνώσιμη από άνθρωπο αναπαράσταση συμβολοσειράς αυτού του Code128ExtendedParameters.

**Returns:** A string that represents this Code128ExtendedParameters.
