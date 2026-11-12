---
title: "BarcodeQualityMode"
linktitle: "BarcodeQualityMode"
second_title: "Aspose.BarCode के लिए Node.js via Java API संदर्भ"
description: "वह मोड जो चयनित गुणवत्ता के साथ बारकोड तत्वों को पहचानने की विधियों को सक्षम करता है।"
type: docs
weight: 80
url: /hi/nodejs/global/barcodequalitymode/
---

## BarcodeQualityMode

वह मोड जो चयनित गुणवत्ता के साथ बारकोड तत्वों को पहचानने की विधियों को सक्षम करता है। निम्न गुणवत्ता वाले बारकोड तत्व को अधिक कठिन विधियों की आवश्यकता होती है, जिससे पहचान धीमी हो जाती है। यह उदाहरण दिखाता है कि BarcodeQuality मोड का उपयोग कैसे करें let reader = new BarCodeReader("test.png", null, [DecodeType.CODE_39_FULL_ASCII, DecodeType.CODE_128]); reader.getQualitySettings().setBarcodeQuality(BarcodeQualityMode.LOW); let results = reader.readBarCodes(); for(let i = 0; i < results.length; i++) { let result = results[i]; console.log("BarCode CodeText: " + result.getCodeText()); }

## मान

| नाम | विवरण |
| --- | --- |
| SOLID | एक ठोस रेखा को निर्दिष्ट करता है। |
| DASH | डैश वाली रेखा को निर्दिष्ट करता है। |
| DOT | डॉट वाली रेखा को निर्दिष्ट करता है। |
| DASH_DOT | डैश-डॉट के दोहराव पैटर्न वाली रेखा को निर्दिष्ट करता है। |
| DASH_DOT_DOT | डैश-डॉट-डॉट के दोहराव पैटर्न वाली रेखा को निर्दिष्ट करता है। |
