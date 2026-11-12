---
title: "MaxiCodeStandardCodetext"
linktitle: "MaxiCodeStandardCodetext"
second_title: "Αναφορά API του Aspose.BarCode για Node.js μέσω Java"
description: "Κλάση για κωδικοποίηση και αποκωδικοποίηση του κειμένου MaxiCode για τις λειτουργίες 4, 5 και 6."
type: docs
weight: 670
url: /el/nodejs/aspose.barcode/maxicodestandardcodetext/
---

## MaxiCodeStandardCodetext class

Κλάση για κωδικοποίηση και αποκωδικοποίηση του κειμένου MaxiCode για τις λειτουργίες 4, 5 και 6.

```js
new MaxiCodeStandardCodetext()
```

**Example:**

```js
//Mode 4
let maxiCodeCodetext = new MaxiCodeStandardCodetext();
maxiCodeCodetext.setMode(MaxiCodeMode.MODE_4);
maxiCodeCodetext.setMessage("Test message");
let complexGenerator = new ComplexBarcodeGenerator(maxiCodeCodetext.getConstructedCodetext());
complexGenerator.generateBarCodeImage(BarcodeImageFormat.PNG);
```

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [equals(obj)](#equals) | Επιστρέφει μια τιμή που υποδεικνύει εάν αυτή η περίπτωση είναι ίση με μια καθορισμένη τιμή. |
| [getConstructedCodetext()](#getconstructedcodetext) | Δημιουργεί κείμενο κώδικα. |
| [getHashCode()](#gethashcode) | Επιστρέφει τον κωδικό κατακερματισμού για αυτήν την παρουσία. |
| [getMessage()](#getmessage) | Λαμβάνει το μήνυμα. |
| [getMode()](#getmode) | Λαμβάνει τη λειτουργία MaxiCode. |
| [initFromString(constructedCodetext)](#initfromstring) | Αρχικοποιεί την παρουσία από το δημιουργημένο κείμενο κώδικα. |
| [setMessage()](#setmessage) | Ορίζει το μήνυμα. |
| [setMode()](#setmode) | Ορίζει τη λειτουργία MaxiCode. Το τυπικό κείμενο κώδικα μπορεί να χρησιμοποιηθεί μόνο με τις λειτουργίες 4, 5 και 6. |

### equals(obj) {#equals}

Επιστρέφει μια τιμή που υποδεικνύει εάν αυτή η περίπτωση είναι ίση με μια καθορισμένη τιμή.

| Παράμετρος | Περιγραφή |
| --- | --- |
| obj | Μια τιμή για σύγκριση με αυτήν την παρουσία. |

**Returns:** if obj has the same value as this instance; otherwise, false .

### getConstructedCodetext() {#getconstructedcodetext}

Δημιουργεί κείμενο κώδικα.

**Returns:** Constructed codetext

### getHashCode() {#gethashcode}

Επιστρέφει τον κωδικό κατακερματισμού για αυτήν την παρουσία.

**Returns:** A 32-bit signed integer hash code

### getMessage() {#getmessage}

Λαμβάνει το μήνυμα.

### getMode() {#getmode}

Λαμβάνει τη λειτουργία MaxiCode.

**Returns:** MaxiCode mode

### initFromString(constructedCodetext) {#initfromstring}

Αρχικοποιεί την παρουσία από το δημιουργημένο κείμενο κώδικα.

| Παράμετρος | Περιγραφή |
| --- | --- |
| constructedCodetext | Δημιουργημένο κείμενο κώδικα. |

### setMessage() {#setmessage}

Ορίζει το μήνυμα.

### setMode() {#setmode}

Ορίζει τη λειτουργία MaxiCode. Το τυπικό κείμενο κώδικα μπορεί να χρησιμοποιηθεί μόνο με τις λειτουργίες 4, 5 και 6.
