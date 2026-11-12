---
title: "AztecExtCodetextBuilder"
linktitle: "AztecExtCodetextBuilder"
second_title: "Aspose.BarCode के लिए Node.js via Java API संदर्भ"
description: "Aztec बारकोड के लिए ExtendedCodetext मोड में ExtendedCodetext जेनरेटर। AztecEncodeMode के ExtendedCodetext मोड के लिए BarcodeGenerator की TwoDDisplayText प्रॉपर्टी का उपयोग करके दृश्यमान टेक्स्ट सेट करें।"
type: docs
weight: 50
url: /hi/nodejs/aspose.barcode/aztecextcodetextbuilder/
---

## AztecExtCodetextBuilder class

Aztec बारकोड के लिए ExtendedCodetext मोड में ExtendedCodetext जेनरेटर। AztecEncodeMode के ExtendedCodetext मोड के लिए BarcodeGenerator की TwoDDisplayText प्रॉपर्टी का उपयोग करके दृश्यमान टेक्स्ट को प्रबंधकीय अक्षरों को हटाते हुए सेट करें। यह उदाहरण दिखाता है कि Extended मोड में AztecExtCodetextBuilder का कैसे उपयोग किया जाता है।

```js
new AztecExtCodetextBuilder()
```

**Example:**

```js
//create codetext
     let textBuilder = new AztecExtCodetextBuilder();
     textBuilder.addECICodetext(ECIEncodings.Win1251, "Will");
     textBuilder.addECICodetext(ECIEncodings.UTF8, "犬Right狗");
     textBuilder.addECICodetext(ECIEncodings.UTF16BE, "犬Power狗");
     textBuilder.addPlainCodetext("Plain text");
     //generate codetext
     let codetext = textBuilder.getExtendedCodetext();
     //generate
     let generator = new BarcodeGenerator(EncodeTypes.AZTEC, codetext);
     generator.getParameters().getBarcode().getCodeTextParameters().setwoDDisplayText("My Text");
     generator.save("test.bmp", BarcodeImageFormat.BMP);
```

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [getExtendedCodetext()](#getextendedcodetext) | Extended codetext सूची से Extended codetext उत्पन्न करता है। |

### getExtendedCodetext() {#getextendedcodetext}

Extended codetext सूची से Extended codetext उत्पन्न करता है।

**Returns:** Extended codetext as string
