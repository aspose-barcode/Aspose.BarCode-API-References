---
title: "Code128ExtendedParameters"
linktitle: "Code128ExtendedParameters"
second_title: "Aspose.BarCode के लिए Node.js via Java API संदर्भ"
description: "Code128 पहचाने गए बारकोड का विशेष डेटा संग्रहीत करता है जो पहचाने गए बारकोड के क्षेत्र और बारकोड कोण को दर्शाता है"
type: docs
weight: 240
url: /hi/nodejs/aspose.barcode/code128extendedparameters/
---

## Code128ExtendedParameters class

Code128 पहचाने गए बारकोड का विशेष डेटा संग्रहीत करता है जो पहचाने गए बारकोड के क्षेत्र और बारकोड कोण को दर्शाता है

```js
new Code128ExtendedParameters()
```

**Example:**

```js
//This sample shows how to get code128 raw values
let generator = new BarcodeGenerator(EncodeTypes.Code128, "12345");
generator.save("test.png");
let reader = new BarCodeReader("test.png", null,  DecodeType.CODE_128);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
   let result = results[i];
   console.log("BarCode Type: " + result.getCodeTypeName());
   console.log("BarCode CodeText: " + result.getCodeText());
   console.log("Code128 Data Portions: " + result.getExtended().getCode128());
}
```

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [equals(obj)](#equals) | एक मान लौटाता है जो दर्शाता है कि यह इंस्टेंस निर्दिष्ट Code128ExtendedParameters मान के बराबर है या नहीं। |
| [getCode128DataPortions()](#getcode128dataportions) | पहचाने गए Code128 बारकोड का Code128DataPortion ऐरे प्राप्त करता है। Code128DataPortion का मान। |
| [hashCode()](#hashcode) | इस उदाहरण के लिए हैश कोड लौटाता है। |
| [toString()](#tostring) | इस Code128ExtendedParameters का मानव-पठनीय स्ट्रिंग प्रतिनिधित्व लौटाता है। |

### equals(obj) {#equals}

एक मान लौटाता है जो दर्शाता है कि यह इंस्टेंस निर्दिष्ट Code128ExtendedParameters मान के बराबर है या नहीं।

| पैरामीटर | विवरण |
| --- | --- |
| obj | इस इंस्टेंस से तुलना करने के लिए एक System.Object मान। |

**Returns:** true if obj has the same value as this instance; otherwise, false.

### getCode128DataPortions() {#getcode128dataportions}

पहचाने गए Code128 बारकोड का Code128DataPortion ऐरे प्राप्त करता है। Code128DataPortion का मान।

### hashCode() {#hashcode}

इस उदाहरण के लिए हैश कोड लौटाता है।

**Returns:** A 32-bit signed integer hash code.

### toString() {#tostring}

इस Code128ExtendedParameters का मानव-पठनीय स्ट्रिंग प्रतिनिधित्व लौटाता है।

**Returns:** A string that represents this Code128ExtendedParameters.
