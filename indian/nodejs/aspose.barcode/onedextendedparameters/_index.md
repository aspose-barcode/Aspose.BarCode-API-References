---
title: "OneDExtendedParameters"
linktitle: "OneDExtendedParameters"
second_title: "Aspose.BarCode के लिए Node.js via Java API संदर्भ"
description: "पहचाने गए 1D बारकोड के विशेष डेटा जैसे अलग कोडटेक्स्ट और चेकसम को संग्रहीत करता है"
type: docs
weight: 720
url: /hi/nodejs/aspose.barcode/onedextendedparameters/
---

## OneDExtendedParameters class

पहचाने गए 1D बारकोड के विशेष डेटा जैसे अलग कोडटेक्स्ट और चेकसम को संग्रहीत करता है

```js
new OneDExtendedParameters()
```

**Example:**

```js
//This sample shows how to get 1D barcode value and checksum
let generator = new BarcodeGenerator(EncodeTypes.EAN_13, "1234567890128");
generator.save("test.png");
let reader = new BarCodeReader("test.png", null,  DecodeType.EAN_13);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
   let result = results[i];
   console.log("BarCode Type: " + result.getCodeTypeName());
   console.log("BarCode CodeText: " + result.getCodeText());
   console.log("BarCode Value: " + result.getExtended().getOneD().getValue());
   console.log("BarCode Checksum: " + result.getExtended().getOneD().getCheckSum());
}
```

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [equals(obj)](#equals) | एक मान लौटाता है जो दर्शाता है कि यह उदाहरण निर्दिष्ट OneDExtendedParameters मान के बराबर है या नहीं। |
| [getCheckSum()](#getchecksum) | 1D बारकोड के लिए चेकसम प्राप्त करता है। मान: 1D बारकोड का चेकसम। |
| [getValue()](#getvalue) | चेकसम के बिना 1D बारकोड का कोडटेक्स्ट प्राप्त करता है। मान: चेकसम के बिना 1D बारकोड का कोडटेक्स्ट। |
| [hashCode()](#hashcode) | इस उदाहरण के लिए हैश कोड लौटाता है। |
| [isEmpty()](#isempty) | जाँचता है कि सभी पैरामीटर केवल डिफ़ॉल्ट मान रखते हैं या नहीं। मान: यदि सभी पैरामीटर केवल डिफ़ॉल्ट मान रखते हैं तो `true` लौटाता है; o |
| [toString()](#tostring) | इस OneDExtendedParameters का मानव-पठनीय स्ट्रिंग प्रतिनिधित्व लौटाता है। |

### equals(obj) {#equals}

एक मान लौटाता है जो दर्शाता है कि यह उदाहरण निर्दिष्ट OneDExtendedParameters मान के बराबर है या नहीं।

| पैरामीटर | विवरण |
| --- | --- |
| obj | इस इंस्टेंस से तुलना करने के लिए एक System.Object मान। |

**Returns:** true if obj has the same value as this instance; otherwise, false.

### getCheckSum() {#getchecksum}

1D बारकोड के लिए चेकसम प्राप्त करता है। मान: 1D बारकोड का चेकसम।

### getValue() {#getvalue}

चेकसम के बिना 1D बारकोड का कोडटेक्स्ट प्राप्त करता है। मान: चेकसम के बिना 1D बारकोड का कोडटेक्स्ट।

### hashCode() {#hashcode}

इस उदाहरण के लिए हैश कोड लौटाता है।

**Returns:** A 32-bit signed integer hash code.

### isEmpty() {#isempty}

जाँचता है कि सभी पैरामीटर केवल डिफ़ॉल्ट मान रखते हैं या नहीं। मान: यदि सभी पैरामीटर केवल डिफ़ॉल्ट मान रखते हैं तो `true` लौटाता है; अन्यथा, `false`।

### toString() {#tostring}

इस OneDExtendedParameters का मानव-पठनीय स्ट्रिंग प्रतिनिधित्व लौटाता है।

**Returns:** A string that represents this OneDExtendedParameters.
