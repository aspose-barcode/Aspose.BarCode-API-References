---
title: "DataMatrixExtCodetextBuilder"
linktitle: "DataMatrixExtCodetextBuilder"
second_title: "Aspose.BarCode के लिए Node.js via Java API संदर्भ"
description: "DataMatrixEncodeMode के ExtendedCodetext मोड के लिए 2D DataMatrix बारकोड के लिए विस्तारित कोडटेक्स्ट जेनरेटर //Extended codetext mode //create codetext let textBuil"
type: docs
weight: 340
url: /hi/nodejs/aspose.barcode/datamatrixextcodetextbuilder/
---

## DataMatrixExtCodetextBuilder class

DataMatrixEncodeMode के ExtendedCodetext मोड के लिए 2D DataMatrix बारकोड के लिए विस्तारित कोडटेक्स्ट जेनरेटर //Extended codetext mode //create codetext let textBuilder = new DataMatrixExtCodetextBuilder(); codetextBuilder.addECICodetextWithEncodeMode(ECIEncodings.Win1251, DataMatrixEncodeMode.BYTES, "World"); codetextBuilder.addPlainCodetext("Will"); codetextBuilder.addECICodetext(ECIEncodings.UTF_8, "犬Right狗"); codetextBuilder.addCodetextWithEncodeMode(DataMatrixEncodeMode.C_40, "ABCDE"); //generate codetext let codetext = textBuilder.getExtendedCodetext(); //generate let generator = new BarcodeGenerator(EncodeTypes.DATA_MATRIX, null, codetext); generator.getParameters().getBarcode().getDataMatrix().setDataMatrixEncodeMode(DataMatrixEncodeMode.EXTENDED_CODETEXT); generator.save("test.bmp", BarcodeImageFormat.BMP);

```js
new DataMatrixExtCodetextBuilder()
```

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [addCodetextWithEncodeMode(encodeMode, codetext)](#addcodetextwithencodemode) | परिभाषित एन्कोड मोड के साथ कोडटेक्स्ट को विस्तारित कोडटेक्स्ट आइटम्स में जोड़ता है |
| [addECICodetextWithEncodeMode(ECIEncoding, encodeMode, codetext)](#addecicodetextwithencodemode) | परिभाषित एन्कोड मोड के साथ विस्तारित चैनल पहचानकर्ता के साथ कोडटेक्स्ट जोड़ता है |
| [getExtendedCodetext()](#getextendedcodetext) | Extended codetext सूची से Extended codetext उत्पन्न करता है। |

### addCodetextWithEncodeMode(encodeMode, codetext) {#addcodetextwithencodemode}

परिभाषित एन्कोड मोड के साथ कोडटेक्स्ट को विस्तारित कोडटेक्स्ट आइटम्स में जोड़ता है

| पैरामीटर | विवरण |
| --- | --- |
| encodeMode | एन्कोड मोड मान |
| codetext | विस्तारित कोडटेक्स्ट आइटम के रूप में जोड़ने के लिए यूनिकोड में कोडटेक्स्ट |

### addECICodetextWithEncodeMode(ECIEncoding, encodeMode, codetext) {#addecicodetextwithencodemode}

परिभाषित एन्कोड मोड के साथ विस्तारित चैनल पहचानकर्ता के साथ कोडटेक्स्ट जोड़ता है

| पैरामीटर | विवरण |
| --- | --- |
| ECIEncoding | विस्तारित चैनल पहचानकर्ता |
| encodeMode | एन्कोड मोड मान |
| codetext | परिभाषित एन्कोड मोड के साथ विस्तारित चैनल पहचानकर्ता के साथ विस्तारित कोडटेक्स्ट आइटम के रूप में जोड़ने के लिए यूनिकोड में कोडटेक्स्ट |

### getExtendedCodetext() {#getextendedcodetext}

Extended codetext सूची से Extended codetext उत्पन्न करता है।

**Returns:** Extended codetext as string
