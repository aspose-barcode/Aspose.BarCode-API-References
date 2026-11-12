---
title: "MaxiCodeCodetext"
linktitle: "MaxiCodeCodetext"
second_title: "Aspose.BarCode के लिए Node.js via Java API संदर्भ"
description: "MaxiCode कोड में एम्बेडेड टेक्स्ट को एन्कोड और डिकोड करने के लिए बेस क्लास।"
type: docs
weight: 600
url: /hi/nodejs/aspose.barcode/maxicodecodetext/
---

## MaxiCodeCodetext class

MaxiCode कोड में एम्बेडेड टेक्स्ट को एन्कोड और डिकोड करने के लिए बेस क्लास। यह उदाहरण दिखाता है कि कैसे कच्चे MaxiCode कोडटेक्स्ट को MaxiCodeCodetext इंस्टेंस में डिकोड किया जाए।

```js
new MaxiCodeCodetext()
```

**Example:**

```js
let reader = new BarCodeReader("c:\\test.png", null, DecodeType.MAXI_CODE);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
     let result = results[i];
     let resultMaxiCodeCodetext = ComplexCodetextReader.tryDecodeMaxiCode(result.getExtended().getMaxiCode().getMaxiCodeMode(), result.getCodeText());
     console.log("BarCode Type: " + resultMaxiCodeCodetext.getBarcodeType());
     console.log("MaxiCode mode: " + resultMaxiCodeCodetext.getMode());
     console.log("BarCode CodeText: " + resultMaxiCodeCodetext.getConstructedCodetext());
}
```

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [getBarcodeType()](#getbarcodetype) | बारकोड प्रकार प्राप्त करता है। |
| [getECIEncoding()](#geteciencoding) | ECI एन्कोडिंग प्राप्त करता है। जब MaxiCodeEncodeMode AUTO हो तो उपयोग किया जाता है। |
| [getEncodeMode()](#getencodemode) | MaxiCode एन्कोड मोड प्राप्त करता है। डिफ़ॉल्ट मान: Auto। |
| [getMaxiCodeEncodeMode()](#getmaxicodeencodemode) ~~(deprecated)~~ | MaxiCode एन्कोड मोड प्राप्त करता है। |
| [getMode()](#getmode) | MaxiCode मोड प्राप्त करता है। |
| [setECIEncoding()](#seteciencoding) | ECI एन्कोडिंग सेट करता है। जब MaxiCodeEncodeMode AUTO हो तो उपयोग किया जाता है। |
| [setEncodeMode(value)](#setencodemode) | MaxiCode एन्कोड मोड सेट करता है। डिफ़ॉल्ट मान: Auto. |
| [setMaxiCodeEncodeMode()](#setmaxicodeencodemode) ~~(deprecated)~~ | MaxiCode एन्कोड मोड सेट करता है। |

### getBarcodeType() {#getbarcodetype}

बारकोड प्रकार प्राप्त करता है।

**Returns:** Barcode type

### getECIEncoding() {#geteciencoding}

ECI एन्कोडिंग प्राप्त करता है। जब MaxiCodeEncodeMode AUTO हो तो उपयोग किया जाता है।

### getEncodeMode() {#getencodemode}

MaxiCode एन्कोड मोड प्राप्त करता है। डिफ़ॉल्ट मान: Auto।

**Returns:** a MaxiCode encode mode.

### getMaxiCodeEncodeMode() {#getmaxicodeencodemode}

> **Deprecated.** See method description for replacement.

MaxiCode एन्कोड मोड प्राप्त करता है।

### getMode() {#getmode}

MaxiCode मोड प्राप्त करता है।

**Returns:** MaxiCode mode

### setECIEncoding() {#seteciencoding}

ECI एन्कोडिंग सेट करता है। जब MaxiCodeEncodeMode AUTO हो तो उपयोग किया जाता है।

### setEncodeMode(value) {#setencodemode}

MaxiCode एन्कोड मोड सेट करता है। डिफ़ॉल्ट मान: Auto.

| पैरामीटर | विवरण |
| --- | --- |
| मान | एक MaxiCode एन्कोड मोड। |

### setMaxiCodeEncodeMode() {#setmaxicodeencodemode}

> **Deprecated.** See method description for replacement.

MaxiCode एन्कोड मोड सेट करता है।
