---
title: "Code128EncodeMode"
linktitle: "Code128EncodeMode"
second_title: "Aspose.BarCode के लिए Node.js via Java API संदर्भ"
description: "Code128 बारकोड के लिए एन्कोडिंग मोड।"
type: docs
weight: 130
url: /hi/nodejs/global/code128encodemode/
---

## Code128EncodeMode

Code128 बारकोड के लिए एन्कोडिंग मोड। `Code 128` विनिर्देश। यह कोड दिखाता है कि विभिन्न एन्कोडिंग के साथ code 128 कैसे जेनरेट करें //Generate code 128 with ISO 15417 encoding let generator = new BarcodeGenerator(EncodeTypes.CODE_128, "ABCD1234567890"); generator.getParameters().getBarcode().getCode128().setCode128EncodeMode(Code128EncodeMode.AUTO); generator.save("d:\\code128Auto.png", BarCodeImageFormat.PNG); //Generate code 128 only with Codeset A encoding let generator = new BarcodeGenerator(EncodeTypes.CODE_128, "ABCD1234567890"); generator.getParameters().getBarcode().getCode128().setCode128EncodeMode(Code128EncodeMode.CODE_A); generator.save("d:\\code128CodeA.png", BarCodeImageFormat.PNG);

## मान

| नाम | विवरण |
| --- | --- |
| CODE_SET_A | ASCII अक्षर 00 से 95 (0–9, A–Z और नियंत्रण कोड), विशेष अक्षर, और FNC 1–4 /// |
| CODE_SET_B | ASCII अक्षर 32 से 127 (0–9, A–Z, a–z), विशेष अक्षर, और FNC 1–4 /// |
| CODE_SET_C | 00–99 (एकल कोड पॉइंट के साथ दो अंकों को एन्कोड करता है) और FNC1 /// |
