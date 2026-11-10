---
title: "Κλάση USADriveIdCodetext"
second_title: "Αναφορά API του Aspose.BarCode για .NET"
description: "Aspose.BarCode.ComplexBarcode.USADriveIdCodetext κλάση. Κλάση για κωδικοποίηση και αποκωδικοποίηση του κειμένου που ενσωματώνεται στον κώδικα PDF417 της αμερικανικής άδειας οδήγησης (USA Driving License)."
type: docs
weight: 810
url: /el/net/aspose.barcode.complexbarcode/usadriveidcodetext/
---
## USADriveIdCodetext class

Κλάση για κωδικοποίηση και αποκωδικοποίηση του κειμένου που ενσωματώνεται στον κώδικα USA Driving License PDF417.

```csharp
public sealed class USADriveIdCodetext : IComplexCodetext
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [USADriveIdCodetext](usadriveidcodetext/)() | Ο προεπιλεγμένος κατασκευαστής. |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [AAMVAVersionNumber](../../aspose.barcode.complexbarcode/usadriveidcodetext/aamvaversionnumber/) { get; set; } | Αριθμός Έκδοσης AAMVA 00-99 |
| [IssuerIdentificationNumber](../../aspose.barcode.complexbarcode/usadriveidcodetext/issueridentificationnumber/) { get; set; } | Αυτός ο αριθμός αναγνωρίζει μοναδικά τη δικαιοδοσία έκδοσης και μπορεί να ληφθεί επικοινωνώντας με την Αρχή Έκδοσης ISO (AAMVA). Το πλήρες 6-ψήφιο IIN πρέπει να κωδικοποιηθεί. |
| [JurisdictionSpecificSubfile](../../aspose.barcode.complexbarcode/usadriveidcodetext/jurisdictionspecificsubfile/) { get; set; } | Πεδία Ειδικά για τη Δικαιοδοσία |
| [JurisdictionVersionNumber](../../aspose.barcode.complexbarcode/usadriveidcodetext/jurisdictionversionnumber/) { get; set; } | Αριθμός Έκδοσης Δικαιοδοσίας 00-99 |
| [MandatoryElements](../../aspose.barcode.complexbarcode/usadriveidcodetext/mandatoryelements/) { get; set; } | Υποχρεωτικά στοιχεία (πεδία) της κάρτας |
| [NumberOfEntries](../../aspose.barcode.complexbarcode/usadriveidcodetext/numberofentries/) { get; set; } | Αριθμός 00-99 των υποαρχείων |
| [OptionalElements](../../aspose.barcode.complexbarcode/usadriveidcodetext/optionalelements/) { get; set; } | Προαιρετικά στοιχεία (πεδία) της κάρτας |
| [SubfileDesignator](../../aspose.barcode.complexbarcode/usadriveidcodetext/subfiledesignator/) { get; set; } | Περιέχει πληροφορίες για τα παρακάτω υποαρχεία, τύπους, μετατοπίσεις και μήκη. Σημαντικό: ορίστε μόνο τον τύπο, η μετατόπιση και το μήκος θα οριστούν αυτόματα. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [GetBarcodeType](../../aspose.barcode.complexbarcode/usadriveidcodetext/getbarcodetype/)() | Επιστρέφει τον τύπο barcode της αμερικανικής άδειας οδήγησης (USA DL) (Pdf417) |
| [GetConstructedCodetext](../../aspose.barcode.complexbarcode/usadriveidcodetext/getconstructedcodetext/)() | Δημιουργήστε κείμενο κώδικα από τα δεδομένα USA DL |
| [InitFromString](../../aspose.barcode.complexbarcode/usadriveidcodetext/initfromstring/)(string) | Αρχικοποιήστε το αντικείμενο USA DL από το κείμενο κώδικα |
| [SaveToXml](../../aspose.barcode.complexbarcode/usadriveidcodetext/savetoxml/)(Stream) | Αποθηκεύει σε XML |

## Άλλα μέλη

| Όνομα | Περιγραφή |
| --- | --- |
| class [MandatoryFields](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields) | Υποχρεωτικά στοιχεία (πεδία) της κάρτας |
| class [OptionalFields](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields) | Προαιρετικά στοιχεία (πεδία) της κάρτας |
| class [SubfileProperties](../../aspose.barcode.complexbarcode/usadriveidcodetext.subfileproperties) | Οι ιδιότητες υποαρχείου USA DL, μετατόπιση και μήκος, ορίζονται αυτόματα. |

### Δείτε επίσης

* interface [IComplexCodetext](../icomplexcodetext/)
* namespace [Aspose.BarCode.ComplexBarcode](../../aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](../../)


