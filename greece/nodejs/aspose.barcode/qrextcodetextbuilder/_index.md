---
title: "QrExtCodetextBuilder"
linktitle: "QrExtCodetextBuilder"
second_title: "Αναφορά API του Aspose.BarCode για Node.js μέσω Java"
description: "Εκτεταμένος γεννήτορας κειμένου κώδικα για 2D QR barcode για τη λειτουργία ExtendedCodetext του QREncodeMode. Χρησιμοποιήστε την ιδιότητα Display2DText του BarCodeBuilder για να ορίσετε το ορατό κείμενο σε rem"
type: docs
weight: 820
url: /el/nodejs/aspose.barcode/qrextcodetextbuilder/
---

## QrExtCodetextBuilder class

Εκτεταμένος γεννήτορας κειμένου κώδικα για 2D QR barcode για τη λειτουργία ExtendedCodetext του QREncodeMode. Χρησιμοποιήστε την ιδιότητα Display2DText του BarCodeBuilder για να ορίσετε το ορατό κείμενο αφαιρώντας διαχειριστικούς χαρακτήρες.

```js
new QrExtCodetextBuilder()
```

**Example:**

```js
//Example how to generate FNC1 first position for Extended Mode
 //create codetext
 const lTextBuilder = new QrExtCodetextBuilder();
 lTextBuilder.addFNC1FirstPosition();
 lTextBuilder.addPlainCodetext("000%89%%0");
 lTextBuilder.addFNC1GroupSeparator();
 lTextBuilder.addPlainCodetext("12345&lt;FNC1&gt;");
 //generate codetext
 const lCodetext = lTextBuilder.getExtendedCodetext();
```

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [addCodetextWithCompactionMode(mode, codetext)](#addcodetextwithcompactionmode) | Προσθέτει κείμενο κώδικα με την καθορισμένη λειτουργία συμπίεσης QR στα στοιχεία εκτεταμένου κειμένου κώδικα. |
| [addFNC1FirstPosition()](#addfnc1firstposition) | Προσθέτει FNC1 στην πρώτη θέση στα στοιχεία εκτεταμένου κειμένου κώδικα. |
| [addFNC1GroupSeparator()](#addfnc1groupseparator) | Προσθέτει το διαχωριστικό ομάδας (GS - '\\u001D') στα στοιχεία εκτεταμένου κειμένου κώδικα. |
| [addFNC1SecondPosition(codetext)](#addfnc1secondposition) | Προσθέτει FNC1 στη δεύτερη θέση στα στοιχεία εκτεταμένου κειμένου κώδικα. |
| [clear()](#clear) | Καθαρίζει τα στοιχεία επεκταμένου κώδικα |
| [getExtendedCodetext()](#getextendedcodetext) | Δημιουργεί Extended codetext από τη λίστα Extended codetext. |

### addCodetextWithCompactionMode(mode, codetext) {#addcodetextwithcompactionmode}

Προσθέτει κείμενο κώδικα με την καθορισμένη λειτουργία συμπίεσης QR στα στοιχεία εκτεταμένου κειμένου κώδικα.

| Παράμετρος | Περιγραφή |
| --- | --- |
| λειτουργία | Λειτουργία συμπίεσης QR για το κείμενο κώδικα. |
| codetext | Κείμενο κώδικα σε Unicode για προσθήκη ως στοιχείο εκτεταμένου κειμένου κώδικα. |

**Throws:** IllegalArgumentException The specified codetext cannot be encoded in the selected QR compaction mode.

### addFNC1FirstPosition() {#addfnc1firstposition}

Προσθέτει FNC1 στην πρώτη θέση στα στοιχεία εκτεταμένου κειμένου κώδικα.

### addFNC1GroupSeparator() {#addfnc1groupseparator}

Προσθέτει το διαχωριστικό ομάδας (GS - '\\u001D') στα στοιχεία εκτεταμένου κειμένου κώδικα.

### addFNC1SecondPosition(codetext) {#addfnc1secondposition}

Προσθέτει FNC1 στη δεύτερη θέση στα στοιχεία εκτεταμένου κειμένου κώδικα.

| Παράμετρος | Περιγραφή |
| --- | --- |
| codetext | Τιμή του FNC1 στη δεύτερη θέση |

### clear() {#clear}

Καθαρίζει τα στοιχεία επεκταμένου κώδικα

### getExtendedCodetext() {#getextendedcodetext}

Δημιουργεί Extended codetext από τη λίστα Extended codetext.

**Returns:** Extended codetext as string
