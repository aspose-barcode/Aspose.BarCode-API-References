---
title: "ChecksumValidation"
linktitle: "ChecksumValidation"
second_title: "Referencia de API de Aspose.BarCode para Node.js vía Java"
description: "Habilitar la validación de suma de verificación durante el reconocimiento de códigos de barras 1D."
type: docs
weight: 100
url: /es/nodejs/global/checksumvalidation/
---

## ChecksumValidation

Habilitar la validación de suma de verificación durante el reconocimiento de códigos de barras 1D. Por defecto se trata como Sí para las simbologías que deben contener suma de verificación, y como No donde la suma de verificación solo es posible. Suma de verificación nunca usada: Codabar. Suma de verificación posible: Code39 Standard/Extended, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, DeutschePostIdentcode, DeutschePostLeitcode, VIN. Suma de verificación siempre usada: resto de simbologías. Este ejemplo muestra la influencia de ChecksumValidation en la calidad y resultados del reconocimiento \code generator = BarcodeGenerator(EncodeTypes.EAN_13, "1234567890128") generator.save("test.png", BarCodeImageFormat.PNG) reader = Recognition.BarCodeReader("test.png", None, DecodeType.EAN_13) #checksum disabled reader.setChecksumValidation(ChecksumValidation.OFF) for result in reader.readBarCodes(): print("BarCode CodeText: " + result.getCodeText()) print("BarCode Value: " + result.getExtended().getOneD().getValue()) print("BarCode Checksum: " + result.getExtended().getOneD().getCheckSum()) \endcode \code reader = Recognition.BarCodeReader("test.png", None, DecodeType.EAN_13) #checksum enabled reader.setChecksumValidation(ChecksumValidation.ON) for result in reader.readBarCodes(): print("BarCode CodeText: " + result.getCodeText()) print("BarCode Value: " + result.getExtended().getOneD().getValue()) print("BarCode Checksum: " + result.getExtended().getOneD().getCheckSum()) \endcode

## Valores

| Nombre | Descripción |
| --- | --- |
| MOD_10 | Especifica el algoritmo Mod 10 para Codabar. |
| MOD_16 | Especifica el algoritmo Mod 16 para Codabar (recomendado AIIM). |
