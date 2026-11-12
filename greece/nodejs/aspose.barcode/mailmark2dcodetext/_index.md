---
title: "Mailmark2DCodetext"
linktitle: "Mailmark2DCodetext"
second_title: "Αναφορά API του Aspose.BarCode για Node.js μέσω Java"
description: "Κλάση για κωδικοποίηση και αποκωδικοποίηση του κειμένου ενσωματωμένου στον κώδικα Royal Mail 2D Mailmark."
type: docs
weight: 570
url: /el/nodejs/aspose.barcode/mailmark2dcodetext/
---

## Mailmark2DCodetext class

Κλάση για κωδικοποίηση και αποκωδικοποίηση του κειμένου ενσωματωμένου στον κώδικα Royal Mail 2D Mailmark.

```js
new Mailmark2DCodetext()
```

Δημιουργεί προεπιλεγμένη παρουσία της κλάσης Mailmark2DCodetext.

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [getBarcodeType()](#getbarcodetype) | Λαμβάνει τον τύπο barcode. |
| [getClass_()](#getclass-) | Καθορίζει την κλάση του αντικειμένου. Έγκυρες τιμές: '1' - 1C (Λιανική) '2' - 2C (Λιανική) '3' - Economy (Λιανική) '5' - Deffere |
| [getConstructedCodetext()](#getconstructedcodetext) | Δημιουργήστε κώδικα κειμένου από τα δεδομένα Mailmark. |
| [getCustomerContent()](#getcustomercontent) | Προαιρετικός χώρος για χρήση από τον πελάτη. Μέγιστο μήκος ανά τύπο: Τύπος 7: 6 χαρακτήρες Τύπος 9: 45 χαρακτήρες Τύπος 29: 25 χαρακτήρες |
| [getCustomerContentEncodeMode()](#getcustomercontentencodemode) | Λειτουργία κωδικοποίησης του barcode Datamatrix. Προεπιλεγμένη τιμή: DataMatrixEncodeMode.C40. |
| [getDataMatrixType()](#getdatamatrixtype) | Ο τύπος 2D Mailmark ορίζει το μέγεθος του barcode Data Matrix. |
| [getDestinationPostCodeAndDPS()](#getdestinationpostcodeanddps) | Περιέχει τον ταχυδρομικό κώδικα της διεύθυνσης παράδοσης με DPS. Εάν είναι ενδοχώρα, ο ταχυδρομικός κώδικας/DP περιέχει τον ακόλουθο αριθμό χαρακτήρων |
| [getInformationTypeID()](#getinformationtypeid) | Καθορίζει το payload του barcode Royal Mail Mailmark για κάθε τύπο προϊόντος. Έγκυρες τιμές: '0' - Domestic Sorted & Unsorted |
| [getItemID()](#getitemid) | Αναγνωρίζει το μοναδικό στοιχείο εντός του Supply Chain ID. Κάθε γραμμικός κώδικας Mailmark απαιτείται να φέρει ένα ID ώστε να μπορεί να είναι un |
| [getReturnToSenderPostCode()](#getreturntosenderpostcode) | Περιέχει τον κωδικό επιστροφής αποστολέα αλλά χωρίς DPS. Ο κωδικός (χωρίς DPS) πρέπει να συμμορφώνεται με μορφή PAF®. |
| [getRTSFlag()](#getrtsflag) | Σημαία που υποδεικνύει ποιο επίπεδο υπηρεσίας Return to Sender ζητείται. |
| [getSupplyChainID()](#getsupplychainid) | Αναγνωρίζει τη μοναδική ομάδα πελατών που συμμετέχουν στην αποστολή. Μέγιστη τιμή: 9999999. |
| [getUPUCountryID()](#getupucountryid) | Αναγνωρίζει το UPU Country ID. Μέγιστο μήκος: 4 χαρακτήρες. |
| [getVersionID()](#getversionid) | Αναγνωρίζει την έκδοση του barcode όπως σχετίζεται με κάθε Information Type ID. Έγκυρες τιμές: Προς το παρόν '1'. '0' & '2' έως '9' an |
| [initFromString(constructedCodetext)](#initfromstring) | Αρχικοποιεί τα δεδομένα Mailmark από τον κατασκευασμένο κώδικα κειμένου. |
| [setClass_(value)](#setclass-) | Καθορίζει την κλάση του αντικειμένου. Έγκυρες τιμές: '1' - 1C (Λιανική) '2' - 2C (Λιανική) '3' - Economy (Λιανική) '5' - Deffere |
| [setCustomerContent(value)](#setcustomercontent) | Προαιρετικός χώρος για χρήση από τον πελάτη. Μέγιστο μήκος ανά τύπο: Τύπος 7: 6 χαρακτήρες Τύπος 9: 45 χαρακτήρες Τύπος 29: 25 χαρακτήρες |
| [setCustomerContentEncodeMode(value)](#setcustomercontentencodemode) | Λειτουργία κωδικοποίησης του barcode Datamatrix. Προεπιλεγμένη τιμή: DataMatrixEncodeMode.C40. |
| [setDataMatrixType(value)](#setdatamatrixtype) | Ο τύπος 2D Mailmark ορίζει το μέγεθος του barcode Data Matrix. |
| [setDestinationPostCodeAndDPS(value)](#setdestinationpostcodeanddps) | Περιέχει τον ταχυδρομικό κώδικα της διεύθυνσης παράδοσης με DPS. Εάν είναι ενδοχώρα, ο ταχυδρομικός κώδικας/DP περιέχει τον ακόλουθο αριθμό χαρακτήρων |
| [setInformationTypeID(value)](#setinformationtypeid) | Καθορίζει το payload του barcode Royal Mail Mailmark για κάθε τύπο προϊόντος. Έγκυρες τιμές: '0' - Domestic Sorted & Unsorted |
| [setItemID(value)](#setitemid) | Αναγνωρίζει το μοναδικό στοιχείο εντός του Supply Chain ID. Κάθε γραμμικός κώδικας Mailmark απαιτείται να φέρει ένα ID ώστε να μπορεί να είναι un |
| [setReturnToSenderPostCode(value)](#setreturntosenderpostcode) | Περιέχει τον κωδικό επιστροφής αποστολέα αλλά χωρίς DPS. Ο κωδικός (χωρίς DPS) πρέπει να συμμορφώνεται με μορφή PAF®. |
| [setRTSFlag()](#setrtsflag) | Σημαία που υποδεικνύει ποιο επίπεδο υπηρεσίας Return to Sender ζητείται. |
| [setSupplyChainID(value)](#setsupplychainid) | Αναγνωρίζει τη μοναδική ομάδα πελατών που συμμετέχουν στην αποστολή. Μέγιστη τιμή: 9999999. |
| [setUPUCountryID(value)](#setupucountryid) | Αναγνωρίζει το UPU Country ID. Μέγιστο μήκος: 4 χαρακτήρες. |
| [setVersionID(value)](#setversionid) | Αναγνωρίζει την έκδοση του barcode όπως σχετίζεται με κάθε Information Type ID. Έγκυρες τιμές: Προς το παρόν '1'. '0' & '2' έως '9' an |

### getBarcodeType() {#getbarcodetype}

Λαμβάνει τον τύπο barcode.

**Returns:** Barcode type.

### getClass_() {#getclass-}

Αναγνωρίζει την κλάση του στοιχείου. Έγκυρες τιμές: '1' - 1C (Λιανική) '2' - 2C (Λιανική) '3' - Economy (Λιανική) '5' - Deffered (Λιανική) '8' - Premium (Πρόσβαση Δικτύου) '9' - Standard (Πρόσβαση Δικτύου)

**Returns:** class of the item

### getConstructedCodetext() {#getconstructedcodetext}

Δημιουργήστε κώδικα κειμένου από τα δεδομένα Mailmark.

**Returns:** Constructed codetext

### getCustomerContent() {#getcustomercontent}

Προαιρετικός χώρος για χρήση από τον πελάτη. Μέγιστο μήκος ανά τύπο: Τύπος 7: 6 χαρακτήρες Τύπος 9: 45 χαρακτήρες Τύπος 29: 25 χαρακτήρες

**Returns:** Customer content

### getCustomerContentEncodeMode() {#getcustomercontentencodemode}

Λειτουργία κωδικοποίησης του barcode Datamatrix. Προεπιλεγμένη τιμή: DataMatrixEncodeMode.C40.

**Returns:** Encode mode of Datamatrix barcode.

### getDataMatrixType() {#getdatamatrixtype}

Ο τύπος 2D Mailmark ορίζει το μέγεθος του barcode Data Matrix.

**Returns:** Size of Data Matrix barcode

### getDestinationPostCodeAndDPS() {#getdestinationpostcodeanddps}

Περιέχει τον ταχυδρομικό κώδικα της διεύθυνσης παράδοσης με DPS. Εάν είναι ενδοχώρα, ο ταχυδρομικός κώδικας/DP περιέχει τον ακόλουθο αριθμό χαρακτήρων. Περιοχή (1 ή 2 χαρακτήρες) Περιφέρεια (1 ή 2 χαρακτήρες) Τομέας (1 χαρακτήρας) Μονάδα (2 χαρακτήρες) DPS (2 χαρακτήρες). Ο ταχυδρομικός κώδικας και το DPS πρέπει να συμμορφώνονται με έγκυρη μορφή PAF®.

**Returns:** the Postcode of the Delivery Address with DPS

### getInformationTypeID() {#getinformationtypeid}

Αναγνωρίζει το payload του barcode Royal Mail Mailmark για κάθε τύπο προϊόντος. Έγκυρες τιμές: '0' - Ενδοχώρα Ταξινομημένα & Αταξινόμητα 'A' - Online Postage 'B' - Franking 'C' - Consolidation

**Returns:** Information type ID

### getItemID() {#getitemid}

Αναγνωρίζει το μοναδικό στοιχείο εντός του Supply Chain ID. Κάθε barcode Mailmark απαιτείται να φέρει ένα ID ώστε να μπορεί να αναγνωρίζεται μοναδικά για τουλάχιστον 90 ημέρες. Μέγιστη τιμή: 99999999.

**Returns:** item within the Supply Chain ID

### getReturnToSenderPostCode() {#getreturntosenderpostcode}

Περιέχει τον κωδικό επιστροφής αποστολέα αλλά χωρίς DPS. Ο κωδικός (χωρίς DPS) πρέπει να συμμορφώνεται με μορφή PAF®.

**Returns:** Return to Sender Post Code but no DPS

### getRTSFlag() {#getrtsflag}

Σημαία που υποδεικνύει ποιο επίπεδο υπηρεσίας Return to Sender ζητείται.

**Returns:** RTS Flag

### getSupplyChainID() {#getsupplychainid}

Αναγνωρίζει τη μοναδική ομάδα πελατών που συμμετέχουν στην αποστολή. Μέγιστη τιμή: 9999999.

**Returns:** Supply chain ID

### getUPUCountryID() {#getupucountryid}

Αναγνωρίζει το UPU Country ID. Μέγιστο μήκος: 4 χαρακτήρες.

**Returns:** Country ID

### getVersionID() {#getversionid}

Αναγνωρίζει την έκδοση του barcode όπως σχετίζεται με κάθε Information Type ID. Έγκυρες τιμές: Προς το παρόν '1'. '0' & '2' έως '9' και 'A' έως 'Z' διατηρούνται για ενδεχόμενη μελλοντική χρήση.

**Returns:** Version ID

### initFromString(constructedCodetext) {#initfromstring}

Αρχικοποιεί τα δεδομένα Mailmark από τον κατασκευασμένο κώδικα κειμένου.

| Παράμετρος | Περιγραφή |
| --- | --- |
| constructedCodetext | Δημιουργημένο κείμενο κώδικα. |

### setClass_(value) {#setclass-}

Αναγνωρίζει την κλάση του στοιχείου. Έγκυρες τιμές: '1' - 1C (Λιανική) '2' - 2C (Λιανική) '3' - Economy (Λιανική) '5' - Deffered (Λιανική) '8' - Premium (Πρόσβαση Δικτύου) '9' - Standard (Πρόσβαση Δικτύου)

| Παράμετρος | Περιγραφή |
| --- | --- |
| τιμή | κλάση του στοιχείου |

### setCustomerContent(value) {#setcustomercontent}

Προαιρετικός χώρος για χρήση από τον πελάτη. Μέγιστο μήκος ανά τύπο: Τύπος 7: 6 χαρακτήρες Τύπος 9: 45 χαρακτήρες Τύπος 29: 25 χαρακτήρες

| Παράμετρος | Περιγραφή |
| --- | --- |
| τιμή | Περιεχόμενο πελάτη |

### setCustomerContentEncodeMode(value) {#setcustomercontentencodemode}

Λειτουργία κωδικοποίησης του barcode Datamatrix. Προεπιλεγμένη τιμή: DataMatrixEncodeMode.C40.

| Παράμετρος | Περιγραφή |
| --- | --- |
| τιμή | Λειτουργία κωδικοποίησης του barcode Datamatrix. |

### setDataMatrixType(value) {#setdatamatrixtype}

Ο τύπος 2D Mailmark ορίζει το μέγεθος του barcode Data Matrix.

| Παράμετρος | Περιγραφή |
| --- | --- |
| τιμή | Μέγεθος του barcode Data Matrix |

### setDestinationPostCodeAndDPS(value) {#setdestinationpostcodeanddps}

Περιέχει τον ταχυδρομικό κώδικα της διεύθυνσης παράδοσης με DPS. Εάν είναι ενδοχώρα, ο ταχυδρομικός κώδικας/DP περιέχει τον ακόλουθο αριθμό χαρακτήρων. Περιοχή (1 ή 2 χαρακτήρες) Περιφέρεια (1 ή 2 χαρακτήρες) Τομέας (1 χαρακτήρας) Μονάδα (2 χαρακτήρες) DPS (2 χαρακτήρες). Ο ταχυδρομικός κώδικας και το DPS πρέπει να συμμορφώνονται με έγκυρη μορφή PAF®.

| Παράμετρος | Περιγραφή |
| --- | --- |
| τιμή | ο ταχυδρομικός κώδικας της διεύθυνσης παράδοσης με DPS |

### setInformationTypeID(value) {#setinformationtypeid}

Αναγνωρίζει το payload του barcode Royal Mail Mailmark για κάθε τύπο προϊόντος. Έγκυρες τιμές: '0' - Ενδοχώρα Ταξινομημένα & Αταξινόμητα 'A' - Online Postage 'B' - Franking 'C' - Consolidation

| Παράμετρος | Περιγραφή |
| --- | --- |
| τιμή | ID τύπου πληροφορίας |

### setItemID(value) {#setitemid}

Αναγνωρίζει το μοναδικό στοιχείο εντός του Supply Chain ID. Κάθε barcode Mailmark απαιτείται να φέρει ένα ID ώστε να μπορεί να αναγνωρίζεται μοναδικά για τουλάχιστον 90 ημέρες. Μέγιστη τιμή: 99999999.

| Παράμετρος | Περιγραφή |
| --- | --- |
| τιμή | στοιχείο εντός του Supply Chain ID |

### setReturnToSenderPostCode(value) {#setreturntosenderpostcode}

Περιέχει τον κωδικό επιστροφής αποστολέα αλλά χωρίς DPS. Ο κωδικός (χωρίς DPS) πρέπει να συμμορφώνεται με μορφή PAF®.

| Παράμετρος | Περιγραφή |
| --- | --- |
| τιμή | Κωδικός επιστροφής αποστολέα αλλά χωρίς DPS |

### setRTSFlag() {#setrtsflag}

Σημαία που υποδεικνύει ποιο επίπεδο υπηρεσίας Return to Sender ζητείται.

**Returns:** RTS Flag

### setSupplyChainID(value) {#setsupplychainid}

Αναγνωρίζει τη μοναδική ομάδα πελατών που συμμετέχουν στην αποστολή. Μέγιστη τιμή: 9999999.

| Παράμετρος | Περιγραφή |
| --- | --- |
| τιμή | Αναγνωριστικό αλυσίδας εφοδιασμού |

### setUPUCountryID(value) {#setupucountryid}

Αναγνωρίζει το UPU Country ID. Μέγιστο μήκος: 4 χαρακτήρες.

| Παράμετρος | Περιγραφή |
| --- | --- |
| τιμή | Κωδικός χώρας |

### setVersionID(value) {#setversionid}

Αναγνωρίζει την έκδοση του barcode όπως σχετίζεται με κάθε Information Type ID. Έγκυρες τιμές: Προς το παρόν '1'. '0' & '2' έως '9' και 'A' έως 'Z' διατηρούνται για ενδεχόμενη μελλοντική χρήση.

| Παράμετρος | Περιγραφή |
| --- | --- |
| τιμή | Κωδικός έκδοσης |
