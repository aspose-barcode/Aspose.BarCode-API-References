---
title: "SwissQRBill"
linktitle: "SwissQRBill"
second_title: "Αναφορά API του Aspose.BarCode για Node.js μέσω Java"
description: "Δεδομένα λογαριασμού SwissQR"
type: docs
weight: 920
url: /el/nodejs/aspose.barcode/swissqrbill/
---

## SwissQRBill class

Δεδομένα λογαριασμού SwissQR

```js
new SwissQRBill()
```

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [createAndSetCreditorReference(rawReference)](#createandsetcreditorreference) | Δημιουργεί και ορίζει μια αναφορά πιστωτή ISO11649 από μια ακατέργαστη συμβολοσειρά προσθέτοντας στην αρχή της συμβολοσειράς το "RF" και το modulo 97 che |
| [equals(obj)](#equals) | Καθορίζει εάν το καθορισμένο αντικείμενο είναι ίσο με το τρέχον αντικείμενο. |
| [getAccount()](#getaccount) | Λαμβάνει τον αριθμό λογαριασμού του πιστωτή. Οι αριθμοί λογαριασμού πρέπει να είναι έγκυρα IBAN τράπεζας της Ελβετίας ή του Λιχτενστάιν. Space |
| [getAlternativeSchemes()](#getalternativeschemes) | Λαμβάνει ή ορίζει τα εναλλακτικά σχήματα πληρωμής. Επιτρέπονται το πολύ δύο σχήματα με παραμέτρους. |
| [getAmount()](#getamount) | Λαμβάνει το ποσό πληρωμής. Έγκυρες τιμές είναι μεταξύ 0.01 και 999,999,999.99. |
| [getBillInformation()](#getbillinformation) | Λαμβάνει τις πρόσθετες δομημένες πληροφορίες τιμολογίου. |
| [getCreditor()](#getcreditor) | Λαμβάνει τη διεύθυνση του πιστωτή. |
| [getCurrency()](#getcurrency) | Λαμβάνει το νόμισμα πληρωμής. Έγκυρες τιμές είναι "CHF" και "EUR". |
| [getDebtor()](#getdebtor) | Λαμβάνει τη διεύθυνση του οφειλέτη. Ο οφειλέτης είναι προαιρετικός. Εάν παραληφθεί, τόσο η ρύθμιση αυτού του πεδίου σε null όσο και η ρύθμιση μιας διεύθυνσης |
| [getReference()](#getreference) | Λαμβάνει την αναφορά πληρωμής του πιστωτή. Η αναφορά είναι υποχρεωτική για τα SwissQR IBAN, π.χ. IBANs στην περιοχή CHxx30000xxxxx |
| [getUnstructuredMessage()](#getunstructuredmessage) | Λαμβάνει το πρόσθετο αδόμητο μήνυμα. |
| [getVersion()](#getversion) | Λαμβάνει την έκδοση του προτύπου τιμολογίου SwissQR. |
| [hashCode()](#hashcode) | Λαμβάνει τον κωδικό κατακερματισμού για αυτήν την παρουσία. |
| [setAccount(value:)](#setaccount) | Ορίζει τον αριθμό λογαριασμού του πιστωτή. Οι αριθμοί λογαριασμού πρέπει να είναι έγκυρα IBANs τράπεζας της Ελβετίας ή του Λίχτενσταϊν. Διάστημα |
| [setAlternativeSchemes(value:)](#setalternativeschemes) | Λαμβάνει ή ορίζει τα εναλλακτικά σχήματα πληρωμής. Επιτρέπονται το πολύ δύο σχήματα με παραμέτρους. |
| [setAmount(value)](#setamount) | Ορίζει το ποσό πληρωμής. Έγκυρες τιμές είναι μεταξύ 0.01 και 999,999,999.99. |
| [setBillInformation(value:)](#setbillinformation) | Ορίζει τις πρόσθετες δομημένες πληροφορίες τιμολογίου. |
| [setCreditor(value:)](#setcreditor) | Ορίζει τη διεύθυνση του πιστωτή. |
| [setCurrency(value)](#setcurrency) | Ορίζει το νόμισμα πληρωμής. |
| [setDebtor(value:)](#setdebtor) | Ορίζει τη διεύθυνση του οφειλέτη. Ο οφειλέτης είναι προαιρετικός. Εάν παραληφθεί, τόσο η ρύθμιση αυτού του πεδίου σε null όσο και η ρύθμιση μιας διεύθυνσης |
| [setReference(value)](#setreference) | Ορίζει την αναφορά πληρωμής του πιστωτή. Η αναφορά είναι υποχρεωτική για τα SwissQR IBAN, π.χ. IBANs στην περιοχή CHxx30000xxxxx. |
| [setUnstructuredMessage(value:)](#setunstructuredmessage) | Ορίζει το πρόσθετο αδόμητο μήνυμα. |
| [setVersion(value)](#setversion) | Ορίζει την έκδοση του προτύπου τιμολογίου SwissQR. |

### createAndSetCreditorReference(rawReference) {#createandsetcreditorreference}

Δημιουργεί και ορίζει μια αναφορά πιστωτή ISO11649 από μια ακατέργαστη συμβολοσειρά προσθέτοντας στην αρχή της συμβολοσειράς το "RF" και τον έλεγχο modulo 97. Τα κενά διαστήματα αφαιρούνται από την αναφορά.

| Παράμετρος | Περιγραφή |
| --- | --- |
| rawReference | Η ακατέργαστη αναφορά. |

**Throws:** ArgumentException rawReference contains invalid characters.

### equals(obj) {#equals}

Καθορίζει εάν το καθορισμένο αντικείμενο είναι ίσο με το τρέχον αντικείμενο.

| Παράμετρος | Περιγραφή |
| --- | --- |
| obj | Το αντικείμενο προς σύγκριση με το τρέχον αντικείμενο. |

**Returns:** true if the specified object is equal to the current object; otherwise, false.

### getAccount() {#getaccount}

Λαμβάνει τον αριθμό λογαριασμού του πιστωτή. Οι αριθμοί λογαριασμού πρέπει να είναι έγκυρα IBANs τράπεζας της Ελβετίας ή του Λίχτενσταϊν. Επιτρέπονται κενά στο αριθμό λογαριασμού.

**Returns:** The creditor account number.

### getAlternativeSchemes() {#getalternativeschemes}

Λαμβάνει ή ορίζει τα εναλλακτικά σχήματα πληρωμής. Επιτρέπονται το πολύ δύο σχήματα με παραμέτρους.

**Returns:** The alternative payment schemes.

### getAmount() {#getamount}

Λαμβάνει το ποσό πληρωμής. Έγκυρες τιμές είναι μεταξύ 0.01 και 999,999,999.99.

**Returns:** The payment amount.

### getBillInformation() {#getbillinformation}

Λαμβάνει τις πρόσθετες δομημένες πληροφορίες τιμολογίου.

**Returns:** The structured bill information.

### getCreditor() {#getcreditor}

Λαμβάνει τη διεύθυνση του πιστωτή.

**Returns:** The creditor address.

### getCurrency() {#getcurrency}

Λαμβάνει το νόμισμα πληρωμής. Έγκυρες τιμές είναι "CHF" και "EUR".

**Returns:** The payment currency.

### getDebtor() {#getdebtor}

Λαμβάνει τη διεύθυνση του οφειλέτη. Ο οφειλέτης είναι προαιρετικός. Εάν παραληφθεί, τόσο η ρύθμιση αυτού του πεδίου σε null όσο και η ρύθμιση μιας διεύθυνσης με όλες τις τιμές null ή κενές είναι εντάξει.

**Returns:** The debtor address.

### getReference() {#getreference}

Λαμβάνει την αναφορά πληρωμής του πιστωτή. Η αναφορά είναι υποχρεωτική για τα SwissQR IBAN, π.χ. IBANs στην περιοχή CHxx30000xxxxxx έως CHxx31999xxxxx. Εάν καθοριστεί, η αναφορά πρέπει να είναι είτε μια έγκυρη αναφορά SwissQR (σύμφωνη με τη μορφή αναφοράς ISR) είτε μια έγκυρη αναφορά πιστωτή σύμφωνα με ISO 11649 ("RFxxxx"). Και τα δύο μπορεί να περιέχουν κενά για μορφοποίηση.

**Returns:** The creditor payment reference.

### getUnstructuredMessage() {#getunstructuredmessage}

Λαμβάνει το πρόσθετο αδόμητο μήνυμα.

**Returns:** The unstructured message.

### getVersion() {#getversion}

Λαμβάνει την έκδοση του προτύπου τιμολογίου SwissQR.

**Returns:** The SwissQR bill standard version.

### hashCode() {#hashcode}

Λαμβάνει τον κωδικό κατακερματισμού για αυτήν την παρουσία.

**Returns:** A hash code for the current object.

### setAccount(value:) {#setaccount}

Ορίζει τον αριθμό λογαριασμού του πιστωτή. Οι αριθμοί λογαριασμού πρέπει να είναι έγκυρα IBANs τράπεζας της Ελβετίας ή του Λίχτενσταϊν. Επιτρέπονται κενά στο αριθμό λογαριασμού.

| Παράμετρος | Περιγραφή |
| --- | --- |
| τιμή: | Ο αριθμός λογαριασμού του πιστωτή. |

### setAlternativeSchemes(value:) {#setalternativeschemes}

Λαμβάνει ή ορίζει τα εναλλακτικά σχήματα πληρωμής. Επιτρέπονται το πολύ δύο σχήματα με παραμέτρους.

| Παράμετρος | Περιγραφή |
| --- | --- |
| τιμή: | Τα εναλλακτικά σχήματα πληρωμής. |

### setAmount(value) {#setamount}

Ορίζει το ποσό πληρωμής. Έγκυρες τιμές είναι μεταξύ 0.01 και 999,999,999.99.

| Παράμετρος | Περιγραφή |
| --- | --- |
| τιμή | Το ποσό πληρωμής. |

### setBillInformation(value:) {#setbillinformation}

Ορίζει τις πρόσθετες δομημένες πληροφορίες τιμολογίου.

| Παράμετρος | Περιγραφή |
| --- | --- |
| τιμή: | Οι δομημένες πληροφορίες τιμολογίου. |

### setCreditor(value:) {#setcreditor}

Ορίζει τη διεύθυνση του πιστωτή.

| Παράμετρος | Περιγραφή |
| --- | --- |
| τιμή: | Η διεύθυνση του πιστωτή. |

### setCurrency(value) {#setcurrency}

Ορίζει το νόμισμα πληρωμής.

| Παράμετρος | Περιγραφή |
| --- | --- |
| τιμή | Οι έγκυρες τιμές είναι "CHF" και "EUR". |

### setDebtor(value:) {#setdebtor}

Ορίζει τη διεύθυνση του οφειλέτη. Ο οφειλέτης είναι προαιρετικός. Εάν παραλειφθεί, τόσο η ρύθμιση αυτού του πεδίου σε null όσο και η ρύθμιση μιας διεύθυνσης με όλες τις τιμές null ή κενές είναι αποδεκτή.

| Παράμετρος | Περιγραφή |
| --- | --- |
| τιμή: | Η διεύθυνση του οφειλέτη. |

### setReference(value) {#setreference}

Ορίζει την αναφορά πληρωμής του πιστωτή. Η αναφορά είναι υποχρεωτική για τα SwissQR IBAN, δηλαδή IBAN στην περιοχή CHxx30000xxxxxx έως CHxx31999xxxxx. Εάν καθοριστεί, η αναφορά πρέπει να είναι είτε μια έγκυρη αναφορά SwissQR (σύμφωνη με τη μορφή αναφοράς ISR) είτε μια έγκυρη αναφορά πιστωτή σύμφωνα με το ISO 11649 ("RFxxxx"). Και τα δύο μπορούν να περιέχουν κενά για μορφοποίηση.

| Παράμετρος | Περιγραφή |
| --- | --- |
| τιμή | Η αναφορά πληρωμής του πιστωτή. |

### setUnstructuredMessage(value:) {#setunstructuredmessage}

Ορίζει το πρόσθετο αδόμητο μήνυμα.

| Παράμετρος | Περιγραφή |
| --- | --- |
| τιμή: | Το αδόμητο μήνυμα. |

### setVersion(value) {#setversion}

Ορίζει την έκδοση του προτύπου τιμολογίου SwissQR.

| Παράμετρος | Περιγραφή |
| --- | --- |
| τιμή | Η έκδοση του πρότυπου τιμολογίου SwissQR. |
