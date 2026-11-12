---
title: "ChecksumValidation"
linktitle: "ChecksumValidation"
second_title: "Αναφορά API του Aspose.BarCode για Node.js μέσω Java"
description: "Ενεργοποιήστε την επαλήθευση αθροίσματος ελέγχου κατά την αναγνώριση για 1D γραμμικούς κώδικες."
type: docs
weight: 100
url: /el/nodejs/global/checksumvalidation/
---

## ChecksumValidation

Ενεργοποιήστε την επαλήθευση αθροίσματος ελέγχου κατά την αναγνώριση για 1D γραμμικούς κώδικες. Η προεπιλογή θεωρείται Ναι για τις συμβολές που πρέπει να περιέχουν άθροισμα ελέγχου, και Όχι όπου το άθροισμα ελέγχου είναι μόνο δυνατό. Το άθροισμα ελέγχου δεν χρησιμοποιείται ποτέ: Codabar Το άθροισμα ελέγχου είναι δυνατό: Code39 Standard/Extended, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, DeutschePostIdentcode, DeutschePostLeitcode, VIN Το άθροισμα ελέγχου χρησιμοποιείται πάντα: Οι υπόλοιπες συμβολές Αυτό το παράδειγμα δείχνει την επίδραση του ChecksumValidation στην ποιότητα και τα αποτελέσματα της αναγνώρισης \code generator = BarcodeGenerator(EncodeTypes.EAN_13, "1234567890128") generator.save("test.png", BarCodeImageFormat.PNG) reader = Recognition.BarCodeReader("test.png", None, DecodeType.EAN_13) #checksum disabled reader.setChecksumValidation(ChecksumValidation.OFF) for result in reader.readBarCodes(): print("BarCode CodeText: " + result.getCodeText()) print("BarCode Value: " + result.getExtended().getOneD().getValue()) print("BarCode Checksum: " + result.getExtended().getOneD().getCheckSum()) \endcode \code reader = Recognition.BarCodeReader("test.png", None, DecodeType.EAN_13) #checksum enabled reader.setChecksumValidation(ChecksumValidation.ON) for result in reader.readBarCodes(): print("BarCode CodeText: " + result.getCodeText()) print("BarCode Value: " + result.getExtended().getOneD().getValue()) print("BarCode Checksum: " + result.getExtended().getOneD().getCheckSum()) \endcode

## Τιμές

| Όνομα | Περιγραφή |
| --- | --- |
| MOD_10 | Καθορίζει τον αλγόριθμο Mod 10 για το Codabar. |
| MOD_16 | Καθορίζει τον αλγόριθμο Mod 16 για Codabar (συνιστάται AIIM). |
