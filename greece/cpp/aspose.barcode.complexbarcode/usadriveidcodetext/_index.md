---
title: "Aspose::BarCode::ComplexBarcode::USADriveIdCodetext κλάση"
linktitle: "USADriveIdCodetext"
second_title: "Aspose.BarCode για C++ Αναφορά API"
description: "Aspose::BarCode::ComplexBarcode::USADriveIdCodetext κλάση. Κλάση για κωδικοποίηση και αποκωδικοποίηση του κειμένου ενσωματωμένου στον κώδικα PDF417 της Αμερικανικής Άδειας Οδήγησης σε C++."
type: docs
weight: 2900
url: /el/cpp/aspose.barcode.complexbarcode/usadriveidcodetext/
---
## USADriveIdCodetext class


Κλάση για κωδικοποίηση και αποκωδικοποίηση του κειμένου ενσωματωμένου στην Αμερικανική [Άδεια](../../aspose.barcode/license/) PDF417.

```cpp
class USADriveIdCodetext : public Aspose::BarCode::ComplexBarcode::IComplexCodetext
```

## Methods

| Method | Περιγραφή |
| --- | --- |
| [get_AAMVAVersionNumber](./get_aamvaversionnumber/)() const | Αριθμός Έκδοσης AAMVA 00-99 |
| [get_IssuerIdentificationNumber](./get_issueridentificationnumber/)() const | Αυτός ο αριθμός αναγνωρίζει μοναδικά την εκδούσα δικαιοδοσία και μπορεί να ληφθεί επικοινωνώντας με την Αρχή Έκδοσης ISO (AAMVA). Το πλήρες 6-ψήφιο IIN πρέπει να κωδικοποιηθεί. |
| [get_JurisdictionSpecificSubfile](./get_jurisdictionspecificsubfile/)() const | Πεδία Συγκεκριμένα για τη Δικαιοδοσία |
| [get_JurisdictionVersionNumber](./get_jurisdictionversionnumber/)() const | Αριθμός Έκδοσης Δικαιοδοσίας 00-99 |
| [get_MandatoryElements](./get_mandatoryelements/)() const | Υποχρεωτικά στοιχεία (πεδία) της κάρτας |
| [get_NumberOfEntries](./get_numberofentries/)() const | Αριθμός 00-99 υποαρχείων |
| [get_OptionalElements](./get_optionalelements/)() const | Προαιρετικά στοιχεία (πεδία) της κάρτας |
| [get_SubfileDesignator](./get_subfiledesignator/)() const | Περιέχει πληροφορίες για τα παρακάτω υποαρχεία, τύπους, μετατοπίσεις και μήκη. Σημαντικό: ορίστε μόνο τον τύπο, η μετατόπιση και το μήκος θα οριστούν αυτόματα. |
| [GetBarcodeType](./getbarcodetype/)() override | Επιστρέφει τον τύπο barcode της Αμερικανικής Άδειας Οδήγησης (Pdf417) |
| [GetConstructedCodetext](./getconstructedcodetext/)() override | Δημιουργήστε κείμενο κώδικα από τα δεδομένα της Αμερικανικής Άδειας Οδήγησης |
| [InitFromString](./initfromstring/)(System::String) override | Αρχικοποιήστε το αντικείμενο Αμερικανικής Άδειας Οδήγησης από το κείμενο κώδικα |
| [SaveToXml](./savetoxml/)(System::SharedPtr\<System::IO::Stream\>) | Αποθηκεύει σε XML |
| [set_AAMVAVersionNumber](./set_aamvaversionnumber/)(System::String) | Αριθμός Έκδοσης AAMVA 00-99 |
| [set_IssuerIdentificationNumber](./set_issueridentificationnumber/)(System::String) | Αυτός ο αριθμός αναγνωρίζει μοναδικά την εκδούσα δικαιοδοσία και μπορεί να ληφθεί επικοινωνώντας με την Αρχή Έκδοσης ISO (AAMVA). Το πλήρες 6-ψήφιο IIN πρέπει να κωδικοποιηθεί. |
| [set_JurisdictionSpecificSubfile](./set_jurisdictionspecificsubfile/)(System::SharedPtr\<USADriveIdJurisdSubfile\>) | Πεδία Συγκεκριμένα για τη Δικαιοδοσία |
| [set_JurisdictionVersionNumber](./set_jurisdictionversionnumber/)(System::String) | Αριθμός Έκδοσης Δικαιοδοσίας 00-99 |
| [set_MandatoryElements](./set_mandatoryelements/)(System::SharedPtr\<USADriveIdCodetext::MandatoryFields\>) | Υποχρεωτικά στοιχεία (πεδία) της κάρτας |
| [set_NumberOfEntries](./set_numberofentries/)(int32_t) | Αριθμός 00-99 υποαρχείων |
| [set_OptionalElements](./set_optionalelements/)(System::SharedPtr\<USADriveIdCodetext::OptionalFields\>) | Προαιρετικά στοιχεία (πεδία) της κάρτας |
| [set_SubfileDesignator](./set_subfiledesignator/)(System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<USADriveIdCodetext::SubfileProperties\>>>) | Περιέχει πληροφορίες για τα παρακάτω υποαρχεία, τύπους, μετατοπίσεις και μήκη. Σημαντικό: ορίστε μόνο τον τύπο, η μετατόπιση και το μήκος θα οριστούν αυτόματα. |
| [USADriveIdCodetext](./usadriveidcodetext/)() | Προεπιλεγμένος κατασκευαστής |
## Δείτε επίσης

* Class [IComplexCodetext](../icomplexcodetext/)
* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
