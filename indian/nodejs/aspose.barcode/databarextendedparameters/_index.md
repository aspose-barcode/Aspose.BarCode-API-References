---
title: "DataBarExtendedParameters"
linktitle: "DataBarExtendedParameters"
second_title: "Aspose.BarCode के लिए Node.js via Java API संदर्भ"
description: "पहचाने गए बारकोड की DataBar अतिरिक्त जानकारी संग्रहीत करता है"
type: docs
weight: 310
url: /hi/nodejs/aspose.barcode/databarextendedparameters/
---

## DataBarExtendedParameters class

पहचाने गए बारकोड की DataBar अतिरिक्त जानकारी संग्रहीत करता है

```js
new DataBarExtendedParameters()
```

**Example:**

```js
let reader = new BarCodeReader("test.png", DecodeType.DATABAR_OMNI_DIRECTIONAL);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
   let result = results[i];
   console.log("BarCode Type: " + result.getCodeTypeName());
   console.log("BarCode CodeText: " + result.getCodeText());
   console.log("QR Structured Append Quantity: " + result.getExtended().getQR().getQRStructuredAppendModeBarCodesQuantity());
}
```

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [equals(obj)](#equals) | एक मान लौटाता है जो दर्शाता है कि यह इंस्टेंस निर्दिष्ट DataBarExtendedParameters मान के बराबर है या नहीं। |
| [hashCode()](#hashcode) | इस उदाहरण के लिए हैश कोड लौटाता है। |
| [is2DCompositeComponent()](#is2dcompositecomponent) | DataBar 2D कॉम्पोजिट कॉम्पोनेंट फ़्लैग प्राप्त करता है। डिफ़ॉल्ट मान false है। |
| [toString()](#tostring) | इसका मानव-पठनीय स्ट्रिंग प्रतिनिधित्व लौटाता है। |

### equals(obj) {#equals}

एक मान लौटाता है जो दर्शाता है कि यह इंस्टेंस निर्दिष्ट DataBarExtendedParameters मान के बराबर है या नहीं।

| पैरामीटर | विवरण |
| --- | --- |
| obj | इस इंस्टेंस से तुलना करने के लिए DataBarExtendedParameters मान। |

**Returns:** true if obj has the same value as this instance; otherwise, false .

### hashCode() {#hashcode}

इस उदाहरण के लिए हैश कोड लौटाता है।

**Returns:** A 32-bit signed integer hash code.

### is2DCompositeComponent() {#is2dcompositecomponent}

DataBar 2D कॉम्पोजिट कॉम्पोनेंट फ़्लैग प्राप्त करता है। डिफ़ॉल्ट मान false है।

**Returns:** The DataBar 2D composite component flag.

### toString() {#tostring}

इसका मानव-पठनीय स्ट्रिंग प्रतिनिधित्व लौटाता है।

**Returns:** A string that represents this .
