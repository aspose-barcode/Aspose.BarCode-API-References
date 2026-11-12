---
title: "QrParameters"
linktitle: "QrParameters"
second_title: "Αναφορά API του Aspose.BarCode για Node.js μέσω Java"
description: "Παράμετροι QR."
type: docs
weight: 830
url: /el/nodejs/aspose.barcode/qrparameters/
---

## QrParameters class

Παράμετροι QR.

```js
new QrParameters()
```

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [getAspectRatio()](#getaspectratio) | Λόγος ύψους/πλάτους του μονάδας 2D BarCode. |
| [getECIEncoding()](#geteciencoding) | Αναγνωριστικά Εκτεταμένης Ερμηνείας Καναλιού. Χρησιμοποιείται για να ενημερώσει τον αναγνώστη barcode λεπτομέρειες σχετικά με τις χρησιμοποιημένες αναφορές για |
| [getEncodeGS1SeparatorInByteMode()](#getencodegs1separatorinbytemode) | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν οι ειδικοί χαρακτήρες GS1 πρέπει να κωδικοποιούνται σε λειτουργία Byte για QR και RectMicroQR barcode |
| [getEncodeMode()](#getencodemode) | Τύπος συμβολισμού QR της λειτουργίας κωδικοποίησης του BarCode. Προεπιλεγμένη τιμή: QREncodeMode.Auto. |
| [getErrorLevel()](#geterrorlevel) | Επίπεδο διόρθωσης σφαλμάτων Reed-Solomon για QR, MicroQR και RectMicroQR barcode. Από χαμηλό προς υψηλό: LevelL, LevelM, LevelQ |
| [getMicroQRVersion()](#getmicroqrversion) | Έκδοση του MicroQR Code. Από την έκδοση M1 έως την έκδοση M4. Προεπιλεγμένη τιμή είναι MicroQRVersion.Auto. |
| [getQrECIEncoding()](#getqreciencoding) ~~(deprecated)~~ | Αναγνωριστικά Εκτεταμένης Ερμηνείας Καναλιού. Χρησιμοποιείται για να ενημερώσει τον αναγνώστη barcode λεπτομέρειες σχετικά με τις χρησιμοποιημένες αναφορές για |
| [getQrEncodeMode()](#getqrencodemode) | Τύπος συμβολισμού QR της λειτουργίας κωδικοποίησης του BarCode. Προεπιλεγμένη τιμή: QREncodeMode.AUTO. |
| [getQrEncodeType()](#getqrencodetype) ~~(deprecated)~~ | Λειτουργία επιλογέα QR / MicroQR. Επιλέξτε ForceQR για τυπικά σύμβολα QR, Auto για MicroQR. |
| [getQrErrorLevel()](#getqrerrorlevel) ~~(deprecated)~~ | Επίπεδο διόρθωσης σφαλμάτων Reed-Solomon για QR barcode. Από χαμηλό προς υψηλό: LEVEL_L, LEVEL_M, LEVEL_Q, LEVEL_H. δείτε QRError |
| [getQrVersion()](#getqrversion) ~~(deprecated)~~ | Έκδοση του QR Code. Από Version1 έως Version40 για QR code και από M1 έως M4 για MicroQr. Προεπιλεγμένη τιμή είναι QRVersion.AUT |
| [getRectMicroQrVersion()](#getrectmicroqrversion) | Έκδοση του RectMicroQR Code. Από την έκδοση R7x59 έως την έκδοση R17x139. Προεπιλεγμένη τιμή είναι RectMicroQRVersion.Auto. |
| [getStructuredAppend()](#getstructuredappend) | Παράμετροι QR structured append. |
| [getVersion()](#getversion) | Έκδοση του QR Code. Από Version1 έως Version40. Προεπιλεγμένη τιμή είναι QRVersion.Auto. |
| [setAspectRatio()](#setaspectratio) | Λόγος ύψους/πλάτους του μονάδας 2D BarCode. |
| [setECIEncoding()](#seteciencoding) | Αναγνωριστικά Εκτεταμένης Ερμηνείας Καναλιού. Χρησιμοποιείται για να ενημερώσει τον αναγνώστη barcode λεπτομέρειες σχετικά με τις χρησιμοποιημένες αναφορές για |
| [setEncodeGS1SeparatorInByteMode(value)](#setencodegs1separatorinbytemode) | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν οι ειδικοί χαρακτήρες GS1 πρέπει να κωδικοποιούνται σε λειτουργία Byte για QR και RectMicroQR barcode |
| [setEncodeMode()](#setencodemode) | Τύπος συμβολισμού QR της λειτουργίας κωδικοποίησης του BarCode. Προεπιλεγμένη τιμή: QREncodeMode.Auto. |
| [setErrorLevel()](#seterrorlevel) | Επίπεδο διόρθωσης σφαλμάτων Reed-Solomon για QR, MicroQR και RectMicroQR barcode. Από χαμηλό προς υψηλό: LevelL, LevelM, LevelQ |
| [setMicroQRVersion()](#setmicroqrversion) | Έκδοση του MicroQR Code. Από την έκδοση M1 έως την έκδοση M4. Προεπιλεγμένη τιμή είναι MicroQRVersion.Auto. |
| [setQrECIEncoding()](#setqreciencoding) ~~(deprecated)~~ | Αναγνωριστικά Εκτεταμένης Ερμηνείας Καναλιού. Χρησιμοποιείται για να ενημερώσει τον αναγνώστη barcode λεπτομέρειες σχετικά με τις χρησιμοποιημένες αναφορές για |
| [setQrEncodeMode()](#setqrencodemode) ~~(deprecated)~~ | Τύπος συμβολισμού QR της λειτουργίας κωδικοποίησης του BarCode. Προεπιλεγμένη τιμή: QREncodeMode.AUTO. |
| [setQrEncodeType()](#setqrencodetype) ~~(deprecated)~~ | Λειτουργία επιλογέα QR / MicroQR. Επιλέξτε ForceQR για τυπικά σύμβολα QR, Auto για MicroQR. |
| [setQrErrorLevel()](#setqrerrorlevel) ~~(deprecated)~~ | Επίπεδο διόρθωσης σφαλμάτων Reed-Solomon για QR barcode. Από χαμηλό προς υψηλό: LEVEL_L, LEVEL_M, LEVEL_Q, LEVEL_H. δείτε QRError |
| [setQrVersion()](#setqrversion) ~~(deprecated)~~ | Έκδοση του QR Code. Από Version1 έως Version40 για QR code και από M1 έως M4 για MicroQr. Προεπιλεγμένη τιμή είναι QRVersion.AUT |
| [setRectMicroQrVersion()](#setrectmicroqrversion) | Έκδοση του RectMicroQR Code. Από την έκδοση R7x59 έως την έκδοση R17x139. Προεπιλεγμένη τιμή είναι RectMicroQRVersion.Auto. |
| [setStructuredAppend()](#setstructuredappend) | Παράμετροι QR structured append. |
| [setVersion()](#setversion) | Έκδοση του QR Code. Από Version1 έως Version40. Προεπιλεγμένη τιμή είναι QRVersion.Auto. |
| [toString()](#tostring) | Επιστρέφει μια αναγνώσιμη από άνθρωπο αναπαράσταση συμβολοσειράς αυτού του QrParameters. |

### getAspectRatio() {#getaspectratio}

Λόγος ύψους/πλάτους του μονάδας 2D BarCode.

### getECIEncoding() {#geteciencoding}

Αναγνωριστικά Επεκταμένης Ερμηνείας Καναλιού. Χρησιμοποιείται για να ενημερώσει τον αναγνώστη barcode λεπτομέρειες σχετικά με τις χρησιμοποιημένες αναφορές για την κωδικοποίηση των δεδομένων στο σύμβολο. Η τρέχουσα υλοποίηση περιλαμβάνει όλες τις γνωστές κωδικοποιήσεις συνόλων χαρακτήρων. Δεν υποστηρίζεται από MicroQR.

### getEncodeGS1SeparatorInByteMode() {#getencodegs1separatorinbytemode}

Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν οι ειδικοί χαρακτήρες GS1 πρέπει να κωδικοποιούνται σε λειτουργία Byte για QR και RectMicroQR barcode. Εάν είναι ψευδής, οι διαχωριστές GS1 μπορεί να κωδικοποιηθούν ως '%' σε αλφαριθμητική λειτουργία σύμφωνα με την προδιαγραφή QR. Εάν είναι αληθής, οι διαχωριστές ομάδας GS1 κωδικοποιούνται σε λειτουργία Byte ως ο χαρακτήρας 0x1D, και οι χαρακτήρες '%' επίσης κωδικοποιούνται σε λειτουργία Byte για να διατηρηθούν ως δεδομένα. Αυτή η επιλογή μπορεί να βελτιώσει τη συμβατότητα με αποκωδικοποιητές που αναμένουν διαχωριστές ομάδας GS1 επιπέδου byte και αποτρέπει τους χαρακτήρες δεδομένων '%' από το να ερμηνευτούν ως διαχωριστές GS1.

**Returns:** a value indicating whether GS1 special characters should be encoded in Byte mode for QR and RectMicroQR barcodes.

### getEncodeMode() {#getencodemode}

Τύπος συμβολισμού QR της λειτουργίας κωδικοποίησης του BarCode. Προεπιλεγμένη τιμή: QREncodeMode.Auto.

### getErrorLevel() {#geterrorlevel}

Επίπεδο διόρθωσης σφαλμάτων Reed-Solomon για QR, MicroQR και RectMicroQR barcode. Από χαμηλό προς υψηλό: LevelL, LevelM, LevelQ, LevelH. Δείτε QRErrorLevel.

### getMicroQRVersion() {#getmicroqrversion}

Έκδοση του MicroQR Code. Από την έκδοση M1 έως την έκδοση M4. Προεπιλεγμένη τιμή είναι MicroQRVersion.Auto.

### getQrECIEncoding() {#getqreciencoding}

> **Deprecated.** See method description for replacement.

Αναγνωριστικά Επεκταμένης Ερμηνείας Καναλιού. Χρησιμοποιείται για να ενημερώσει τον αναγνώστη barcode λεπτομέρειες σχετικά με τις χρησιμοποιημένες αναφορές για την κωδικοποίηση των δεδομένων στο σύμβολο. Η τρέχουσα υλοποίηση αποτελεί όλες τις γνωστές κωδικοποιήσεις συνόλων χαρακτήρων.

### getQrEncodeMode() {#getqrencodemode}

Τύπος συμβολισμού QR της λειτουργίας κωδικοποίησης του BarCode. Προεπιλεγμένη τιμή: QREncodeMode.AUTO.

### getQrEncodeType() {#getqrencodetype}

> **Deprecated.** See method description for replacement.

Λειτουργία επιλογέα QR / MicroQR. Επιλέξτε ForceQR για τυπικά σύμβολα QR, Auto για MicroQR.

### getQrErrorLevel() {#getqrerrorlevel}

> **Deprecated.** See method description for replacement.

Επίπεδο διόρθωσης σφαλμάτων Reed-Solomon για QR barcode. Από χαμηλό προς υψηλό: LEVEL_L, LEVEL_M, LEVEL_Q, LEVEL_H. δείτε QRErrorLevel.

### getQrVersion() {#getqrversion}

> **Deprecated.** See method description for replacement.

Έκδοση του QR Code. Από Version1 έως Version40 για QR code και από M1 έως M4 για MicroQr. Προεπιλεγμένη τιμή είναι QRVersion.AUTO.

### getRectMicroQrVersion() {#getrectmicroqrversion}

Έκδοση του RectMicroQR Code. Από την έκδοση R7x59 έως την έκδοση R17x139. Προεπιλεγμένη τιμή είναι RectMicroQRVersion.Auto.

### getStructuredAppend() {#getstructuredappend}

Παράμετροι QR structured append.

### getVersion() {#getversion}

Έκδοση του QR Code. Από Version1 έως Version40. Προεπιλεγμένη τιμή είναι QRVersion.Auto.

### setAspectRatio() {#setaspectratio}

Λόγος ύψους/πλάτους του μονάδας 2D BarCode.

### setECIEncoding() {#seteciencoding}

Αναγνωριστικά Επεκταμένης Ερμηνείας Καναλιού. Χρησιμοποιείται για να ενημερώσει τον αναγνώστη barcode λεπτομέρειες σχετικά με τις χρησιμοποιημένες αναφορές για την κωδικοποίηση των δεδομένων στο σύμβολο. Η τρέχουσα υλοποίηση περιλαμβάνει όλες τις γνωστές κωδικοποιήσεις συνόλων χαρακτήρων. Δεν υποστηρίζεται από MicroQR.

### setEncodeGS1SeparatorInByteMode(value) {#setencodegs1separatorinbytemode}

Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν οι ειδικοί χαρακτήρες GS1 πρέπει να κωδικοποιούνται σε λειτουργία Byte για QR και RectMicroQR barcode. Εάν είναι ψευδής, οι διαχωριστές GS1 μπορεί να κωδικοποιηθούν ως '%' σε αλφαριθμητική λειτουργία σύμφωνα με την προδιαγραφή QR. Εάν είναι αληθής, οι διαχωριστές ομάδας GS1 κωδικοποιούνται σε λειτουργία Byte ως ο χαρακτήρας 0x1D, και οι χαρακτήρες '%' επίσης κωδικοποιούνται σε λειτουργία Byte για να διατηρηθούν ως δεδομένα. Αυτή η επιλογή μπορεί να βελτιώσει τη συμβατότητα με αποκωδικοποιητές που αναμένουν διαχωριστές ομάδας GS1 επιπέδου byte και αποτρέπει τους χαρακτήρες δεδομένων '%' από το να ερμηνευτούν ως διαχωριστές GS1.

| Παράμετρος | Περιγραφή |
| --- | --- |
| τιμή | μια τιμή που υποδεικνύει εάν οι ειδικοί χαρακτήρες GS1 πρέπει να κωδικοποιούνται σε λειτουργία Byte για QR και RectMicroQR barcode. |

### setEncodeMode() {#setencodemode}

Τύπος συμβολισμού QR της λειτουργίας κωδικοποίησης του BarCode. Προεπιλεγμένη τιμή: QREncodeMode.Auto.

### setErrorLevel() {#seterrorlevel}

Επίπεδο διόρθωσης σφαλμάτων Reed-Solomon για QR, MicroQR και RectMicroQR barcode. Από χαμηλό προς υψηλό: LevelL, LevelM, LevelQ, LevelH. Δείτε QRErrorLevel.

### setMicroQRVersion() {#setmicroqrversion}

Έκδοση του MicroQR Code. Από την έκδοση M1 έως την έκδοση M4. Προεπιλεγμένη τιμή είναι MicroQRVersion.Auto.

### setQrECIEncoding() {#setqreciencoding}

> **Deprecated.** See method description for replacement.

Αναγνωριστικά Επεκταμένης Ερμηνείας Καναλιού. Χρησιμοποιείται για να ενημερώσει τον αναγνώστη barcode λεπτομέρειες σχετικά με τις χρησιμοποιημένες αναφορές για την κωδικοποίηση των δεδομένων στο σύμβολο. Η τρέχουσα υλοποίηση αποτελεί όλες τις γνωστές κωδικοποιήσεις συνόλων χαρακτήρων.

### setQrEncodeMode() {#setqrencodemode}

> **Deprecated.** See method description for replacement.

Τύπος συμβολισμού QR της λειτουργίας κωδικοποίησης του BarCode. Προεπιλεγμένη τιμή: QREncodeMode.AUTO.

### setQrEncodeType() {#setqrencodetype}

> **Deprecated.** See method description for replacement.

Λειτουργία επιλογέα QR / MicroQR. Επιλέξτε ForceQR για τυπικά σύμβολα QR, Auto για MicroQR.

### setQrErrorLevel() {#setqrerrorlevel}

> **Deprecated.** See method description for replacement.

Επίπεδο διόρθωσης σφαλμάτων Reed-Solomon για QR barcode. Από χαμηλό προς υψηλό: LEVEL_L, LEVEL_M, LEVEL_Q, LEVEL_H. δείτε QRErrorLevel.

### setQrVersion() {#setqrversion}

> **Deprecated.** See method description for replacement.

Έκδοση του QR Code. Από Version1 έως Version40 για QR code και από M1 έως M4 για MicroQr. Προεπιλεγμένη τιμή είναι QRVersion.AUTO.

### setRectMicroQrVersion() {#setrectmicroqrversion}

Έκδοση του RectMicroQR Code. Από την έκδοση R7x59 έως την έκδοση R17x139. Προεπιλεγμένη τιμή είναι RectMicroQRVersion.Auto.

### setStructuredAppend() {#setstructuredappend}

Παράμετροι QR structured append.

### setVersion() {#setversion}

Έκδοση του QR Code. Από Version1 έως Version40. Προεπιλεγμένη τιμή είναι QRVersion.Auto.

### toString() {#tostring}

Επιστρέφει μια αναγνώσιμη από άνθρωπο αναπαράσταση συμβολοσειράς αυτού του QrParameters.

**Returns:** A string that represents this QrParameters.
