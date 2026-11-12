---
title: "InverseImageMode"
linktitle: "InverseImageMode"
second_title: "Αναφορά API του Aspose.BarCode για Node.js μέσω Java"
description: "Λειτουργία που ενεργοποιεί ή απενεργοποιεί την πρόσθετη αναγνώριση κωδικών barcode σε εικόνες με αντιστροφή χρωμάτων (λαμπρότητα)."
type: docs
weight: 370
url: /el/nodejs/global/inverseimagemode/
---

## InverseImageMode

Λειτουργία που ενεργοποιεί ή απενεργοποιεί την πρόσθετη αναγνώριση γραμμικών κωδίκων σε εικόνες με αντιστροφή χρωμάτων (φωτεινότητα). Αυτό το παράδειγμα δείχνει πώς να χρησιμοποιήσετε τη λειτουργία InverseImage let reader = new BarCodeReader("test.png", null, [DecodeType.CODE_39_FULL_ASCII, DecodeType.CODE_128]); reader.getQualitySettings().setInverseImage(InverseImageMode.ENABLED); let results = reader.readBarCodes(); for(let i = 0; i < results.length; i++) { let result = results[i]; console.log("BarCode CodeText: " + result.getCodeText()); }

## Τιμές

| Όνομα | Περιγραφή |
| --- | --- |
| NONE | ΧΩΡΙΣ περίγραμμα που περιβάλλει τον barcode |
| ΠΛΑΙΣΙΟ | ΠΛΑΙΣΙΟ που περιβάλλει τον barcode |
| ΓΡΑΜΜΗ | Δύο οριζόντιες γραμμές που περιβάλλουν τον barcode |
| ΠΛΑΙΣΙΟ_ΕΞΩ | ΠΛΑΙΣΙΟ που περιβάλλει τον barcode |
| ΓΡΑΜΜΗ_ΕΞΩ | Δύο οριζόντιες γραμμές που περιβάλλουν τον barcode |
