---
title: "DataMatrixParameters"
linktitle: "DataMatrixParameters"
second_title: "Αναφορά API του Aspose.BarCode για Node.js μέσω Java"
description: "Παράμετροι DataMatrix."
type: docs
weight: 360
url: /el/nodejs/aspose.barcode/datamatrixparameters/
---

## DataMatrixParameters class

Παράμετροι DataMatrix.

```js
new DataMatrixParameters()
```

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [getAspectRatio()](#getaspectratio) | Λόγος ύψους/πλάτους του μονάδας 2D BarCode. |
| [getColumns()](#getcolumns) | Αριθμός στηλών. |
| [getDataMatrixEcc()](#getdatamatrixecc) ~~(deprecated)~~ | Λαμβάνει έναν τύπο ECC του Datamatrix. Προεπιλεγμένη τιμή: DataMatrixEccType.ECC_200. |
| [getDataMatrixEncodeMode()](#getdatamatrixencodemode) ~~(deprecated)~~ | Λειτουργία κωδικοποίησης του barcode Datamatrix. Προεπιλεγμένη τιμή: DataMatrixEncodeMode.AUTO. |
| [getDataMatrixVersion()](#getdatamatrixversion) ~~(deprecated)~~ | Λαμβάνει το μέγεθος συμβόλου Datamatrix. Προεπιλεγμένη τιμή: DataMatrixVersion.Auto. |
| [getEccType()](#getecctype) | Λαμβάνει έναν τύπο ECC του Datamatrix. Προεπιλεγμένη τιμή: DataMatrixEccType.Ecc200. |
| [getECIEncoding()](#geteciencoding) | Λαμβάνει την κωδικοποίηση ECI. Χρησιμοποιείται όταν DataMatrixEncodeMode είναι Auto. Προεπιλεγμένη τιμή: ISO-8859-1 |
| [getEncodeMode()](#getencodemode) | Λειτουργία κωδικοποίησης του barcode Datamatrix. Προεπιλεγμένη τιμή: EncodeMode.Auto. |
| [getMacroCharacters()](#getmacrocharacters) | ISO/IEC 16022 5.2.4.7 Μακροχαρακτήρες 11.3 Πρωτόκολλο για μακροχαρακτήρες στην πρώτη θέση (μόνο ECC 200) Macro Cha |
| [getRows()](#getrows) | Αριθμός γραμμών. |
| [getStructuredAppendBarcodeId()](#getstructuredappendbarcodeid) | Αναγνωριστικό barcode για τη λειτουργία Structured Append του barcode Datamatrix. Προεπιλεγμένη τιμή: 0 |
| [getStructuredAppendBarcodesCount()](#getstructuredappendbarcodescount) | Αριθμός barcode για τη λειτουργία Structured Append του barcode Datamatrix. Προεπιλεγμένη τιμή: 0 |
| [getStructuredAppendFileId()](#getstructuredappendfileid) | Αναγνωριστικό αρχείου για τη λειτουργία Structured Append του barcode Datamatrix. Προεπιλεγμένη τιμή: 0 |
| [getVersion()](#getversion) | Λαμβάνει το μέγεθος συμβόλου Datamatrix. Προεπιλεγμένη τιμή: Version.Auto. |
| [isReaderProgramming()](#isreaderprogramming) | Χρησιμοποιείται για να καθοδηγήσει τον αναγνώστη να ερμηνεύσει τα δεδομένα που περιέχονται στο σύμβολο ως προγραμματισμό για την αρχικοποίηση του αναγνώστη. |
| [setAspectRatio()](#setaspectratio) | Λόγος ύψους/πλάτους του μονάδας 2D BarCode. |
| [setColumns()](#setcolumns) | Αριθμός στηλών. |
| [setDataMatrixEcc()](#setdatamatrixecc) ~~(deprecated)~~ | Ορίζει έναν τύπο ECC του Datamatrix. Προεπιλεγμένη τιμή: DataMatrixEccType.ECC_200. |
| [setDataMatrixEncodeMode()](#setdatamatrixencodemode) ~~(deprecated)~~ | Λειτουργία κωδικοποίησης του barcode Datamatrix. Προεπιλεγμένη τιμή: DataMatrixEncodeMode.AUTO. |
| [setDataMatrixVersion()](#setdatamatrixversion) ~~(deprecated)~~ | Ορίζει το μέγεθος συμβόλου Datamatrix. Προεπιλεγμένη τιμή: DataMatrixVersion.Auto. |
| [setEccType(value)](#setecctype) | Ορίζει έναν τύπο ECC του Datamatrix. Προεπιλεγμένη τιμή: DataMatrixEccType.Ecc200. |
| [setECIEncoding()](#seteciencoding) | Ορίζει την κωδικοποίηση ECI. Χρησιμοποιείται όταν DataMatrixEncodeMode είναι Auto. Προεπιλεγμένη τιμή: ISO-8859-1 |
| [setEncodeMode()](#setencodemode) | Λειτουργία κωδικοποίησης του barcode Datamatrix. Προεπιλεγμένη τιμή: EncodeMode.Auto. |
| [setMacroCharacters()](#setmacrocharacters) | ISO/IEC 16022 5.2.4.7 Μακροχαρακτήρες 11.3 Πρωτόκολλο για μακροχαρακτήρες στην πρώτη θέση (μόνο ECC 200) Macro Cha |
| [setReaderProgramming()](#setreaderprogramming) | Χρησιμοποιείται για να καθοδηγήσει τον αναγνώστη να ερμηνεύσει τα δεδομένα που περιέχονται στο σύμβολο ως προγραμματισμό για την αρχικοποίηση του αναγνώστη. |
| [setRows()](#setrows) | Αριθμός γραμμών. |
| [setStructuredAppendBarcodeId()](#setstructuredappendbarcodeid) | Αναγνωριστικό barcode για τη λειτουργία Structured Append του barcode Datamatrix. Προεπιλεγμένη τιμή: 0 |
| [setStructuredAppendBarcodesCount()](#setstructuredappendbarcodescount) | Αριθμός barcode για τη λειτουργία Structured Append του barcode Datamatrix. Προεπιλεγμένη τιμή: 0 |
| [setStructuredAppendFileId()](#setstructuredappendfileid) | Αναγνωριστικό αρχείου για τη λειτουργία Structured Append του barcode Datamatrix. Προεπιλεγμένη τιμή: 0 |
| [setVersion(value)](#setversion) | Ορίζει το μέγεθος συμβόλου Datamatrix. Προεπιλεγμένη τιμή: Version.Auto. |
| [toString()](#tostring) | Επιστρέφει μια αναγνώσιμη από άνθρωπο αναπαράσταση συμβολοσειράς αυτού του DataMatrixParameters. |

### getAspectRatio() {#getaspectratio}

Λόγος ύψους/πλάτους του μονάδας 2D BarCode.

### getColumns() {#getcolumns}

Αριθμός στηλών.

### getDataMatrixEcc() {#getdatamatrixecc}

> **Deprecated.** See method description for replacement.

Λαμβάνει έναν τύπο ECC του Datamatrix. Προεπιλεγμένη τιμή: DataMatrixEccType.ECC_200.

### getDataMatrixEncodeMode() {#getdatamatrixencodemode}

> **Deprecated.** See method description for replacement.

Λειτουργία κωδικοποίησης του barcode Datamatrix. Προεπιλεγμένη τιμή: DataMatrixEncodeMode.AUTO.

### getDataMatrixVersion() {#getdatamatrixversion}

> **Deprecated.** See method description for replacement.

Λαμβάνει το μέγεθος συμβόλου Datamatrix. Προεπιλεγμένη τιμή: DataMatrixVersion.Auto.

### getEccType() {#getecctype}

Λαμβάνει έναν τύπο ECC του Datamatrix. Προεπιλεγμένη τιμή: DataMatrixEccType.Ecc200.

**Returns:** a Datamatrix ECC type.

### getECIEncoding() {#geteciencoding}

Λαμβάνει την κωδικοποίηση ECI. Χρησιμοποιείται όταν DataMatrixEncodeMode είναι Auto. Προεπιλεγμένη τιμή: ISO-8859-1

### getEncodeMode() {#getencodemode}

Λειτουργία κωδικοποίησης του barcode Datamatrix. Προεπιλεγμένη τιμή: EncodeMode.Auto.

### getMacroCharacters() {#getmacrocharacters}

ISO/IEC 16022 5.2.4.7 Μακροχαρακτήρες 11.3 Πρωτόκολλο για Μακροχαρακτήρες στην πρώτη θέση (μόνο ECC 200) Οι τιμές Μακροχαρακτήρων 05 και 06 χρησιμοποιούνται για την απόκτηση πιο συμπαγούς κωδικοποίησης σε ειδικές λειτουργίες. Μπορεί να χρησιμοποιηθεί μόνο με DataMatrixEccType.ECC_200 ή DataMatrixEccType.ECC_AUTO. Δεν μπορεί να χρησιμοποιηθεί με EncodeTypes.GS_1_DATA_MATRIX Προεπιλεγμένη τιμή: MacroCharacter.NONE.

### getRows() {#getrows}

Αριθμός γραμμών.

### getStructuredAppendBarcodeId() {#getstructuredappendbarcodeid}

Αναγνωριστικό barcode για τη λειτουργία Structured Append του barcode Datamatrix. Προεπιλεγμένη τιμή: 0

### getStructuredAppendBarcodesCount() {#getstructuredappendbarcodescount}

Αριθμός barcode για τη λειτουργία Structured Append του barcode Datamatrix. Προεπιλεγμένη τιμή: 0

### getStructuredAppendFileId() {#getstructuredappendfileid}

Αναγνωριστικό αρχείου για τη λειτουργία Structured Append του barcode Datamatrix. Προεπιλεγμένη τιμή: 0

### getVersion() {#getversion}

Λαμβάνει το μέγεθος συμβόλου Datamatrix. Προεπιλεγμένη τιμή: Version.Auto.

**Returns:** a Datamatrix symbol size.

### isReaderProgramming() {#isreaderprogramming}

Χρησιμοποιείται για να καθοδηγήσει τον αναγνώστη να ερμηνεύσει τα δεδομένα που περιέχονται στο σύμβολο ως προγραμματισμό για την εκκίνηση του αναγνώστη. Προεπιλεγμένη τιμή: false

### setAspectRatio() {#setaspectratio}

Λόγος ύψους/πλάτους του μονάδας 2D BarCode.

### setColumns() {#setcolumns}

Αριθμός στηλών.

### setDataMatrixEcc() {#setdatamatrixecc}

> **Deprecated.** See method description for replacement.

Ορίζει έναν τύπο ECC του Datamatrix. Προεπιλεγμένη τιμή: DataMatrixEccType.ECC_200.

### setDataMatrixEncodeMode() {#setdatamatrixencodemode}

> **Deprecated.** See method description for replacement.

Λειτουργία κωδικοποίησης του barcode Datamatrix. Προεπιλεγμένη τιμή: DataMatrixEncodeMode.AUTO.

### setDataMatrixVersion() {#setdatamatrixversion}

> **Deprecated.** See method description for replacement.

Ορίζει το μέγεθος συμβόλου Datamatrix. Προεπιλεγμένη τιμή: DataMatrixVersion.Auto.

### setEccType(value) {#setecctype}

Ορίζει έναν τύπο ECC του Datamatrix. Προεπιλεγμένη τιμή: DataMatrixEccType.Ecc200.

| Παράμετρος | Περιγραφή |
| --- | --- |
| τιμή | ένας τύπος Datamatrix ECC. |

### setECIEncoding() {#seteciencoding}

Ορίζει την κωδικοποίηση ECI. Χρησιμοποιείται όταν DataMatrixEncodeMode είναι Auto. Προεπιλεγμένη τιμή: ISO-8859-1

### setEncodeMode() {#setencodemode}

Λειτουργία κωδικοποίησης του barcode Datamatrix. Προεπιλεγμένη τιμή: EncodeMode.Auto.

### setMacroCharacters() {#setmacrocharacters}

ISO/IEC 16022 5.2.4.7 Μακροχαρακτήρες 11.3 Πρωτόκολλο για Μακροχαρακτήρες στην πρώτη θέση (μόνο ECC 200) Οι τιμές Μακροχαρακτήρων 05 και 06 χρησιμοποιούνται για την απόκτηση πιο συμπαγούς κωδικοποίησης σε ειδικές λειτουργίες. Μπορεί να χρησιμοποιηθεί μόνο με DataMatrixEccType.ECC_200 ή DataMatrixEccType.ECC_AUTO. Δεν μπορεί να χρησιμοποιηθεί με EncodeTypes.GS_1_DATA_MATRIX Προεπιλεγμένη τιμή: MacroCharacter.NONE.

### setReaderProgramming() {#setreaderprogramming}

Χρησιμοποιείται για να καθοδηγήσει τον αναγνώστη να ερμηνεύσει τα δεδομένα που περιέχονται στο σύμβολο ως προγραμματισμό για την εκκίνηση του αναγνώστη. Προεπιλεγμένη τιμή: false

### setRows() {#setrows}

Αριθμός γραμμών.

### setStructuredAppendBarcodeId() {#setstructuredappendbarcodeid}

Αναγνωριστικό barcode για τη λειτουργία Structured Append του barcode Datamatrix. Προεπιλεγμένη τιμή: 0

### setStructuredAppendBarcodesCount() {#setstructuredappendbarcodescount}

Αριθμός barcode για τη λειτουργία Structured Append του barcode Datamatrix. Προεπιλεγμένη τιμή: 0

### setStructuredAppendFileId() {#setstructuredappendfileid}

Αναγνωριστικό αρχείου για τη λειτουργία Structured Append του barcode Datamatrix. Προεπιλεγμένη τιμή: 0

### setVersion(value) {#setversion}

Ορίζει το μέγεθος συμβόλου Datamatrix. Προεπιλεγμένη τιμή: Version.Auto.

| Παράμετρος | Περιγραφή |
| --- | --- |
| τιμή | ένα μέγεθος συμβόλου Datamatrix. |

### toString() {#tostring}

Επιστρέφει μια αναγνώσιμη από άνθρωπο αναπαράσταση συμβολοσειράς αυτού του DataMatrixParameters.

**Returns:** presentation of this DataMatrixParameters.
