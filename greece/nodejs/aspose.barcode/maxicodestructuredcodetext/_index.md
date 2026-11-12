---
title: "MaxiCodeStructuredCodetext"
linktitle: "MaxiCodeStructuredCodetext"
second_title: "Αναφορά API του Aspose.BarCode για Node.js μέσω Java"
description: "Βασική κλάση για κωδικοποίηση και αποκωδικοποίηση του κειμένου ενσωματωμένου στον κώδικα MaxiCode για τις λειτουργίες 2 και 3."
type: docs
weight: 700
url: /el/nodejs/aspose.barcode/maxicodestructuredcodetext/
---

## MaxiCodeStructuredCodetext class

Βασική κλάση για κωδικοποίηση και αποκωδικοποίηση του κειμένου ενσωματωμένου στον κώδικα MaxiCode για τις λειτουργίες 2 και 3.

```js
new MaxiCodeStructuredCodetext()
```

**Example:**

```js
This sample shows how to decode raw MaxiCode codetext to MaxiCodeStructuredCodetext instance.

 let reader = new BarCodeReader("c:\\test.png", null, DecodeType.MAXI_CODE);
 let results = reader.readBarCodes();
 for(let i = 0; i < results.length; i++)
 {
    let result = results[i];
     let resultMaxiCodeCodetext = ComplexCodetextReader.tryDecodeMaxiCode(result.getExtended().getMaxiCode().getMaxiCodeMode(), result.getCodeText());
     if (resultMaxiCodeCodetext instanceof MaxiCodeStructuredCodetext)
     {
         let maxiCodeStructuredCodetext = resultMaxiCodeCodetext;
         console.log("BarCode Type: " + maxiCodeStructuredCodetext.getPostalCode());
         console.log("MaxiCode mode: " + maxiCodeStructuredCodetext.getCountryCode());
         console.log("BarCode CodeText: " + maxiCodeStructuredCodetext.getServiceCategory());
     }
 }
```

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [equals(obj)](#equals) | Επιστρέφει μια τιμή που υποδεικνύει εάν αυτή η περίπτωση είναι ίση με μια καθορισμένη τιμή. |
| [getConstructedCodetext()](#getconstructedcodetext) | Δημιουργεί κείμενο κώδικα. |
| [getCountryCode()](#getcountrycode) | Αναγνωρίζει τον 3-ψήφιο κωδικό χώρας. |
| [getHashCode()](#gethashcode) | Επιστρέφει τον κωδικό κατακερματισμού για αυτήν την παρουσία. |
| [getPostalCode()](#getpostalcode) | Αναγνωρίζει τον ταχυδρομικό κώδικα. Πρέπει να είναι 9 ψηφία στη λειτουργία 2 ή 6 αλφαριθμητικά σύμβολα στη λειτουργία 3. |
| [getSecondMessage()](#getsecondmessage) | Αναγνωρίζει το δεύτερο μήνυμα του barcode. |
| [getServiceCategory()](#getservicecategory) | Αναγνωρίζει την 3-ψήφια κατηγορία υπηρεσίας. |
| [initFromString(constructedCodetext)](#initfromstring) | Αρχικοποιεί την παρουσία από το δημιουργημένο κείμενο κώδικα. |
| [setCountryCode()](#setcountrycode) | Αναγνωρίζει τον 3-ψήφιο κωδικό χώρας. |
| [setPostalCode()](#setpostalcode) | Αναγνωρίζει τον ταχυδρομικό κώδικα. Πρέπει να είναι 9 ψηφία στη λειτουργία 2 ή 6 αλφαριθμητικά σύμβολα στη λειτουργία 3. |
| [setSecondMessage()](#setsecondmessage) | Αναγνωρίζει το δεύτερο μήνυμα του barcode. |
| [setServiceCategory()](#setservicecategory) | Αναγνωρίζει την 3-ψήφια κατηγορία υπηρεσίας. |

### equals(obj) {#equals}

Επιστρέφει μια τιμή που υποδεικνύει εάν αυτή η περίπτωση είναι ίση με μια καθορισμένη τιμή.

| Παράμετρος | Περιγραφή |
| --- | --- |
| obj | Μια τιμή για σύγκριση με αυτήν την περίπτωση |

**Returns:** true if obj has the same value as this instance; otherwise, false

### getConstructedCodetext() {#getconstructedcodetext}

Δημιουργεί κείμενο κώδικα.

**Returns:** Constructed codetext

### getCountryCode() {#getcountrycode}

Αναγνωρίζει τον 3-ψήφιο κωδικό χώρας.

### getHashCode() {#gethashcode}

Επιστρέφει τον κωδικό κατακερματισμού για αυτήν την παρουσία.

**Returns:** A 32-bit signed integer hash code.

### getPostalCode() {#getpostalcode}

Αναγνωρίζει τον ταχυδρομικό κώδικα. Πρέπει να είναι 9 ψηφία στη λειτουργία 2 ή 6 αλφαριθμητικά σύμβολα στη λειτουργία 3.

### getSecondMessage() {#getsecondmessage}

Αναγνωρίζει το δεύτερο μήνυμα του barcode.

### getServiceCategory() {#getservicecategory}

Αναγνωρίζει την 3-ψήφια κατηγορία υπηρεσίας.

### initFromString(constructedCodetext) {#initfromstring}

Αρχικοποιεί την παρουσία από το δημιουργημένο κείμενο κώδικα.

| Παράμετρος | Περιγραφή |
| --- | --- |
| constructedCodetext | Δημιουργημένο κείμενο κώδικα. |

### setCountryCode() {#setcountrycode}

Αναγνωρίζει τον 3-ψήφιο κωδικό χώρας.

### setPostalCode() {#setpostalcode}

Αναγνωρίζει τον ταχυδρομικό κώδικα. Πρέπει να είναι 9 ψηφία στη λειτουργία 2 ή 6 αλφαριθμητικά σύμβολα στη λειτουργία 3.

### setSecondMessage() {#setsecondmessage}

Αναγνωρίζει το δεύτερο μήνυμα του barcode.

### setServiceCategory() {#setservicecategory}

Αναγνωρίζει την 3-ψήφια κατηγορία υπηρεσίας.
