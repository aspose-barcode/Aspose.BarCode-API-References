---
title: "ChecksumValidation"
linktitle: "ChecksumValidation"
second_title: "Référence de l'API Aspose.BarCode pour Node.js via Java"
description: "Activer la validation du checksum lors de la reconnaissance des codes-barres 1D."
type: docs
weight: 100
url: /fr/nodejs/global/checksumvalidation/
---

## ChecksumValidation

Activer la validation du checksum lors de la reconnaissance des codes-barres 1D. La valeur par défaut est considérée comme Oui pour les symbologies qui doivent contenir un checksum, et comme Non lorsque le checksum n'est possible que facultativement. Checksum jamais utilisé : Codabar. Checksum possible : Code39 Standard/Extended, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, DeutschePostIdentcode, DeutschePostLeitcode, VIN. Checksum toujours utilisé : le reste des symbologies. Cet exemple montre l'influence de ChecksumValidation sur la qualité et les résultats de la reconnaissance \code generator = BarcodeGenerator(EncodeTypes.EAN_13, "1234567890128") generator.save("test.png", BarCodeImageFormat.PNG) reader = Recognition.BarCodeReader("test.png", None, DecodeType.EAN_13) #checksum disabled reader.setChecksumValidation(ChecksumValidation.OFF) for result in reader.readBarCodes(): print("BarCode CodeText: " + result.getCodeText()) print("BarCode Value: " + result.getExtended().getOneD().getValue()) print("BarCode Checksum: " + result.getExtended().getOneD().getCheckSum()) \endcode \code reader = Recognition.BarCodeReader("test.png", None, DecodeType.EAN_13) #checksum enabled reader.setChecksumValidation(ChecksumValidation.ON) for result in reader.readBarCodes(): print("BarCode CodeText: " + result.getCodeText()) print("BarCode Value: " + result.getExtended().getOneD().getValue()) print("BarCode Checksum: " + result.getExtended().getOneD().getCheckSum()) \endcode

## Valeurs

| Nom | Description |
| --- | --- |
| MOD_10 | Spécifie l'algorithme Mod 10 pour Codabar. |
| MOD_16 | Spécifie l'algorithme Mod 16 pour Codabar (recommandé AIIM). |
