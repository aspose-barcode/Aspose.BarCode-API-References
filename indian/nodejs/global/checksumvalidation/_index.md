---
title: "ChecksumValidation"
linktitle: "ChecksumValidation"
second_title: "Aspose.BarCode के लिए Node.js via Java API संदर्भ"
description: "1D बारकोड की पहचान के दौरान चेकसम सत्यापन सक्षम करें।"
type: docs
weight: 100
url: /hi/nodejs/global/checksumvalidation/
---

## ChecksumValidation

1D बारकोड की पहचान के दौरान चेकसम सत्यापन सक्षम करें। डिफ़ॉल्ट रूप से उन सिम्बोलॉजीज़ के लिए हाँ माना जाता है जिनमें चेकसम अनिवार्य है, और जहाँ केवल चेकसम संभव है वहाँ नहीं। चेकसम कभी उपयोग नहीं किया जाता: Codabar। चेकसम संभव है: Code39 Standard/Extended, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, DeutschePostIdentcode, DeutschePostLeitcode, VIN। चेकसम हमेशा उपयोग किया जाता है: शेष सिम्बोलॉजीज़। यह उदाहरण चेकसम वैधता का पहचान गुणवत्ता और परिणामों पर प्रभाव दर्शाता है। \code generator = BarcodeGenerator(EncodeTypes.EAN_13, "1234567890128") generator.save("test.png", BarCodeImageFormat.PNG) reader = Recognition.BarCodeReader("test.png", None, DecodeType.EAN_13) #checksum disabled reader.setChecksumValidation(ChecksumValidation.OFF) for result in reader.readBarCodes(): print("BarCode CodeText: " + result.getCodeText()) print("BarCode Value: " + result.getExtended().getOneD().getValue()) print("BarCode Checksum: " + result.getExtended().getOneD().getCheckSum()) \endcode \code reader = Recognition.BarCodeReader("test.png", None, DecodeType.EAN_13) #checksum enabled reader.setChecksumValidation(ChecksumValidation.ON) for result in reader.readBarCodes(): print("BarCode CodeText: " + result.getCodeText()) print("BarCode Value: " + result.getExtended().getOneD().getValue()) print("BarCode Checksum: " + result.getExtended().getOneD().getCheckSum()) \endcode

## मान

| नाम | विवरण |
| --- | --- |
| MOD_10 | Codabar के लिए Mod 10 एल्गोरिदम निर्दिष्ट करता है। |
| MOD_16 | Codabar के लिए Mod 16 एल्गोरिदम निर्दिष्ट करता है (सिफारिश किया गया AIIM)। |
