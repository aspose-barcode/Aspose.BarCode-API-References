---
title: "Pdf417ExtendedParameters"
linktitle: "Pdf417ExtendedParameters"
second_title: "Αναφορά API του Aspose.BarCode για Node.js μέσω Java"
description: "Αποθηκεύει μεταδεδομένα MacroPdf417 του αναγνωρισμένου barcode."
type: docs
weight: 760
url: /el/nodejs/aspose.barcode/pdf417extendedparameters/
---

## Pdf417ExtendedParameters class

Αποθηκεύει μεταδεδομένα MacroPdf417 του αναγνωρισμένου barcode.

```js
new Pdf417ExtendedParameters()
```

**Example:**

```js
//This sample shows how to get Macro Pdf417 metadata
let generator = new BarcodeGenerator(EncodeTypes.MacroPdf417, "12345");
generator.getParameters().getBarcode().getPdf417().setPdf417MacroFileID(10);
generator.getParameters().getBarcode().getPdf417().setPdf417MacroSegmentsCount(2);
generator.getParameters().getBarcode().getPdf417().setPdf417MacroSegmentID(1);
generator.save("test.png");
let reader = new BarCodeReader("test.png", null,  DecodeType.MACRO_PDF_417);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
    let result = results[i];
    console.log("BarCode Type: " + result.getCodeTypeName());
    console.log("BarCode CodeText: " + result.getCodeText());
    console.log("Macro Pdf417 FileID: " + result.getExtended().getPdf417().getMacroPdf417FileID());
    console.log("Macro Pdf417 Segments: " + result.getExtended().getPdf417().getMacroPdf417SegmentsCount());
    console.log("Macro Pdf417 SegmentID: " + result.getExtended().getPdf417().getMacroPdf417SegmentID());
}
```

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [equals(obj)](#equals) | Επιστρέφει μια τιμή που υποδεικνύει εάν αυτή η παρουσία είναι ίση με μια καθορισμένη τιμή Pdf417ExtendedParameters. |
| [getMacroPdf417Addressee()](#getmacropdf417addressee) | Όνομα παραλήπτη Macro PDF417 (προαιρετικό). |
| [getMacroPdf417Checksum()](#getmacropdf417checksum) | Άθροισμα ελέγχου Macro PDF417 (προαιρετικό). |
| [getMacroPdf417FileID()](#getmacropdf417fileid) | Αποκτά το αναγνωριστικό αρχείου του barcode, διαθέσιμο μόνο με MacroPdf417. Τιμή: Το αναγνωριστικό αρχείου για MacroPdf417 |
| [getMacroPdf417FileName()](#getmacropdf417filename) | Όνομα αρχείου Macro PDF417 (προαιρετικό). |
| [getMacroPdf417FileSize()](#getmacropdf417filesize) | Μέγεθος αρχείου Macro PDF417 (προαιρετικό). |
| [getMacroPdf417SegmentID()](#getmacropdf417segmentid) | Λαμβάνει το αναγνωριστικό τμήματος του γραμμωτού κώδικα, διαθέσιμο μόνο με MacroPdf417.Τιμή: Το αναγνωριστικό τμήματος του γραμμωτού κώδικα. |
| [getMacroPdf417SegmentsCount()](#getmacropdf417segmentscount) | Λαμβάνει τον αριθμό τμημάτων του γραμμωτού κώδικα macro pdf417. Η προεπιλεγμένη τιμή είναι -1.Τιμή: Αριθμός τμημάτων. |
| [getMacroPdf417Sender()](#getmacropdf417sender) | Όνομα αποστολέα Macro PDF417 (προαιρετικό). |
| [getMacroPdf417Terminator()](#getmacropdf417terminator) | Χρησιμοποιείται για να καθοδηγήσει τον αναγνώστη να ερμηνεύσει τα δεδομένα που περιέχονται στο σύμβολο ως προγραμματισμό για την αρχικοποίηση του αναγνώστη. |
| [getMacroPdf417TimeStamp()](#getmacropdf417timestamp) | Χρονική σήμανση Macro PDF417 (προαιρετικό). |
| [hashCode()](#hashcode) | Επιστρέφει τον κωδικό κατακερματισμού για αυτήν την παρουσία. |
| [isCode128Emulation()](#iscode128emulation) | Σημαία που υποδεικνύει ότι ο γραμμωτός κώδικας MicroPdf417 κωδικοποιείται με τις λέξεις κώδικα 908, 909, 910 ή 911 προσομοίωσης Code 128. |
| [isLinked()](#islinked) | Σημαία που υποδεικνύει ότι ο γραμμωτός κώδικας πρέπει να συνδεθεί με γραμμωτό κώδικα 1D. Τιμή: Σημαία σύνδεσης. |
| [isReaderInitialization()](#isreaderinitialization) | Χρησιμοποιείται για να καθοδηγήσει τον αναγνώστη να ερμηνεύσει τα δεδομένα που περιέχονται στο σύμβολο ως προγραμματισμό για την αρχικοποίηση του αναγνώστη. |
| [toString()](#tostring) | Επιστρέφει μια αναγνώσιμη από άνθρωπο αναπαράσταση συμβολοσειράς του Pdf417ExtendedParameters. |

### equals(obj) {#equals}

Επιστρέφει μια τιμή που υποδεικνύει εάν αυτή η παρουσία είναι ίση με μια καθορισμένη τιμή Pdf417ExtendedParameters.

| Παράμετρος | Περιγραφή |
| --- | --- |
| obj | Μια τιμή System.Object για σύγκριση με αυτήν την παρουσία. |

**Returns:** true if obj has the same value as this instance; otherwise, false.

### getMacroPdf417Addressee() {#getmacropdf417addressee}

Όνομα παραλήπτη Macro PDF417 (προαιρετικό).

**Returns:** Addressee name.

### getMacroPdf417Checksum() {#getmacropdf417checksum}

Άθροισμα ελέγχου Macro PDF417 (προαιρετικό).

**Returns:** Checksum.

### getMacroPdf417FileID() {#getmacropdf417fileid}

Αποκτά το αναγνωριστικό αρχείου του barcode, διαθέσιμο μόνο με MacroPdf417. Τιμή: Το αναγνωριστικό αρχείου για MacroPdf417

### getMacroPdf417FileName() {#getmacropdf417filename}

Όνομα αρχείου Macro PDF417 (προαιρετικό).

**Returns:** File name.

### getMacroPdf417FileSize() {#getmacropdf417filesize}

Μέγεθος αρχείου Macro PDF417 (προαιρετικό).

**Returns:** File size.

### getMacroPdf417SegmentID() {#getmacropdf417segmentid}

Λαμβάνει το αναγνωριστικό τμήματος του γραμμωτού κώδικα, διαθέσιμο μόνο με MacroPdf417.Τιμή: Το αναγνωριστικό τμήματος του γραμμωτού κώδικα.

### getMacroPdf417SegmentsCount() {#getmacropdf417segmentscount}

Λαμβάνει τον αριθμό τμημάτων του γραμμωτού κώδικα macro pdf417. Η προεπιλεγμένη τιμή είναι -1.Τιμή: Αριθμός τμημάτων.

### getMacroPdf417Sender() {#getmacropdf417sender}

Όνομα αποστολέα Macro PDF417 (προαιρετικό).

**Returns:** Sender name

### getMacroPdf417Terminator() {#getmacropdf417terminator}

Χρησιμοποιείται για να καθοδηγήσει τον αναγνώστη να ερμηνεύσει τα δεδομένα που περιέχονται στο σύμβολο ως προγραμματισμό για την αρχικοποίηση του αναγνώστη.

**Returns:** Reader initialization flag

### getMacroPdf417TimeStamp() {#getmacropdf417timestamp}

Χρονική σήμανση Macro PDF417 (προαιρετικό).

**Returns:** Time stamp.

### hashCode() {#hashcode}

Επιστρέφει τον κωδικό κατακερματισμού για αυτήν την παρουσία.

**Returns:** A 32-bit signed integer hash code.

### isCode128Emulation() {#iscode128emulation}

Σημαία που υποδεικνύει ότι ο γραμμωτός κώδικας MicroPdf417 κωδικοποιείται με τις λέξεις κώδικα 908, 909, 910 ή 911 προσομοίωσης Code 128.

**Returns:** Code 128 emulation flag

### isLinked() {#islinked}

Σημαία που υποδεικνύει ότι ο γραμμωτός κώδικας πρέπει να συνδεθεί με γραμμωτό κώδικα 1D. Τιμή: Σημαία σύνδεσης.

### isReaderInitialization() {#isreaderinitialization}

Χρησιμοποιείται για να καθοδηγήσει τον αναγνώστη να ερμηνεύσει τα δεδομένα που περιέχονται στο σύμβολο ως προγραμματισμό για την αρχικοποίηση του αναγνώστη.

**Returns:** Reader initialization flag

### toString() {#tostring}

Επιστρέφει μια αναγνώσιμη από άνθρωπο αναπαράσταση συμβολοσειράς του Pdf417ExtendedParameters.

**Returns:** A string that represents this Pdf417ExtendedParameters.
