---
title: "OneDExtendedParameters"
linktitle: "OneDExtendedParameters"
second_title: "Αναφορά API του Aspose.BarCode για Node.js μέσω Java"
description: "Αποθηκεύει ειδικά δεδομένα του αναγνωρισμένου 1D barcode, όπως ξεχωριστό κείμενο κωδικοποίησης και άθροισμα ελέγχου."
type: docs
weight: 720
url: /el/nodejs/aspose.barcode/onedextendedparameters/
---

## OneDExtendedParameters class

Αποθηκεύει ειδικά δεδομένα του αναγνωρισμένου 1D barcode, όπως ξεχωριστό κείμενο κωδικοποίησης και άθροισμα ελέγχου.

```js
new OneDExtendedParameters()
```

**Example:**

```js
//This sample shows how to get 1D barcode value and checksum
let generator = new BarcodeGenerator(EncodeTypes.EAN_13, "1234567890128");
generator.save("test.png");
let reader = new BarCodeReader("test.png", null,  DecodeType.EAN_13);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
   let result = results[i];
   console.log("BarCode Type: " + result.getCodeTypeName());
   console.log("BarCode CodeText: " + result.getCodeText());
   console.log("BarCode Value: " + result.getExtended().getOneD().getValue());
   console.log("BarCode Checksum: " + result.getExtended().getOneD().getCheckSum());
}
```

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [equals(obj)](#equals) | Επιστρέφει μια τιμή που υποδεικνύει εάν αυτή η παρουσία είναι ίση με μια καθορισμένη τιμή OneDExtendedParameters. |
| [getCheckSum()](#getchecksum) | Αποκτά το άθροισμα ελέγχου για 1D barcode. Τιμή: Το άθροισμα ελέγχου για 1D barcode. |
| [getValue()](#getvalue) | Αποκτά το κείμενο κώδικα των 1D barcode χωρίς άθροισμα ελέγχου. Τιμή: Το κείμενο κώδικα των 1D barcode χωρίς άθροισμα ελέγχου. |
| [hashCode()](#hashcode) | Επιστρέφει τον κωδικό κατακερματισμού για αυτήν την παρουσία. |
| [isEmpty()](#isempty) | Δοκιμάζει εάν όλες οι παράμετροι έχουν μόνο τις προεπιλεγμένες τιμές. Τιμή: Επιστρέφει `true` εάν όλες οι παράμετροι έχουν μόνο τις προεπιλεγμένες τιμές; o |
| [toString()](#tostring) | Επιστρέφει μια αναγνώσιμη από άνθρωπο αναπαράσταση συμβολοσειράς αυτού του OneDExtendedParameters. |

### equals(obj) {#equals}

Επιστρέφει μια τιμή που υποδεικνύει εάν αυτή η παρουσία είναι ίση με μια καθορισμένη τιμή OneDExtendedParameters.

| Παράμετρος | Περιγραφή |
| --- | --- |
| obj | Μια τιμή System.Object για σύγκριση με αυτήν την παρουσία. |

**Returns:** true if obj has the same value as this instance; otherwise, false.

### getCheckSum() {#getchecksum}

Αποκτά το άθροισμα ελέγχου για 1D barcode. Τιμή: Το άθροισμα ελέγχου για 1D barcode.

### getValue() {#getvalue}

Αποκτά το κείμενο κώδικα των 1D barcode χωρίς άθροισμα ελέγχου. Τιμή: Το κείμενο κώδικα των 1D barcode χωρίς άθροισμα ελέγχου.

### hashCode() {#hashcode}

Επιστρέφει τον κωδικό κατακερματισμού για αυτήν την παρουσία.

**Returns:** A 32-bit signed integer hash code.

### isEmpty() {#isempty}

Δοκιμάζει εάν όλες οι παράμετροι έχουν μόνο τις προεπιλεγμένες τιμές. Τιμή: Επιστρέφει `true` εάν όλες οι παράμετροι έχουν μόνο τις προεπιλεγμένες τιμές· διαφορετικά, `false`.

### toString() {#tostring}

Επιστρέφει μια αναγνώσιμη από άνθρωπο αναπαράσταση συμβολοσειράς αυτού του OneDExtendedParameters.

**Returns:** A string that represents this OneDExtendedParameters.
