---
title: "MaxiCodeStructuredCodetext"
linktitle: "MaxiCodeStructuredCodetext"
second_title: "Aspose.BarCode के लिए Node.js via Java API संदर्भ"
description: "मोड 2 और 3 के लिए MaxiCode कोड में एम्बेडेड टेक्स्ट को एन्कोड और डिकोड करने की बेस क्लास।"
type: docs
weight: 700
url: /hi/nodejs/aspose.barcode/maxicodestructuredcodetext/
---

## MaxiCodeStructuredCodetext class

मोड 2 और 3 के लिए MaxiCode कोड में एम्बेडेड टेक्स्ट को एन्कोड और डिकोड करने की बेस क्लास।

```js
new MaxiCodeStructuredCodetext()
```

**Example:**

```js
This sample shows how to decode raw MaxiCode codetext to MaxiCodeStructuredCodetext instance.

 let reader = new BarCodeReader("c:\\test.png", null, DecodeType.MAXI_CODE);
 let results = reader.readBarCodes();
 for(let i = 0; i < results.length; i++)
 {
    let result = results[i];
     let resultMaxiCodeCodetext = ComplexCodetextReader.tryDecodeMaxiCode(result.getExtended().getMaxiCode().getMaxiCodeMode(), result.getCodeText());
     if (resultMaxiCodeCodetext instanceof MaxiCodeStructuredCodetext)
     {
         let maxiCodeStructuredCodetext = resultMaxiCodeCodetext;
         console.log("BarCode Type: " + maxiCodeStructuredCodetext.getPostalCode());
         console.log("MaxiCode mode: " + maxiCodeStructuredCodetext.getCountryCode());
         console.log("BarCode CodeText: " + maxiCodeStructuredCodetext.getServiceCategory());
     }
 }
```

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [equals(obj)](#equals) | एक मान लौटाता है जो दर्शाता है कि यह इंस्टेंस निर्दिष्ट मान के बराबर है या नहीं। |
| [getConstructedCodetext()](#getconstructedcodetext) | कोडटेक्स्ट बनाता है |
| [getCountryCode()](#getcountrycode) | 3 अंकों का देश कोड पहचानता है। |
| [getHashCode()](#gethashcode) | इस उदाहरण के लिए हैश कोड लौटाता है। |
| [getPostalCode()](#getpostalcode) | डाक कोड पहचानता है। मोड 2 में यह 9 अंकों का होना चाहिए या मोड 3 में 6 अल्फ़ान्यूमेरिक प्रतीकों का। |
| [getSecondMessage()](#getsecondmessage) | बारकोड का दूसरा संदेश पहचानता है। |
| [getServiceCategory()](#getservicecategory) | 3 अंकों की सेवा श्रेणी पहचानता है। |
| [initFromString(constructedCodetext)](#initfromstring) | निर्मित कोडटेक्स्ट से उदाहरण को प्रारंभ करता है। |
| [setCountryCode()](#setcountrycode) | 3 अंकों का देश कोड पहचानता है। |
| [setPostalCode()](#setpostalcode) | डाक कोड पहचानता है। मोड 2 में यह 9 अंकों का होना चाहिए या मोड 3 में 6 अल्फ़ान्यूमेरिक प्रतीकों का। |
| [setSecondMessage()](#setsecondmessage) | बारकोड का दूसरा संदेश पहचानता है। |
| [setServiceCategory()](#setservicecategory) | 3 अंकों की सेवा श्रेणी पहचानता है। |

### equals(obj) {#equals}

एक मान लौटाता है जो दर्शाता है कि यह इंस्टेंस निर्दिष्ट मान के बराबर है या नहीं।

| पैरामीटर | विवरण |
| --- | --- |
| obj | इस इंस्टेंस से तुलना करने के लिए एक मान |

**Returns:** true if obj has the same value as this instance; otherwise, false

### getConstructedCodetext() {#getconstructedcodetext}

कोडटेक्स्ट बनाता है

**Returns:** Constructed codetext

### getCountryCode() {#getcountrycode}

3 अंकों का देश कोड पहचानता है।

### getHashCode() {#gethashcode}

इस उदाहरण के लिए हैश कोड लौटाता है।

**Returns:** A 32-bit signed integer hash code.

### getPostalCode() {#getpostalcode}

डाक कोड पहचानता है। मोड 2 में यह 9 अंकों का होना चाहिए या मोड 3 में 6 अल्फ़ान्यूमेरिक प्रतीकों का।

### getSecondMessage() {#getsecondmessage}

बारकोड का दूसरा संदेश पहचानता है।

### getServiceCategory() {#getservicecategory}

3 अंकों की सेवा श्रेणी पहचानता है।

### initFromString(constructedCodetext) {#initfromstring}

निर्मित कोडटेक्स्ट से उदाहरण को प्रारंभ करता है।

| पैरामीटर | विवरण |
| --- | --- |
| constructedCodetext | निर्मित कोडटेक्स्ट। |

### setCountryCode() {#setcountrycode}

3 अंकों का देश कोड पहचानता है।

### setPostalCode() {#setpostalcode}

डाक कोड पहचानता है। मोड 2 में यह 9 अंकों का होना चाहिए या मोड 3 में 6 अल्फ़ान्यूमेरिक प्रतीकों का।

### setSecondMessage() {#setsecondmessage}

बारकोड का दूसरा संदेश पहचानता है।

### setServiceCategory() {#setservicecategory}

3 अंकों की सेवा श्रेणी पहचानता है।
