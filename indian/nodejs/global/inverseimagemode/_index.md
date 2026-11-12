---
title: "InverseImageMode"
linktitle: "InverseImageMode"
second_title: "Aspose.BarCode के लिए Node.js via Java API संदर्भ"
description: "वह मोड जो उल्टे रंगों (ल्यूमिनेंस) वाली छवियों पर बारकोड की अतिरिक्त पहचान को सक्षम या अक्षम करता है।"
type: docs
weight: 370
url: /hi/nodejs/global/inverseimagemode/
---

## InverseImageMode

उल्टे रंग (ल्यूमिनेंस) वाली छवियों पर बारकोड की अतिरिक्त पहचान को सक्षम या अक्षम करने वाला मोड। यह उदाहरण InverseImage मोड का उपयोग कैसे करें दिखाता है। let reader = new BarCodeReader("test.png", null, [DecodeType.CODE_39_FULL_ASCII, DecodeType.CODE_128]); reader.getQualitySettings().setInverseImage(InverseImageMode.ENABLED); let results = reader.readBarCodes(); for(let i = 0; i < results.length; i++) { let result = results[i]; console.log("BarCode CodeText: " + result.getCodeText()); }

## मान

| नाम | विवरण |
| --- | --- |
| NONE | बारकोड को घेरने वाली कोई सीमा नहीं |
| FRAME | बारकोड को घेरने वाला FRAME |
| BAR | बारकोड को घेरने वाले दो क्षैतिज BAR |
| FRAME_OUT | बारकोड को घेरने वाला FRAME |
| BAR_OUT | बारकोड को घेरने वाले दो क्षैतिज BAR |
