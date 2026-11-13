---
title: "ChecksumValidation"
linktitle: "ChecksumValidation"
second_title: "Aspose.BarCode för Node.js via Java API-referens"
description: "Aktivera kontrollsummavalidering under igenkänning för 1D-streckkoder."
type: docs
weight: 100
url: /sv/nodejs/global/checksumvalidation/
---

## ChecksumValidation

Aktivera kontrollsummavalidering under igenkänning för 1D-streckkoder. Standard behandlas som Ja för symboler som måste innehålla kontrollsumma, och som Nej där kontrollsumma bara är möjlig. Kontrollsumma används aldrig: Codabar. Kontrollsumma är möjlig: Code39 Standard/Extended, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, DeutschePostIdentcode, DeutschePostLeitcode, VIN. Kontrollsumma används alltid: övriga symboler. Detta exempel visar hur ChecksumValidation påverkar igenkänningskvalitet och resultat \code generator = BarcodeGenerator(EncodeTypes.EAN_13, "1234567890128") generator.save("test.png", BarCodeImageFormat.PNG) reader = Recognition.BarCodeReader("test.png", None, DecodeType.EAN_13) #checksum disabled reader.setChecksumValidation(ChecksumValidation.OFF) for result in reader.readBarCodes(): print("BarCode CodeText: " + result.getCodeText()) print("BarCode Value: " + result.getExtended().getOneD().getValue()) print("BarCode Checksum: " + result.getExtended().getOneD().getCheckSum()) \endcode \code reader = Recognition.BarCodeReader("test.png", None, DecodeType.EAN_13) #checksum enabled reader.setChecksumValidation(ChecksumValidation.ON) for result in reader.readBarCodes(): print("BarCode CodeText: " + result.getCodeText()) print("BarCode Value: " + result.getExtended().getOneD().getValue()) print("BarCode Checksum: " + result.getExtended().getOneD().getCheckSum()) \endcode

## Värden

| Namn | Beskrivning |
| --- | --- |
| MOD_10 | Anger Mod 10-algoritmen för Codabar. |
| MOD_16 | Anger Mod 16-algoritmen för Codabar (rekommenderas av AIIM). |
