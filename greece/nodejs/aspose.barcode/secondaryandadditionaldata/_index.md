---
title: "SecondaryAndAdditionalData"
linktitle: "SecondaryAndAdditionalData"
second_title: "Αναφορά API του Aspose.BarCode για Node.js μέσω Java"
description: "Κλάση για αποθήκευση δευτερευόντων και πρόσθετων δεδομένων HIBC LIC."
type: docs
weight: 880
url: /el/nodejs/aspose.barcode/secondaryandadditionaldata/
---

## SecondaryAndAdditionalData class

Κλάση για αποθήκευση δευτερευόντων και πρόσθετων δεδομένων HIBC LIC.

```js
new SecondaryAndAdditionalData()
```

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [equals(obj)](#equals) | Επιστρέφει μια τιμή που υποδεικνύει εάν αυτή η παρουσία είναι ίση με μια καθορισμένη τιμή `SecondaryAndAdditionalData`. |
| [getDateOfManufacture()](#getdateofmanufacture) | Αναγνωρίζει την ημερομηνία κατασκευής. Η ημερομηνία κατασκευής μπορεί να οριστεί σε DateTime.MinValue ώστε να μην χρησιμοποιηθεί αυτό το πεδίο. Defa |
| [getExpiryDate()](#getexpirydate) | Αναγνωρίζει την ημερομηνία λήξης. Θα χρησιμοποιηθεί εάν το ExpiryDateFormat δεν έχει οριστεί σε None. |
| [getExpiryDateFormat()](#getexpirydateformat) | Αναγνωρίζει τη μορφή ημερομηνίας λήξης. |
| [getLotNumber()](#getlotnumber) | Αναγνωρίζει τον αριθμό παρτίδας ή δέσμης. Ο αριθμός παρτίδας/δέσμης πρέπει να είναι αλφαριθμητικό συμβολοσειρά με μήκος έως 18 συμβόλων. . |
| [getQuantity()](#getquantity) | Αναγνωρίζει την ποσότητα, πρέπει να είναι ακέραια τιμή από 0 έως 500. Η ποσότητα μπορεί να οριστεί σε -1 ώστε να μην χρησιμοποιηθεί αυτό το πεδίο. Defa |
| [getSerialNumber()](#getserialnumber) | Αναγνωρίζει τον σειριακό αριθμό. Ο σειριακός αριθμός πρέπει να είναι αλφαριθμητική συμβολοσειρά έως 18 συμβόλων μήκος. |
| [hashCode()](#hashcode) | Επιστρέφει τον κωδικό κατακερματισμού για αυτήν την παρουσία. |
| [parseFromString(secondaryDataCodetext)](#parsefromstring) | Δημιουργεί δευτερεύοντα και πρόσθετα συμπληρωματικά δεδομένα από μορφή συμβολοσειράς σύμφωνα με την προδιαγραφή HIBC LIC. |
| [setDateOfManufacture()](#setdateofmanufacture) | Αναγνωρίζει την ημερομηνία κατασκευής. Η ημερομηνία κατασκευής μπορεί να οριστεί σε DateTime.MinValue ώστε να μην χρησιμοποιηθεί αυτό το πεδίο. Defa |
| [setExpiryDate()](#setexpirydate) | Αναγνωρίζει την ημερομηνία λήξης. Θα χρησιμοποιηθεί εάν το ExpiryDateFormat δεν έχει οριστεί σε None. |
| [setExpiryDateFormat()](#setexpirydateformat) | Αναγνωρίζει τη μορφή ημερομηνίας λήξης. |
| [setLotNumber()](#setlotnumber) | Αναγνωρίζει τον αριθμό παρτίδας ή δέσμης. Ο αριθμός παρτίδας/δέσμης πρέπει να είναι αλφαριθμητικό συμβολοσειρά με μήκος έως 18 συμβόλων. . |
| [setQuantity()](#setquantity) | Αναγνωρίζει την ποσότητα, πρέπει να είναι ακέραια τιμή από 0 έως 500. Η ποσότητα μπορεί να οριστεί σε -1 ώστε να μην χρησιμοποιηθεί αυτό το πεδίο. Defa |
| [setSerialNumber()](#setserialnumber) | Αναγνωρίζει τον σειριακό αριθμό. Ο σειριακός αριθμός πρέπει να είναι αλφαριθμητική συμβολοσειρά έως 18 συμβόλων μήκος. |
| [toString()](#tostring) | Μετατρέπει τα δεδομένα σε μορφή συμβολοσειράς σύμφωνα με την προδιαγραφή HIBC LIC. |

### equals(obj) {#equals}

Επιστρέφει μια τιμή που υποδεικνύει εάν αυτή η παρουσία είναι ίση με μια καθορισμένη τιμή `SecondaryAndAdditionalData`.

| Παράμετρος | Περιγραφή |
| --- | --- |
| obj | Μια τιμή `SecondaryAndAdditionalData` για σύγκριση με αυτήν την παρουσία. |

**Returns:** `true ` if obj has the same value as this instance; otherwise, `false `.

### getDateOfManufacture() {#getdateofmanufacture}

Αναγνωρίζει την ημερομηνία κατασκευής. Η ημερομηνία κατασκευής μπορεί να οριστεί σε DateTime.MinValue ώστε να μην χρησιμοποιηθεί αυτό το πεδίο. Προεπιλεγμένη τιμή: DateTime.MinValue

### getExpiryDate() {#getexpirydate}

Αναγνωρίζει την ημερομηνία λήξης. Θα χρησιμοποιηθεί εάν το ExpiryDateFormat δεν έχει οριστεί σε None.

### getExpiryDateFormat() {#getexpirydateformat}

Αναγνωρίζει τη μορφή ημερομηνίας λήξης.

### getLotNumber() {#getlotnumber}

Αναγνωρίζει τον αριθμό παρτίδας ή δέσμης. Ο αριθμός παρτίδας/δέσμης πρέπει να είναι αλφαριθμητικό συμβολοσειρά με μήκος έως 18 συμβόλων. .

### getQuantity() {#getquantity}

Αναγνωρίζει την ποσότητα, πρέπει να είναι ακέραια τιμή από 0 έως 500. Η ποσότητα μπορεί να οριστεί σε -1 ώστε να μην χρησιμοποιηθεί αυτό το πεδίο. Προεπιλεγμένη τιμή: -1

### getSerialNumber() {#getserialnumber}

Αναγνωρίζει τον σειριακό αριθμό. Ο σειριακός αριθμός πρέπει να είναι αλφαριθμητική συμβολοσειρά έως 18 συμβόλων μήκος.

### hashCode() {#hashcode}

Επιστρέφει τον κωδικό κατακερματισμού για αυτήν την παρουσία.

**Returns:** A 32-bit signed integer hash code.

### parseFromString(secondaryDataCodetext) {#parsefromstring}

Δημιουργεί δευτερεύοντα και πρόσθετα συμπληρωματικά δεδομένα από μορφή συμβολοσειράς σύμφωνα με την προδιαγραφή HIBC LIC.

| Παράμετρος | Περιγραφή |
| --- | --- |
| secondaryDataCodetext | Μορφοποιημένη συμβολοσειρά. |

### setDateOfManufacture() {#setdateofmanufacture}

Αναγνωρίζει την ημερομηνία κατασκευής. Η ημερομηνία κατασκευής μπορεί να οριστεί σε DateTime.MinValue ώστε να μην χρησιμοποιηθεί αυτό το πεδίο. Προεπιλεγμένη τιμή: DateTime.MinValue

### setExpiryDate() {#setexpirydate}

Αναγνωρίζει την ημερομηνία λήξης. Θα χρησιμοποιηθεί εάν το ExpiryDateFormat δεν έχει οριστεί σε None.

### setExpiryDateFormat() {#setexpirydateformat}

Αναγνωρίζει τη μορφή ημερομηνίας λήξης.

### setLotNumber() {#setlotnumber}

Αναγνωρίζει τον αριθμό παρτίδας ή δέσμης. Ο αριθμός παρτίδας/δέσμης πρέπει να είναι αλφαριθμητικό συμβολοσειρά με μήκος έως 18 συμβόλων. .

### setQuantity() {#setquantity}

Αναγνωρίζει την ποσότητα, πρέπει να είναι ακέραια τιμή από 0 έως 500. Η ποσότητα μπορεί να οριστεί σε -1 ώστε να μην χρησιμοποιηθεί αυτό το πεδίο. Προεπιλεγμένη τιμή: -1

### setSerialNumber() {#setserialnumber}

Αναγνωρίζει τον σειριακό αριθμό. Ο σειριακός αριθμός πρέπει να είναι αλφαριθμητική συμβολοσειρά έως 18 συμβόλων μήκος.

### toString() {#tostring}

Μετατρέπει τα δεδομένα σε μορφή συμβολοσειράς σύμφωνα με την προδιαγραφή HIBC LIC.

**Returns:** Formatted string.
