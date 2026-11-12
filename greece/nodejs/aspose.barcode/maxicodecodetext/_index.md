---
title: "MaxiCodeCodetext"
linktitle: "MaxiCodeCodetext"
second_title: "Αναφορά API του Aspose.BarCode για Node.js μέσω Java"
description: "Βασική κλάση για κωδικοποίηση και αποκωδικοποίηση του κειμένου που ενσωματώνεται στον κώδικα MaxiCode."
type: docs
weight: 600
url: /el/nodejs/aspose.barcode/maxicodecodetext/
---

## MaxiCodeCodetext class

Βασική κλάση για κωδικοποίηση και αποκωδικοποίηση του κειμένου που ενσωματώνεται στον κώδικα MaxiCode. Αυτό το παράδειγμα δείχνει πώς να αποκωδικοποιήσετε ακατέργαστο κείμενο MaxiCode σε παρουσία MaxiCodeCodetext.

```js
new MaxiCodeCodetext()
```

**Example:**

```js
let reader = new BarCodeReader("c:\\test.png", null, DecodeType.MAXI_CODE);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
     let result = results[i];
     let resultMaxiCodeCodetext = ComplexCodetextReader.tryDecodeMaxiCode(result.getExtended().getMaxiCode().getMaxiCodeMode(), result.getCodeText());
     console.log("BarCode Type: " + resultMaxiCodeCodetext.getBarcodeType());
     console.log("MaxiCode mode: " + resultMaxiCodeCodetext.getMode());
     console.log("BarCode CodeText: " + resultMaxiCodeCodetext.getConstructedCodetext());
}
```

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [getBarcodeType()](#getbarcodetype) | Λαμβάνει τον τύπο barcode. |
| [getECIEncoding()](#geteciencoding) | Λαμβάνει κωδικοποίηση ECI. Χρησιμοποιείται όταν το MaxiCodeEncodeMode είναι AUTO. |
| [getEncodeMode()](#getencodemode) | Λαμβάνει μια λειτουργία κωδικοποίησης MaxiCode. Προεπιλεγμένη τιμή: Auto. |
| [getMaxiCodeEncodeMode()](#getmaxicodeencodemode) ~~(deprecated)~~ | Λαμβάνει μια λειτουργία κωδικοποίησης MaxiCode. |
| [getMode()](#getmode) | Λαμβάνει τη λειτουργία MaxiCode. |
| [setECIEncoding()](#seteciencoding) | Ορίζει κωδικοποίηση ECI. Χρησιμοποιείται όταν το MaxiCodeEncodeMode είναι AUTO. |
| [setEncodeMode(value)](#setencodemode) | Ορίζει μια λειτουργία κωδικοποίησης MaxiCode. Προεπιλεγμένη τιμή: Auto. |
| [setMaxiCodeEncodeMode()](#setmaxicodeencodemode) ~~(deprecated)~~ | Ορίζει μια λειτουργία κωδικοποίησης MaxiCode. |

### getBarcodeType() {#getbarcodetype}

Λαμβάνει τον τύπο barcode.

**Returns:** Barcode type

### getECIEncoding() {#geteciencoding}

Λαμβάνει κωδικοποίηση ECI. Χρησιμοποιείται όταν το MaxiCodeEncodeMode είναι AUTO.

### getEncodeMode() {#getencodemode}

Λαμβάνει μια λειτουργία κωδικοποίησης MaxiCode. Προεπιλεγμένη τιμή: Auto.

**Returns:** a MaxiCode encode mode.

### getMaxiCodeEncodeMode() {#getmaxicodeencodemode}

> **Deprecated.** See method description for replacement.

Λαμβάνει μια λειτουργία κωδικοποίησης MaxiCode.

### getMode() {#getmode}

Λαμβάνει τη λειτουργία MaxiCode.

**Returns:** MaxiCode mode

### setECIEncoding() {#seteciencoding}

Ορίζει κωδικοποίηση ECI. Χρησιμοποιείται όταν το MaxiCodeEncodeMode είναι AUTO.

### setEncodeMode(value) {#setencodemode}

Ορίζει μια λειτουργία κωδικοποίησης MaxiCode. Προεπιλεγμένη τιμή: Auto.

| Παράμετρος | Περιγραφή |
| --- | --- |
| τιμή | μια λειτουργία κωδικοποίησης MaxiCode. |

### setMaxiCodeEncodeMode() {#setmaxicodeencodemode}

> **Deprecated.** See method description for replacement.

Ορίζει μια λειτουργία κωδικοποίησης MaxiCode.
