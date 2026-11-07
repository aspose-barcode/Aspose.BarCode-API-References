---
title: "Aspose::BarCode::Generation::QrParameters class"
linktitle: "QrParameters"
second_title: "Aspose.BarCode για C++ Αναφορά API"
description: "Aspose::BarCode::Generation::QrParameters class. Παράμετροι QR σε C++."
type: docs
weight: 4400
url: /el/cpp/aspose.barcode.generation/qrparameters/
---
## QrParameters class


Παράμετροι QR.

```cpp
class QrParameters : public System::Object
```

## Methods

| Method | Περιγραφή |
| --- | --- |
| [get_AspectRatio](./get_aspectratio/)() const | Αναλογία ύψους/πλάτους του 2D [BarCode](../../aspose.barcode/) μονάδας. |
| [get_ECIEncoding](./get_eciencoding/)() const | Αναγνωριστικά Επεκταμένης Ερμηνείας Καναλιού. Χρησιμοποιείται για να ενημερώσει τον αναγνώστη barcode λεπτομέρειες σχετικά με τις χρησιμοποιημένες αναφορές για την κωδικοποίηση των δεδομένων στο σύμβολο. Η τρέχουσα υλοποίηση περιλαμβάνει όλες τις γνωστές κωδικοποιήσεις συνόλων χαρακτήρων. Δεν υποστηρίζεται από το MicroQR. |
| [get_EncodeGS1SeparatorInByteMode](./get_encodegs1separatorinbytemode/)() const |  |
| [get_EncodeMode](./get_encodemode/)() const | Τύπος συμβολισμού QR της λειτουργίας κωδικοποίησης του [BarCode](../../aspose.barcode/). Προεπιλεγμένη τιμή: [QREncodeMode.Auto](../aztecencodemode/). |
| [get_ErrorLevel](./get_errorlevel/)() const | Επίπεδο διόρθωσης σφαλμάτων Reed‑Solomon για τα barcode QR, MicroQR και RectMicroQR. Από χαμηλό προς υψηλό: LevelL, LevelM, LevelQ, LevelH. Δείτε το QRErrorLevel. |
| [get_MicroQRVersion](./get_microqrversion/)() const | Έκδοση του κώδικα MicroQR. Από την έκδοση M1 έως την έκδοση M4. Η προεπιλεγμένη τιμή είναι [MicroQRVersion.Auto](../aztecencodemode/). |
| [get_RectMicroQrVersion](./get_rectmicroqrversion/)() const | Έκδοση του κώδικα RectMicroQR. Από την έκδοση R7x59 έως την έκδοση R17x139. Η προεπιλεγμένη τιμή είναι [RectMicroQRVersion.Auto](../aztecencodemode/). |
| [get_StructuredAppend](./get_structuredappend/)() const | Παράμετροι δομημένης προσθήκης QR. Η λειτουργία δομημένης προσθήκης δεν υποστηρίζεται από τα barcode MicroQR και RectMicroQR. |
| [get_Version](./get_version/)() const | Έκδοση του κώδικα QR. Από την Version1 έως την Version40. Η προεπιλεγμένη τιμή είναι [QRVersion.Auto](../aztecencodemode/). |
| [set_AspectRatio](./set_aspectratio/)(float) | Αναλογία ύψους/πλάτους του 2D [BarCode](../../aspose.barcode/) μονάδας. |
| [set_ECIEncoding](./set_eciencoding/)(ECIEncodings) | Αναγνωριστικά Επεκταμένης Ερμηνείας Καναλιού. Χρησιμοποιείται για να ενημερώσει τον αναγνώστη barcode λεπτομέρειες σχετικά με τις χρησιμοποιημένες αναφορές για την κωδικοποίηση των δεδομένων στο σύμβολο. Η τρέχουσα υλοποίηση περιλαμβάνει όλες τις γνωστές κωδικοποιήσεις συνόλων χαρακτήρων. Δεν υποστηρίζεται από το MicroQR. |
| [set_EncodeGS1SeparatorInByteMode](./set_encodegs1separatorinbytemode/)(bool) |  |
| [set_EncodeMode](./set_encodemode/)(QREncodeMode) | Τύπος συμβολισμού QR της λειτουργίας κωδικοποίησης του [BarCode](../../aspose.barcode/). Προεπιλεγμένη τιμή: [QREncodeMode.Auto](../aztecencodemode/). |
| [set_ErrorLevel](./set_errorlevel/)(QRErrorLevel) | Επίπεδο διόρθωσης σφαλμάτων Reed‑Solomon για τα barcode QR, MicroQR και RectMicroQR. Από χαμηλό προς υψηλό: LevelL, LevelM, LevelQ, LevelH. Δείτε το QRErrorLevel. |
| [set_MicroQRVersion](./set_microqrversion/)(Aspose::BarCode::Generation::MicroQRVersion) | Έκδοση του κώδικα MicroQR. Από την έκδοση M1 έως την έκδοση M4. Η προεπιλεγμένη τιμή είναι [MicroQRVersion.Auto](../aztecencodemode/). |
| [set_RectMicroQrVersion](./set_rectmicroqrversion/)(RectMicroQRVersion) | Έκδοση του κώδικα RectMicroQR. Από την έκδοση R7x59 έως την έκδοση R17x139. Η προεπιλεγμένη τιμή είναι [RectMicroQRVersion.Auto](../aztecencodemode/). |
| [set_StructuredAppend](./set_structuredappend/)(System::SharedPtr\<QrStructuredAppendParameters\>) | Παράμετροι δομημένης προσθήκης QR. Η λειτουργία δομημένης προσθήκης δεν υποστηρίζεται από τα barcode MicroQR και RectMicroQR. |
| [set_Version](./set_version/)(QRVersion) | Έκδοση του κώδικα QR. Από την Version1 έως την Version40. Η προεπιλεγμένη τιμή είναι [QRVersion.Auto](../aztecencodemode/). |
| [ToString](./tostring/)() const override | Επιστρέφει μια αναγνώσιμη από άνθρωπο αναπαράσταση συμβολοσειράς αυτού του [QrParameters](./). |
## Δείτε επίσης

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
