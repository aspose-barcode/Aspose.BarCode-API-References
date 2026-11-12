---
title: "MailmarkCodetext"
linktitle: "MailmarkCodetext"
second_title: "Αναφορά API του Aspose.BarCode για Node.js μέσω Java"
description: "Κλάση για κωδικοποίηση και αποκωδικοποίηση του κειμένου ενσωματωμένου στον κώδικα 4-state Royal Mailmark."
type: docs
weight: 580
url: /el/nodejs/aspose.barcode/mailmarkcodetext/
---

## MailmarkCodetext class

Κλάση για κωδικοποίηση και αποκωδικοποίηση του κειμένου ενσωματωμένου στον κώδικα 4-state Royal Mailmark.

```js
new MailmarkCodetext()
```

Αρχικοποιεί μια νέα παρουσία της κλάσης `MailmarkCodetext`.

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [getBarcodeType()](#getbarcodetype) | Λαμβάνει τον τύπο barcode. |
| [getClass_()](#getclass-) | "0" - Κενό ή Δοκιμή "1" - 1C (Λιανική) "2" - 2C (Λιανική) "3" - 3C (Λιανική) "4" - Premium (RetailPublishing Mail) (for pote |
| [getConstructedCodetext()](#getconstructedcodetext) | Δημιουργήστε κώδικα κειμένου από τα δεδομένα Mailmark. |
| [getDestinationPostCodePlusDPS()](#getdestinationpostcodeplusdps) | Το PC και το DP πρέπει να συμμορφώνονται με μορφή PAF. Συμβολοσειρά εννέα χαρακτήρων που υποδεικνύει το διεθνές "XY11 " (σημειώστε τα 5 τελικά διαστήματα) |
| [getFormat()](#getformat) | "0" – Κενό ή Δοκιμή "1" – Γράμμα "2" – Μεγάλο Γράμμα |
| [getItemID()](#getitemid) | Η μέγιστη τιμή είναι 99999999. |
| [getSupplychainID()](#getsupplychainid) | Οι μέγιστες τιμές είναι 99 για το Barcode C και 999999 για το Barcode L. |
| [getVersionID()](#getversionid) | Προς το παρόν "1" – Για τον κώδικα Mailmark (0 και 2 έως 9 και A έως Z διατηρούνται για μελλοντική χρήση) |
| [initFromString(constructedCodetext)](#initfromstring) | Αρχικοποιεί τα δεδομένα Mailmark από τον κατασκευασμένο κώδικα κειμένου. |
| [setClass_()](#setclass-) | "0" - Κενό ή Δοκιμή "1" - 1C (Λιανική) "2" - 2C (Λιανική) "3" - 3C (Λιανική) "4" - Premium (RetailPublishing Mail) (for pote |
| [setDestinationPostCodePlusDPS()](#setdestinationpostcodeplusdps) | Το PC και το DP πρέπει να συμμορφώνονται με μορφή PAF. Συμβολοσειρά εννέα χαρακτήρων που υποδεικνύει το διεθνές "XY11 " (σημειώστε τα 5 τελικά διαστήματα) |
| [setFormat()](#setformat) | "0" – Κενό ή Δοκιμή "1" – LetterN "2" – Μεγάλο Γράμμα |
| [setItemID()](#setitemid) | Η μέγιστη τιμή είναι 99999999. |
| [setSupplychainID()](#setsupplychainid) | Οι μέγιστες τιμές είναι 99 για το Barcode C και 999999 για το Barcode L. |
| [setVersionID()](#setversionid) | Προς το παρόν "1" – Για τον κώδικα Mailmark (0 και 2 έως 9 και A έως Z διατηρούνται για μελλοντική χρήση) |

### getBarcodeType() {#getbarcodetype}

Λαμβάνει τον τύπο barcode.

**Returns:** Barcode type.

### getClass_() {#getclass-}

"0" - Κενό ή Δοκιμή "1" - 1C (Λιανική) "2" - 2C (Λιανική) "3" - 3C (Λιανική) "4" - Premium (RetailPublishing Mail) (for potential future use) "5" - Deferred (Λιανική) "6" - Air (Λιανική) (for potential future use) "7" - Surface (Λιανική) (for potential future use) "8" - Premium (Network Access) "9" - Standard (Network Access)

### getConstructedCodetext() {#getconstructedcodetext}

Δημιουργήστε κώδικα κειμένου από τα δεδομένα Mailmark.

**Returns:** Constructed codetext

### getDestinationPostCodePlusDPS() {#getdestinationpostcodeplusdps}

Το PC και το DP πρέπει να συμμορφώνονται με μορφή PAF. Συμβολοσειρά εννέα χαρακτήρων που υποδεικνύει το διεθνές "XY11 " (σημειώστε τα 5 τελικά διαστήματα) ή ένα μοτίβο χαρακτήρων που υποδεικνύει έναν εγχώριο κωδικό ταξινόμησης. Ένας εγχώριος κωδικός ταξινόμησης αποτελείται από έναν εξωτερικό ταχυδρομικό κώδικα, έναν εσωτερικό ταχυδρομικό κώδικα και ένα Πρόθεμα Σημείου Παράδοσης.

### getFormat() {#getformat}

"0" – Κενό ή Δοκιμή "1" – Γράμμα "2" – Μεγάλο Γράμμα

### getItemID() {#getitemid}

Η μέγιστη τιμή είναι 99999999.

### getSupplychainID() {#getsupplychainid}

Οι μέγιστες τιμές είναι 99 για το Barcode C και 999999 για το Barcode L.

### getVersionID() {#getversionid}

Προς το παρόν "1" – Για τον κώδικα Mailmark (0 και 2 έως 9 και A έως Z διατηρούνται για μελλοντική χρήση)

### initFromString(constructedCodetext) {#initfromstring}

Αρχικοποιεί τα δεδομένα Mailmark από τον κατασκευασμένο κώδικα κειμένου.

| Παράμετρος | Περιγραφή |
| --- | --- |
| constructedCodetext | Δημιουργημένο κείμενο κώδικα. |

### setClass_() {#setclass-}

"0" - Κενό ή Δοκιμή "1" - 1C (Λιανική) "2" - 2C (Λιανική) "3" - 3C (Λιανική) "4" - Premium (RetailPublishing Mail) (for potential future use) "5" - Deferred (Λιανική) "6" - Air (Λιανική) (for potential future use) "7" - Surface (Λιανική) (for potential future use) "8" - Premium (Network Access) "9" - Standard (Network Access)

### setDestinationPostCodePlusDPS() {#setdestinationpostcodeplusdps}

Το PC και το DP πρέπει να συμμορφώνονται με μορφή PAF. Συμβολοσειρά εννέα χαρακτήρων που υποδεικνύει το διεθνές "XY11 " (σημειώστε τα 5 τελικά διαστήματα) ή ένα μοτίβο χαρακτήρων που υποδεικνύει έναν εγχώριο κωδικό ταξινόμησης. Ένας εγχώριος κωδικός ταξινόμησης αποτελείται από έναν εξωτερικό ταχυδρομικό κώδικα, έναν εσωτερικό ταχυδρομικό κώδικα και ένα Πρόθεμα Σημείου Παράδοσης.

### setFormat() {#setformat}

"0" – Κενό ή Δοκιμή "1" – LetterN "2" – Μεγάλο Γράμμα

### setItemID() {#setitemid}

Η μέγιστη τιμή είναι 99999999.

### setSupplychainID() {#setsupplychainid}

Οι μέγιστες τιμές είναι 99 για το Barcode C και 999999 για το Barcode L.

### setVersionID() {#setversionid}

Προς το παρόν "1" – Για τον κώδικα Mailmark (0 και 2 έως 9 και A έως Z διατηρούνται για μελλοντική χρήση)
