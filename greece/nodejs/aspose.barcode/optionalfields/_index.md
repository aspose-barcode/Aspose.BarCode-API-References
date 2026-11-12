---
title: "OptionalFields"
linktitle: "OptionalFields"
second_title: "Αναφορά API του Aspose.BarCode για Node.js μέσω Java"
description: "Προαιρετικά στοιχεία (πεδία) της κάρτας."
type: docs
weight: 730
url: /el/nodejs/aspose.barcode/optionalfields/
---

## OptionalFields class

Προαιρετικά στοιχεία (πεδία) της κάρτας.

```js
new OptionalFields()
```

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [getAliasAKAFamilyName()](#getaliasakafamilyname) | DBN, Άλλο επώνυμο με το οποίο είναι γνωστός ο κάτοχος κάρτας, DL/ID, V10ANS |
| [getAliasAKAGivenName()](#getaliasakagivenname) | DBG, Άλλο όνομα με το οποίο είναι γνωστός ο κάτοχος κάρτας, DL/ID, V15ANS |
| [getAliasAKASuffixName()](#getaliasakasuffixname) | DBS, Άλλο επίθεμα με το οποίο είναι γνωστός ο κάτοχος κάρτας, DL/ID, V5ANS |
| [getAuditInformation()](#getauditinformation) | DCJ, Μια συμβολοσειρά γραμμάτων και/ή αριθμών που προσδιορίζει πότε, πού και από ποιον δημιουργήθηκε η άδεια οδήγησης/ταυτότητα. Εάν ένα |
| [getCardRevisionDate()](#getcardrevisiondate) | DDB, απαιτούμενο πεδίο του DHS που υποδεικνύει την ημερομηνία της πιο πρόσφατης αλλαγής έκδοσης ή τροποποίησης της ορατής μορφής του t |
| [getComplianceType()](#getcompliancetype) | DDA, απαιτούμενο πεδίο του DHS που υποδεικνύει τη συμμόρφωση: “F” = συμμορφωμένο· και, “N” = μη συμμορφωμένο, DL/ID, F1A |
| [getEndorsementCodeDescription()](#getendorsementcodedescription) | DCQ, Κείμενο που εξηγεί τους κωδικούς ειδικούς για τη δικαιοδοσία που υποδεικνύουν πρόσθετα δικαιώματα οδήγησης που χορηγούνται στο ca |
| [getHairColor()](#gethaircolor) | DAZ, Ξυρισμένος, μαύρος, ξανθός, καστανός, γκρι, κόκκινο/κόκκινο καστανό, αμμώδης, λευκός, άγνωστο. Εάν η εκδούσα δικαιοδοσία επιθυμεί να συντομεύσει |
| [getHAZMATEndorsementExpDate()](#gethazmatendorsementexpdate) | DDC, Ημερομηνία κατά την οποία η έγκριση επικίνδυνου υλικού που χορηγείται από το έγγραφο δεν ισχύει πλέον. (MMDDCCYY για τις ΗΠΑ, CC |
| [getInventoryControlNumber()](#getinventorycontrolnumber) | DCK, Μια ακολουθία γραμμάτων και/ή αριθμών που προσαρτάται στις πρώτες ύλες (χαρτόνι, λαμαρίνα κ.λπ.) που χρησιμοποιούνται στην παραγωγή |
| [getLimitedDurationDocIndicator()](#getlimiteddurationdocindicator) | DDD, απαιτούμενο πεδίο του DHS που υποδεικνύει ότι ο κάτοχος της κάρτας έχει προσωρινή νόμιμη κατάσταση = “1”, DL/ID, F1N |
| [getNameSuffix()](#getnamesuffix) | DCU, Κατάληξη ονόματος (Εάν η δικαιοδοσία συμμετέχει σε συστήματα που απαιτούν κατάληξη ονόματος (PDPS, CDLIS κ.λπ.), η κατάληξη πρέπει να |
| [getOrganDonorIndicator()](#getorgandonorindicator) | DDK, Πεδίο που υποδεικνύει ότι ο κάτοχος της κάρτας είναι δότη οργάνων = “1”, DL/ID, F1N |
| [getPlaceOfBirth()](#getplaceofbirth) | DCI, Χώρα και δήμος και/ή πολιτεία/επάρκεια, DL/ID, V33A |
| [getRaceEthnicity()](#getraceethnicity) | DCL, Κωδικοί για τη φυλή ή την εθνική προέλευση του κατόχου της κάρτας, όπως ορίζονται στο AAMVA D20, DL/ID, V3A |
| [getRestrictionCodeDescription()](#getrestrictioncodedescription) | DCR, Κείμενο που περιγράφει τους κωδικούς περιορισμών ειδικούς για τη δικαιοδοσία που περιορίζουν τα δικαιώματα οδήγησης, DL, V50ANS |
| [getStandardEndorsementCode()](#getstandardendorsementcode) | DCN, Πρότυποι κωδικοί έγκρισης για τον κάτοχο της κάρτας. Δείτε τους κωδικούς στο D20. Αυτό το στοιχείο δεδομένων είναι ένας κράτημα για μελλοντικές προσπάθειες |
| [getStandardRestrictionCode()](#getstandardrestrictioncode) | DCO, Πρότυποι κωδικοί περιορισμού για τον κάτοχο της κάρτας. Δείτε τους κωδικούς στο D20. Αυτό το στοιχείο δεδομένων είναι ένας κράτημα για μελλοντικές προσπάθειες |
| [getStandardVehClassification()](#getstandardvehclassification) | DCM, Πρότυποι κωδικοί ταξινόμησης οχημάτων για τον κάτοχο της κάρτας. Αυτό το στοιχείο δεδομένων είναι ένας κράτημα για μελλοντικές προσπάθειες να |
| [getUnder18Until()](#getunder18until) | DDH, Ημερομηνία κατά την οποία ο κάτοχος της κάρτας γίνεται 18 ετών. (MMDDCCYY για τις ΗΠΑ, CCYYMMDD για τον Καναδά), DL/ID, F8N |
| [getUnder21Until()](#getunder21until) | DDJ, Ημερομηνία κατά την οποία ο κάτοχος της κάρτας γίνεται 21 ετών. (MMDDCCYY για τις ΗΠΑ, CCYYMMDD για τον Καναδά), DL/ID, F8N |
| [getVehClassDescription()](#getvehclassdescription) | DCP, Κείμενο που εξηγεί τους κωδικούς ειδικούς για τη δικαιοδοσία σχετικά με τις ταξινομήσεις οχημάτων που ο κάτοχος της κάρτας έχει εξουσιοδότηση να |
| [getVeteranIndicator()](#getveteranindicator) | DDL, Πεδίο που υποδεικνύει ότι ο κάτοχος της κάρτας είναι βετεράνος = “1”, DL/ID, F1N |
| [getWeightKilograms()](#getweightkilograms) | DAX, Βάρος κατόχου κάρτας σε κιλά, π.χ. 84 kg = “084”, DL/ID, F3N |
| [getWeightPounds()](#getweightpounds) | DAW, Βάρος κατόχου κάρτας σε λίβρες, π.χ. 185 lb = “185”, DL/ID, F3N |
| [getWeightRange()](#getweightrange) | DCE, Δείχνει το προσεγγιστικό εύρος βάρους του κατόχου της κάρτας: 0 = έως 31 kg (έως 70 λίβρες), 1 = 32 – 45 kg (71 – 100 λίβρες |
| [setAddressStreet2()](#setaddressstreet2) | DAH, Δεύτερη γραμμή του τμήματος οδού της διεύθυνσης του κατόχου της κάρτας, DL/ID, V35ANS |
| [setAliasAKAFamilyName()](#setaliasakafamilyname) | DBN, Άλλο επώνυμο με το οποίο είναι γνωστός ο κάτοχος κάρτας, DL/ID, V10ANS |
| [setAliasAKAGivenName()](#setaliasakagivenname) | DBG, Άλλο όνομα με το οποίο είναι γνωστός ο κάτοχος κάρτας, DL/ID, V15ANS |
| [setAliasAKASuffixName()](#setaliasakasuffixname) | DBS, Άλλο επίθεμα με το οποίο είναι γνωστός ο κάτοχος κάρτας, DL/ID, V5ANS |
| [setAuditInformation()](#setauditinformation) | DCJ, Μια συμβολοσειρά γραμμάτων και/ή αριθμών που προσδιορίζει πότε, πού και από ποιον δημιουργήθηκε η άδεια οδήγησης/ταυτότητα. Εάν ένα |
| [setCardRevisionDate()](#setcardrevisiondate) | DDB, απαιτούμενο πεδίο του DHS που υποδεικνύει την ημερομηνία της πιο πρόσφατης αλλαγής έκδοσης ή τροποποίησης της ορατής μορφής του t |
| [setComplianceType()](#setcompliancetype) | DDA, απαιτούμενο πεδίο του DHS που υποδεικνύει τη συμμόρφωση: “F” = συμμορφωμένο· και, “N” = μη συμμορφωμένο, DL/ID, F1A |
| [setEndorsementCodeDescription()](#setendorsementcodedescription) | DCQ, Κείμενο που εξηγεί τους κωδικούς ειδικούς για τη δικαιοδοσία που υποδεικνύουν πρόσθετα δικαιώματα οδήγησης που χορηγούνται στο ca |
| [setHairColor()](#sethaircolor) | DAZ, Ξυρισμένος, μαύρος, ξανθός, καστανός, γκρι, κόκκινο/κόκκινο καστανό, αμμώδης, λευκός, άγνωστο. Εάν η εκδούσα δικαιοδοσία επιθυμεί να συντομεύσει |
| [setInventoryControlNumber()](#setinventorycontrolnumber) | DCK, Μια ακολουθία γραμμάτων και/ή αριθμών που προσαρτάται στις πρώτες ύλες (χαρτόνι, λαμαρίνα κ.λπ.) που χρησιμοποιούνται στην παραγωγή |
| [setLimitedDurationDocIndicator()](#setlimiteddurationdocindicator) | DDD, απαιτούμενο πεδίο του DHS που υποδεικνύει ότι ο κάτοχος της κάρτας έχει προσωρινή νόμιμη κατάσταση = “1”, DL/ID, F1N |
| [setNameSuffix()](#setnamesuffix) | DCU, Κατάληξη ονόματος (Εάν η δικαιοδοσία συμμετέχει σε συστήματα που απαιτούν κατάληξη ονόματος (PDPS, CDLIS κ.λπ.), η κατάληξη πρέπει να |
| [setOrganDonorIndicator()](#setorgandonorindicator) | DDK, Πεδίο που υποδεικνύει ότι ο κάτοχος της κάρτας είναι δότη οργάνων = “1”, DL/ID, F1N |
| [setPlaceOfBirth()](#setplaceofbirth) | DCI, Χώρα και δήμος και/ή πολιτεία/επάρκεια, DL/ID, V33A |
| [setRaceEthnicity()](#setraceethnicity) | DCL, Κωδικοί για τη φυλή ή την εθνική προέλευση του κατόχου της κάρτας, όπως ορίζονται στο AAMVA D20, DL/ID, V3A |
| [setRestrictionCodeDescription()](#setrestrictioncodedescription) | DCR, Κείμενο που περιγράφει τους κωδικούς περιορισμών ειδικούς για τη δικαιοδοσία που περιορίζουν τα δικαιώματα οδήγησης, DL, V50ANS |
| [setStandardEndorsementCode()](#setstandardendorsementcode) | DCN, Πρότυποι κωδικοί έγκρισης για τον κάτοχο της κάρτας. Δείτε τους κωδικούς στο D20. Αυτό το στοιχείο δεδομένων είναι ένας κράτημα για μελλοντικές προσπάθειες |
| [setStandardRestrictionCode()](#setstandardrestrictioncode) | DCO, Πρότυποι κωδικοί περιορισμού για τον κάτοχο της κάρτας. Δείτε τους κωδικούς στο D20. Αυτό το στοιχείο δεδομένων είναι ένας κράτημα για μελλοντικές προσπάθειες |
| [setStandardVehClassification()](#setstandardvehclassification) | DCM, Πρότυποι κωδικοί ταξινόμησης οχημάτων για τον κάτοχο της κάρτας. Αυτό το στοιχείο δεδομένων είναι ένας κράτημα για μελλοντικές προσπάθειες να |
| [setUnder18Until()](#setunder18until) | DDI, Ημερομηνία κατά την οποία ο κάτοχος της κάρτας γίνεται 19 ετών. (MMDDCCYY για τις ΗΠΑ, CCYYMMDD για τον Καναδά), DL/ID, F8N |
| [setUnder19Until()](#setunder19until) | DDI, Ημερομηνία κατά την οποία ο κάτοχος της κάρτας γίνεται 19 ετών. (MMDDCCYY για τις ΗΠΑ, CCYYMMDD για τον Καναδά), DL/ID, F8N |
| [setUnder21Until()](#setunder21until) | DDJ, Ημερομηνία κατά την οποία ο κάτοχος της κάρτας γίνεται 21 ετών. (MMDDCCYY για τις ΗΠΑ, CCYYMMDD για τον Καναδά), DL/ID, F8N |
| [setVehClassDescription()](#setvehclassdescription) | DCP, Κείμενο που εξηγεί τους κωδικούς ειδικούς για τη δικαιοδοσία σχετικά με τις ταξινομήσεις οχημάτων που ο κάτοχος της κάρτας έχει εξουσιοδότηση να |
| [setVeteranIndicator()](#setveteranindicator) | DDL, Πεδίο που υποδεικνύει ότι ο κάτοχος της κάρτας είναι βετεράνος = “1”, DL/ID, F1N |
| [setWeightKilograms()](#setweightkilograms) | DAX, Βάρος κατόχου κάρτας σε κιλά, π.χ. 84 kg = “084”, DL/ID, F3N |
| [setWeightPounds()](#setweightpounds) | DAW, Βάρος κατόχου κάρτας σε λίβρες, π.χ. 185 lb = “185”, DL/ID, F3N |
| [setWeightRange()](#setweightrange) | DCE, Δείχνει το προσεγγιστικό εύρος βάρους του κατόχου της κάρτας: 0 = έως 31 kg (έως 70 λίβρες), 1 = 32 – 45 kg (71 – 100 λίβρες |

### getAliasAKAFamilyName() {#getaliasakafamilyname}

DBN, Άλλο επώνυμο με το οποίο είναι γνωστός ο κάτοχος κάρτας, DL/ID, V10ANS

### getAliasAKAGivenName() {#getaliasakagivenname}

DBG, Άλλο όνομα με το οποίο είναι γνωστός ο κάτοχος κάρτας, DL/ID, V15ANS

### getAliasAKASuffixName() {#getaliasakasuffixname}

DBS, Άλλο επίθεμα με το οποίο είναι γνωστός ο κάτοχος κάρτας, DL/ID, V5ANS

### getAuditInformation() {#getauditinformation}

DCJ, Μια ακολουθία γραμμάτων και/ή αριθμών που προσδιορίζει πότε, πού και από ποιον δημιουργήθηκε η άδεια οδήγησης/ταυτότητα. Εάν οι πληροφορίες ελέγχου δεν χρησιμοποιούνται στην κάρτα ή το MRT, πρέπει να συμπεριληφθούν στο αρχείο του οδηγού, DL/ID, V25ANS

### getCardRevisionDate() {#getcardrevisiondate}

DDB, απαιτούμενο πεδίο του DHS που υποδεικνύει την ημερομηνία της πιο πρόσφατης αλλαγής έκδοσης ή τροποποίησης της ορατής μορφής του DL/ID. (MMDDCCYY για τις Η.Π.Α., CCYYMMDD για τον Καναδά), DL/ID, F8N

### getComplianceType() {#getcompliancetype}

DDA, απαιτούμενο πεδίο του DHS που υποδεικνύει τη συμμόρφωση: “F” = συμμορφωμένο· και, “N” = μη συμμορφωμένο, DL/ID, F1A

### getEndorsementCodeDescription() {#getendorsementcodedescription}

DCQ, Κείμενο που εξηγεί τους κωδικούς ειδικούς για τη δικαιοδοσία που υποδεικνύουν πρόσθετα προνόμια οδήγησης που χορηγούνται στον κάτοχο της κάρτας πέρα από την κατηγορία οχήματος, DL, V50ANS

### getHairColor() {#gethaircolor}

DAZ, Ξυριστό, μαύρο, ξανθό, καστανό, γκρι, κόκκινο/κοραλί, αμμουδερό, λευκό, άγνωστο. Εάν η εκδούσα δικαιοδοσία επιθυμεί να συντομεύσει τα χρώματα, πρέπει να χρησιμοποιηθούν οι τριψήφιοι κωδικοί που παρέχονται στο AAMVA D20, DL/ID, V12A

### getHAZMATEndorsementExpDate() {#gethazmatendorsementexpdate}

DDC, Ημερομηνία κατά την οποία η έγκριση επικίνδυνου υλικού που χορηγείται από το έγγραφο δεν είναι πλέον έγκυρη. (MMDDCCYY για τις Η.Π.Α., CCYYMMDD για τον Καναδά), DL, F8N

### getInventoryControlNumber() {#getinventorycontrolnumber}

DCK, Μια σειρά γραμμάτων και/ή αριθμών που προστίθεται στις πρώτες ύλες (χαρτόνι, λαμεντάδα κ.λπ.) που χρησιμοποιούνται στην παραγωγή αδειών οδήγησης και καρτών ταυτοποίησης. (συνιστώμενο πεδίο του DHS), DL/ID, V25ANS

### getLimitedDurationDocIndicator() {#getlimiteddurationdocindicator}

DDD, απαιτούμενο πεδίο του DHS που υποδεικνύει ότι ο κάτοχος της κάρτας έχει προσωρινή νόμιμη κατάσταση = “1”, DL/ID, F1N

### getNameSuffix() {#getnamesuffix}

DCU, Κατάληξη ονόματος (Εάν η δικαιοδοσία συμμετέχει σε συστήματα που απαιτούν κατάληξη ονόματος (PDPS, CDLIS κ.λπ.), η κατάληξη πρέπει να συλλέγεται και να εμφανίζεται στο DL/ID και στο MRT). JR (Junior), SR (Senior), 1ST ή I (First), έως 9TH ή IX (Ninth), DL/ID, V5ANS

### getOrganDonorIndicator() {#getorgandonorindicator}

DDK, Πεδίο που υποδεικνύει ότι ο κάτοχος της κάρτας είναι δότη οργάνων = “1”, DL/ID, F1N

### getPlaceOfBirth() {#getplaceofbirth}

DCI, Χώρα και δήμος και/ή πολιτεία/επάρκεια, DL/ID, V33A

### getRaceEthnicity() {#getraceethnicity}

DCL, Κωδικοί για τη φυλή ή την εθνική προέλευση του κατόχου της κάρτας, όπως ορίζονται στο AAMVA D20, DL/ID, V3A

### getRestrictionCodeDescription() {#getrestrictioncodedescription}

DCR, Κείμενο που περιγράφει τους κωδικούς περιορισμών ειδικούς για τη δικαιοδοσία που περιορίζουν τα δικαιώματα οδήγησης, DL, V50ANS

### getStandardEndorsementCode() {#getstandardendorsementcode}

DCN, Τυπικοί κωδικοί έγκρισης για τον κάτοχο της κάρτας. Δείτε τους κωδικούς στο D20. Αυτό το στοιχείο δεδομένων είναι ένας κράτημα για μελλοντικές προσπάθειες τυποποίησης των κωδικών έγκρισης, DL, F5AN

### getStandardRestrictionCode() {#getstandardrestrictioncode}

DCO, Τυπικοί κωδικοί περιορισμού για τον κάτοχο της κάρτας. Δείτε τους κωδικούς στο D20. Αυτό το στοιχείο δεδομένων είναι ένας κράτημα για μελλοντικές προσπάθειες τυποποίησης των κωδικών περιορισμού, DL, F12AN

### getStandardVehClassification() {#getstandardvehclassification}

DCM, Τυπικοί κωδικοί ταξινόμησης οχημάτων για τον κάτοχο της κάρτας. Αυτό το στοιχείο δεδομένων είναι ένας κράτημα για μελλοντικές προσπάθειες τυποποίησης των ταξινομήσεων οχημάτων, DL, F4AN

### getUnder18Until() {#getunder18until}

DDH, Ημερομηνία κατά την οποία ο κάτοχος της κάρτας γίνεται 18 ετών. (MMDDCCYY για τις ΗΠΑ, CCYYMMDD για τον Καναδά), DL/ID, F8N

### getUnder21Until() {#getunder21until}

DDJ, Ημερομηνία κατά την οποία ο κάτοχος της κάρτας γίνεται 21 ετών. (MMDDCCYY για τις ΗΠΑ, CCYYMMDD για τον Καναδά), DL/ID, F8N

### getVehClassDescription() {#getvehclassdescription}

DCP, Κείμενο που εξηγεί τους κωδικούς ειδικούς για τη δικαιοδοσία σχετικά με τις ταξινομήσεις οχημάτων που είναι εξουσιοδοτημένος να οδηγεί ο κάτοχος της κάρτας, DL, V50ANS

### getVeteranIndicator() {#getveteranindicator}

DDL, Πεδίο που υποδεικνύει ότι ο κάτοχος της κάρτας είναι βετεράνος = “1”, DL/ID, F1N

### getWeightKilograms() {#getweightkilograms}

DAX, Βάρος κατόχου κάρτας σε κιλά, π.χ. 84 kg = “084”, DL/ID, F3N

### getWeightPounds() {#getweightpounds}

DAW, Βάρος κατόχου κάρτας σε λίβρες, π.χ. 185 lb = “185”, DL/ID, F3N

### getWeightRange() {#getweightrange}

DCE, Δείχνει το περίπου εύρος βάρους του κατόχου: 0 = έως 31 κγ (έως 70 λίβρες), 1 = 32 – 45 κγ (71 – 100 λίβρες), 2 = 46 - 59 κγ (101 – 130 λίβρες), 3 = 60 - 70 κγ (131 – 160 λίβρες), 4 = 71 - 86 κγ (161 – 190 λίβρες), 5 = 87 - 100 κγ (191 – 220 λίβρες), 6 = 101 - 113 κγ (221 – 250 λίβρες), 7 = 114 - 127 κγ (251 – 280 λίβρες), 8 = 128 – 145 κγ (281 – 320 λίβρες), 9 = 146+ κγ (321+ λίβρες), DL/ID, F1N

### setAddressStreet2() {#setaddressstreet2}

DAH, Δεύτερη γραμμή του τμήματος οδού της διεύθυνσης του κατόχου της κάρτας, DL/ID, V35ANS

### setAliasAKAFamilyName() {#setaliasakafamilyname}

DBN, Άλλο επώνυμο με το οποίο είναι γνωστός ο κάτοχος κάρτας, DL/ID, V10ANS

### setAliasAKAGivenName() {#setaliasakagivenname}

DBG, Άλλο όνομα με το οποίο είναι γνωστός ο κάτοχος κάρτας, DL/ID, V15ANS

### setAliasAKASuffixName() {#setaliasakasuffixname}

DBS, Άλλο επίθεμα με το οποίο είναι γνωστός ο κάτοχος κάρτας, DL/ID, V5ANS

### setAuditInformation() {#setauditinformation}

DCJ, Μια ακολουθία γραμμάτων και/ή αριθμών που προσδιορίζει πότε, πού και από ποιον δημιουργήθηκε η άδεια οδήγησης/ταυτότητα. Εάν οι πληροφορίες ελέγχου δεν χρησιμοποιούνται στην κάρτα ή το MRT, πρέπει να συμπεριληφθούν στο αρχείο του οδηγού, DL/ID, V25ANS

### setCardRevisionDate() {#setcardrevisiondate}

DDB, απαιτούμενο πεδίο του DHS που υποδεικνύει την ημερομηνία της πιο πρόσφατης αλλαγής έκδοσης ή τροποποίησης της ορατής μορφής του DL/ID. (MMDDCCYY για τις Η.Π.Α., CCYYMMDD για τον Καναδά), DL/ID, F8N

### setComplianceType() {#setcompliancetype}

DDA, απαιτούμενο πεδίο του DHS που υποδεικνύει τη συμμόρφωση: “F” = συμμορφωμένο· και, “N” = μη συμμορφωμένο, DL/ID, F1A

### setEndorsementCodeDescription() {#setendorsementcodedescription}

DCQ, Κείμενο που εξηγεί τους κωδικούς ειδικούς για τη δικαιοδοσία που υποδεικνύουν πρόσθετα προνόμια οδήγησης που χορηγούνται στον κάτοχο της κάρτας πέρα από την κατηγορία οχήματος, DL, V50ANS

### setHairColor() {#sethaircolor}

DAZ, Ξυριστό, μαύρο, ξανθό, καστανό, γκρι, κόκκινο/κοραλί, αμμουδερό, λευκό, άγνωστο. Εάν η εκδούσα δικαιοδοσία επιθυμεί να συντομεύσει τα χρώματα, πρέπει να χρησιμοποιηθούν οι τριψήφιοι κωδικοί που παρέχονται στο AAMVA D20, DL/ID, V12A

### setInventoryControlNumber() {#setinventorycontrolnumber}

DCK, Μια σειρά γραμμάτων και/ή αριθμών που προστίθεται στις πρώτες ύλες (χαρτόνι, λαμεντάδα κ.λπ.) που χρησιμοποιούνται στην παραγωγή αδειών οδήγησης και καρτών ταυτοποίησης. (συνιστώμενο πεδίο του DHS), DL/ID, V25ANS

### setLimitedDurationDocIndicator() {#setlimiteddurationdocindicator}

DDD, απαιτούμενο πεδίο του DHS που υποδεικνύει ότι ο κάτοχος της κάρτας έχει προσωρινή νόμιμη κατάσταση = “1”, DL/ID, F1N

### setNameSuffix() {#setnamesuffix}

DCU, Κατάληξη ονόματος (Εάν η δικαιοδοσία συμμετέχει σε συστήματα που απαιτούν κατάληξη ονόματος (PDPS, CDLIS κ.λπ.), η κατάληξη πρέπει να συλλέγεται και να εμφανίζεται στο DL/ID και στο MRT). JR (Junior), SR (Senior), 1ST ή I (First), έως 9TH ή IX (Ninth), DL/ID, V5ANS

### setOrganDonorIndicator() {#setorgandonorindicator}

DDK, Πεδίο που υποδεικνύει ότι ο κάτοχος της κάρτας είναι δότη οργάνων = “1”, DL/ID, F1N

### setPlaceOfBirth() {#setplaceofbirth}

DCI, Χώρα και δήμος και/ή πολιτεία/επάρκεια, DL/ID, V33A

### setRaceEthnicity() {#setraceethnicity}

DCL, Κωδικοί για τη φυλή ή την εθνική προέλευση του κατόχου της κάρτας, όπως ορίζονται στο AAMVA D20, DL/ID, V3A

### setRestrictionCodeDescription() {#setrestrictioncodedescription}

DCR, Κείμενο που περιγράφει τους κωδικούς περιορισμών ειδικούς για τη δικαιοδοσία που περιορίζουν τα δικαιώματα οδήγησης, DL, V50ANS

### setStandardEndorsementCode() {#setstandardendorsementcode}

DCN, Τυπικοί κωδικοί έγκρισης για τον κάτοχο της κάρτας. Δείτε τους κωδικούς στο D20. Αυτό το στοιχείο δεδομένων είναι ένας κράτημα για μελλοντικές προσπάθειες τυποποίησης των κωδικών έγκρισης, DL, F5AN

### setStandardRestrictionCode() {#setstandardrestrictioncode}

DCO, Τυπικοί κωδικοί περιορισμού για τον κάτοχο της κάρτας. Δείτε τους κωδικούς στο D20. Αυτό το στοιχείο δεδομένων είναι ένας κράτημα για μελλοντικές προσπάθειες τυποποίησης των κωδικών περιορισμού, DL, F12AN

### setStandardVehClassification() {#setstandardvehclassification}

DCM, Τυπικοί κωδικοί ταξινόμησης οχημάτων για τον κάτοχο της κάρτας. Αυτό το στοιχείο δεδομένων είναι ένας κράτημα για μελλοντικές προσπάθειες τυποποίησης των ταξινομήσεων οχημάτων, DL, F4AN

### setUnder18Until() {#setunder18until}

DDI, Ημερομηνία κατά την οποία ο κάτοχος της κάρτας γίνεται 19 ετών. (MMDDCCYY για τις ΗΠΑ, CCYYMMDD για τον Καναδά), DL/ID, F8N

### setUnder19Until() {#setunder19until}

DDI, Ημερομηνία κατά την οποία ο κάτοχος της κάρτας γίνεται 19 ετών. (MMDDCCYY για τις ΗΠΑ, CCYYMMDD για τον Καναδά), DL/ID, F8N

### setUnder21Until() {#setunder21until}

DDJ, Ημερομηνία κατά την οποία ο κάτοχος της κάρτας γίνεται 21 ετών. (MMDDCCYY για τις ΗΠΑ, CCYYMMDD για τον Καναδά), DL/ID, F8N

### setVehClassDescription() {#setvehclassdescription}

DCP, Κείμενο που εξηγεί τους κωδικούς ειδικούς για τη δικαιοδοσία σχετικά με τις ταξινομήσεις οχημάτων που είναι εξουσιοδοτημένος να οδηγεί ο κάτοχος της κάρτας, DL, V50ANS

### setVeteranIndicator() {#setveteranindicator}

DDL, Πεδίο που υποδεικνύει ότι ο κάτοχος της κάρτας είναι βετεράνος = “1”, DL/ID, F1N

### setWeightKilograms() {#setweightkilograms}

DAX, Βάρος κατόχου κάρτας σε κιλά, π.χ. 84 kg = “084”, DL/ID, F3N

### setWeightPounds() {#setweightpounds}

DAW, Βάρος κατόχου κάρτας σε λίβρες, π.χ. 185 lb = “185”, DL/ID, F3N

### setWeightRange() {#setweightrange}

DCE, Δείχνει το περίπου εύρος βάρους του κατόχου: 0 = έως 31 κγ (έως 70 λίβρες), 1 = 32 – 45 κγ (71 – 100 λίβρες), 2 = 46 - 59 κγ (101 – 130 λίβρες), 3 = 60 - 70 κγ (131 – 160 λίβρες), 4 = 71 - 86 κγ (161 – 190 λίβρες), 5 = 87 - 100 κγ (191 – 220 λίβρες), 6 = 101 - 113 κγ (221 – 250 λίβρες), 7 = 114 - 127 κγ (251 – 280 λίβρες), 8 = 128 – 145 κγ (281 – 320 λίβρες), 9 = 146+ κγ (321+ λίβρες), DL/ID, F1N
