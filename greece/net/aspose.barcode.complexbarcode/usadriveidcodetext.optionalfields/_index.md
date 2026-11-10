---
title: "Κλάση USADriveIdCodetext.OptionalFields"
second_title: "Αναφορά API του Aspose.BarCode για .NET"
description: "Κλάση Aspose.BarCode.ComplexBarcode.USADriveIdCodetextOptionalFields. Πεδία προαιρετικών στοιχείων της κάρτας"
type: docs
weight: 830
url: /el/net/aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/
---
## USADriveIdCodetext.OptionalFields class

Προαιρετικά στοιχεία (πεδία) της κάρτας

```csharp
public class OptionalFields
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [OptionalFields](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/.ctor)() | Ο προεπιλεγμένος κατασκευαστής. |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [AddressStreet2](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/addressstreet2) { get; set; } | DAH, Δεύτερη γραμμή του τμήματος οδού της διεύθυνσης του κατόχου της κάρτας, DL/ID, V35ANS |
| [AliasAKAFamilyName](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/aliasakafamilyname) { get; set; } | DBN, Άλλο επώνυμο με το οποίο είναι γνωστός ο κάτοχος της κάρτας, DL/ID, V10ANS |
| [AliasAKAGivenName](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/aliasakagivenname) { get; set; } | DBG, Άλλο όνομα με το οποίο είναι γνωστός ο κάτοχος της κάρτας, DL/ID, V15ANS |
| [AliasAKASuffixName](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/aliasakasuffixname) { get; set; } | DBS, Άλλο επίθεμα με το οποίο είναι γνωστός ο κάτοχος της κάρτας, DL/ID, V5ANS |
| [AuditInformation](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/auditinformation) { get; set; } | DCJ, Μία αλφαριθμητική σειρά που προσδιορίζει πότε, πού και από ποιον δημιουργήθηκε η άδεια οδήγησης/ταυτότητα. Εάν δεν χρησιμοποιούνται πληροφορίες ελέγχου στην κάρτα ή το MRT, πρέπει να συμπεριληφθούν στο αρχείο του οδηγού, DL/ID, V25ANS |
| [CardRevisionDate](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/cardrevisiondate) { get; set; } | DDB, Υποχρεωτικό πεδίο DHS που υποδεικνύει την ημερομηνία της πιο πρόσφατης αλλαγής έκδοσης ή τροποποίησης της ορατής μορφής του DL/ID. (MMDDCCYY για τις Η.Π.Α., CCYYMMDD για τον Καναδά), DL/ID, F8N |
| [ComplianceType](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/compliancetype) { get; set; } | DDA, Υποχρεωτικό πεδίο DHS που υποδεικνύει τη συμμόρφωση: “F” = συμμορφωμένο· και, “N” = μη συμμορφωμένο, DL/ID, F1A |
| [EndorsementCodeDescription](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/endorsementcodedescription) { get; set; } | DCQ, Κείμενο που εξηγεί τους κωδικούς ειδικούς για τη δικαιοδοσία που υποδεικνύουν πρόσθετα προνόμια οδήγησης που χορηγούνται στον κάτοχο της κάρτας πέρα από την κατηγορία οχήματος, DL, V50ANS |
| [HairColor](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/haircolor) { get; set; } | DAZ, Ξυρισμένος, μαύρος, ξανθός, καστανός, γκρι, κόκκινος/κόκκινο-καφέ, αμμουδιά, λευκός, άγνωστο. Εάν η εκδούσα δικαιοδοσία επιθυμεί να συντομεύσει τα χρώματα, πρέπει να χρησιμοποιηθούν οι τριψήφιοι κωδικοί που παρέχονται στο AAMVA D20, DL/ID, V12A |
| [HAZMATEndorsementExpDate](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/hazmatendorsementexpdate) { get; set; } | DDC, Ημερομηνία κατά την οποία η έγκριση επικίνδυνου υλικού που χορηγείται από το έγγραφο δεν ισχύει πλέον. (MMDDCCYY για τις Η.Π.Α., CCYYMMDD για τον Καναδά), DL, F8N |
| [InventoryControlNumber](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/inventorycontrolnumber) { get; set; } | DCK, Μία αλφαριθμητική σειρά που προστίθεται στα ακατέργαστα υλικά (χαρτόνι, επίστρωση κ.λπ.) που χρησιμοποιούνται στην παραγωγή αδειών οδήγησης και ταυτοτήτων. (Πεδίο που συνιστά το DHS), DL/ID, V25ANS |
| [LimitedDurationDocIndicator](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/limiteddurationdocindicator) { get; set; } | DDD, Υποχρεωτικό πεδίο DHS που υποδεικνύει ότι ο κάτοχος της κάρτας έχει προσωρινή νόμιμη κατάσταση = “1”, DL/ID, F1N |
| [NameSuffix](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/namesuffix) { get; set; } | DCU, Κατάληξη ονόματος (Εάν η δικαιοδοσία συμμετέχει σε συστήματα που απαιτούν κατάληξη ονόματος (PDPS, CDLIS κ.λπ.), η κατάληξη πρέπει να συλλέγεται και να εμφανίζεται στο DL/ID και στο MRT). JR (Junior), SR (Senior), 1ST ή I (First), έως 9TH ή IX (Ninth), DL/ID, V5ANS |
| [OrganDonorIndicator](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/organdonorindicator) { get; set; } | DDK, Πεδίο που υποδεικνύει ότι ο κάτοχος της κάρτας είναι δωρητής οργάνων = “1”, DL/ID, F1N |
| [PlaceOfBirth](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/placeofbirth) { get; set; } | DCI, Χώρα και δήμος και/ή πολιτεία/επάρκεια, DL/ID, V33A |
| [RaceEthnicity](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/raceethnicity) { get; set; } | DCL, Κωδικοί για τη φυλή ή την εθνική προέλευση του κατόχου της κάρτας, όπως ορίζονται στο AAMVA D20, DL/ID, V3A |
| [RestrictionCodeDescription](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/restrictioncodedescription) { get; set; } | DCR, Κείμενο που περιγράφει τους κωδικούς περιορισμών ειδικούς για τη δικαιοδοσία που περιορίζουν τα προνόμια οδήγησης, DL, V50ANS |
| [StandardEndorsementCode](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/standardendorsementcode) { get; set; } | DCN, Πρότυποι κωδικοί ενδείξεων για τον κάτοχο της κάρτας. Δείτε τους κωδικούς στο D20. Αυτό το στοιχείο δεδομένων είναι ένας κράτημα για μελλοντικές προσπάθειες τυποποίησης των κωδικών ενδείξεων, DL, F5AN |
| [StandardRestrictionCode](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/standardrestrictioncode) { get; set; } | DCO, Τυπικοί κωδικοί περιορισμού για τον κάτοχο της κάρτας. Δείτε τους κωδικούς στο D20. Αυτό το στοιχείο δεδομένων είναι ένας κράτημα για μελλοντικές προσπάθειες τυποποίησης των κωδικών περιορισμού, DL, F12AN |
| [StandardVehClassification](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/standardvehclassification) { get; set; } | DCM, Τυπικοί κωδικοί ταξινόμησης οχημάτων για τον κάτοχο της κάρτας. Αυτό το στοιχείο δεδομένων είναι ένας κράτημα για μελλοντικές προσπάθειες τυποποίησης των ταξινομήσεων οχημάτων, DL, F4AN |
| [Under18Until](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/under18until) { get; set; } | DDH, Ημερομηνία κατά την οποία ο κάτοχος της κάρτας γίνεται 18 ετών. (MMDDCCYY για Η.Π.Α., CCYYMMDD για τον Καναδά), DL/ID, F8N |
| [Under19Until](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/under19until) { get; set; } | DDI, Ημερομηνία κατά την οποία ο κάτοχος της κάρτας γίνεται 19 ετών. (MMDDCCYY για Η.Π.Α., CCYYMMDD για τον Καναδά), DL/ID, F8N |
| [Under21Until](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/under21until) { get; set; } | DDJ, Ημερομηνία κατά την οποία ο κάτοχος της κάρτας γίνεται 21 ετών. (MMDDCCYY για Η.Π.Α., CCYYMMDD για τον Καναδά), DL/ID, F8N |
| [VehClassDescription](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/vehclassdescription) { get; set; } | DCP, Κείμενο που εξηγεί τους κωδικούς ειδικών δικαιοδοσιών για τις ταξινομήσεις οχημάτων που ο κάτοχος της κάρτας είναι εξουσιοδοτημένος να οδηγεί, DL, V50ANS |
| [VeteranIndicator](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/veteranindicator) { get; set; } | DDL, Πεδίο που υποδεικνύει ότι ο κάτοχος της κάρτας είναι βετεράνος = “1”, DL/ID, F1N |
| [WeightKilograms](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/weightkilograms) { get; set; } | DAX, Βάρος του κατόχου της κάρτας σε κιλά, Π.χ. 84 kg = “084”, DL/ID, F3N |
| [WeightPounds](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/weightpounds) { get; set; } | DAW, Βάρος του κατόχου της κάρτας σε λίβρες, Π.χ. 185 lb = “185”, DL/ID, F3N |
| [WeightRange](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/weightrange) { get; set; } | DCE, Δείχνει το προσεγγιστικό εύρος βάρους του κατόχου της κάρτας: 0 = έως 31 kg (έως 70 λίβρες), 1 = 32 – 45 kg (71 – 100 λίβρες), 2 = 46 - 59 kg (101 – 130 λίβρες), 3 = 60 - 70 kg (131 – 160 λίβρες), 4 = 71 - 86 kg (161 – 190 λίβρες), 5 = 87 - 100 kg (191 – 220 λίβρες), 6 = 101 - 113 kg (221 – 250 λίβρες), 7 = 114 - 127 kg (251 – 280 λίβρες), 8 = 128 – 145 kg (281 – 320 λίβρες), 9 = 146+ kg (321+ λίβρες), DL/ID, F1N |

### Δείτε επίσης

* class [USADriveIdCodetext](../usadriveidcodetext/)
* namespace [Aspose.BarCode.ComplexBarcode](../../aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](../../)


