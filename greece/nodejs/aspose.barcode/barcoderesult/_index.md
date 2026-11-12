---
title: "BarCodeResult"
linktitle: "BarCodeResult"
second_title: "Αναφορά API του Aspose.BarCode για Node.js μέσω Java"
description: "Αποθηκεύει τα αναγνωρισμένα δεδομένα barcode όπως τύπο SingleDecodeType, `string` codetext, περιοχή BarCodeRegionParameters και άλλες παραμέτρους."
type: docs
weight: 110
url: /el/nodejs/aspose.barcode/barcoderesult/
---

## BarCodeResult class

Αποθηκεύει τα αναγνωρισμένα δεδομένα barcode όπως τύπο SingleDecodeType, `string` codetext, περιοχή BarCodeRegionParameters και άλλες παραμέτρους.

```js
new BarCodeResult()
```

**Example:**

```js
//This sample shows how to obtain BarCodeResult.
let generator = new BarcodeGenerator(EncodeTypes.Code128, "12345");
generator.save("test.png");
let reader = new BarCodeReader("test.png", null,  [ DecodeType.CODE_39, DecodeType.CODE_128 ]);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
   let result = results[i];
    console.log("BarCode Type: " + result.getCodeTypeName());
    console.log("BarCode CodeText: " + result.getCodeText());
    console.log("BarCode Confidence: " + result.getConfidence());
    console.log("BarCode ReadingQuality: " + result.getReadingQuality());
    console.log("BarCode Angle: " + result.getRegion().getAngle());
}
```

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [deepClone()](#deepclone) | Δημιουργεί ένα αντίγραφο της κλάσης BarCodeResult. |
| [equals(other)](#equals) | Επιστρέφει μια τιμή που υποδεικνύει εάν αυτή η παρουσία είναι ίση με μια καθορισμένη τιμή BarCodeResult. |
| [getCodeBytes()](#getcodebytes) | Αποκτά τα κωδικοποιημένα bytes του κώδικα. Τιμή: Τα bytes του κώδικα του barcode. |
| [getCodeText(encoding)](#getcodetext) | Αποκτά το κείμενο κώδικα με κωδικοποίηση. Αυτό το παράδειγμα δείχνει πώς να χρησιμοποιήσετε `getCodeText`: let gen = new BarcodeGenerator(EncodeType |
| [getCodeType()](#getcodetype) | Αποκτά τον τύπο του barcode. Τιμή: Οι πληροφορίες τύπου του αναγνωρισμένου barcode. |
| [getCodeTypeName()](#getcodetypename) | Αποκτά το όνομα του τύπου barcode. Τιμή: Το όνομα τύπου του αναγνωρισμένου barcode. |
| [getConfidence()](#getconfidence) | Αποκτά το επίπεδο εμπιστοσύνης αναγνώρισης του αναγνωρισμένου barcode. Τιμή: BarCodeConfidence.Strong δεν έχει ψεύτικα ή λανθασμένα misre |
| [getExtended()](#getextended) | Αποκτά τις επεκταμένες παραμέτρους του αναγνωρισμένου barcode. Τιμή: Οι επεκταμένες παράμετροι του αναγνωρισμένου barcode. |
| [getReadingQuality()](#getreadingquality) | Αποκτά την ποιότητα ανάγνωσης. Λειτουργεί για 1D και ταχυδρομικά barcodes. Τιμή: Το ποσοστό ποιότητας ανάγνωσης. |
| [getRegion()](#getregion) | Αποκτά την περιοχή του barcode. Τιμή: Η περιοχή του αναγνωρισμένου barcode. |
| [hashCode()](#hashcode) | Επιστρέφει τον κωδικό κατακερματισμού για αυτήν την παρουσία. |
| [toString()](#tostring) | Επιστρέφει μια αναγνώσιμη από άνθρωπο συμβολοσειρά αναπαράστασης αυτού του BarCodeResult. |

### deepClone() {#deepclone}

Δημιουργεί ένα αντίγραφο της κλάσης BarCodeResult.

**Returns:** Returns copy of BarCodeResult class.

### equals(other) {#equals}

Επιστρέφει μια τιμή που υποδεικνύει εάν αυτή η παρουσία είναι ίση με μια καθορισμένη τιμή BarCodeResult.

| Παράμετρος | Περιγραφή |
| --- | --- |
| άλλο | Μια τιμή BarCodeResult για σύγκριση με αυτήν την παρουσία. |

**Returns:** true if obj has the same value as this instance; otherwise, false.

### getCodeBytes() {#getcodebytes}

Αποκτά τα κωδικοποιημένα bytes του κώδικα. Τιμή: Τα bytes του κώδικα του barcode.

### getCodeText(encoding) {#getcodetext}

Αποκτά το κείμενο κώδικα με κωδικοποίηση. Αυτό το παράδειγμα δείχνει πώς να χρησιμοποιήσετε `getCodeText`: let gen = new BarcodeGenerator(EncodeTypes.DATA_MATRIX, null); gen.setCodeText("車種名", "932"); gen.save("barcode.png", BarCodeImageFormat.PNG); let reader = new BarCodeReader("barcode.png", null, DecodeType.DATA_MATRIX); let results = reader.readBarCodes(); for(let i = 0; i < results.length; i++) { let result = results[i]; console.log("BarCode CodeText: " + result.getCodeText("932")); }

| Παράμετρος | Περιγραφή |
| --- | --- |
| κωδικοποίηση | Η κωδικοποίηση για το codetext. |

**Returns:** A string containing recognized code text.

### getCodeType() {#getcodetype}

Αποκτά τον τύπο του barcode. Τιμή: Οι πληροφορίες τύπου του αναγνωρισμένου barcode.

### getCodeTypeName() {#getcodetypename}

Αποκτά το όνομα του τύπου barcode. Τιμή: Το όνομα τύπου του αναγνωρισμένου barcode.

### getConfidence() {#getconfidence}

Αποκτά το επίπεδο εμπιστοσύνης αναγνώρισης του αναγνωρισμένου barcode. Τιμή: BarCodeConfidence.Strong δεν έχει ψεύτικα ή λανθασμένες αναγνώσεις, BarCodeConfidence.Moderate μπορεί μερικές φορές να έχει ψεύτικα ή λανθασμένο codetext επειδή αυτό το επίπεδο εμπιστοσύνης για barcodews με αδύναμο checksum ή ακόμη και χωρίς αυτό, BarCodeConfidence.NONE έχει πάντα λανθασμένο codetext και μπορεί να είναι ψεύτικες αναγνώσεις.

### getExtended() {#getextended}

Αποκτά τις επεκταμένες παραμέτρους του αναγνωρισμένου barcode. Τιμή: Οι επεκταμένες παράμετροι του αναγνωρισμένου barcode.

### getReadingQuality() {#getreadingquality}

Αποκτά την ποιότητα ανάγνωσης. Λειτουργεί για 1D και ταχυδρομικά barcodes. Τιμή: Το ποσοστό ποιότητας ανάγνωσης.

### getRegion() {#getregion}

Αποκτά την περιοχή του barcode. Τιμή: Η περιοχή του αναγνωρισμένου barcode.

### hashCode() {#hashcode}

Επιστρέφει τον κωδικό κατακερματισμού για αυτήν την παρουσία.

**Returns:** A 32-bit signed integer hash code.

### toString() {#tostring}

Επιστρέφει μια αναγνώσιμη από άνθρωπο συμβολοσειρά αναπαράστασης αυτού του BarCodeResult.

**Returns:** A string that represents this BarCodeResult.
