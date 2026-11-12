---
title: "MaxiCodeExtCodetextBuilder"
linktitle: "MaxiCodeExtCodetextBuilder"
second_title: "Aspose.BarCode के लिए Node.js via Java API संदर्भ"
description: "Extended codetext जेनरेटर MaxiCode बारकोड के लिए, MaxiCodeEncodeMode के ExtendedCodetext Mode के लिए। BarcodeGenerator की TwoDDisplayText प्रॉपर्टी का उपयोग करके दृश्यता सेट करें।"
type: docs
weight: 630
url: /hi/nodejs/aspose.barcode/maxicodeextcodetextbuilder/
---

## MaxiCodeExtCodetextBuilder class

MaxiCode बारकोड के लिए ExtendedCodetext मोड में MaxiCodeEncodeMode के लिए विस्तारित कोडटेक्स्ट जेनरेटर। BarcodeGenerator की TwoDDisplayText प्रॉपर्टी का उपयोग करके दृश्यमान टेक्स्ट सेट करने और प्रबंधकीय अक्षरों को हटाने के लिए। यह उदाहरण दिखाता है कि Extended मोड में MaxiCodeExtCodetextBuilder का उपयोग कैसे करें।

```js
new MaxiCodeExtCodetextBuilder()
```

**Example:**

```js
//create codetext
let textBuilder = new MaxiCodeExtCodetextBuilder();
textBuilder.addECICodetext(ECIEncodings.Win1251, "Will");
textBuilder.addECICodetext(ECIEncodings.UTF8, "犬Right狗");
textBuilder.addECICodetext(ECIEncodings.UTF16BE, "犬Power狗");
textBuilder.addPlainCodetext("Plain text");

//generate codetext
let codetext = textBuilder.getExtendedCodetext();

//generate
let generator = new BarcodeGenerator(EncodeTypes.MAXI_CODE, codetext);
generator.getParameters().getBarcode().getCodeTextParameters().setTwoDDisplayText("My Text");
generator.save("test.bmp", BarcodeImageFormat.BMP);
```

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [getExtendedCodetext()](#getextendedcodetext) | Extended codetext सूची से Extended codetext उत्पन्न करता है। |

### getExtendedCodetext() {#getextendedcodetext}

Extended codetext सूची से Extended codetext उत्पन्न करता है।

**Returns:** Extended codetext as string
