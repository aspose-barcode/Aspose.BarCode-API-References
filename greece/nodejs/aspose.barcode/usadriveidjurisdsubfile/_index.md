---
title: "USADriveIdJurisdSubfile"
linktitle: "USADriveIdJurisdSubfile"
second_title: "Αναφορά API του Aspose.BarCode για Node.js μέσω Java"
description: "Κλάση για πεδία ειδικά για δικαιοδοσία για USA DL"
type: docs
weight: 950
url: /el/nodejs/aspose.barcode/usadriveidjurisdsubfile/
---

## USADriveIdJurisdSubfile class

Κλάση για πεδία ειδικά για δικαιοδοσία για USA DL

```js
new USADriveIdJurisdSubfile()
```

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [addOrReplace(id, value)](#addorreplace) | Προσθέτει ένα νέο DataElement με το καθορισμένο αναγνωριστικό και τιμή, ή αντικαθιστά το υπάρχον στοιχείο εάν υπάρχει μια καταχώρηση με το sa |
| [addOrReplaceNode(node)](#addorreplacenode) | Προσθέτει νέο DataElement ή το αντικαθιστά εάν το ElementID υπάρχει ήδη. |
| [clear()](#clear) | Καθαρίζει όλα τα στοιχεία δεδομένων |
| [findDataElement(id, isOpenOrCreate)](#finddataelement) | Αναζητά στοιχείο δεδομένων με βάση το 3-γράμματο id |
| [get(indexOrId)](#get) | Λαμβάνει ένα στοιχείο δεδομένων με το δείκτη του ή το 3-γράμματο ID. |
| [insert(index, node)](#insert) | Εισάγει το καθορισμένο DataElement στη δοσμένη θέση. Εάν υπάρχει ήδη ένα DataElement με το ίδιο ElementID, θα b |
| [remove(indexOrId)](#remove) | Προσπαθεί να αφαιρέσει ένα στοιχείο με το δείκτη του ή το 3-γράμματο ID. |
| [set(indexOrId, value)](#set) | Ορίζει ένα στοιχείο δεδομένων με το δείκτη του ή το 3-γράμματο ID. |
| [size()](#size) | Επιστρέφει τον αριθμό των στοιχείων δεδομένων |

### addOrReplace(id, value) {#addorreplace}

Προσθέτει ένα νέο DataElement με το καθορισμένο αναγνωριστικό και τιμή, ή αντικαθιστά το υπάρχον στοιχείο εάν υπάρχει ήδη μια καταχώρηση με το ίδιο ElementID.

| Παράμετρος | Περιγραφή |
| --- | --- |
| id | Ένα 3-γράμματο αναγνωριστικό που καθορίζει μοναδικά το στοιχείο δεδομένων σχετικό με τη δικαιοδοσία. |
| τιμή | Η τιμή κειμένου που έχει ανατεθεί στο στοιχείο δεδομένων· αυτή η τιμή θα αντικαταστήσει την υπάρχουσα εάν το στοιχείο υπάρχει ήδη. |

**Returns:** The DataElement instance that was added to the collection or updated in place.

### addOrReplaceNode(node) {#addorreplacenode}

Προσθέτει νέο DataElement ή το αντικαθιστά εάν το ElementID υπάρχει ήδη.

| Παράμετρος | Περιγραφή |
| --- | --- |
| node | DataElement για προσθήκη |

**Returns:** Added/replaced data element

### clear() {#clear}

Καθαρίζει όλα τα στοιχεία δεδομένων

### findDataElement(id, isOpenOrCreate) {#finddataelement}

Αναζητά στοιχείο δεδομένων με βάση το 3-γράμματο id

| Παράμετρος | Περιγραφή |
| --- | --- |
| id | 3-γράμματο id |
| isOpenOrCreate | Εάν είναι true, θα δημιουργηθεί εάν δεν βρεθεί |

**Returns:** Found data element

### get(indexOrId) {#get}

Λαμβάνει ένα στοιχείο δεδομένων με το δείκτη του ή το 3-γράμματο ID.

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| indexOrId | number\ | string | Ακέραιος δείκτης ή 3-γράμματο element ID. |

**Returns:** DataElement — Corresponding data element.

### insert(index, node) {#insert}

Εισάγει το καθορισμένο DataElement στη δοσμένη θέση. Εάν υπάρχει ήδη ένα DataElement με το ίδιο ElementID, θα αντικατασταθεί.

| Παράμετρος | Περιγραφή |
| --- | --- |
| index | Ο μηδενικός δείκτης στο οποίο πρέπει να εισαχθεί το στοιχείο. |
| node | Η παρουσία DataElement για εισαγωγή ή αντικατάσταση στη θέση-στόχο. |

**Returns:** The DataElement that was inserted or used to replace an existing entry.

### remove(indexOrId) {#remove}

Προσπαθεί να αφαιρέσει ένα στοιχείο με το δείκτη του ή το 3-γράμματο ID.

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| indexOrId | number\ | string | Ακέραιος δείκτης ή 3-γράμματο element ID. |

**Returns:** boolean — true if the element was removed; otherwise, false.

### set(indexOrId, value) {#set}

Ορίζει ένα στοιχείο δεδομένων με το δείκτη του ή το 3-γράμματο ID.

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| indexOrId | number\ | string | Ακέραιος δείκτης ή 3-γράμματο element ID. |
| τιμή | DataElement | Στοιχείο δεδομένων για ορισμό. |

### size() {#size}

Επιστρέφει τον αριθμό των στοιχείων δεδομένων
