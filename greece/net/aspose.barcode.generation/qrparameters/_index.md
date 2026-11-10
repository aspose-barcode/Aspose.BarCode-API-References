---
title: "Κλάση QrParameters"
second_title: "Αναφορά API του Aspose.BarCode για .NET"
description: "Κλάση Aspose.BarCode.Generation.QrParameters. Παράμετροι QR"
type: docs
weight: 1650
url: /el/net/aspose.barcode.generation/qrparameters/
---
## QrParameters class

Παράμετροι QR.

```csharp
public class QrParameters
```

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [AspectRatio](../../aspose.barcode.generation/qrparameters/aspectratio/) { get; set; } | Αναλογία Ύψος/Πλάτος του 2D BarCode μονάδας. |
| [ECIEncoding](../../aspose.barcode.generation/qrparameters/eciencoding/) { get; set; } | Αναγνωριστικά Επεκταμένης Ερμηνείας Καναλιού (Extended Channel Interpretation Identifiers). Χρησιμοποιούνται για να ενημερώνουν τον αναγνώστη barcode λεπτομέρειες σχετικά με τις χρησιμοποιημένες αναφορές για την κωδικοποίηση των δεδομένων στο σύμβολο. Η τρέχουσα υλοποίηση περιλαμβάνει όλες τις γνωστές κωδικοποιήσεις χαρακτήρων. Δεν υποστηρίζεται από το MicroQR. |
| [EncodeGS1SeparatorInByteMode](../../aspose.barcode.generation/qrparameters/encodegs1separatorinbytemode/) { get; set; } | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν οι ειδικοί χαρακτήρες GS1 πρέπει να κωδικοποιηθούν σε λειτουργία Byte για τους κωδικούς QR και RectMicroQR. |
| [EncodeMode](../../aspose.barcode.generation/qrparameters/encodemode/) { get; set; } | Τύπος συμβολισμού QR για τη λειτουργία κωδικοποίησης του BarCode. Προεπιλεγμένη τιμή: QREncodeMode.Auto. |
| [ErrorLevel](../../aspose.barcode.generation/qrparameters/errorlevel/) { get; set; } | Επίπεδο διόρθωσης σφαλμάτων Reed-Solomon για τους κωδικούς QR, MicroQR και RectMicroQR. Από χαμηλό προς υψηλό: LevelL, LevelM, LevelQ, LevelH. Δείτε το QRErrorLevel. |
| [MicroQRVersion](../../aspose.barcode.generation/qrparameters/microqrversion/) { get; set; } | Έκδοση του κώδικα MicroQR. Από την έκδοση M1 έως την έκδοση M4. Η προεπιλεγμένη τιμή είναι MicroQRVersion.Auto. |
| [RectMicroQrVersion](../../aspose.barcode.generation/qrparameters/rectmicroqrversion/) { get; set; } | Έκδοση του κώδικα RectMicroQR. Από την έκδοση R7x59 έως την έκδοση R17x139. Η προεπιλεγμένη τιμή είναι RectMicroQRVersion.Auto. |
| [StructuredAppend](../../aspose.barcode.generation/qrparameters/structuredappend/) { get; set; } | Παράμετροι δομημένης προσθήκης QR. Η λειτουργία δομημένης προσθήκης δεν υποστηρίζεται από τους κωδικούς MicroQR και RectMicroQR. |
| [Version](../../aspose.barcode.generation/qrparameters/version/) { get; set; } | Έκδοση του κώδικα QR. Από Version1 έως Version40. Η προεπιλεγμένη τιμή είναι QRVersion.Auto. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| override [ToString](../../aspose.barcode.generation/qrparameters/tostring/)() | Επιστρέφει μια αναγνώσιμη από άνθρωπο αναπαράσταση συμβολοσειράς αυτού του `QrParameters`. |

### Δείτε επίσης

* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


