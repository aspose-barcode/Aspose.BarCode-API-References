---
title: "AztecParameters"
linktitle: "AztecParameters"
second_title: "Αναφορά API του Aspose.BarCode για Node.js μέσω Java"
description: "Παράμετροι Aztec."
type: docs
weight: 70
url: /el/nodejs/aspose.barcode/aztecparameters/
---

## AztecParameters class

Παράμετροι Aztec.

```js
new AztecParameters()
```

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [getAspectRatio()](#getaspectratio) | Λόγος ύψους/πλάτους του μονάδας 2D BarCode. |
| [getAztecEncodeMode()](#getaztecencodemode) ~~(deprecated)~~ | Λαμβάνει μια λειτουργία κωδικοποίησης Aztec. Προεπιλεγμένη τιμή: Auto. |
| [getAztecErrorLevel()](#getaztecerrorlevel) ~~(deprecated)~~ | Επίπεδο διόρθωσης σφαλμάτων των τύπων barcode Aztec. Η τιμή πρέπει να είναι μεταξύ 5 και 95. |
| [getAztecSymbolMode()](#getaztecsymbolmode) ~~(deprecated)~~ | Λαμβάνει μια λειτουργία συμβόλου Aztec. Προεπιλεγμένη τιμή: AztecSymbolMode.Auto. |
| [getECIEncoding()](#geteciencoding) | Λαμβάνει κωδικοποίηση ECI. Χρησιμοποιείται όταν AztecEncodeMode είναι Auto. Προεπιλεγμένη τιμή: ISO-8859-1 |
| [getEncodeMode()](#getencodemode) | Λαμβάνει μια λειτουργία κωδικοποίησης Aztec. Προεπιλεγμένη τιμή: Auto. |
| [getErrorLevel()](#geterrorlevel) | Επίπεδο διόρθωσης σφαλμάτων των τύπων barcode Aztec. Η τιμή πρέπει να είναι μεταξύ 5 και 95. |
| [getLayersCount()](#getlayerscount) | Λαμβάνει τον αριθμό επιπέδων του συμβόλου Aztec. Ο αριθμός επιπέδων πρέπει να είναι στο εύρος από 1 έως 3 για λειτουργία Compact και στο εύρος από 1 έως 3 |
| [getStructuredAppendBarcodeId()](#getstructuredappendbarcodeid) | Αναγνωριστικό Barcode για λειτουργία Structured Append του Aztec barcode. Το Barcode ID πρέπει να είναι στο εύρος από 1 έως τον αριθμό των barcode. Προεπιλογή |
| [getStructuredAppendBarcodesCount()](#getstructuredappendbarcodescount) | Ο αριθμός των barcode για τη λειτουργία Structured Append του κώδικα Aztec. Ο αριθμός των barcode πρέπει να είναι στο εύρος από 1 έως 26. Προεπιλεγμένη τιμή |
| [getStructuredAppendFileId()](#getstructuredappendfileid) | Αναγνωριστικό αρχείου για τη λειτουργία Structured Append του κώδικα Aztec (προαιρετικό πεδίο). Το αναγνωριστικό αρχείου δεν πρέπει να περιέχει κενά. Προεπιλεγμένη τιμή: |
| [getSymbolMode()](#getsymbolmode) | Λαμβάνει μια λειτουργία συμβόλου Aztec. Προεπιλεγμένη τιμή: AztecSymbolMode.Auto. |
| [isReaderInitialization()](#isreaderinitialization) | Χρησιμοποιείται για να καθοδηγήσει τον αναγνώστη να ερμηνεύσει τα δεδομένα που περιέχονται στο σύμβολο ως προγραμματισμό για την αρχικοποίηση του αναγνώστη. |
| [setAspectRatio()](#setaspectratio) | Λόγος ύψους/πλάτους του μονάδας 2D BarCode. |
| [setAztecEncodeMode()](#setaztecencodemode) ~~(deprecated)~~ | Ορίζει μια λειτουργία κωδικοποίησης Aztec. Προεπιλεγμένη τιμή: Auto. |
| [setAztecErrorLevel()](#setaztecerrorlevel) ~~(deprecated)~~ | Επίπεδο διόρθωσης σφαλμάτων των τύπων barcode Aztec. Η τιμή πρέπει να είναι μεταξύ 5 και 95. |
| [setAztecSymbolMode()](#setaztecsymbolmode) ~~(deprecated)~~ | Ορίζει μια λειτουργία συμβόλου Aztec. Προεπιλεγμένη τιμή: AztecSymbolMode.Auto. |
| [setECIEncoding()](#seteciencoding) | Ορίζει κωδικοποίηση ECI. Χρησιμοποιείται όταν AztecEncodeMode είναι Auto. Προεπιλεγμένη τιμή: ISO-8859-1 |
| [setEncodeMode(value)](#setencodemode) | Ορίζει μια λειτουργία κωδικοποίησης Aztec. Προεπιλεγμένη τιμή: Auto. |
| [setErrorLevel()](#seterrorlevel) | Επίπεδο διόρθωσης σφαλμάτων των τύπων barcode Aztec. Η τιμή πρέπει να είναι μεταξύ 5 και 95. |
| [setLayersCount()](#setlayerscount) | Ορίζει τον αριθμό των επιπέδων του συμβόλου Aztec. Ο αριθμός των επιπέδων πρέπει να είναι στο εύρος από 1 έως 3 για τη λειτουργία Compact και στο εύρος από 1 έως 3 |
| [setReaderInitialization()](#setreaderinitialization) | Χρησιμοποιείται για να καθοδηγήσει τον αναγνώστη να ερμηνεύσει τα δεδομένα που περιέχονται στο σύμβολο ως προγραμματισμό για την αρχικοποίηση του αναγνώστη. |
| [setStructuredAppendBarcodeId()](#setstructuredappendbarcodeid) | Αναγνωριστικό Barcode για λειτουργία Structured Append του Aztec barcode. Το Barcode ID πρέπει να είναι στο εύρος από 1 έως τον αριθμό των barcode. Προεπιλογή |
| [setStructuredAppendBarcodesCount()](#setstructuredappendbarcodescount) | Ο αριθμός των barcode για τη λειτουργία Structured Append του κώδικα Aztec. Ο αριθμός των barcode πρέπει να είναι στο εύρος από 1 έως 26. Προεπιλεγμένη τιμή |
| [setStructuredAppendFileId()](#setstructuredappendfileid) | Αναγνωριστικό αρχείου για τη λειτουργία Structured Append του κώδικα Aztec (προαιρετικό πεδίο). Το αναγνωριστικό αρχείου δεν πρέπει να περιέχει κενά. Προεπιλεγμένη τιμή: |
| [setSymbolMode(value)](#setsymbolmode) | Ορίζει μια λειτουργία συμβόλου Aztec. Προεπιλεγμένη τιμή: AztecSymbolMode.Auto. |
| [toString()](#tostring) | Επιστρέφει μια αναγνώσιμη από άνθρωπο αναπαράσταση συμβολοσειράς αυτού του `AztecParameters`. |

### getAspectRatio() {#getaspectratio}

Λόγος ύψους/πλάτους του μονάδας 2D BarCode.

### getAztecEncodeMode() {#getaztecencodemode}

> **Deprecated.** See method description for replacement.

Λαμβάνει μια λειτουργία κωδικοποίησης Aztec. Προεπιλεγμένη τιμή: Auto.

### getAztecErrorLevel() {#getaztecerrorlevel}

> **Deprecated.** See method description for replacement.

Επίπεδο διόρθωσης σφαλμάτων των τύπων barcode Aztec. Η τιμή πρέπει να είναι μεταξύ 5 και 95.

### getAztecSymbolMode() {#getaztecsymbolmode}

> **Deprecated.** See method description for replacement.

Λαμβάνει μια λειτουργία συμβόλου Aztec. Προεπιλεγμένη τιμή: AztecSymbolMode.Auto.

### getECIEncoding() {#geteciencoding}

Λαμβάνει κωδικοποίηση ECI. Χρησιμοποιείται όταν AztecEncodeMode είναι Auto. Προεπιλεγμένη τιμή: ISO-8859-1

### getEncodeMode() {#getencodemode}

Λαμβάνει μια λειτουργία κωδικοποίησης Aztec. Προεπιλεγμένη τιμή: Auto.

**Returns:** a Aztec encode mode.

### getErrorLevel() {#geterrorlevel}

Επίπεδο διόρθωσης σφαλμάτων των τύπων barcode Aztec. Η τιμή πρέπει να είναι μεταξύ 5 και 95.

### getLayersCount() {#getlayerscount}

Λαμβάνει τον αριθμό των επιπέδων του συμβόλου Aztec. Ο αριθμός των επιπέδων πρέπει να είναι στο εύρος από 1 έως 3 για τη λειτουργία Compact και στο εύρος από 1 έως 32 για τη λειτουργία Full Range. Προεπιλεγμένη τιμή: 0 (auto).

### getStructuredAppendBarcodeId() {#getstructuredappendbarcodeid}

Αναγνωριστικό barcode για τη λειτουργία Structured Append του κώδικα Aztec. Το αναγνωριστικό barcode πρέπει να είναι στο εύρος από 1 έως τον αριθμό των barcode. Προεπιλεγμένη τιμή: 0

### getStructuredAppendBarcodesCount() {#getstructuredappendbarcodescount}

Αριθμός barcode για τη λειτουργία Structured Append του κώδικα Aztec. Ο αριθμός των barcode πρέπει να είναι στο εύρος από 1 έως 26. Προεπιλεγμένη τιμή: 0

### getStructuredAppendFileId() {#getstructuredappendfileid}

Αναγνωριστικό αρχείου για τη λειτουργία Structured Append του κώδικα Aztec (προαιρετικό πεδίο). Το αναγνωριστικό αρχείου δεν πρέπει να περιέχει κενά. Προεπιλεγμένη τιμή: κενή συμβολοσειρά

### getSymbolMode() {#getsymbolmode}

Λαμβάνει μια λειτουργία συμβόλου Aztec. Προεπιλεγμένη τιμή: AztecSymbolMode.Auto.

**Returns:** a Aztec Symbol mode.

### isReaderInitialization() {#isreaderinitialization}

Χρησιμοποιείται για να καθοδηγήσει τον αναγνώστη να ερμηνεύσει τα δεδομένα που περιέχονται στο σύμβολο ως προγραμματισμό για την αρχικοποίηση του αναγνώστη.

### setAspectRatio() {#setaspectratio}

Λόγος ύψους/πλάτους του μονάδας 2D BarCode.

### setAztecEncodeMode() {#setaztecencodemode}

> **Deprecated.** See method description for replacement.

Ορίζει μια λειτουργία κωδικοποίησης Aztec. Προεπιλεγμένη τιμή: Auto.

### setAztecErrorLevel() {#setaztecerrorlevel}

> **Deprecated.** See method description for replacement.

Επίπεδο διόρθωσης σφαλμάτων των τύπων barcode Aztec. Η τιμή πρέπει να είναι μεταξύ 5 και 95.

### setAztecSymbolMode() {#setaztecsymbolmode}

> **Deprecated.** See method description for replacement.

Ορίζει μια λειτουργία συμβόλου Aztec. Προεπιλεγμένη τιμή: AztecSymbolMode.Auto.

### setECIEncoding() {#seteciencoding}

Ορίζει κωδικοποίηση ECI. Χρησιμοποιείται όταν AztecEncodeMode είναι Auto. Προεπιλεγμένη τιμή: ISO-8859-1

### setEncodeMode(value) {#setencodemode}

Ορίζει μια λειτουργία κωδικοποίησης Aztec. Προεπιλεγμένη τιμή: Auto.

| Παράμετρος | Περιγραφή |
| --- | --- |
| τιμή | μια λειτουργία κωδικοποίησης Aztec. |

### setErrorLevel() {#seterrorlevel}

Επίπεδο διόρθωσης σφαλμάτων των τύπων barcode Aztec. Η τιμή πρέπει να είναι μεταξύ 5 και 95.

### setLayersCount() {#setlayerscount}

Ορίζει τον αριθμό των επιπέδων του συμβόλου Aztec. Ο αριθμός των επιπέδων πρέπει να είναι στο εύρος από 1 έως 3 για τη λειτουργία Compact και στο εύρος από 1 έως 32 για τη λειτουργία Full Range. Προεπιλεγμένη τιμή: 0 (auto).

### setReaderInitialization() {#setreaderinitialization}

Χρησιμοποιείται για να καθοδηγήσει τον αναγνώστη να ερμηνεύσει τα δεδομένα που περιέχονται στο σύμβολο ως προγραμματισμό για την αρχικοποίηση του αναγνώστη.

### setStructuredAppendBarcodeId() {#setstructuredappendbarcodeid}

Αναγνωριστικό barcode για τη λειτουργία Structured Append του κώδικα Aztec. Το αναγνωριστικό barcode πρέπει να είναι στο εύρος από 1 έως τον αριθμό των barcode. Προεπιλεγμένη τιμή: 0

### setStructuredAppendBarcodesCount() {#setstructuredappendbarcodescount}

Αριθμός barcode για τη λειτουργία Structured Append του κώδικα Aztec. Ο αριθμός των barcode πρέπει να είναι στο εύρος από 1 έως 26. Προεπιλεγμένη τιμή: 0

### setStructuredAppendFileId() {#setstructuredappendfileid}

Αναγνωριστικό αρχείου για τη λειτουργία Structured Append του κώδικα Aztec (προαιρετικό πεδίο). Το αναγνωριστικό αρχείου δεν πρέπει να περιέχει κενά. Προεπιλεγμένη τιμή: κενή συμβολοσειρά

### setSymbolMode(value) {#setsymbolmode}

Ορίζει μια λειτουργία συμβόλου Aztec. Προεπιλεγμένη τιμή: AztecSymbolMode.Auto.

| Παράμετρος | Περιγραφή |
| --- | --- |
| τιμή | μια λειτουργία συμβόλου Aztec. |

### toString() {#tostring}

Επιστρέφει μια αναγνώσιμη από άνθρωπο αναπαράσταση συμβολοσειράς αυτού του `AztecParameters`.

**Returns:** A string that represents this `AztecParameters`.
