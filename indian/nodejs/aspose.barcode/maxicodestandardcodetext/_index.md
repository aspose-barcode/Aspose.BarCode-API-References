---
title: "MaxiCodeStandardCodetext"
linktitle: "MaxiCodeStandardCodetext"
second_title: "Aspose.BarCode के लिए Node.js via Java API संदर्भ"
description: "मोड 4, 5 और 6 के लिए MaxiCode कोडटेक्स्ट को एन्कोड और डिकोड करने वाली क्लास।"
type: docs
weight: 670
url: /hi/nodejs/aspose.barcode/maxicodestandardcodetext/
---

## MaxiCodeStandardCodetext class

मोड 4, 5 और 6 के लिए MaxiCode कोडटेक्स्ट को एन्कोड और डिकोड करने वाली क्लास।

```js
new MaxiCodeStandardCodetext()
```

**Example:**

```js
//Mode 4
let maxiCodeCodetext = new MaxiCodeStandardCodetext();
maxiCodeCodetext.setMode(MaxiCodeMode.MODE_4);
maxiCodeCodetext.setMessage("Test message");
let complexGenerator = new ComplexBarcodeGenerator(maxiCodeCodetext.getConstructedCodetext());
complexGenerator.generateBarCodeImage(BarcodeImageFormat.PNG);
```

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [equals(obj)](#equals) | एक मान लौटाता है जो दर्शाता है कि यह इंस्टेंस निर्दिष्ट मान के बराबर है या नहीं। |
| [getConstructedCodetext()](#getconstructedcodetext) | कोडटेक्स्ट बनाता है |
| [getHashCode()](#gethashcode) | इस उदाहरण के लिए हैश कोड लौटाता है। |
| [getMessage()](#getmessage) | संदेश प्राप्त करता है। |
| [getMode()](#getmode) | MaxiCode मोड प्राप्त करता है। |
| [initFromString(constructedCodetext)](#initfromstring) | निर्मित कोडटेक्स्ट से उदाहरण को प्रारंभ करता है। |
| [setMessage()](#setmessage) | संदेश सेट करता है। |
| [setMode()](#setmode) | MaxiCode मोड सेट करता है। मानक कोडटेक्स्ट केवल मोड 4, 5 और 6 के साथ उपयोग किया जा सकता है। |

### equals(obj) {#equals}

एक मान लौटाता है जो दर्शाता है कि यह इंस्टेंस निर्दिष्ट मान के बराबर है या नहीं।

| पैरामीटर | विवरण |
| --- | --- |
| obj | इस उदाहरण से तुलना करने के लिए एक मान। |

**Returns:** if obj has the same value as this instance; otherwise, false .

### getConstructedCodetext() {#getconstructedcodetext}

कोडटेक्स्ट बनाता है

**Returns:** Constructed codetext

### getHashCode() {#gethashcode}

इस उदाहरण के लिए हैश कोड लौटाता है।

**Returns:** A 32-bit signed integer hash code

### getMessage() {#getmessage}

संदेश प्राप्त करता है।

### getMode() {#getmode}

MaxiCode मोड प्राप्त करता है।

**Returns:** MaxiCode mode

### initFromString(constructedCodetext) {#initfromstring}

निर्मित कोडटेक्स्ट से उदाहरण को प्रारंभ करता है।

| पैरामीटर | विवरण |
| --- | --- |
| constructedCodetext | निर्मित कोडटेक्स्ट। |

### setMessage() {#setmessage}

संदेश सेट करता है।

### setMode() {#setmode}

MaxiCode मोड सेट करता है। मानक कोडटेक्स्ट केवल मोड 4, 5 और 6 के साथ उपयोग किया जा सकता है।
