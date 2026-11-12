---
title: "ChecksumValidation"
linktitle: "ChecksumValidation"
second_title: "Aspose.BarCode voor Node.js via Java API-referentie"
description: "Schakel checksumvalidatie in tijdens herkenning voor 1D-streepjescodes."
type: docs
weight: 100
url: /nl/nodejs/global/checksumvalidation/
---

## ChecksumValidation

Schakel checksumvalidatie in tijdens herkenning voor 1D-streepjescodes. Standaard wordt behandeld als Ja voor symbologieën die een checksum moeten bevatten, en als Nee waar een checksum alleen mogelijk is. Checksum nooit gebruikt: Codabar Checksum is mogelijk: Code39 Standard/Extended, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, DeutschePostIdentcode, DeutschePostLeitcode, VIN Checksum altijd gebruikt: overige symbologieën Deze voorbeeld toont de invloed van ChecksumValidation op de herkenningskwaliteit en resultaten \code generator = BarcodeGenerator(EncodeTypes.EAN_13, "1234567890128") generator.save("test.png", BarCodeImageFormat.PNG) reader = Recognition.BarCodeReader("test.png", None, DecodeType.EAN_13) #checksum disabled reader.setChecksumValidation(ChecksumValidation.OFF) for result in reader.readBarCodes(): print("BarCode CodeText: " + result.getCodeText()) print("BarCode Value: " + result.getExtended().getOneD().getValue()) print("BarCode Checksum: " + result.getExtended().getOneD().getCheckSum()) \endcode \code reader = Recognition.BarCodeReader("test.png", None, DecodeType.EAN_13) #checksum enabled reader.setChecksumValidation(ChecksumValidation.ON) for result in reader.readBarCodes(): print("BarCode CodeText: " + result.getCodeText()) print("BarCode Value: " + result.getExtended().getOneD().getValue()) print("BarCode Checksum: " + result.getExtended().getOneD().getCheckSum()) \endcode

## Waarden

| Naam | Beschrijving |
| --- | --- |
| MOD_10 | Specificeert Mod 10-algoritme voor Codabar. |
| MOD_16 | Specificeert Mod 16-algoritme voor Codabar (aanbevolen AIIM). |
