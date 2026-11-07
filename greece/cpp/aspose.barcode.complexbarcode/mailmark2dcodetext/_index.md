---
title: "Aspose::BarCode::ComplexBarcode::Mailmark2DCodetext κλάση"
linktitle: "Mailmark2DCodetext"
second_title: "Aspose.BarCode για C++ Αναφορά API"
description: "Aspose::BarCode::ComplexBarcode::Mailmark2DCodetext κλάση. Κλάση για κωδικοποίηση και αποκωδικοποίηση του κειμένου που ενσωματώνεται στον κώδικα Royal Mail 2D Mailmark σε C++."
type: docs
weight: 1400
url: /el/cpp/aspose.barcode.complexbarcode/mailmark2dcodetext/
---
## Mailmark2DCodetext class


Κλάση για κωδικοποίηση και αποκωδικοποίηση του κειμένου ενσωματωμένου στον κώδικα Royal Mail 2D Mailmark.

```cpp
class Mailmark2DCodetext : public Aspose::BarCode::ComplexBarcode::IComplexCodetext
```

## Methods

| Method | Περιγραφή |
| --- | --- |
| [get_Class](./get_class/)() const | Καθορίζει την κλάση του αντικειμένου. |
| [get_CustomerContent](./get_customercontent/)() const | Προαιρετικός χώρος για χρήση από τον πελάτη. |
| [get_CustomerContentEncodeMode](./get_customercontentencodemode/)() const | Λειτουργία κωδικοποίησης του barcode Datamatrix. Προεπιλεγμένη τιμή: EncodeMode.C40. |
| [get_DataMatrixType](./get_datamatrixtype/)() const | Ο τύπος 2D Mailmark ορίζει το μέγεθος του barcode Data Matrix. |
| [get_DestinationPostCodeAndDPS](./get_destinationpostcodeanddps/)() const | Περιέχει τον ταχυδρομικό κώδικα της Διεύθυνσης Παράδοσης [Address](../address/) με DPS. Εάν είναι ενδοχώρα, ο ταχυδρομικός κώδικας/DP περιέχει τον ακόλουθο αριθμό χαρακτήρων. Περιοχή (1 ή 2 χαρακτήρες) Περιφέρεια (1 ή 2 χαρακτήρες) Τομέας (1 χαρακτήρας) Μονάδα (2 χαρακτήρες) DPS (2 χαρακτήρες). Ο ταχυδρομικός κώδικας και το DPS πρέπει να συμμορφώνονται με έγκυρη μορφή PAF®. |
| [get_InformationTypeID](./get_informationtypeid/)() const | Καθορίζει το φορτίο του barcode Royal Mail Mailmark για κάθε τύπο προϊόντος. |
| [get_ItemID](./get_itemid/)() const | Καθορίζει το μοναδικό αντικείμενο εντός του Supply Chain ID. Κάθε barcode Mailmark πρέπει να περιέχει ένα ID ώστε να μπορεί να ταυτοποιηθεί μοναδικά για τουλάχιστον 90 ημέρες. Μέγιστη τιμή: 99999999. |
| [get_ReturnToSenderPostCode](./get_returntosenderpostcode/)() const | Περιέχει τον Ταχυδρομικό Κώδικα Επιστροφής στον Αποστολέα αλλά χωρίς DPS. Ο κώδικας (χωρίς DPS) πρέπει να συμμορφώνεται με μορφή PAF®. |
| [get_RTSFlag](./get_rtsflag/)() const | Σημαία που υποδεικνύει ποιο επίπεδο υπηρεσίας Επιστροφής στον Αποστολέα ζητείται. |
| [get_SupplyChainID](./get_supplychainid/)() const | Καθορίζει τη μοναδική ομάδα πελατών που συμμετέχουν στην αποστολή. Μέγιστη τιμή: 9999999. |
| [get_UPUCountryID](./get_upucountryid/)() const | Καθορίζει το UPU Country ID. Μέγιστο μήκος: 4 χαρακτήρες. |
| [get_VersionID](./get_versionid/)() const | Καθορίζει την έκδοση του barcode όπως σχετίζεται με κάθε Information Type ID. |
| [GetBarcodeType](./getbarcodetype/)() override | Λαμβάνει τον τύπο barcode. |
| [GetConstructedCodetext](./getconstructedcodetext/)() override | Δημιουργήστε κείμενο κώδικα από τα δεδομένα Mailmark. |
| [InitFromString](./initfromstring/)(System::String) override | Αρχικοποιεί τα δεδομένα Mailmark από το κατασκευασμένο κείμενο κώδικα. |
| [Mailmark2DCodetext](./mailmark2dcodetext/)() | Κατασκευαστής. Δημιουργεί προεπιλεγμένη παρουσία της κλάσης [Mailmark2DCodetext](./). |
| [set_Class](./set_class/)(System::String) | Καθορίζει την κλάση του αντικειμένου. |
| [set_CustomerContent](./set_customercontent/)(System::String) | Προαιρετικός χώρος για χρήση από τον πελάτη. |
| [set_CustomerContentEncodeMode](./set_customercontentencodemode/)(Generation::DataMatrixEncodeMode) | Λειτουργία κωδικοποίησης του barcode Datamatrix. Προεπιλεγμένη τιμή: EncodeMode.C40. |
| [set_DataMatrixType](./set_datamatrixtype/)(Mailmark2DType) | Ο τύπος 2D Mailmark ορίζει το μέγεθος του barcode Data Matrix. |
| [set_DestinationPostCodeAndDPS](./set_destinationpostcodeanddps/)(System::String) | Περιέχει τον ταχυδρομικό κώδικα της Διεύθυνσης Παράδοσης [Address](../address/) με DPS. Εάν είναι ενδοχώρα, ο ταχυδρομικός κώδικας/DP περιέχει τον ακόλουθο αριθμό χαρακτήρων. Περιοχή (1 ή 2 χαρακτήρες) Περιφέρεια (1 ή 2 χαρακτήρες) Τομέας (1 χαρακτήρας) Μονάδα (2 χαρακτήρες) DPS (2 χαρακτήρες). Ο ταχυδρομικός κώδικας και το DPS πρέπει να συμμορφώνονται με έγκυρη μορφή PAF®. |
| [set_InformationTypeID](./set_informationtypeid/)(System::String) | Καθορίζει το φορτίο του barcode Royal Mail Mailmark για κάθε τύπο προϊόντος. |
| [set_ItemID](./set_itemid/)(int32_t) | Καθορίζει το μοναδικό αντικείμενο εντός του Supply Chain ID. Κάθε barcode Mailmark πρέπει να περιέχει ένα ID ώστε να μπορεί να ταυτοποιηθεί μοναδικά για τουλάχιστον 90 ημέρες. Μέγιστη τιμή: 99999999. |
| [set_ReturnToSenderPostCode](./set_returntosenderpostcode/)(System::String) | Περιέχει τον Ταχυδρομικό Κώδικα Επιστροφής στον Αποστολέα αλλά χωρίς DPS. Ο κώδικας (χωρίς DPS) πρέπει να συμμορφώνεται με μορφή PAF®. |
| [set_RTSFlag](./set_rtsflag/)(System::String) | Σημαία που υποδεικνύει ποιο επίπεδο υπηρεσίας Επιστροφής στον Αποστολέα ζητείται. |
| [set_SupplyChainID](./set_supplychainid/)(int32_t) | Καθορίζει τη μοναδική ομάδα πελατών που συμμετέχουν στην αποστολή. Μέγιστη τιμή: 9999999. |
| [set_UPUCountryID](./set_upucountryid/)(System::String) | Καθορίζει το UPU Country ID. Μέγιστο μήκος: 4 χαρακτήρες. |
| [set_VersionID](./set_versionid/)(System::String) | Καθορίζει την έκδοση του barcode όπως σχετίζεται με κάθε Information Type ID. |
## Δείτε επίσης

* Class [IComplexCodetext](../icomplexcodetext/)
* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
