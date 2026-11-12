---
title: "DotCodeParameters"
linktitle: "DotCodeParameters"
second_title: "Αναφορά API του Aspose.BarCode για Node.js μέσω Java"
description: "Παράμετροι DotCode."
type: docs
weight: 390
url: /el/nodejs/aspose.barcode/dotcodeparameters/
---

## DotCodeParameters class

Παράμετροι DotCode.

```js
new DotCodeParameters()
```

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [getAspectRatio()](#getaspectratio) | Λόγος ύψους/πλάτους του μονάδας 2D BarCode. |
| [getColumns()](#getcolumns) | Αναγνωρίζει τον αριθμό των στηλών. Το άθροισμα του αριθμού των γραμμών συν τον αριθμό των στηλών ενός συμβόλου DotCode πρέπει να είναι περιττό. Number o |
| [getDotCodeEncodeMode()](#getdotcodeencodemode) ~~(deprecated)~~ | Αναγνωρίζει τη λειτουργία κωδικοποίησης DotCode. Προεπιλεγμένη τιμή: Auto. |
| [getDotCodeStructuredAppendModeBarcodeId()](#getdotcodestructuredappendmodebarcodeid) ~~(deprecated)~~ | Αναγνωρίζει το ID του barcode λειτουργίας δομημένης προσθήκης DotCode. Το ID ξεκινά από 1 και πρέπει να είναι μικρότερο ή ίσο με τα barcodes |
| [getDotCodeStructuredAppendModeBarcodesCount()](#getdotcodestructuredappendmodebarcodescount) ~~(deprecated)~~ | Αναγνωρίζει τον αριθμό των barcode σε λειτουργία δομημένης προσθήκης DotCode. Η προεπιλεγμένη τιμή είναι -1. Ο αριθμός πρέπει να είναι τιμή από 1 έως 35. |
| [getECIEncoding()](#geteciencoding) | Αναγνωρίζει κωδικοποίηση ECI. Χρησιμοποιείται όταν το DotCodeEncodeMode είναι AUTO. Προεπιλεγμένη τιμή: ISO-8859-1 |
| [getEncodeMode()](#getencodemode) | Αναγνωρίζει τη λειτουργία κωδικοποίησης DotCode. Προεπιλεγμένη τιμή: Auto. |
| [getRows()](#getrows) | Αναγνωρίζει τον αριθμό των σειρών. Το άθροισμα του αριθμού των σειρών και του αριθμού των στηλών ενός συμβόλου DotCode πρέπει να είναι περιττό. Αριθμός r |
| [getStructuredAppendModeBarcodeId()](#getstructuredappendmodebarcodeid) | Αναγνωρίζει το ID του barcode λειτουργίας δομημένης προσθήκης DotCode. Το ID ξεκινά από 1 και πρέπει να είναι μικρότερο ή ίσο με τα barcodes |
| [getStructuredAppendModeBarcodesCount()](#getstructuredappendmodebarcodescount) | Αναγνωρίζει τον αριθμό των barcode σε λειτουργία δομημένης προσθήκης DotCode. Η προεπιλεγμένη τιμή είναι -1. Ο αριθμός πρέπει να είναι τιμή από 1 έως 35. |
| [isReaderInitialization()](#isreaderinitialization) | Δείχνει εάν ο κώδικας χρησιμοποιείται για να καθοδηγήσει τον αναγνώστη να ερμηνεύσει τα παρακάτω δεδομένα ως οδηγίες για την αρχικοποίηση ή |
| [setAspectRatio()](#setaspectratio) | Λόγος ύψους/πλάτους του μονάδας 2D BarCode. |
| [setColumns()](#setcolumns) | Αναγνωρίζει τον αριθμό των στηλών. Το άθροισμα του αριθμού των γραμμών συν τον αριθμό των στηλών ενός συμβόλου DotCode πρέπει να είναι περιττό. Number o |
| [setDotCodeEncodeMode()](#setdotcodeencodemode) ~~(deprecated)~~ | Αναγνωρίζει τη λειτουργία κωδικοποίησης DotCode. Προεπιλεγμένη τιμή: Auto. |
| [setDotCodeStructuredAppendModeBarcodeId()](#setdotcodestructuredappendmodebarcodeid) ~~(deprecated)~~ | Αναγνωρίζει το ID του barcode λειτουργίας δομημένης προσθήκης DotCode. Το ID ξεκινά από 1 και πρέπει να είναι μικρότερο ή ίσο με τα barcodes |
| [setDotCodeStructuredAppendModeBarcodesCount()](#setdotcodestructuredappendmodebarcodescount) ~~(deprecated)~~ | Αναγνωρίζει τον αριθμό των barcode σε λειτουργία δομημένης προσθήκης DotCode. Η προεπιλεγμένη τιμή είναι -1. Ο αριθμός πρέπει να είναι τιμή από 1 έως 35. |
| [setECIEncoding()](#seteciencoding) | Αναγνωρίζει κωδικοποίηση ECI. Χρησιμοποιείται όταν το DotCodeEncodeMode είναι AUTO. Προεπιλεγμένη τιμή: ISO-8859-1 |
| [setEncodeMode()](#setencodemode) | Αναγνωρίζει τη λειτουργία κωδικοποίησης DotCode. Προεπιλεγμένη τιμή: Auto. |
| [setReaderInitialization()](#setreaderinitialization) | Δείχνει εάν ο κώδικας χρησιμοποιείται για να καθοδηγήσει τον αναγνώστη να ερμηνεύσει τα παρακάτω δεδομένα ως οδηγίες για την αρχικοποίηση ή |
| [setRows()](#setrows) | Αναγνωρίζει τον αριθμό των σειρών. Το άθροισμα του αριθμού των σειρών και του αριθμού των στηλών ενός συμβόλου DotCode πρέπει να είναι περιττό. Αριθμός r |
| [setStructuredAppendModeBarcodeId()](#setstructuredappendmodebarcodeid) | Αναγνωρίζει το ID του barcode λειτουργίας δομημένης προσθήκης DotCode. Το ID ξεκινά από 1 και πρέπει να είναι μικρότερο ή ίσο με τα barcodes |
| [setStructuredAppendModeBarcodesCount()](#setstructuredappendmodebarcodescount) | Αναγνωρίζει τον αριθμό των barcode σε λειτουργία δομημένης προσθήκης DotCode. Η προεπιλεγμένη τιμή είναι -1. Ο αριθμός πρέπει να είναι τιμή από 1 έως 35. |
| [toString()](#tostring) | Επιστρέφει μια αναγνώσιμη από άνθρωπο αναπαράσταση συμβολοσειράς αυτού του DotCodeParameters. |

### getAspectRatio() {#getaspectratio}

Λόγος ύψους/πλάτους του μονάδας 2D BarCode.

### getColumns() {#getcolumns}

Αναγνωρίζει τον αριθμό των στηλών. Το άθροισμα του αριθμού των σειρών και του αριθμού των στηλών ενός συμβόλου DotCode πρέπει να είναι περιττό. Ο αριθμός των στηλών πρέπει να είναι τουλάχιστον 5. Προεπιλεγμένη τιμή: -1

### getDotCodeEncodeMode() {#getdotcodeencodemode}

> **Deprecated.** See method description for replacement.

Αναγνωρίζει τη λειτουργία κωδικοποίησης DotCode. Προεπιλεγμένη τιμή: Auto.

### getDotCodeStructuredAppendModeBarcodeId() {#getdotcodestructuredappendmodebarcodeid}

> **Deprecated.** See method description for replacement.

Αναγνωρίζει το ID του barcode DotCode σε λειτουργία structured append. Το ID ξεκινά από 1 και πρέπει να είναι μικρότερο ή ίσο με τον αριθμό των barcode. Η προεπιλεγμένη τιμή είναι -1.

### getDotCodeStructuredAppendModeBarcodesCount() {#getdotcodestructuredappendmodebarcodescount}

> **Deprecated.** See method description for replacement.

Αναγνωρίζει τον αριθμό των barcode σε λειτουργία δομημένης προσθήκης DotCode. Η προεπιλεγμένη τιμή είναι -1. Ο αριθμός πρέπει να είναι τιμή από 1 έως 35.

### getECIEncoding() {#geteciencoding}

Αναγνωρίζει κωδικοποίηση ECI. Χρησιμοποιείται όταν το DotCodeEncodeMode είναι AUTO. Προεπιλεγμένη τιμή: ISO-8859-1

### getEncodeMode() {#getencodemode}

Αναγνωρίζει τη λειτουργία κωδικοποίησης DotCode. Προεπιλεγμένη τιμή: Auto.

### getRows() {#getrows}

Αναγνωρίζει τον αριθμό των σειρών. Το άθροισμα του αριθμού των σειρών και του αριθμού των στηλών ενός συμβόλου DotCode πρέπει να είναι περιττό. Ο αριθμός των σειρών πρέπει να είναι τουλάχιστον 5. Προεπιλεγμένη τιμή: -1

### getStructuredAppendModeBarcodeId() {#getstructuredappendmodebarcodeid}

Αναγνωρίζει το ID του barcode DotCode σε λειτουργία structured append. Το ID ξεκινά από 1 και πρέπει να είναι μικρότερο ή ίσο με τον αριθμό των barcode. Η προεπιλεγμένη τιμή είναι -1.

### getStructuredAppendModeBarcodesCount() {#getstructuredappendmodebarcodescount}

Αναγνωρίζει τον αριθμό των barcode σε λειτουργία δομημένης προσθήκης DotCode. Η προεπιλεγμένη τιμή είναι -1. Ο αριθμός πρέπει να είναι τιμή από 1 έως 35.

### isReaderInitialization() {#isreaderinitialization}

Δείχνει εάν ο κώδικας χρησιμοποιείται για να καθοδηγήσει τον αναγνώστη να ερμηνεύσει τα παρακάτω δεδομένα ως οδηγίες για την αρχικοποίηση ή την επαναπρογραμματισμό του αναγνώστη barcode. Η προεπιλεγμένη τιμή είναι false.

### setAspectRatio() {#setaspectratio}

Λόγος ύψους/πλάτους του μονάδας 2D BarCode.

### setColumns() {#setcolumns}

Αναγνωρίζει τον αριθμό των στηλών. Το άθροισμα του αριθμού των σειρών και του αριθμού των στηλών ενός συμβόλου DotCode πρέπει να είναι περιττό. Ο αριθμός των στηλών πρέπει να είναι τουλάχιστον 5. Προεπιλεγμένη τιμή: -1

### setDotCodeEncodeMode() {#setdotcodeencodemode}

> **Deprecated.** See method description for replacement.

Αναγνωρίζει τη λειτουργία κωδικοποίησης DotCode. Προεπιλεγμένη τιμή: Auto.

### setDotCodeStructuredAppendModeBarcodeId() {#setdotcodestructuredappendmodebarcodeid}

> **Deprecated.** See method description for replacement.

Αναγνωρίζει το ID του barcode DotCode σε λειτουργία structured append. Το ID ξεκινά από 1 και πρέπει να είναι μικρότερο ή ίσο με τον αριθμό των barcode. Η προεπιλεγμένη τιμή είναι -1.

### setDotCodeStructuredAppendModeBarcodesCount() {#setdotcodestructuredappendmodebarcodescount}

> **Deprecated.** See method description for replacement.

Αναγνωρίζει τον αριθμό των barcode σε λειτουργία δομημένης προσθήκης DotCode. Η προεπιλεγμένη τιμή είναι -1. Ο αριθμός πρέπει να είναι τιμή από 1 έως 35.

### setECIEncoding() {#seteciencoding}

Αναγνωρίζει κωδικοποίηση ECI. Χρησιμοποιείται όταν το DotCodeEncodeMode είναι AUTO. Προεπιλεγμένη τιμή: ISO-8859-1

### setEncodeMode() {#setencodemode}

Αναγνωρίζει τη λειτουργία κωδικοποίησης DotCode. Προεπιλεγμένη τιμή: Auto.

### setReaderInitialization() {#setreaderinitialization}

Δείχνει εάν ο κώδικας χρησιμοποιείται για να καθοδηγήσει τον αναγνώστη να ερμηνεύσει τα παρακάτω δεδομένα ως οδηγίες για την αρχικοποίηση ή την επαναπρογραμματισμό του αναγνώστη barcode. Η προεπιλεγμένη τιμή είναι false.

### setRows() {#setrows}

Αναγνωρίζει τον αριθμό των σειρών. Το άθροισμα του αριθμού των σειρών και του αριθμού των στηλών ενός συμβόλου DotCode πρέπει να είναι περιττό. Ο αριθμός των σειρών πρέπει να είναι τουλάχιστον 5. Προεπιλεγμένη τιμή: -1

### setStructuredAppendModeBarcodeId() {#setstructuredappendmodebarcodeid}

Αναγνωρίζει το ID του barcode DotCode σε λειτουργία structured append. Το ID ξεκινά από 1 και πρέπει να είναι μικρότερο ή ίσο με τον αριθμό των barcode. Η προεπιλεγμένη τιμή είναι -1.

### setStructuredAppendModeBarcodesCount() {#setstructuredappendmodebarcodescount}

Αναγνωρίζει τον αριθμό των barcode σε λειτουργία δομημένης προσθήκης DotCode. Η προεπιλεγμένη τιμή είναι -1. Ο αριθμός πρέπει να είναι τιμή από 1 έως 35.

### toString() {#tostring}

Επιστρέφει μια αναγνώσιμη από άνθρωπο αναπαράσταση συμβολοσειράς αυτού του DotCodeParameters.

**Returns:** A string that represents this DotCodeParameters.
