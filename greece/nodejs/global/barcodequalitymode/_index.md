---
title: "BarcodeQualityMode"
linktitle: "BarcodeQualityMode"
second_title: "Αναφορά API του Aspose.BarCode για Node.js μέσω Java"
description: "Λειτουργία που ενεργοποιεί μεθόδους για την αναγνώριση στοιχείων barcode με την επιλεγμένη ποιότητα."
type: docs
weight: 80
url: /el/nodejs/global/barcodequalitymode/
---

## BarcodeQualityMode

Λειτουργία που επιτρέπει στις μεθόδους να αναγνωρίζουν στοιχεία barcode με την επιλεγμένη ποιότητα. Ένα στοιχείο barcode με χαμηλότερη ποιότητα απαιτεί περισσότερες απαιτητικές μεθόδους, κάτι που επιβραδύνει την αναγνώριση. Αυτό το παράδειγμα δείχνει πώς να χρησιμοποιήσετε τη λειτουργία BarcodeQuality let reader = new BarCodeReader("test.png", null, [DecodeType.CODE_39_FULL_ASCII, DecodeType.CODE_128]); reader.getQualitySettings().setBarcodeQuality(BarcodeQualityMode.LOW); let results = reader.readBarCodes(); for(let i = 0; i < results.length; i++) { let result = results[i]; console.log("BarCode CodeText: " + result.getCodeText()); }

## Τιμές

| Όνομα | Περιγραφή |
| --- | --- |
| ΣΤΑΘΕΡΟ | Καθορίζει μια συμπαγή γραμμή. |
| ΔΙΑΚΟΠΗ | Καθορίζει μια γραμμή που αποτελείται από παύλες. |
| ΤΕΛΕ | Καθορίζει μια γραμμή που αποτελείται από τελείες. |
| ΔΙΑΚΟΠΗ_ΤΕΛΕ | Καθορίζει μια γραμμή που αποτελείται από επαναλαμβανόμενο μοτίβο διακοπής-τελείας. |
| ΔΙΑΚΟΠΗ_ΤΕΛΕ_ΤΕΛΕ | Καθορίζει μια γραμμή που αποτελείται από επαναλαμβανόμενο μοτίβο διακοπής-τελείας-τελείας. |
