---
title: "HIBCLICPrimaryDataCodetext"
linktitle: "HIBCLICPrimaryDataCodetext"
second_title: "Aspose.BarCode के लिए Node.js via Java API संदर्भ"
description: "HIBC LIC कोड में एम्बेडेड टेक्स्ट को एन्कोड और डिकोड करने के लिए क्लास, जो प्राथमिक डेटा संग्रहीत करता है।"
type: docs
weight: 460
url: /hi/nodejs/aspose.barcode/hibclicprimarydatacodetext/
---

## HIBCLICPrimaryDataCodetext class

HIBC LIC कोड में एम्बेडेड टेक्स्ट को एन्कोड और डिकोड करने के लिए क्लास, जो प्राथमिक डेटा संग्रहीत करता है। यह उदाहरण दिखाता है कि HIBCLICPrimaryCodetext का उपयोग करके HIBC LIC को कैसे एन्कोड और डिकोड किया जाए।

```js
new HIBCLICPrimaryDataCodetext()
```

**Example:**

```js
let complexCodetext  = new HIBCLICPrimaryCodetext();
complexCodetext.setBarcodeType(EncodeTypes.HIBCQRLIC);
complexCodetext.setData(new PrimaryData());
complexCodetext.getData().setProductOrCatalogNumber("12345");
complexCodetext.getData().setLabelerIdentificationCode("A999");
complexCodetext.getData().setUnitOfMeasureID(1);
let generator = new ComplexBarcodeGenerator(complexCodetext);
let image = generator.generateBarCodeImage(BarCodeImageFormat.PNG);
let reader = new BarCodeReader(image, null, DecodeType.HIBCQRLIC);
reader.readBarCodes();
let codetext = reader.getFoundBarCodes()[0].getCodeText();
let result = ComplexCodetextReader.tryDecodeHIBCLIC(codetext) ;
print("Product or catalog number: " + result.getData().getProductOrCatalogNumber());
print("Labeler identification code: " + result.getData().getLabelerIdentificationCode());
print("Unit of measure ID: " + result.getData().getUnitOfMeasureID());
```

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [equals(obj)](#equals) | `HIBCLICPrimaryDataCodetext` मान के साथ तुलना करने पर यह इंस्टेंस समान है या नहीं, यह दर्शाने वाला मान लौटाता है। |
| [getConstructedCodetext()](#getconstructedcodetext) | कोडटेक्स्ट बनाता है |
| [getData()](#getdata) | प्राथमिक डेटा की पहचान करता है। |
| [hashCode()](#hashcode) | इस उदाहरण के लिए हैश कोड लौटाता है। |
| [initFromString(constructedCodetext)](#initfromstring) | निर्मित कोडटेक्स्ट से उदाहरण को प्रारंभ करता है। |
| [setData()](#setdata) | प्राथमिक डेटा की पहचान करता है। |

### equals(obj) {#equals}

`HIBCLICPrimaryDataCodetext` मान के साथ तुलना करने पर यह इंस्टेंस समान है या नहीं, यह दर्शाने वाला मान लौटाता है।

| पैरामीटर | विवरण |
| --- | --- |
| obj | इस इंस्टेंस से तुलना करने के लिए एक `HIBCLICPrimaryDataCodetext` मान। |

**Returns:** `true ` if obj has the same value as this instance; otherwise, `false `.

### getConstructedCodetext() {#getconstructedcodetext}

कोडटेक्स्ट बनाता है

**Returns:** Constructed codetext

### getData() {#getdata}

प्राथमिक डेटा की पहचान करता है।

### hashCode() {#hashcode}

इस उदाहरण के लिए हैश कोड लौटाता है।

**Returns:** A 32-bit signed integer hash code.

### initFromString(constructedCodetext) {#initfromstring}

निर्मित कोडटेक्स्ट से उदाहरण को प्रारंभ करता है।

| पैरामीटर | विवरण |
| --- | --- |
| constructedCodetext | निर्मित कोडटेक्स्ट। |

### setData() {#setdata}

प्राथमिक डेटा की पहचान करता है।
