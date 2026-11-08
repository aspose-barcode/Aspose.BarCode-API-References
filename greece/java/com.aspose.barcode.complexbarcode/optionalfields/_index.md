---
title: "USADriveIdCodetext.OptionalFields"
second_title: "Aspose.BarCode για Java Αναφορά API"
description: "Προαιρετικά πεδία στοιχείων της κάρτας"
type: docs
weight: 11
url: /el/java/com.aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/
---
**Inheritance:**
java.lang.Object
```
public static class USADriveIdCodetext.OptionalFields
```

Προαιρετικά στοιχεία (πεδία) της κάρτας
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [OptionalFields()](#OptionalFields--) |  |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAddressStreet2()](#getAddressStreet2--) | DAH, Δεύτερη γραμμή του τμήματος οδού της διεύθυνσης του κατόχου της κάρτας, DL/ID, V35ANS |
| [getAliasAKAFamilyName()](#getAliasAKAFamilyName--) | DBN, Άλλο επώνυμο με το οποίο είναι γνωστός ο κάτοχος της κάρτας, DL/ID, V10ANS |
| [getAliasAKAGivenName()](#getAliasAKAGivenName--) | DBG, Άλλο όνομα με το οποίο είναι γνωστός ο κάτοχος της κάρτας, DL/ID, V15ANS |
| [getAliasAKASuffixName()](#getAliasAKASuffixName--) | DBS, Άλλο επίθεμα με το οποίο είναι γνωστός ο κάτοχος της κάρτας, DL/ID, V5ANS |
| [getAuditInformation()](#getAuditInformation--) | DCJ, Μια σειρά από γράμματα και/ή αριθμούς που προσδιορίζει πότε, πού και από ποιον δημιουργήθηκε η άδεια οδήγησης/ταυτότητα. |
| [getCardRevisionDate()](#getCardRevisionDate--) | DDB, Υποχρεωτικό πεδίο του DHS που υποδεικνύει την ημερομηνία της πιο πρόσφατης αλλαγής έκδοσης ή τροποποίησης της ορατής μορφής της άδειας/ταυτότητας. |
| [getClass()](#getClass--) |  |
| [getComplianceType()](#getComplianceType--) | DDA, Υποχρεωτικό πεδίο του DHS που υποδεικνύει τη συμμόρφωση: \\u201cF\\u201d = συμμορφωμένο· και, \\u201cN\\u201d = μη συμμορφωμένο, DL/ID, F1A |
| [getEndorsementCodeDescription()](#getEndorsementCodeDescription--) | DCQ, Κείμενο που εξηγεί τους κωδικούς ειδικούς για τη δικαιοδοσία που υποδεικνύουν πρόσθετα προνόμια οδήγησης που χορηγούνται στον κάτοχο πέρα από την κατηγορία οχήματος, DL, V50ANS |
| [getHAZMATEndorsementExpDate()](#getHAZMATEndorsementExpDate--) | DDC, Ημερομηνία κατά την οποία η έγκριση επικίνδυνων υλικών που χορηγείται από το έγγραφο δεν ισχύει πλέον. |
| [getHairColor()](#getHairColor--) | DAZ, Ξυρισμένος, μαύρο, ξανθό, καστανό, γκρι, κόκκινο/κόκκινο-καστανό, αμμώδης, λευκό, άγνωστο. |
| [getInventoryControlNumber()](#getInventoryControlNumber--) | DCK, Μια σειρά από γράμματα και/ή αριθμούς που προσκολλάται στα ακατέργαστα υλικά (χαρτόνι, λαμεντάδα κ.λπ.) που χρησιμοποιούνται στην παραγωγή αδειών οδήγησης και ταυτοτήτων. |
| [getLimitedDurationDocIndicator()](#getLimitedDurationDocIndicator--) | DDD, Υποχρεωτικό πεδίο του DHS που υποδεικνύει ότι ο κάτοχος έχει προσωρινή νόμιμη κατάσταση = \\u201c1\\u201d, DL/ID, F1N |
| [getNameSuffix()](#getNameSuffix--) | DCU, Κατάληξη ονόματος (Εάν η δικαιοδοσία συμμετέχει σε συστήματα που απαιτούν κατάληξη ονόματος (PDPS, CDLIS κ.λπ.), η κατάληξη πρέπει να συλλέγεται και να εμφανίζεται στην άδεια/ταυτότητα και στο MRT). |
| [getOrganDonorIndicator()](#getOrganDonorIndicator--) | DDK, Πεδίο που υποδεικνύει ότι ο κάτοχος είναι δωρητής οργάνων = \\u201c1\\u201d, DL/ID, F1N |
| [getPlaceOfBirth()](#getPlaceOfBirth--) | DCI, Χώρα και δήμος και/ή πολιτεία/επικράτεια, DL/ID, V33A |
| [getRaceEthnicity()](#getRaceEthnicity--) | DCL, Κωδικοί για τη φυλή ή την εθνική προέλευση του κατόχου, όπως ορίζονται στο AAMVA D20, DL/ID, V3A |
| [getRestrictionCodeDescription()](#getRestrictionCodeDescription--) | DCR, Κείμενο που περιγράφει τους κωδικούς περιορισμών ειδικούς για τη δικαιοδοσία που περιορίζουν τα προνόμια οδήγησης, DL, V50ANS |
| [getStandardEndorsementCode()](#getStandardEndorsementCode--) | DCN, Πρότυποι κωδικοί έγκρισης για τον κάτοχο. |
| [getStandardRestrictionCode()](#getStandardRestrictionCode--) | DCO, Πρότυποι κωδικοί περιορισμού για τον κάτοχο. |
| [getStandardVehClassification()](#getStandardVehClassification--) | DCM, Πρότυποι κωδικοί ταξινόμησης οχημάτων για τον κάτοχο. |
| [getUnder18Until()](#getUnder18Until--) | DDH, Ημερομηνία κατά την οποία ο κάτοχος γίνεται 18 ετών. |
| [getUnder19Until()](#getUnder19Until--) | DDI, Ημερομηνία κατά την οποία ο κάτοχος γίνεται 19 ετών. |
| [getUnder21Until()](#getUnder21Until--) | DDJ, Ημερομηνία κατά την οποία ο κάτοχος γίνεται 21 ετών. |
| [getVehClassDescription()](#getVehClassDescription--) | DCP, Κείμενο που εξηγεί τους κωδικούς ειδικούς για τη δικαιοδοσία σχετικά με τις ταξινομήσεις οχημάτων που ο κάτοχος έχει εξουσιοδότηση να οδηγεί, DL, V50ANS |
| [getVeteranIndicator()](#getVeteranIndicator--) | DDL, Πεδίο που υποδεικνύει ότι ο κάτοχος είναι βετεράνος = \\u201c1\\u201d, DL/ID, F1N |
| [getWeightKilograms()](#getWeightKilograms--) | DAX, Βάρος κατόχου σε κιλά, Παράδειγμα. |
| [getWeightPounds()](#getWeightPounds--) | DAW, Βάρος κατόχου σε λίβρες, Παράδειγμα. |
| [getWeightRange()](#getWeightRange--) | DCE, Δείχνει το προσεγγιστικό εύρος βάρους του κατόχου: 0 = έως 31 kg (έως 70 λίβρες), 1 = 32 \\u2013 45 kg (71 \\u2013 100 λίβρες), 2 = 46 - 59 kg (101 \\u2013 130 λίβρες), 3 = 60 - 70 kg (131 \\u2013 160 λίβρες), 4 = 71 - 86 kg (161 \\u2013 190 λίβρες), 5 = 87 - 100 kg (191 \\u2013 220 λίβρες), 6 = 101 - 113 kg (221 \\u2013 250 λίβρες), 7 = 114 - 127 kg (251 \\u2013 280 λίβρες), 8 = 128 \\u2013 145 kg (281 \\u2013 320 λίβρες), 9 = 146+ kg (321+ λίβρες), DL/ID, F1N |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAddressStreet2(String value)](#setAddressStreet2-java.lang.String-) | DAH, Δεύτερη γραμμή του τμήματος οδού της διεύθυνσης του κατόχου της κάρτας, DL/ID, V35ANS |
| [setAliasAKAFamilyName(String value)](#setAliasAKAFamilyName-java.lang.String-) | DBN, Άλλο επώνυμο με το οποίο είναι γνωστός ο κάτοχος της κάρτας, DL/ID, V10ANS |
| [setAliasAKAGivenName(String value)](#setAliasAKAGivenName-java.lang.String-) | DBG, Άλλο όνομα με το οποίο είναι γνωστός ο κάτοχος της κάρτας, DL/ID, V15ANS |
| [setAliasAKASuffixName(String value)](#setAliasAKASuffixName-java.lang.String-) | DBS, Άλλο επίθεμα με το οποίο είναι γνωστός ο κάτοχος της κάρτας, DL/ID, V5ANS |
| [setAuditInformation(String value)](#setAuditInformation-java.lang.String-) | DCJ, Μια σειρά από γράμματα και/ή αριθμούς που προσδιορίζει πότε, πού και από ποιον δημιουργήθηκε η άδεια οδήγησης/ταυτότητα. |
| [setCardRevisionDate(LocalDate value)](#setCardRevisionDate-java.time.LocalDate-) | DDB, Υποχρεωτικό πεδίο του DHS που υποδεικνύει την ημερομηνία της πιο πρόσφατης αλλαγής έκδοσης ή τροποποίησης της ορατής μορφής της άδειας/ταυτότητας. |
| [setComplianceType(String value)](#setComplianceType-java.lang.String-) | DDA, Υποχρεωτικό πεδίο του DHS που υποδεικνύει τη συμμόρφωση: \\u201cF\\u201d = συμμορφωμένο· και, \\u201cN\\u201d = μη συμμορφωμένο, DL/ID, F1A |
| [setEndorsementCodeDescription(String value)](#setEndorsementCodeDescription-java.lang.String-) | DCQ, Κείμενο που εξηγεί τους κωδικούς ειδικούς για τη δικαιοδοσία που υποδεικνύουν πρόσθετα προνόμια οδήγησης που χορηγούνται στον κάτοχο πέρα από την κατηγορία οχήματος, DL, V50ANS |
| [setHAZMATEndorsementExpDate(LocalDate value)](#setHAZMATEndorsementExpDate-java.time.LocalDate-) | DDC, Ημερομηνία κατά την οποία η έγκριση επικίνδυνων υλικών που χορηγείται από το έγγραφο δεν ισχύει πλέον. |
| [setHairColor(USADriveIdHairColor value)](#setHairColor-com.aspose.barcode.complexbarcode.USADriveIdHairColor-) | DAZ, Ξυρισμένος, μαύρο, ξανθό, καστανό, γκρι, κόκκινο/κόκκινο-καστανό, αμμώδης, λευκό, άγνωστο. |
| [setInventoryControlNumber(String value)](#setInventoryControlNumber-java.lang.String-) | DCK, Μια σειρά από γράμματα και/ή αριθμούς που προσκολλάται στα ακατέργαστα υλικά (χαρτόνι, λαμεντάδα κ.λπ.) που χρησιμοποιούνται στην παραγωγή αδειών οδήγησης και ταυτοτήτων. |
| [setLimitedDurationDocIndicator(String value)](#setLimitedDurationDocIndicator-java.lang.String-) | DDD, Υποχρεωτικό πεδίο του DHS που υποδεικνύει ότι ο κάτοχος έχει προσωρινή νόμιμη κατάσταση = \\u201c1\\u201d, DL/ID, F1N |
| [setNameSuffix(String value)](#setNameSuffix-java.lang.String-) | DCU, Κατάληξη ονόματος (Εάν η δικαιοδοσία συμμετέχει σε συστήματα που απαιτούν κατάληξη ονόματος (PDPS, CDLIS κ.λπ.), η κατάληξη πρέπει να συλλέγεται και να εμφανίζεται στην άδεια/ταυτότητα και στο MRT). |
| [setOrganDonorIndicator(String value)](#setOrganDonorIndicator-java.lang.String-) | DDK, Πεδίο που υποδεικνύει ότι ο κάτοχος είναι δωρητής οργάνων = \\u201c1\\u201d, DL/ID, F1N |
| [setPlaceOfBirth(String value)](#setPlaceOfBirth-java.lang.String-) | DCI, Χώρα και δήμος και/ή πολιτεία/επικράτεια, DL/ID, V33A |
| [setRaceEthnicity(String value)](#setRaceEthnicity-java.lang.String-) | DCL, Κωδικοί για τη φυλή ή την εθνική προέλευση του κατόχου, όπως ορίζονται στο AAMVA D20, DL/ID, V3A |
| [setRestrictionCodeDescription(String value)](#setRestrictionCodeDescription-java.lang.String-) | DCR, Κείμενο που περιγράφει τους κωδικούς περιορισμών ειδικούς για τη δικαιοδοσία που περιορίζουν τα προνόμια οδήγησης, DL, V50ANS |
| [setStandardEndorsementCode(String value)](#setStandardEndorsementCode-java.lang.String-) | DCN, Πρότυποι κωδικοί έγκρισης για τον κάτοχο. |
| [setStandardRestrictionCode(String value)](#setStandardRestrictionCode-java.lang.String-) | DCO, Πρότυποι κωδικοί περιορισμού για τον κάτοχο. |
| [setStandardVehClassification(String value)](#setStandardVehClassification-java.lang.String-) | DCM, Πρότυποι κωδικοί ταξινόμησης οχημάτων για τον κάτοχο. |
| [setUnder18Until(LocalDate value)](#setUnder18Until-java.time.LocalDate-) | DDH, Ημερομηνία κατά την οποία ο κάτοχος γίνεται 18 ετών. |
| [setUnder19Until(LocalDate value)](#setUnder19Until-java.time.LocalDate-) | DDI, Ημερομηνία κατά την οποία ο κάτοχος γίνεται 19 ετών. |
| [setUnder21Until(LocalDate value)](#setUnder21Until-java.time.LocalDate-) | DDJ, Ημερομηνία κατά την οποία ο κάτοχος γίνεται 21 ετών. |
| [setVehClassDescription(String value)](#setVehClassDescription-java.lang.String-) | DCP, Κείμενο που εξηγεί τους κωδικούς ειδικούς για τη δικαιοδοσία σχετικά με τις ταξινομήσεις οχημάτων που ο κάτοχος έχει εξουσιοδότηση να οδηγεί, DL, V50ANS |
| [setVeteranIndicator(String value)](#setVeteranIndicator-java.lang.String-) | DDL, Πεδίο που υποδεικνύει ότι ο κάτοχος είναι βετεράνος = \\u201c1\\u201d, DL/ID, F1N |
| [setWeightKilograms(int value)](#setWeightKilograms-int-) | DAX, Βάρος κατόχου σε κιλά, Παράδειγμα. |
| [setWeightPounds(int value)](#setWeightPounds-int-) | DAW, Βάρος κατόχου σε λίβρες, Παράδειγμα. |
| [setWeightRange(String value)](#setWeightRange-java.lang.String-) | DCE, Δείχνει το προσεγγιστικό εύρος βάρους του κατόχου: 0 = έως 31 kg (έως 70 λίβρες), 1 = 32 \\u2013 45 kg (71 \\u2013 100 λίβρες), 2 = 46 - 59 kg (101 \\u2013 130 λίβρες), 3 = 60 - 70 kg (131 \\u2013 160 λίβρες), 4 = 71 - 86 kg (161 \\u2013 190 λίβρες), 5 = 87 - 100 kg (191 \\u2013 220 λίβρες), 6 = 101 - 113 kg (221 \\u2013 250 λίβρες), 7 = 114 - 127 kg (251 \\u2013 280 λίβρες), 8 = 128 \\u2013 145 kg (281 \\u2013 320 λίβρες), 9 = 146+ kg (321+ λίβρες), DL/ID, F1N |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### OptionalFields() {#OptionalFields--}
```
public OptionalFields()
```


### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getAddressStreet2() {#getAddressStreet2--}
```
public final String getAddressStreet2()
```


DAH, Δεύτερη γραμμή του τμήματος οδού της διεύθυνσης του κατόχου της κάρτας, DL/ID, V35ANS

**Returns:**
java.lang.String
### getAliasAKAFamilyName() {#getAliasAKAFamilyName--}
```
public final String getAliasAKAFamilyName()
```


DBN, Άλλο επώνυμο με το οποίο είναι γνωστός ο κάτοχος της κάρτας, DL/ID, V10ANS

**Returns:**
java.lang.String
### getAliasAKAGivenName() {#getAliasAKAGivenName--}
```
public final String getAliasAKAGivenName()
```


DBG, Άλλο όνομα με το οποίο είναι γνωστός ο κάτοχος της κάρτας, DL/ID, V15ANS

**Returns:**
java.lang.String
### getAliasAKASuffixName() {#getAliasAKASuffixName--}
```
public final String getAliasAKASuffixName()
```


DBS, Άλλο επίθεμα με το οποίο είναι γνωστός ο κάτοχος της κάρτας, DL/ID, V5ANS

**Returns:**
java.lang.String
### getAuditInformation() {#getAuditInformation--}
```
public final String getAuditInformation()
```


DCJ, Μια σειρά από γράμματα και/ή αριθμούς που προσδιορίζει πότε, πού και από ποιον δημιουργήθηκε η άδεια οδήγησης/ταυτότητα. Εάν οι πληροφορίες ελέγχου δεν χρησιμοποιούνται στην κάρτα ή στο MRT, πρέπει να συμπεριληφθούν στο αρχείο του οδηγού, DL/ID, V25ANS

**Returns:**
java.lang.String
### getCardRevisionDate() {#getCardRevisionDate--}
```
public final LocalDate getCardRevisionDate()
```


DDB, απαιτούμενο πεδίο του DHS που υποδεικνύει την ημερομηνία της πιο πρόσφατης αλλαγής έκδοσης ή τροποποίησης της ορατής μορφής του DL/ID. (MMDDCCYY για Η.Π.Α., CCYYMMDD για τον Καναδά), DL/ID, F8N

**Returns:**
java.time.LocalDate
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getComplianceType() {#getComplianceType--}
```
public final String getComplianceType()
```


DDA, Υποχρεωτικό πεδίο του DHS που υποδεικνύει τη συμμόρφωση: \\u201cF\\u201d = συμμορφωμένο· και, \\u201cN\\u201d = μη συμμορφωμένο, DL/ID, F1A

**Returns:**
java.lang.String
### getEndorsementCodeDescription() {#getEndorsementCodeDescription--}
```
public final String getEndorsementCodeDescription()
```


DCQ, Κείμενο που εξηγεί τους κωδικούς ειδικούς για τη δικαιοδοσία που υποδεικνύουν πρόσθετα προνόμια οδήγησης που χορηγούνται στον κάτοχο πέρα από την κατηγορία οχήματος, DL, V50ANS

**Returns:**
java.lang.String
### getHAZMATEndorsementExpDate() {#getHAZMATEndorsementExpDate--}
```
public final LocalDate getHAZMATEndorsementExpDate()
```


DDC, Ημερομηνία κατά την οποία η έγκριση επικίνδυνου υλικού που χορηγείται από το έγγραφο δεν ισχύει πλέον. (MMDDCCYY για Η.Π.Α., CCYYMMDD για τον Καναδά), DL, F8N

**Returns:**
java.time.LocalDate
### getHairColor() {#getHairColor--}
```
public final USADriveIdHairColor getHairColor()
```


DAZ, ξαθόμαστος, μαύρο, ξανθό, καστανό, γκρι, κόκκινο/κόκκινο-καστανό, αμμουδερό, λευκό, άγνωστο. Εάν η εκδούσα αρχή επιθυμεί να συντομεύσει τα χρώματα, πρέπει να χρησιμοποιηθούν οι τριψήφιοι κωδικοί που παρέχονται στο AAMVA D20, DL/ID, V12A

**Returns:**
[USADriveIdHairColor](../../com.aspose.barcode.complexbarcode/usadriveidhaircolor)
### getInventoryControlNumber() {#getInventoryControlNumber--}
```
public final String getInventoryControlNumber()
```


DCK, Μια σειρά από γράμματα και/ή αριθμούς που προσκολλάται στα ακατέργαστα υλικά (χαρτόνι, laminat κ.λπ.) που χρησιμοποιούνται στην παραγωγή αδειών οδήγησης και καρτών ID. (συστήνεται πεδίο από το DHS), DL/ID, V25ANS

**Returns:**
java.lang.String
### getLimitedDurationDocIndicator() {#getLimitedDurationDocIndicator--}
```
public final String getLimitedDurationDocIndicator()
```


DDD, Υποχρεωτικό πεδίο του DHS που υποδεικνύει ότι ο κάτοχος έχει προσωρινή νόμιμη κατάσταση = \\u201c1\\u201d, DL/ID, F1N

**Returns:**
java.lang.String
### getNameSuffix() {#getNameSuffix--}
```
public final String getNameSuffix()
```


DCU, Κατάληξη ονόματος (Εάν η δικαιοδοσία συμμετέχει σε συστήματα που απαιτούν κατάληξη ονόματος (PDPS, CDLIS κ.λπ.), η κατάληξη πρέπει να συλλέγεται και να εμφανίζεται στο DL/ID και στο MRT). JR (Junior), SR (Senior), 1ST ή I (First), έως 9TH ή IX (Ninth), DL/ID, V5ANS

**Returns:**
java.lang.String
### getOrganDonorIndicator() {#getOrganDonorIndicator--}
```
public final String getOrganDonorIndicator()
```


DDK, Πεδίο που υποδεικνύει ότι ο κάτοχος είναι δωρητής οργάνων = \\u201c1\\u201d, DL/ID, F1N

**Returns:**
java.lang.String
### getPlaceOfBirth() {#getPlaceOfBirth--}
```
public final String getPlaceOfBirth()
```


DCI, Χώρα και δήμος και/ή πολιτεία/επικράτεια, DL/ID, V33A

**Returns:**
java.lang.String
### getRaceEthnicity() {#getRaceEthnicity--}
```
public final String getRaceEthnicity()
```


DCL, Κωδικοί για τη φυλή ή την εθνική προέλευση του κατόχου, όπως ορίζονται στο AAMVA D20, DL/ID, V3A

**Returns:**
java.lang.String
### getRestrictionCodeDescription() {#getRestrictionCodeDescription--}
```
public final String getRestrictionCodeDescription()
```


DCR, Κείμενο που περιγράφει τους κωδικούς περιορισμών ειδικούς για τη δικαιοδοσία που περιορίζουν τα προνόμια οδήγησης, DL, V50ANS

**Returns:**
java.lang.String
### getStandardEndorsementCode() {#getStandardEndorsementCode--}
```
public final String getStandardEndorsementCode()
```


DCN, Τυπικοί κωδικοί έγκρισης για τον κάτοχο της κάρτας. Δείτε τους κωδικούς στο D20. Αυτό το στοιχείο δεδομένων είναι ένας χώρος κράτησης για μελλοντικές προσπάθειες τυποποίησης κωδικών έγκρισης, DL, F5AN

**Returns:**
java.lang.String
### getStandardRestrictionCode() {#getStandardRestrictionCode--}
```
public final String getStandardRestrictionCode()
```


DCO, Τυπικοί κωδικοί περιορισμού για τον κάτοχο της κάρτας. Δείτε τους κωδικούς στο D20. Αυτό το στοιχείο δεδομένων είναι ένας χώρος κράτησης για μελλοντικές προσπάθειες τυποποίησης κωδικών περιορισμού, DL, F12AN

**Returns:**
java.lang.String
### getStandardVehClassification() {#getStandardVehClassification--}
```
public final String getStandardVehClassification()
```


DCM, Τυπικοί κωδικοί ταξινόμησης οχημάτων για τον κάτοχο της κάρτας. Αυτό το στοιχείο δεδομένων είναι ένας χώρος κράτησης για μελλοντικές προσπάθειες τυποποίησης ταξινομήσεων οχημάτων, DL, F4AN

**Returns:**
java.lang.String
### getUnder18Until() {#getUnder18Until--}
```
public final LocalDate getUnder18Until()
```


DDH, Ημερομηνία κατά την οποία ο κάτοχος της κάρτας γίνεται 18 ετών. (MMDDCCYY για Η.Π.Α., CCYYMMDD για τον Καναδά), DL/ID, F8N

**Returns:**
java.time.LocalDate
### getUnder19Until() {#getUnder19Until--}
```
public final LocalDate getUnder19Until()
```


DDI, Ημερομηνία κατά την οποία ο κάτοχος της κάρτας γίνεται 19 ετών. (MMDDCCYY για Η.Π.Α., CCYYMMDD για τον Καναδά), DL/ID, F8N

**Returns:**
java.time.LocalDate
### getUnder21Until() {#getUnder21Until--}
```
public final LocalDate getUnder21Until()
```


DDJ, Ημερομηνία κατά την οποία ο κάτοχος της κάρτας γίνεται 21 ετών. (MMDDCCYY για Η.Π.Α., CCYYMMDD για τον Καναδά), DL/ID, F8N

**Returns:**
java.time.LocalDate
### getVehClassDescription() {#getVehClassDescription--}
```
public final String getVehClassDescription()
```


DCP, Κείμενο που εξηγεί τους κωδικούς ειδικούς για τη δικαιοδοσία σχετικά με τις ταξινομήσεις οχημάτων που ο κάτοχος έχει εξουσιοδότηση να οδηγεί, DL, V50ANS

**Returns:**
java.lang.String
### getVeteranIndicator() {#getVeteranIndicator--}
```
public final String getVeteranIndicator()
```


DDL, Πεδίο που υποδεικνύει ότι ο κάτοχος είναι βετεράνος = \\u201c1\\u201d, DL/ID, F1N

**Returns:**
java.lang.String
### getWeightKilograms() {#getWeightKilograms--}
```
public final int getWeightKilograms()
```


DAX, Βάρος του κατόχου σε κιλά, Παρ. 84 kg = \\u201c084\\u201d, DL/ID, F3N

**Returns:**
int
### getWeightPounds() {#getWeightPounds--}
```
public final int getWeightPounds()
```


DAW, Βάρος του κατόχου σε λίβρες, Παρ. 185 lb = \\u201c185\\u201d, DL/ID, F3N

**Returns:**
int
### getWeightRange() {#getWeightRange--}
```
public final String getWeightRange()
```


DCE, Δείχνει το προσεγγιστικό εύρος βάρους του κατόχου: 0 = έως 31 kg (έως 70 λίβρες), 1 = 32 \\u2013 45 kg (71 \\u2013 100 λίβρες), 2 = 46 - 59 kg (101 \\u2013 130 λίβρες), 3 = 60 - 70 kg (131 \\u2013 160 λίβρες), 4 = 71 - 86 kg (161 \\u2013 190 λίβρες), 5 = 87 - 100 kg (191 \\u2013 220 λίβρες), 6 = 101 - 113 kg (221 \\u2013 250 λίβρες), 7 = 114 - 127 kg (251 \\u2013 280 λίβρες), 8 = 128 \\u2013 145 kg (281 \\u2013 320 λίβρες), 9 = 146+ kg (321+ λίβρες), DL/ID, F1N

**Returns:**
java.lang.String
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setAddressStreet2(String value) {#setAddressStreet2-java.lang.String-}
```
public final void setAddressStreet2(String value)
```


DAH, Δεύτερη γραμμή του τμήματος οδού της διεύθυνσης του κατόχου της κάρτας, DL/ID, V35ANS

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### setAliasAKAFamilyName(String value) {#setAliasAKAFamilyName-java.lang.String-}
```
public final void setAliasAKAFamilyName(String value)
```


DBN, Άλλο επώνυμο με το οποίο είναι γνωστός ο κάτοχος της κάρτας, DL/ID, V10ANS

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### setAliasAKAGivenName(String value) {#setAliasAKAGivenName-java.lang.String-}
```
public final void setAliasAKAGivenName(String value)
```


DBG, Άλλο όνομα με το οποίο είναι γνωστός ο κάτοχος της κάρτας, DL/ID, V15ANS

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### setAliasAKASuffixName(String value) {#setAliasAKASuffixName-java.lang.String-}
```
public final void setAliasAKASuffixName(String value)
```


DBS, Άλλο επίθεμα με το οποίο είναι γνωστός ο κάτοχος της κάρτας, DL/ID, V5ANS

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### setAuditInformation(String value) {#setAuditInformation-java.lang.String-}
```
public final void setAuditInformation(String value)
```


DCJ, Μια σειρά από γράμματα και/ή αριθμούς που προσδιορίζει πότε, πού και από ποιον δημιουργήθηκε η άδεια οδήγησης/ταυτότητα. Εάν οι πληροφορίες ελέγχου δεν χρησιμοποιούνται στην κάρτα ή στο MRT, πρέπει να συμπεριληφθούν στο αρχείο του οδηγού, DL/ID, V25ANS

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### setCardRevisionDate(LocalDate value) {#setCardRevisionDate-java.time.LocalDate-}
```
public final void setCardRevisionDate(LocalDate value)
```


DDB, απαιτούμενο πεδίο του DHS που υποδεικνύει την ημερομηνία της πιο πρόσφατης αλλαγής έκδοσης ή τροποποίησης της ορατής μορφής του DL/ID. (MMDDCCYY για Η.Π.Α., CCYYMMDD για τον Καναδά), DL/ID, F8N

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.time.LocalDate |  |

### setComplianceType(String value) {#setComplianceType-java.lang.String-}
```
public final void setComplianceType(String value)
```


DDA, Υποχρεωτικό πεδίο του DHS που υποδεικνύει τη συμμόρφωση: \\u201cF\\u201d = συμμορφωμένο· και, \\u201cN\\u201d = μη συμμορφωμένο, DL/ID, F1A

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### setEndorsementCodeDescription(String value) {#setEndorsementCodeDescription-java.lang.String-}
```
public final void setEndorsementCodeDescription(String value)
```


DCQ, Κείμενο που εξηγεί τους κωδικούς ειδικούς για τη δικαιοδοσία που υποδεικνύουν πρόσθετα προνόμια οδήγησης που χορηγούνται στον κάτοχο πέρα από την κατηγορία οχήματος, DL, V50ANS

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### setHAZMATEndorsementExpDate(LocalDate value) {#setHAZMATEndorsementExpDate-java.time.LocalDate-}
```
public final void setHAZMATEndorsementExpDate(LocalDate value)
```


DDC, Ημερομηνία κατά την οποία η έγκριση επικίνδυνου υλικού που χορηγείται από το έγγραφο δεν ισχύει πλέον. (MMDDCCYY για Η.Π.Α., CCYYMMDD για τον Καναδά), DL, F8N

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.time.LocalDate |  |

### setHairColor(USADriveIdHairColor value) {#setHairColor-com.aspose.barcode.complexbarcode.USADriveIdHairColor-}
```
public final void setHairColor(USADriveIdHairColor value)
```


DAZ, ξαθόμαστος, μαύρο, ξανθό, καστανό, γκρι, κόκκινο/κόκκινο-καστανό, αμμουδερό, λευκό, άγνωστο. Εάν η εκδούσα αρχή επιθυμεί να συντομεύσει τα χρώματα, πρέπει να χρησιμοποιηθούν οι τριψήφιοι κωδικοί που παρέχονται στο AAMVA D20, DL/ID, V12A

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [USADriveIdHairColor](../../com.aspose.barcode.complexbarcode/usadriveidhaircolor) |  |

### setInventoryControlNumber(String value) {#setInventoryControlNumber-java.lang.String-}
```
public final void setInventoryControlNumber(String value)
```


DCK, Μια σειρά από γράμματα και/ή αριθμούς που προσκολλάται στα ακατέργαστα υλικά (χαρτόνι, laminat κ.λπ.) που χρησιμοποιούνται στην παραγωγή αδειών οδήγησης και καρτών ID. (συστήνεται πεδίο από το DHS), DL/ID, V25ANS

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### setLimitedDurationDocIndicator(String value) {#setLimitedDurationDocIndicator-java.lang.String-}
```
public final void setLimitedDurationDocIndicator(String value)
```


DDD, Υποχρεωτικό πεδίο του DHS που υποδεικνύει ότι ο κάτοχος έχει προσωρινή νόμιμη κατάσταση = \\u201c1\\u201d, DL/ID, F1N

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### setNameSuffix(String value) {#setNameSuffix-java.lang.String-}
```
public final void setNameSuffix(String value)
```


DCU, Κατάληξη ονόματος (Εάν η δικαιοδοσία συμμετέχει σε συστήματα που απαιτούν κατάληξη ονόματος (PDPS, CDLIS κ.λπ.), η κατάληξη πρέπει να συλλέγεται και να εμφανίζεται στο DL/ID και στο MRT). JR (Junior), SR (Senior), 1ST ή I (First), έως 9TH ή IX (Ninth), DL/ID, V5ANS

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### setOrganDonorIndicator(String value) {#setOrganDonorIndicator-java.lang.String-}
```
public final void setOrganDonorIndicator(String value)
```


DDK, Πεδίο που υποδεικνύει ότι ο κάτοχος είναι δωρητής οργάνων = \\u201c1\\u201d, DL/ID, F1N

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### setPlaceOfBirth(String value) {#setPlaceOfBirth-java.lang.String-}
```
public final void setPlaceOfBirth(String value)
```


DCI, Χώρα και δήμος και/ή πολιτεία/επικράτεια, DL/ID, V33A

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### setRaceEthnicity(String value) {#setRaceEthnicity-java.lang.String-}
```
public final void setRaceEthnicity(String value)
```


DCL, Κωδικοί για τη φυλή ή την εθνική προέλευση του κατόχου, όπως ορίζονται στο AAMVA D20, DL/ID, V3A

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### setRestrictionCodeDescription(String value) {#setRestrictionCodeDescription-java.lang.String-}
```
public final void setRestrictionCodeDescription(String value)
```


DCR, Κείμενο που περιγράφει τους κωδικούς περιορισμών ειδικούς για τη δικαιοδοσία που περιορίζουν τα προνόμια οδήγησης, DL, V50ANS

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### setStandardEndorsementCode(String value) {#setStandardEndorsementCode-java.lang.String-}
```
public final void setStandardEndorsementCode(String value)
```


DCN, Τυπικοί κωδικοί έγκρισης για τον κάτοχο της κάρτας. Δείτε τους κωδικούς στο D20. Αυτό το στοιχείο δεδομένων είναι ένας χώρος κράτησης για μελλοντικές προσπάθειες τυποποίησης κωδικών έγκρισης, DL, F5AN

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### setStandardRestrictionCode(String value) {#setStandardRestrictionCode-java.lang.String-}
```
public final void setStandardRestrictionCode(String value)
```


DCO, Τυπικοί κωδικοί περιορισμού για τον κάτοχο της κάρτας. Δείτε τους κωδικούς στο D20. Αυτό το στοιχείο δεδομένων είναι ένας χώρος κράτησης για μελλοντικές προσπάθειες τυποποίησης κωδικών περιορισμού, DL, F12AN

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### setStandardVehClassification(String value) {#setStandardVehClassification-java.lang.String-}
```
public final void setStandardVehClassification(String value)
```


DCM, Τυπικοί κωδικοί ταξινόμησης οχημάτων για τον κάτοχο της κάρτας. Αυτό το στοιχείο δεδομένων είναι ένας χώρος κράτησης για μελλοντικές προσπάθειες τυποποίησης ταξινομήσεων οχημάτων, DL, F4AN

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### setUnder18Until(LocalDate value) {#setUnder18Until-java.time.LocalDate-}
```
public final void setUnder18Until(LocalDate value)
```


DDH, Ημερομηνία κατά την οποία ο κάτοχος της κάρτας γίνεται 18 ετών. (MMDDCCYY για Η.Π.Α., CCYYMMDD για τον Καναδά), DL/ID, F8N

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.time.LocalDate |  |

### setUnder19Until(LocalDate value) {#setUnder19Until-java.time.LocalDate-}
```
public final void setUnder19Until(LocalDate value)
```


DDI, Ημερομηνία κατά την οποία ο κάτοχος της κάρτας γίνεται 19 ετών. (MMDDCCYY για Η.Π.Α., CCYYMMDD για τον Καναδά), DL/ID, F8N

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.time.LocalDate |  |

### setUnder21Until(LocalDate value) {#setUnder21Until-java.time.LocalDate-}
```
public final void setUnder21Until(LocalDate value)
```


DDJ, Ημερομηνία κατά την οποία ο κάτοχος της κάρτας γίνεται 21 ετών. (MMDDCCYY για Η.Π.Α., CCYYMMDD για τον Καναδά), DL/ID, F8N

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.time.LocalDate |  |

### setVehClassDescription(String value) {#setVehClassDescription-java.lang.String-}
```
public final void setVehClassDescription(String value)
```


DCP, Κείμενο που εξηγεί τους κωδικούς ειδικούς για τη δικαιοδοσία σχετικά με τις ταξινομήσεις οχημάτων που ο κάτοχος έχει εξουσιοδότηση να οδηγεί, DL, V50ANS

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### setVeteranIndicator(String value) {#setVeteranIndicator-java.lang.String-}
```
public final void setVeteranIndicator(String value)
```


DDL, Πεδίο που υποδεικνύει ότι ο κάτοχος είναι βετεράνος = \\u201c1\\u201d, DL/ID, F1N

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### setWeightKilograms(int value) {#setWeightKilograms-int-}
```
public final void setWeightKilograms(int value)
```


DAX, Βάρος του κατόχου σε κιλά, Παρ. 84 kg = \\u201c084\\u201d, DL/ID, F3N

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setWeightPounds(int value) {#setWeightPounds-int-}
```
public final void setWeightPounds(int value)
```


DAW, Βάρος του κατόχου σε λίβρες, Παρ. 185 lb = \\u201c185\\u201d, DL/ID, F3N

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setWeightRange(String value) {#setWeightRange-java.lang.String-}
```
public final void setWeightRange(String value)
```


DCE, Δείχνει το προσεγγιστικό εύρος βάρους του κατόχου: 0 = έως 31 kg (έως 70 λίβρες), 1 = 32 \\u2013 45 kg (71 \\u2013 100 λίβρες), 2 = 46 - 59 kg (101 \\u2013 130 λίβρες), 3 = 60 - 70 kg (131 \\u2013 160 λίβρες), 4 = 71 - 86 kg (161 \\u2013 190 λίβρες), 5 = 87 - 100 kg (191 \\u2013 220 λίβρες), 6 = 101 - 113 kg (221 \\u2013 250 λίβρες), 7 = 114 - 127 kg (251 \\u2013 280 λίβρες), 8 = 128 \\u2013 145 kg (281 \\u2013 320 λίβρες), 9 = 146+ kg (321+ λίβρες), DL/ID, F1N

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final native void wait(long arg0)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

