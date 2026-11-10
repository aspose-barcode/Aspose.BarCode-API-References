---
title: "Κλάση USADriveIdCodetext.MandatoryFields"
second_title: "Αναφορά API του Aspose.BarCode για .NET"
description: "Aspose.BarCode.ComplexBarcode.USADriveIdCodetextMandatoryFields κλάση. Υποχρεωτικά στοιχεία (πεδία) της κάρτας"
type: docs
weight: 820
url: /el/net/aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/
---
## USADriveIdCodetext.MandatoryFields class

Υποχρεωτικά στοιχεία (πεδία) της κάρτας

```csharp
public class MandatoryFields
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [MandatoryFields](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/.ctor)() | Ο προεπιλεγμένος κατασκευαστής. |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [AddressCity](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/addresscity) { get; set; } | DAI, Τμήμα πόλης της διεύθυνσης του κατόχου της κάρτας, DL/ID, V20ANS |
| [AddressPostalCode](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/addresspostalcode) { get; set; } | DAK, Τμήμα ταχυδρομικού κώδικα της διεύθυνσης του κατόχου της κάρτας στις Η.Π.Α. και τον Καναδά. Εάν το τελικό τμήμα του ταχυδρομικού κώδικα στις Η.Π.Α. δεν είναι γνωστό, μηδενικά θα χρησιμοποιηθούν για να συμπληρώσουν το τελικό σύνολο αριθμών μέχρι 9 ψηφία, DL/ID, F11ANS |
| [AddressState](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/addressstate) { get; set; } | DAJ, Τμήμα πολιτείας της διεύθυνσης του κατόχου της κάρτας, DL/ID, F2A |
| [AddressStreet1](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/addressstreet1) { get; set; } | DAG, Τμήμα οδού της διεύθυνσης του κατόχου της κάρτας, DL/ID, V35ANS |
| [CountryIdentification](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/countryidentification) { get; set; } | DCG, Χώρα στην οποία εκδίδεται το DL/ID. Η.Π.Α. = USA, Καναδάς = CAN, DL/ID, F3A |
| [CustomerIDNumber](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/customeridnumber) { get; set; } | DAQ, Ο αριθμός που εκχωρεί ή υπολογίζει η αρχή έκδοσης, DL/ID, V25ANS |
| [DateOfBirth](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/dateofbirth) { get; set; } | DBB, Ημερομηνία έκδοσης του εγγράφου, MMDDCCYY for U.S., CCYYMMDD for Canada, DL/ID, F8N |
| [DocumentDiscriminator](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/documentdiscriminator) { get; set; } | DCF, Ο αριθμός πρέπει να αναγνωρίζει μοναδικά ένα συγκεκριμένο έγγραφο που εκδόθηκε σε αυτόν τον πελάτη από άλλα που μπορεί να έχουν εκδοθεί στο παρελθόν. Αυτός ο αριθμός μπορεί να εξυπηρετεί πολλαπλούς σκοπούς διακριτικής ταυτοποίησης εγγράφου, αριθμό πληροφοριών ελέγχου και/ή έλεγχο αποθεμάτων, DL/ID, V25ANS |
| [EndorsementCodes](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/endorsementcodes) { get; set; } | DCD, Κώδικες ενδείξεων ειδικών για τη δικαιοδοσία, DL, V5ANS |
| [ExpirationDate](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/expirationdate) { get; set; } | DBA, Ημερομηνία λήξης εγγράφου, MMDDCCYY for U.S., CCYYMMDD for Canada, DL/ID, F8N |
| [EyeColor](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/eyecolor) { get; set; } | DAY, Χρώμα των ματιών του κατόχου της κάρτας. (ANSI D-20 codes). DL/ID, F3A |
| [FamilyName](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/familyname) { get; set; } | DCS, Επώνυμο του κατόχου της κάρτας, DL/ID, V40ANS |
| [FamilyNameTruncation](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/familynametruncation) { get; set; } | DDE, Κώδικας που υποδεικνύει εάν ένα πεδίο έχει περικοπεί (T), δεν έχει περικοπεί (N), ή είναι άγνωστο αν έχει περικοπεί (U), DL/ID, F1A |
| [FirstName](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/firstname) { get; set; } | DAC, Όνομα του κατόχου της κάρτας, DL/ID, V40ANS |
| [FirstNameTruncation](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/firstnametruncation) { get; set; } | DDF, Κώδικας που υποδεικνύει εάν ένα πεδίο έχει περικοπεί (T), δεν έχει περικοπεί (N), ή είναι άγνωστο αν έχει περικοπεί (U), DL/ID, F1A |
| [Height](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/height) { get; set; } | DAU, Ύψος του κατόχου της κάρτας. Ίντσες (in): αριθμός ίντσες ακολουθούμενος από " in" π.χ. 6'1'' = "073 in" Σεντίνια (cm): αριθμός εκατοστών ακολουθούμενος από " cm" π.χ. 181 εκατοστά = "181 cm" , DL/ID, F6ANS |
| [IssueDate](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/issuedate) { get; set; } | DBD, Ημερομηνία έκδοσης του εγγράφου, MMDDCCYY for U.S., CCYYMMDD for Canada, DL/ID, F8N |
| [MiddleName](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/middlename) { get; set; } | DAD, Μεσαίο όνομα(ον) του κατόχου της κάρτας. Σε περίπτωση πολλαπλών μεσαίων ονομάτων πρέπει να διαχωρίζονται με κόμμα ",". , DL/ID, V40ANS |
| [MiddleNameTruncation](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/middlenametruncation) { get; set; } | DDG, Κώδικας που υποδεικνύει εάν ένα πεδίο έχει περικοπεί (T), δεν έχει περικοπεί (N), ή είναι άγνωστο αν έχει περικοπεί (U), DL/ID, F1A |
| [RestrictionCodes](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/restrictioncodes) { get; set; } | DCB, Κώδικες περιορισμών ειδικών για τη δικαιοδοσία, DL, V12ANS |
| [Sex](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/sex) { get; set; } | DBC, Φύλο του κατόχου της κάρτας. 1 = άνδρας, 2 = γυναίκα, 9 = μη καθορισμένο, DL/ID, F1N |
| [VehicleClass](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/vehicleclass) { get; set; } | DCA, Κώδικας κλάσης / ομάδας οχήματος ειδικός για τη δικαιοδοσία, DL, V6ANS |

### Δείτε επίσης

* class [USADriveIdCodetext](../usadriveidcodetext/)
* namespace [Aspose.BarCode.ComplexBarcode](../../aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](../../)


