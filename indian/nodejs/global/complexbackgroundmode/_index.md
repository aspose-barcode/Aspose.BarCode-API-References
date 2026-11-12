---
title: "ComplexBackgroundMode"
linktitle: "ComplexBackgroundMode"
second_title: "Aspose.BarCode के लिए Node.js via Java API संदर्भ"
description: "रंगीन छवियों पर रंगीन बारकोड की अतिरिक्त पहचान को सक्षम या अक्षम करने वाला मोड।"
type: docs
weight: 160
url: /hi/nodejs/global/complexbackgroundmode/
---

## ComplexBackgroundMode

रंगीन छवियों पर रंगीन बारकोड की अतिरिक्त पहचान को सक्षम या अक्षम करने वाला मोड। यह उदाहरण दिखाता है कि ComplexBackground मोड का उपयोग कैसे करें let reader = new BarCodeReader("test.png", null, [DecodeType.CODE_39_FULL_ASCII, DecodeType.CODE_128]); reader.getQualitySettings().setComplexBackground(ComplexBackgroundMode.ENABLED); let results = reader.readBarCodes(); for(let i = 0; i < results.length; i++) { let result = results[i]; console.log("BarCode CodeText: " + result.getCodeText()); }

## मान

| नाम | विवरण |
| --- | --- |
| C_TABLE | C_TABLE का उपयोग ग्राहक जानकारी की व्याख्या करने के लिए करें। A..Z, a..z, 1..9, स्पेस और # चिन्ह की अनुमति देता है। |
| N_TABLE | N_TABLE का उपयोग ग्राहक जानकारी की व्याख्या करने के लिए करें। अंकों की अनुमति देता है। |
| OTHER | ग्राहक जानकारी की व्याख्या न करें। केवल 0, 1, 2 या 3 प्रतीक की अनुमति है। |
