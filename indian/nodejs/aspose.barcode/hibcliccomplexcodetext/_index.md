---
title: "HIBCLICComplexCodetext"
linktitle: "HIBCLICComplexCodetext"
second_title: "Aspose.BarCode के लिए Node.js via Java API संदर्भ"
description: "HIBC LIC कोड में एम्बेडेड टेक्स्ट को एन्कोड और डिकोड करने के लिए बेस क्लास।"
type: docs
weight: 450
url: /hi/nodejs/aspose.barcode/hibcliccomplexcodetext/
---

## HIBCLICComplexCodetext class

HIBC LIC कोड में एम्बेडेड टेक्स्ट को एन्कोड और डिकोड करने के लिए बेस क्लास। यह उदाहरण दिखाता है कि कैसे रॉ HIBC LIC कोडटेक्स्ट को HIBCLICComplexCodetext इंस्टेंस में डिकोड किया जाता है।

```js
new HIBCLICComplexCodetext()
```

**Example:**

```js
let reader = new BarCodeReader("c:\\test.png", null, DecodeType.HIBC_AZTEC_LIC);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
    let result = results[i];
   let resultHIBCLICComplexCodetext = ComplexCodetextReader.tryDecodeHIBCLIC(result.getCodeText());
   print("BarCode Type: " + resultMaxiCodeCodetext.getBarcodeType());
   print("BarCode CodeText: " + resultMaxiCodeCodetext.getConstructedCodetext());
}
```

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [getBarcodeType()](#getbarcodetype) | बारकोड प्रकार प्राप्त करता है या सेट करता है। HIBC LIC कोडटेक्स्ट को HIBCCode39LIC, HIBCCode128LIC, HIBCAztecLIC, HIBCDataM का उपयोग करके एन्कोड किया जा सकता है। |
| [getConstructedCodetext()](#getconstructedcodetext) | कोडटेक्स्ट बनाता है |
| [initFromString(constructedCodetext)](#initfromstring) | निर्मित कोडटेक्स्ट से उदाहरण को प्रारंभ करता है। |
| [setBarcodeType()](#setbarcodetype) | बारकोड प्रकार प्राप्त करता है या सेट करता है। HIBC LIC कोडटेक्स्ट को HIBCCode39LIC, HIBCCode128LIC, HIBCAztecLIC, HIBCDataM का उपयोग करके एन्कोड किया जा सकता है। |

### getBarcodeType() {#getbarcodetype}

बारकोड प्रकार प्राप्त करता है या सेट करता है। HIBC LIC कोडटेक्स्ट को HIBCCode39LIC, HIBCCode128LIC, HIBCAztecLIC, HIBCDataMatrixLIC और HIBCQRLIC एन्कोड प्रकारों का उपयोग करके एन्कोड किया जा सकता है। डिफ़ॉल्ट मान: HIBCCode39LIC।

**Returns:** Barcode type.

### getConstructedCodetext() {#getconstructedcodetext}

कोडटेक्स्ट बनाता है

**Returns:** Constructed codetext

### initFromString(constructedCodetext) {#initfromstring}

निर्मित कोडटेक्स्ट से उदाहरण को प्रारंभ करता है।

| पैरामीटर | विवरण |
| --- | --- |
| constructedCodetext | निर्मित कोडटेक्स्ट। |

### setBarcodeType() {#setbarcodetype}

बारकोड प्रकार प्राप्त करता है या सेट करता है। HIBC LIC कोडटेक्स्ट को HIBCCode39LIC, HIBCCode128LIC, HIBCAztecLIC, HIBCDataMatrixLIC और HIBCQRLIC एन्कोड प्रकारों का उपयोग करके एन्कोड किया जा सकता है। डिफ़ॉल्ट मान: HIBCCode39LIC।

**Returns:** Barcode type.
