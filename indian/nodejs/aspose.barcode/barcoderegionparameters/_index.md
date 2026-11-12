---
title: "BarCodeRegionParameters"
linktitle: "BarCodeRegionParameters"
second_title: "Aspose.BarCode के लिए Node.js via Java API संदर्भ"
description: "पहचाने गए बारकोड के क्षेत्र और बारकोड कोण को दर्शाता है"
type: docs
weight: 100
url: /hi/nodejs/aspose.barcode/barcoderegionparameters/
---

## BarCodeRegionParameters class

पहचाने गए बारकोड के क्षेत्र और बारकोड कोण को दर्शाता है

```js
new BarCodeRegionParameters()
```

**Example:**

```js
//This sample shows how to get barcode Angle and bounding quadrangle values
let generator = new BarcodeGenerator(EncodeTypes.Code128, "12345");
generator.save("test.png");
let reader = new BarCodeReader("test.png", null,  [ DecodeType.CODE_39, DecodeType.CODE_128 ]);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
   let result = results[i];
   console.log("BarCode CodeText: " + result.getCodeText());
   console.log("BarCode Angle: " + result.getRegion().getAngle());
   console.log("BarCode Quadrangle: " + result.getRegion().getQuadrangle());
}
```

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [equals(obj)](#equals) | BarCodeRegionParameters मान के साथ तुलना करने पर यह इंस्टेंस समान है या नहीं, यह दर्शाने वाला मान लौटाता है। |
| [getAngle()](#getangle) | बारकोड का कोण (0-360) प्राप्त करता है। मान: बारकोड का कोण (0-360)। |
| [getPoints()](#getpoints) | बारकोड क्षेत्र को सीमित करने वाले पॉइंट्स एरे को प्राप्त करता है मान: बारकोड क्षेत्र को सीमित करने वाले पॉइंट्स एरे को लौटाता है |
| [getQuadrangle()](#getquadrangle) | बारकोड क्षेत्र को सीमित करने वाले क्वाड्रैंगल को प्राप्त करता है मान: बारकोड क्षेत्र को सीमित करने वाले क्वाड्रैंगल को लौटाता है |
| [getRectangle()](#getrectangle) | बारकोड क्षेत्र को सीमित करने वाले रेक्टैंगल को प्राप्त करता है मान: बारकोड क्षेत्र को सीमित करने वाले रेक्टैंगल को लौटाता है |
| [hashCode()](#hashcode) | इस उदाहरण के लिए हैश कोड लौटाता है। |
| [toString()](#tostring) | इस BarCodeRegionParameters की मानव-पठनीय स्ट्रिंग प्रतिनिधित्व को लौटाता है। |

### equals(obj) {#equals}

BarCodeRegionParameters मान के साथ तुलना करने पर यह इंस्टेंस समान है या नहीं, यह दर्शाने वाला मान लौटाता है।

| पैरामीटर | विवरण |
| --- | --- |
| obj | इस इंस्टेंस से तुलना करने के लिए एक System.Object मान। |

**Returns:** true if obj has the same value as this instance; otherwise, false.

### getAngle() {#getangle}

बारकोड का कोण (0-360) प्राप्त करता है। मान: बारकोड का कोण (0-360)।

### getPoints() {#getpoints}

बारकोड क्षेत्र को सीमित करने वाले पॉइंट्स एरे को प्राप्त करता है मान: बारकोड क्षेत्र को सीमित करने वाले पॉइंट्स एरे को लौटाता है

### getQuadrangle() {#getquadrangle}

बारकोड क्षेत्र को सीमित करने वाले क्वाड्रैंगल को प्राप्त करता है मान: बारकोड क्षेत्र को सीमित करने वाले क्वाड्रैंगल को लौटाता है

### getRectangle() {#getrectangle}

बारकोड क्षेत्र को सीमित करने वाले रेक्टैंगल को प्राप्त करता है मान: बारकोड क्षेत्र को सीमित करने वाले रेक्टैंगल को लौटाता है

### hashCode() {#hashcode}

इस उदाहरण के लिए हैश कोड लौटाता है।

**Returns:** A 32-bit signed integer hash code.

### toString() {#tostring}

इस BarCodeRegionParameters की मानव-पठनीय स्ट्रिंग प्रतिनिधित्व को लौटाता है।

**Returns:** A string that represents this BarCodeRegionParameters.
