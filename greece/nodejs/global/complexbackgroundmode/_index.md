---
title: "ComplexBackgroundMode"
linktitle: "ComplexBackgroundMode"
second_title: "Αναφορά API του Aspose.BarCode για Node.js μέσω Java"
description: "Λειτουργία που ενεργοποιεί ή απενεργοποιεί την πρόσθετη αναγνώριση χρωματικών barcode σε χρωματικές εικόνες."
type: docs
weight: 160
url: /el/nodejs/global/complexbackgroundmode/
---

## ComplexBackgroundMode

Λειτουργία που ενεργοποιεί ή απενεργοποιεί την πρόσθετη αναγνώριση χρωματικών barcode σε χρωματικές εικόνες. Αυτό το παράδειγμα δείχνει πώς να χρησιμοποιήσετε τη λειτουργία ComplexBackground let reader = new BarCodeReader("test.png", null, [DecodeType.CODE_39_FULL_ASCII, DecodeType.CODE_128]); reader.getQualitySettings().setComplexBackground(ComplexBackgroundMode.ENABLED); let results = reader.readBarCodes(); for(let i = 0; i < results.length; i++) { let result = results[i]; console.log("BarCode CodeText: " + result.getCodeText()); }

## Τιμές

| Όνομα | Περιγραφή |
| --- | --- |
| C_TABLE | Χρησιμοποιήστε το C_TABLE για την ερμηνεία των πληροφοριών πελάτη. Επιτρέπει A..Z, a..z, 1..9, κενό και το σύμβολο #. |
| N_TABLE | Χρησιμοποιήστε το N_TABLE για την ερμηνεία των πληροφοριών πελάτη. Επιτρέπει ψηφία. |
| OTHER | Μην ερμηνεύετε τις πληροφορίες πελάτη. Επιτρέπει μόνο το σύμβολο 0, 1, 2 ή 3. |
