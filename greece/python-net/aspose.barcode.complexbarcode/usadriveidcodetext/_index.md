---
title: "USADriveIdCodetext"
second_title: "Aspose.BarCode για Python μέσω .NET API Reference"
description: 
type: docs
url: /el/python-net/aspose.barcode.complexbarcode/usadriveidcodetext/
---

## USADriveIdCodetext class

Κλάση για κωδικοποίηση και αποκωδικοποίηση του κειμένου που ενσωματώνεται στον κώδικα USA Driving License PDF417.

Ο τύπος USADriveIdCodetext εκθέτει τα ακόλουθα μέλη:
## Κατασκευαστές
| Όνομα | Περιγραφή |
| :- | :- |
| USADriveIdCodetext() | Αρχικοποιεί μια νέα παρουσία της κλάσης USADriveIdCodetext |
## Ιδιότητες
| Όνομα | Περιγραφή |
| :- | :- |
| issuer_identification_number | Αυτός ο αριθμός αναγνωρίζει μοναδικά <br/>            τη δικαιοδοσία έκδοσης και μπορεί να ληφθεί επικοινωνώντας με την Αρχή Έκδοσης ISO<br/>            (AAMVA).  Το πλήρες 6-ψήφιο IIN πρέπει να κωδικοποιηθεί. |
| aamva_version_number | Αριθμός Έκδοσης AAMVA 00-99 |
| jurisdiction_version_number | Αριθμός Έκδοσης Δικαιοδοσίας 00-99 |
| number_of_entries | Αριθμός 00-99 των υποαρχείων |
| subfile_designator | Περιέχει πληροφορίες σχετικά με τα παρακάτω υποαρχεία, τύπους, μετατοπίσεις και μήκη. <br/>            Σημαντικό: ορίστε μόνο τον τύπο, η μετατόπιση και το μήκος θα οριστούν αυτόματα. |
| mandatory_elements | Υποχρεωτικά στοιχεία (πεδία) της κάρτας |
| optional_elements | Προαιρετικά στοιχεία (πεδία) της κάρτας |
| jurisdiction_specific_subfile | Πεδία Συγκεκριμένα για τη Δικαιοδοσία |
## Μέθοδοι
| Όνομα | Περιγραφή |
| :- | :- |
| get_constructed_codetext() | Construct codetext from USA DL data |
| init_from_string(constructed_codetext) | Initialize USA DL object from codetext |
| get_barcode_type() | Returns barcode type of USA DL (Pdf417) |
| save_to_xml(stream) | Αποθηκεύει σε XML |

### Δείτε επίσης

* namespace [aspose.barcode.complexbarcode](/barcode/python-net/aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](/barcode/python-net/)

