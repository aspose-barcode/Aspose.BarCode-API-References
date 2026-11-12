---
title: "ChecksumValidation"
linktitle: "ChecksumValidation"
second_title: "Aspose.BarCode für Node.js über Java API-Referenz"
description: "Aktivieren Sie die Prüfsummenvalidierung während der Erkennung von 1D-Strichcodes."
type: docs
weight: 100
url: /de/nodejs/global/checksumvalidation/
---

## ChecksumValidation

Aktivieren Sie die Prüfsummenvalidierung während der Erkennung von 1D-Strichcodes. Standardmäßig wird dies als Ja für Symbologien behandelt, die eine Prüfsumme enthalten müssen, und als Nein, wo eine Prüfsumme nur optional ist. Prüfsumme wird nie verwendet: Codabar Prüfsumme ist möglich: Code39 Standard/Extended, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, DeutschePostIdentcode, DeutschePostLeitcode, VIN Prüfsumme wird immer verwendet: übrige Symbologien Dieses Beispiel zeigt den Einfluss von ChecksumValidation auf die Erkennungsqualität und -ergebnisse \code generator = BarcodeGenerator(EncodeTypes.EAN_13, "1234567890128") generator.save("test.png", BarCodeImageFormat.PNG) reader = Recognition.BarCodeReader("test.png", None, DecodeType.EAN_13) #checksum disabled reader.setChecksumValidation(ChecksumValidation.OFF) for result in reader.readBarCodes(): print("BarCode CodeText: " + result.getCodeText()) print("BarCode Value: " + result.getExtended().getOneD().getValue()) print("BarCode Checksum: " + result.getExtended().getOneD().getCheckSum()) \endcode \code reader = Recognition.BarCodeReader("test.png", None, DecodeType.EAN_13) #checksum enabled reader.setChecksumValidation(ChecksumValidation.ON) for result in reader.readBarCodes(): print("BarCode CodeText: " + result.getCodeText()) print("BarCode Value: " + result.getExtended().getOneD().getValue()) print("BarCode Checksum: " + result.getExtended().getOneD().getCheckSum()) \endcode

## Werte

| Name | Beschreibung |
| --- | --- |
| MOD_10 | Gibt den Mod‑10‑Algorithmus für Codabar an. |
| MOD_16 | Gibt den Mod‑16‑Algorithmus für Codabar an (empfohlenes AIIM). |
