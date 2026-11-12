---
title: "QRExtendedParameters"
linktitle: "QRExtendedParameters"
second_title: "Αναφορά API του Aspose.BarCode για Node.js μέσω Java"
description: "Αποθηκεύει πληροφορίες QR Structured Append του αναγνωρισμένου barcode."
type: docs
weight: 810
url: /el/nodejs/aspose.barcode/qrextendedparameters/
---

## QRExtendedParameters class

Αποθηκεύει πληροφορίες QR Structured Append του αναγνωρισμένου barcode.

```js
new QRExtendedParameters()
```

**Example:**

```js
//This sample shows how to get QR Structured Append data

let reader = new BarCodeReader("test.png", null,  DecodeType.QR);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
   let result = results[i];
   console.log("BarCode Type: " + result.getCodeTypeName());
   console.log("BarCode CodeText: " + result.getCodeText());
   console.log("QR Structured Append Quantity: " + result.getExtended().getQR().getQRStructuredAppendModeBarCodesQuantity());
   console.log("QR Structured Append Index: " + result.getExtended().getQR().getQRStructuredAppendModeBarCodeIndex());
   console.log("QR Structured Append ParityData: " + result.getExtended().getQR().getQRStructuredAppendModeParityData());
}
```

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [equals(obj)](#equals) | Επιστρέφει μια τιμή που υποδεικνύει εάν αυτό το αντικείμενο είναι ίσο με μια συγκεκριμένη τιμή του QRExtendedParameters. |
| [getErrorLevel()](#geterrorlevel) | Επίπεδο διόρθωσης σφαλμάτων Reed-Solomon του αναγνωρισμένου barcode. Από χαμηλό προς υψηλό: LevelL, LevelM, LevelQ, LevelH. |
| [getMicroQRVersion()](#getmicroqrversion) | Έκδοση του αναγνωρισμένου MicroQR Code. Από M1 έως M4. |
| [getQRErrorLevel()](#getqrerrorlevel) ~~(deprecated)~~ | Επίπεδο διόρθωσης σφαλμάτων Reed-Solomon του αναγνωρισμένου barcode. Από χαμηλό προς υψηλό: LevelL, LevelM, LevelQ, LevelH. |
| [getQRStructuredAppendModeBarCodeIndex()](#getqrstructuredappendmodebarcodeindex) ~~(deprecated)~~ | Λαμβάνει το ευρετήριο του barcode σε λειτουργία δομημένης προσθήκης QR. Το ευρετήριο ξεκινά από 0. Η προεπιλεγμένη τιμή είναι -1.Τιμή: Η ποσότητα του |
| [getQRStructuredAppendModeBarCodesQuantity()](#getqrstructuredappendmodebarcodesquantity) ~~(deprecated)~~ | Λαμβάνει την ποσότητα των barcode σε λειτουργία δομημένης προσθήκης QR. Η προεπιλεγμένη τιμή είναι -1.Τιμή: Η ποσότητα των QR δομημένων προσθέσεων |
| [getQRStructuredAppendModeParityData()](#getqrstructuredappendmodeparitydata) ~~(deprecated)~~ | Λαμβάνει τα δεδομένα ισοτιμίας της λειτουργίας δομημένης προσθήκης QR. Η προεπιλεγμένη τιμή είναι -1.Τιμή: Το ευρετήριο της λειτουργίας δομημένης προσθήκης QR |
| [getQRVersion()](#getqrversion) ~~(deprecated)~~ | Έκδοση του αναγνωρισμένου QR Code. Από Version1 έως Version40. |
| [getRectMicroQRVersion()](#getrectmicroqrversion) | Έκδοση του αναγνωρισμένου RectMicroQR Code. Από R7x43 έως R17x139. |
| [getStructuredAppendModeBarCodeIndex()](#getstructuredappendmodebarcodeindex) | Λαμβάνει το ευρετήριο του barcode σε λειτουργία δομημένης προσθήκης QR. Το ευρετήριο ξεκινά από 0. Η προεπιλεγμένη τιμή είναι -1. Τιμή: Η ποσότητα του |
| [getStructuredAppendModeBarCodesQuantity()](#getstructuredappendmodebarcodesquantity) | Λαμβάνει την ποσότητα των barcode σε λειτουργία δομημένης προσθήκης QR. Η προεπιλεγμένη τιμή είναι -1. Τιμή: Η ποσότητα των QR δομημένων προσθέσεων |
| [getStructuredAppendModeParityData()](#getstructuredappendmodeparitydata) | Λαμβάνει τα δεδομένα ισοτιμίας της λειτουργίας δομημένης προσθήκης QR. Η προεπιλεγμένη τιμή είναι -1. Τιμή: Το ευρετήριο της λειτουργίας δομημένης προσθήκης QR |
| [getVersion()](#getversion) | Έκδοση του αναγνωρισμένου QR Code. Από Version1 έως Version40. |
| [hashCode()](#hashcode) | Επιστρέφει τον κωδικό κατακερματισμού για αυτήν την παρουσία. |
| [isEmpty()](#isempty) | Δοκιμάζει εάν όλες οι παράμετροι έχουν μόνο προεπιλεγμένες τιμές Τιμή |
| [toString()](#tostring) | Επιστρέφει μια αναγνώσιμη από άνθρωπο συμβολοσειρά που αντιπροσωπεύει αυτό το QRExtendedParameters. |

### equals(obj) {#equals}

Επιστρέφει μια τιμή που υποδεικνύει εάν αυτό το αντικείμενο είναι ίσο με μια συγκεκριμένη τιμή του QRExtendedParameters.

| Παράμετρος | Περιγραφή |
| --- | --- |
| obj | Μια τιμή αντικειμένου για σύγκριση με αυτό το αντικείμενο. |

**Returns:** true if obj has the same value as this instance; otherwise, false.

### getErrorLevel() {#geterrorlevel}

Επίπεδο διόρθωσης σφαλμάτων Reed-Solomon του αναγνωρισμένου barcode. Από χαμηλό προς υψηλό: LevelL, LevelM, LevelQ, LevelH.

### getMicroQRVersion() {#getmicroqrversion}

Έκδοση του αναγνωρισμένου MicroQR Code. Από M1 έως M4.

**Returns:** Version of recognized MicroQR Code. From M1 to M4.

### getQRErrorLevel() {#getqrerrorlevel}

> **Deprecated.** See method description for replacement.

Επίπεδο διόρθωσης σφαλμάτων Reed-Solomon του αναγνωρισμένου barcode. Από χαμηλό προς υψηλό: LevelL, LevelM, LevelQ, LevelH.

**Returns:** Reed-Solomon error correction level of recognized barcode.

### getQRStructuredAppendModeBarCodeIndex() {#getqrstructuredappendmodebarcodeindex}

> **Deprecated.** See method description for replacement.

Λαμβάνει το ευρετήριο του barcode σε λειτουργία προσθήκης δομημένου QR. Το ευρετήριο ξεκινά από 0. Η προεπιλεγμένη τιμή είναι -1.Τιμή: Η ποσότητα του barcode σε λειτουργία προσθήκης δομημένου QR.

### getQRStructuredAppendModeBarCodesQuantity() {#getqrstructuredappendmodebarcodesquantity}

> **Deprecated.** See method description for replacement.

Λαμβάνει την ποσότητα των barcode σε λειτουργία προσθήκης δομημένου QR. Η προεπιλεγμένη τιμή είναι -1.Τιμή: Η ποσότητα του barcode σε λειτουργία προσθήκης δομημένου QR.

### getQRStructuredAppendModeParityData() {#getqrstructuredappendmodeparitydata}

> **Deprecated.** See method description for replacement.

Λαμβάνει τα δεδομένα ισοτιμίας της λειτουργίας προσθήκης δομημένου QR. Η προεπιλεγμένη τιμή είναι -1.Τιμή: Το ευρετήριο του barcode σε λειτουργία προσθήκης δομημένου QR.

### getQRVersion() {#getqrversion}

> **Deprecated.** See method description for replacement.

Έκδοση του αναγνωρισμένου QR Code. Από Version1 έως Version40.

**Returns:** Version of recognized QR Code

### getRectMicroQRVersion() {#getrectmicroqrversion}

Έκδοση του αναγνωρισμένου RectMicroQR Code. Από R7x43 έως R17x139.

**Returns:** Version of recognized RectMicroQR Code

### getStructuredAppendModeBarCodeIndex() {#getstructuredappendmodebarcodeindex}

Λαμβάνει το ευρετήριο του barcode σε λειτουργία προσθήκης δομημένου QR. Το ευρετήριο ξεκινά από 0. Η προεπιλεγμένη τιμή είναι -1. Τιμή: Η ποσότητα του barcode σε λειτουργία προσθήκης δομημένου QR.

**Returns:** the index of the QR structured append mode barcode.

### getStructuredAppendModeBarCodesQuantity() {#getstructuredappendmodebarcodesquantity}

Λαμβάνει την ποσότητα των barcode σε λειτουργία προσθήκης δομημένου QR. Η προεπιλεγμένη τιμή είναι -1. Τιμή: Η ποσότητα του barcode σε λειτουργία προσθήκης δομημένου QR.

**Returns:** the QR structured append mode barcodes quantity.

### getStructuredAppendModeParityData() {#getstructuredappendmodeparitydata}

Λαμβάνει τα δεδομένα ισοτιμίας της λειτουργίας προσθήκης δομημένου QR. Η προεπιλεγμένη τιμή είναι -1. Τιμή: Το ευρετήριο του barcode σε λειτουργία προσθήκης δομημένου QR.

**Returns:** the QR structured append mode parity data.

### getVersion() {#getversion}

Έκδοση του αναγνωρισμένου QR Code. Από Version1 έως Version40.

### hashCode() {#hashcode}

Επιστρέφει τον κωδικό κατακερματισμού για αυτήν την παρουσία.

**Returns:** A 32-bit signed integer hash code.

### isEmpty() {#isempty}

Δοκιμάζει εάν όλες οι παράμετροι έχουν μόνο προεπιλεγμένες τιμές Τιμή

**Returns:** true if all parameters has only default values; otherwise, `false `.

### toString() {#tostring}

Επιστρέφει μια αναγνώσιμη από άνθρωπο συμβολοσειρά που αντιπροσωπεύει αυτό το QRExtendedParameters.

**Returns:** A string that represents this QRExtendedParameters.
