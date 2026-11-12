---
title: "ChecksumValidation"
linktitle: "ChecksumValidation"
second_title: "Riferimento API di Aspose.BarCode per Node.js via Java"
description: "Abilita la convalida del checksum durante il riconoscimento per i codici a barre 1D."
type: docs
weight: 100
url: /it/nodejs/global/checksumvalidation/
---

## ChecksumValidation

Abilita la convalida del checksum durante il riconoscimento per i codici a barre 1D. Il valore predefinito è considerato Sì per le simbologie che devono contenere il checksum, e No dove il checksum è solo possibile. Checksum mai usato: Codabar Checksum è possibile: Code39 Standard/Extended, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, DeutschePostIdentcode, DeutschePostLeitcode, VIN Checksum sempre usato: Resto delle simbologie Questo esempio mostra l'influenza di ChecksumValidation sulla qualità e sui risultati del riconoscimento \code generator = BarcodeGenerator(EncodeTypes.EAN_13, "1234567890128") generator.save("test.png", BarCodeImageFormat.PNG) reader = Recognition.BarCodeReader("test.png", None, DecodeType.EAN_13) #checksum disabled reader.setChecksumValidation(ChecksumValidation.OFF) for result in reader.readBarCodes(): print("BarCode CodeText: " + result.getCodeText()) print("BarCode Value: " + result.getExtended().getOneD().getValue()) print("BarCode Checksum: " + result.getExtended().getOneD().getCheckSum()) \endcode \code reader = Recognition.BarCodeReader("test.png", None, DecodeType.EAN_13) #checksum enabled reader.setChecksumValidation(ChecksumValidation.ON) for result in reader.readBarCodes(): print("BarCode CodeText: " + result.getCodeText()) print("BarCode Value: " + result.getExtended().getOneD().getValue()) print("BarCode Checksum: " + result.getExtended().getOneD().getCheckSum()) \endcode

## Valori

| Nome | Descrizione |
| --- | --- |
| MOD_10 | Specifica l'algoritmo Mod 10 per Codabar. |
| MOD_16 | Specifica l'algoritmo Mod 16 per Codabar (AIIM consigliato). |
