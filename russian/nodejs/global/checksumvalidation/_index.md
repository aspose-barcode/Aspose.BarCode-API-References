---
title: "ChecksumValidation"
linktitle: "ChecksumValidation"
second_title: "Aspose.BarCode для Node.js через Java справка API"
description: "Включить проверку контрольной суммы при распознавании 1D штрихкодов."
type: docs
weight: 100
url: /ru/nodejs/global/checksumvalidation/
---

## ChecksumValidation

Включить проверку контрольной суммы при распознавании 1D штрихкодов. По умолчанию считается «Да» для символогий, которым обязательна контрольная сумма, и «Нет», где контрольная сумма возможна только. Контрольная сумма никогда не используется: Codabar Контрольная сумма возможна: Code39 Standard/Extended, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, DeutschePostIdentcode, DeutschePostLeitcode, VIN Контрольная сумма всегда используется: остальные символогии Этот пример демонстрирует влияние ChecksumValidation на качество распознавания и результаты \\code generator = BarcodeGenerator(EncodeTypes.EAN_13, \"1234567890128\") generator.save(\"test.png\", BarCodeImageFormat.PNG) reader = Recognition.BarCodeReader(\"test.png\", None, DecodeType.EAN_13) #checksum disabled reader.setChecksumValidation(ChecksumValidation.OFF) for result in reader.readBarCodes(): print(\"BarCode CodeText: \" + result.getCodeText()) print(\"BarCode Value: \" + result.getExtended().getOneD().getValue()) print(\"BarCode Checksum: \" + result.getExtended().getOneD().getCheckSum()) \\endcode \\code reader = Recognition.BarCodeReader(\"test.png\", None, DecodeType.EAN_13) #checksum enabled reader.setChecksumValidation(ChecksumValidation.ON) for result in reader.readBarCodes(): print(\"BarCode CodeText: \" + result.getCodeText()) print(\"BarCode Value: \" + result.getExtended().getOneD().getValue()) print(\"BarCode Checksum: \" + result.getExtended().getOneD().getCheckSum()) \\endcode

## Значения

| Имя | Описание |
| --- | --- |
| MOD_10 | Указывает алгоритм Mod 10 для Codabar. |
| MOD_16 | Указывает алгоритм Mod 16 для Codabar (рекомендовано AIIM). |
