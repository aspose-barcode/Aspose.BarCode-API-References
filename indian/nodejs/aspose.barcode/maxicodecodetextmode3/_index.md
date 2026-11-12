---
title: "MaxiCodeCodetextMode3"
linktitle: "MaxiCodeCodetextMode3"
second_title: "Aspose.BarCode के लिए Node.js via Java API संदर्भ"
description: "मोड 3 के लिए MaxiCode कोड में एम्बेडेड टेक्स्ट को एन्कोड और डिकोड करने के लिए क्लास।"
type: docs
weight: 620
url: /hi/nodejs/aspose.barcode/maxicodecodetextmode3/
---

## MaxiCodeCodetextMode3 class

क्लास जो MaxiCode कोड में एम्बेडेड टेक्स्ट को एन्कोड और डिकोड करने के लिए है मोड 3 के लिए। यह उदाहरण दिखाता है कि कैसे MaxiCode कोडटेक्स्ट को मोड 3 के लिए एन्कोड और डिकोड किया जाता है।

```js
new MaxiCodeCodetextMode3()
```

**Example:**

```js
//Mode 3 with standart second message
 let maxiCodeCodetext = new MaxiCodeCodetextMode3();
 maxiCodeCodetext.setPostalCode("B1050");
 maxiCodeCodetext.setCountryCode(056);
 maxiCodeCodetext.setServiceCategory(999);
 let MaxiCodeStandardSecondMessage = new MaxiCodeStandardSecondMessage();
 MaxiCodeStandardSecondMessage.setMessage("Test message");
 maxiCodeCodetext.setSecondMessage(MaxiCodeStandardSecondMessage);
 let complexGenerator = new ComplexBarcodeGenerator(maxiCodeCodetext);
 complexGenerator.generateBarCodeImage(BarcodeImageFormat.PNG);
```

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [getMode()](#getmode) | MaxiCode मोड प्राप्त करता है। |

### getMode() {#getmode}

MaxiCode मोड प्राप्त करता है।

**Returns:** MaxiCode mode
