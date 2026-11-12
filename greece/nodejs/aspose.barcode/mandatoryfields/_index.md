---
title: "MandatoryFields"
linktitle: "MandatoryFields"
second_title: "Αναφορά API του Aspose.BarCode για Node.js μέσω Java"
description: "Υποχρεωτικά στοιχεία (πεδία) της κάρτας"
type: docs
weight: 590
url: /el/nodejs/aspose.barcode/mandatoryfields/
---

## MandatoryFields class

Υποχρεωτικά στοιχεία (πεδία) της κάρτας

```js
new MandatoryFields()
```

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [getAddressCity()](#getaddresscity) | DAI, Τμήμα Πόλης της διεύθυνσης του κατόχου κάρτας, DL/ID, V20ANS |
| [getAddressPostalCode()](#getaddresspostalcode) | DAK, Τμήμα Ταχυδρομικού κώδικα της διεύθυνσης του κατόχου κάρτας στις Η.Π.Α. και τον Καναδά. Εάν το τελικό τμήμα του ταχυδρομικού κώδικα σε |
| [getAddressState()](#getaddressstate) | DAJ, Τμήμα Πολιτείας της διεύθυνσης του κατόχου κάρτας, DL/ID, F2A |
| [getAddressStreet1()](#getaddressstreet1) | DAG, Τμήμα Οδού της διεύθυνσης του κατόχου κάρτας, DL/ID, V35ANS |
| [getCountryIdentification()](#getcountryidentification) | DCG, Χώρα στην οποία εκδίδεται το DL/ID. U.S. = USA, Canada = CAN, DL/ID, F3A |
| [getCustomerIDNumber()](#getcustomeridnumber) | DAQ, Ο αριθμός που εκχωρεί ή υπολογίζεται από την αρχή έκδοσης, DL/ID, V25ANS |
| [getDateOfBirth()](#getdateofbirth) | DBB, Ημερομηνία έκδοσης του εγγράφου, MMDDCCYY για τις Η.Π.Α., CCYYMMDD για τον Καναδά, DL/ID, F8N |
| [getDocumentDiscriminator()](#getdocumentdiscriminator) | DCF, Ο αριθμός πρέπει να αναγνωρίζει μοναδικά ένα συγκεκριμένο έγγραφο που εκδόθηκε σε αυτόν τον πελάτη από άλλα που ενδέχεται να έχουν εκδοθεί i |
| [getEndorsementCodes()](#getendorsementcodes) | DCD, Κωδικοί ενδείξεων ειδικοί για τη δικαιοδοσία, DL, V5ANS |
| [getEyeColor()](#geteyecolor) | DAY, Χρώμα των ματιών του κατόχου της κάρτας. (Κωδικοί ANSI D-20). DL/ID, F3A |
| [getFamilyName()](#getfamilyname) | DCS, Επώνυμο του κατόχου της κάρτας, DL/ID, V40ANS |
| [getFamilyNameTruncation()](#getfamilynametruncation) | DDE, Κώδικας που υποδεικνύει εάν ένα πεδίο έχει περικοπεί (T), δεν έχει περικοπεί (N), ή είναι άγνωστο αν έχει περικοπεί |
| [getFirstName()](#getfirstname) | DAC, Όνομα του κατόχου της κάρτας, DL/ID, V40ANS |
| [getFirstNameTruncation()](#getfirstnametruncation) | DDF, Κώδικας που υποδεικνύει εάν ένα πεδίο έχει περικοπεί (T), δεν έχει περικοπεί (N), ή είναι άγνωστο αν έχει περικοπεί |
| [getHeight()](#getheight) | DAU, Ύψος του κατόχου της κάρτας. Ίντσες (in): αριθμός ιντσών ακολουθούμενος από \" in\" π.χ. 6'1'' = \"073 in\" Σεντίνια(cm) : αριθμός |
| [getMiddleName()](#getmiddlename) | DAD, Μεσαίο(α) όνομα(α) του κατόχου της κάρτας. Σε περίπτωση πολλαπλών μεσαίων ονομάτων πρέπει να διαχωρίζονται με κόμμα \",\". , DL |
| [getMiddleNameTruncation()](#getmiddlenametruncation) | DDG, Κώδικας που υποδεικνύει εάν ένα πεδίο έχει περικοπεί (T), δεν έχει περικοπεί (N), ή είναι άγνωστο αν έχει περικοπεί |
| [getRestrictionCodes()](#getrestrictioncodes) | DCB, Κωδικοί περιορισμών ειδικοί για τη δικαιοδοσία, DL, V12ANS |
| [getSex()](#getsex) | DBC, Φύλο του κατόχου της κάρτας. 1 = άνδρας, 2 = γυναίκα, 9 = μη καθορισμένο, DL/ID, F1N |
| [getVehicleClass()](#getvehicleclass) | DCA, Κωδικός κατηγορίας / ομάδας οχήματος ειδικός για τη δικαιοδοσία, DL, V6ANS |
| [setAddressCity()](#setaddresscity) | DAI, Τμήμα Πόλης της διεύθυνσης του κατόχου κάρτας, DL/ID, V20ANS |
| [setAddressPostalCode()](#setaddresspostalcode) | DAK, Τμήμα Ταχυδρομικού κώδικα της διεύθυνσης του κατόχου κάρτας στις Η.Π.Α. και τον Καναδά. Εάν το τελικό τμήμα του ταχυδρομικού κώδικα σε |
| [setAddressState()](#setaddressstate) | DAJ, Τμήμα Πολιτείας της διεύθυνσης του κατόχου κάρτας, DL/ID, F2A |
| [setAddressStreet1()](#setaddressstreet1) | DAG, Τμήμα Οδού της διεύθυνσης του κατόχου κάρτας, DL/ID, V35ANS |
| [setCountryIdentification()](#setcountryidentification) | DCG, Χώρα στην οποία εκδίδεται το DL/ID. U.S. = USA, Canada = CAN, DL/ID, F3A |
| [setCustomerIDNumber()](#setcustomeridnumber) | DAQ, Ο αριθμός που εκχωρεί ή υπολογίζεται από την αρχή έκδοσης, DL/ID, V25ANS |
| [setDateOfBirth()](#setdateofbirth) | DBB, Ημερομηνία έκδοσης του εγγράφου, MMDDCCYY για τις Η.Π.Α., CCYYMMDD για τον Καναδά, DL/ID, F8N |
| [setDocumentDiscriminator()](#setdocumentdiscriminator) | DCF, Ο αριθμός πρέπει να αναγνωρίζει μοναδικά ένα συγκεκριμένο έγγραφο που εκδόθηκε σε αυτόν τον πελάτη από άλλα που ενδέχεται να έχουν εκδοθεί i |
| [setEndorsementCodes()](#setendorsementcodes) | DCD, Κωδικοί ενδείξεων ειδικοί για τη δικαιοδοσία, DL, V5ANS |
| [setEyeColor()](#seteyecolor) | DAY, Χρώμα των ματιών του κατόχου της κάρτας. (Κωδικοί ANSI D-20). DL/ID, F3A |
| [setFamilyName()](#setfamilyname) | DCS, Επώνυμο του κατόχου της κάρτας, DL/ID, V40ANS |
| [setFamilyNameTruncation()](#setfamilynametruncation) | DDE, Κώδικας που υποδεικνύει εάν ένα πεδίο έχει περικοπεί (T), δεν έχει περικοπεί (N), ή είναι άγνωστο αν έχει περικοπεί |
| [setFirstName()](#setfirstname) | DAC, Όνομα του κατόχου της κάρτας, DL/ID, V40ANS |
| [setFirstNameTruncation()](#setfirstnametruncation) | DDF, Κώδικας που υποδεικνύει εάν ένα πεδίο έχει περικοπεί (T), δεν έχει περικοπεί (N), ή είναι άγνωστο αν έχει περικοπεί |
| [setHeight()](#setheight) | DAU, Ύψος του κατόχου της κάρτας. Ίντσες (in): αριθμός ιντσών ακολουθούμενος από \" in\" π.χ. 6'1'' = \"073 in\" Σεντίνια(cm) : αριθμός |
| [setMiddleName()](#setmiddlename) | DAD, Μεσαίο(α) όνομα(α) του κατόχου της κάρτας. Σε περίπτωση πολλαπλών μεσαίων ονομάτων πρέπει να διαχωρίζονται με κόμμα \",\". , DL |
| [setMiddleNameTruncation()](#setmiddlenametruncation) | DDG, Κώδικας που υποδεικνύει εάν ένα πεδίο έχει περικοπεί (T), δεν έχει περικοπεί (N), ή είναι άγνωστο αν έχει περικοπεί |
| [setRestrictionCodes()](#setrestrictioncodes) | DCB, Κωδικοί περιορισμών ειδικοί για τη δικαιοδοσία, DL, V12ANS |
| [setSex()](#setsex) | DBC, Φύλο του κατόχου της κάρτας. 1 = άνδρας, 2 = γυναίκα, 9 = μη καθορισμένο, DL/ID, F1N |
| [setVehicleClass()](#setvehicleclass) | DCA, Κωδικός κατηγορίας / ομάδας οχήματος ειδικός για τη δικαιοδοσία, DL, V6ANS |

### getAddressCity() {#getaddresscity}

DAI, Τμήμα Πόλης της διεύθυνσης του κατόχου κάρτας, DL/ID, V20ANS

### getAddressPostalCode() {#getaddresspostalcode}

DAK, Τμήμα ταχυδρομικού κώδικα της διεύθυνσης του κατόχου της κάρτας στις Η.Π.Α. και τον Καναδά. Εάν το τελικό τμήμα του ταχυδρομικού κώδικα στις Η.Π.Α. δεν είναι γνωστό, θα χρησιμοποιηθούν μηδενικά για να συμπληρωθεί το τελικό σύνολο αριθμών έως 9 ψηφία, DL/ID, F11ANS

### getAddressState() {#getaddressstate}

DAJ, Τμήμα Πολιτείας της διεύθυνσης του κατόχου κάρτας, DL/ID, F2A

### getAddressStreet1() {#getaddressstreet1}

DAG, Τμήμα Οδού της διεύθυνσης του κατόχου κάρτας, DL/ID, V35ANS

### getCountryIdentification() {#getcountryidentification}

DCG, Χώρα στην οποία εκδίδεται το DL/ID. U.S. = USA, Canada = CAN, DL/ID, F3A

### getCustomerIDNumber() {#getcustomeridnumber}

DAQ, Ο αριθμός που εκχωρεί ή υπολογίζεται από την αρχή έκδοσης, DL/ID, V25ANS

### getDateOfBirth() {#getdateofbirth}

DBB, Ημερομηνία έκδοσης του εγγράφου, MMDDCCYY για τις Η.Π.Α., CCYYMMDD για τον Καναδά, DL/ID, F8N

### getDocumentDiscriminator() {#getdocumentdiscriminator}

DCF, Ο αριθμός πρέπει να αναγνωρίζει μοναδικά ένα συγκεκριμένο έγγραφο που εκδόθηκε σε αυτόν τον πελάτη από άλλα που ενδέχεται να έχουν εκδοθεί στο παρελθόν. Αυτός ο αριθμός μπορεί να εξυπηρετεί πολλαπλούς σκοπούς όπως διακριτική ταυτοποίηση εγγράφου, αριθμό πληροφοριών ελέγχου, και/ή έλεγχο αποθεμάτων, DL/ID, V25ANS

### getEndorsementCodes() {#getendorsementcodes}

DCD, Κωδικοί ενδείξεων ειδικοί για τη δικαιοδοσία, DL, V5ANS

### getEyeColor() {#geteyecolor}

DAY, Χρώμα των ματιών του κατόχου της κάρτας. (Κωδικοί ANSI D-20). DL/ID, F3A

### getFamilyName() {#getfamilyname}

DCS, Επώνυμο του κατόχου της κάρτας, DL/ID, V40ANS

### getFamilyNameTruncation() {#getfamilynametruncation}

DDE, Κώδικας που υποδεικνύει εάν ένα πεδίο έχει περικοπεί (T), δεν έχει περικοπεί (N), ή είναι άγνωστο αν έχει περικοπεί (U), DL/ID, F1A

### getFirstName() {#getfirstname}

DAC, Όνομα του κατόχου της κάρτας, DL/ID, V40ANS

### getFirstNameTruncation() {#getfirstnametruncation}

DDF, Κώδικας που υποδεικνύει εάν ένα πεδίο έχει περικοπεί (T), δεν έχει περικοπεί (N), ή είναι άγνωστο αν έχει περικοπεί (U), DL/ID, F1A

### getHeight() {#getheight}

DAU, Ύψος του κατόχου της κάρτας. Ίντσες (in): αριθμός ιντσών ακολουθούμενος από \" in\" π.χ. 6'1'' = \"073 in\" Σεντίνια(cm) : αριθμός εκατοστών ακολουθούμενος από \" cm\" π.χ. 181 εκατοστά=\"181 cm\" , DL/ID, F6ANS

### getMiddleName() {#getmiddlename}

DAD, Μεσαίο(α) όνομα(α) του κατόχου της κάρτας. Σε περίπτωση πολλαπλών μεσαίων ονομάτων πρέπει να διαχωρίζονται με κόμμα \",\". , DL/ID, V40ANS

### getMiddleNameTruncation() {#getmiddlenametruncation}

DDG, Κώδικας που υποδεικνύει εάν ένα πεδίο έχει περικοπεί (T), δεν έχει περικοπεί (N), ή είναι άγνωστο αν έχει περικοπεί (U), DL/ID, F1A

### getRestrictionCodes() {#getrestrictioncodes}

DCB, Κωδικοί περιορισμών ειδικοί για τη δικαιοδοσία, DL, V12ANS

### getSex() {#getsex}

DBC, Φύλο του κατόχου της κάρτας. 1 = άνδρας, 2 = γυναίκα, 9 = μη καθορισμένο, DL/ID, F1N

### getVehicleClass() {#getvehicleclass}

DCA, Κωδικός κατηγορίας / ομάδας οχήματος ειδικός για τη δικαιοδοσία, DL, V6ANS

### setAddressCity() {#setaddresscity}

DAI, Τμήμα Πόλης της διεύθυνσης του κατόχου κάρτας, DL/ID, V20ANS

### setAddressPostalCode() {#setaddresspostalcode}

DAK, Τμήμα ταχυδρομικού κώδικα της διεύθυνσης του κατόχου της κάρτας στις Η.Π.Α. και τον Καναδά. Εάν το τελικό τμήμα του ταχυδρομικού κώδικα στις Η.Π.Α. δεν είναι γνωστό, θα χρησιμοποιηθούν μηδενικά για να συμπληρωθεί το τελικό σύνολο αριθμών έως 9 ψηφία, DL/ID, F11ANS

### setAddressState() {#setaddressstate}

DAJ, Τμήμα Πολιτείας της διεύθυνσης του κατόχου κάρτας, DL/ID, F2A

### setAddressStreet1() {#setaddressstreet1}

DAG, Τμήμα Οδού της διεύθυνσης του κατόχου κάρτας, DL/ID, V35ANS

### setCountryIdentification() {#setcountryidentification}

DCG, Χώρα στην οποία εκδίδεται το DL/ID. U.S. = USA, Canada = CAN, DL/ID, F3A

### setCustomerIDNumber() {#setcustomeridnumber}

DAQ, Ο αριθμός που εκχωρεί ή υπολογίζεται από την αρχή έκδοσης, DL/ID, V25ANS

### setDateOfBirth() {#setdateofbirth}

DBB, Ημερομηνία έκδοσης του εγγράφου, MMDDCCYY για τις Η.Π.Α., CCYYMMDD για τον Καναδά, DL/ID, F8N

### setDocumentDiscriminator() {#setdocumentdiscriminator}

DCF, Ο αριθμός πρέπει να αναγνωρίζει μοναδικά ένα συγκεκριμένο έγγραφο που εκδόθηκε σε αυτόν τον πελάτη από άλλα που ενδέχεται να έχουν εκδοθεί στο παρελθόν. Αυτός ο αριθμός μπορεί να εξυπηρετεί πολλαπλούς σκοπούς όπως διακριτική ταυτοποίηση εγγράφου, αριθμό πληροφοριών ελέγχου, και/ή έλεγχο αποθεμάτων, DL/ID, V25ANS

### setEndorsementCodes() {#setendorsementcodes}

DCD, Κωδικοί ενδείξεων ειδικοί για τη δικαιοδοσία, DL, V5ANS

### setEyeColor() {#seteyecolor}

DAY, Χρώμα των ματιών του κατόχου της κάρτας. (Κωδικοί ANSI D-20). DL/ID, F3A

### setFamilyName() {#setfamilyname}

DCS, Επώνυμο του κατόχου της κάρτας, DL/ID, V40ANS

### setFamilyNameTruncation() {#setfamilynametruncation}

DDE, Κώδικας που υποδεικνύει εάν ένα πεδίο έχει περικοπεί (T), δεν έχει περικοπεί (N), ή είναι άγνωστο αν έχει περικοπεί (U), DL/ID, F1A

### setFirstName() {#setfirstname}

DAC, Όνομα του κατόχου της κάρτας, DL/ID, V40ANS

### setFirstNameTruncation() {#setfirstnametruncation}

DDF, Κώδικας που υποδεικνύει εάν ένα πεδίο έχει περικοπεί (T), δεν έχει περικοπεί (N), ή είναι άγνωστο αν έχει περικοπεί (U), DL/ID, F1A

### setHeight() {#setheight}

DAU, Ύψος του κατόχου της κάρτας. Ίντσες (in): αριθμός ιντσών ακολουθούμενος από \" in\" π.χ. 6'1'' = \"073 in\" Σεντίνια(cm) : αριθμός εκατοστών ακολουθούμενος από \" cm\" π.χ. 181 εκατοστά=\"181 cm\" , DL/ID, F6ANS

### setMiddleName() {#setmiddlename}

DAD, Μεσαίο(α) όνομα(α) του κατόχου της κάρτας. Σε περίπτωση πολλαπλών μεσαίων ονομάτων πρέπει να διαχωρίζονται με κόμμα \",\". , DL/ID, V40ANS

### setMiddleNameTruncation() {#setmiddlenametruncation}

DDG, Κώδικας που υποδεικνύει εάν ένα πεδίο έχει περικοπεί (T), δεν έχει περικοπεί (N), ή είναι άγνωστο αν έχει περικοπεί (U), DL/ID, F1A

### setRestrictionCodes() {#setrestrictioncodes}

DCB, Κωδικοί περιορισμών ειδικοί για τη δικαιοδοσία, DL, V12ANS

### setSex() {#setsex}

DBC, Φύλο του κατόχου της κάρτας. 1 = άνδρας, 2 = γυναίκα, 9 = μη καθορισμένο, DL/ID, F1N

### setVehicleClass() {#setvehicleclass}

DCA, Κωδικός κατηγορίας / ομάδας οχήματος ειδικός για τη δικαιοδοσία, DL, V6ANS
