---
title: "SecondaryAndAdditionalData"
linktitle: "SecondaryAndAdditionalData"
second_title: "Aspose.BarCode के लिए Node.js via Java API संदर्भ"
description: "HIBC LIC द्वितीयक और अतिरिक्त डेटा संग्रहीत करने वाली क्लास।"
type: docs
weight: 880
url: /hi/nodejs/aspose.barcode/secondaryandadditionaldata/
---

## SecondaryAndAdditionalData class

HIBC LIC द्वितीयक और अतिरिक्त डेटा संग्रहीत करने वाली क्लास।

```js
new SecondaryAndAdditionalData()
```

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [equals(obj)](#equals) | एक मान लौटाता है जो दर्शाता है कि यह उदाहरण निर्दिष्ट `SecondaryAndAdditionalData` मान के बराबर है या नहीं। |
| [getDateOfManufacture()](#getdateofmanufacture) | निर्माण तिथि की पहचान करता है। निर्माण तिथि को इस फ़ील्ड का उपयोग न करने के लिए DateTime.MinValue पर सेट किया जा सकता है। Defa |
| [getExpiryDate()](#getexpirydate) | समाप्ति तिथि की पहचान करता है। यदि ExpiryDateFormat को None पर सेट नहीं किया गया है तो इसका उपयोग किया जाएगा। |
| [getExpiryDateFormat()](#getexpirydateformat) | समाप्ति तिथि प्रारूप की पहचान करता है। |
| [getLotNumber()](#getlotnumber) | लॉट या बैच नंबर की पहचान करता है। लॉट/बैच नंबर को अधिकतम 18 अक्षरों की अल्फ़ान्यूमेरिक स्ट्रिंग होना चाहिए। . |
| [getQuantity()](#getquantity) | मात्रा की पहचान करता है, जो 0 से 500 के बीच पूर्णांक मान होना चाहिए। इस फ़ील्ड का उपयोग न करने के लिए मात्रा को -1 पर सेट किया जा सकता है। Defa |
| [getSerialNumber()](#getserialnumber) | सीरियल नंबर की पहचान करता है। सीरियल नंबर को अधिकतम 18 अक्षरों की अल्फ़ान्यूमेरिक स्ट्रिंग होना चाहिए। |
| [hashCode()](#hashcode) | इस उदाहरण के लिए हैश कोड लौटाता है। |
| [parseFromString(secondaryDataCodetext)](#parsefromstring) | HIBC LIC विनिर्देश के अनुसार स्ट्रिंग फ़ॉर्मेट से द्वितीयक और अतिरिक्त पूरक डेटा को इंस्टैंशिएट करता है। |
| [setDateOfManufacture()](#setdateofmanufacture) | निर्माण तिथि की पहचान करता है। निर्माण तिथि को इस फ़ील्ड का उपयोग न करने के लिए DateTime.MinValue पर सेट किया जा सकता है। Defa |
| [setExpiryDate()](#setexpirydate) | समाप्ति तिथि की पहचान करता है। यदि ExpiryDateFormat को None पर सेट नहीं किया गया है तो इसका उपयोग किया जाएगा। |
| [setExpiryDateFormat()](#setexpirydateformat) | समाप्ति तिथि प्रारूप की पहचान करता है। |
| [setLotNumber()](#setlotnumber) | लॉट या बैच नंबर की पहचान करता है। लॉट/बैच नंबर को अधिकतम 18 अक्षरों की अल्फ़ान्यूमेरिक स्ट्रिंग होना चाहिए। . |
| [setQuantity()](#setquantity) | मात्रा की पहचान करता है, जो 0 से 500 के बीच पूर्णांक मान होना चाहिए। इस फ़ील्ड का उपयोग न करने के लिए मात्रा को -1 पर सेट किया जा सकता है। Defa |
| [setSerialNumber()](#setserialnumber) | सीरियल नंबर की पहचान करता है। सीरियल नंबर को अधिकतम 18 अक्षरों की अल्फ़ान्यूमेरिक स्ट्रिंग होना चाहिए। |
| [toString()](#tostring) | डेटा को HIBC LIC विनिर्देश के अनुसार स्ट्रिंग फ़ॉर्मेट में परिवर्तित करता है। |

### equals(obj) {#equals}

एक मान लौटाता है जो दर्शाता है कि यह उदाहरण निर्दिष्ट `SecondaryAndAdditionalData` मान के बराबर है या नहीं।

| पैरामीटर | विवरण |
| --- | --- |
| obj | इस इंस्टेंस से तुलना करने के लिए एक `SecondaryAndAdditionalData` मान। |

**Returns:** `true ` if obj has the same value as this instance; otherwise, `false `.

### getDateOfManufacture() {#getdateofmanufacture}

निर्माण तिथि की पहचान करता है। निर्माण तिथि को इस फ़ील्ड का उपयोग न करने के लिए DateTime.MinValue पर सेट किया जा सकता है। डिफ़ॉल्ट मान: DateTime.MinValue

### getExpiryDate() {#getexpirydate}

समाप्ति तिथि की पहचान करता है। यदि ExpiryDateFormat को None पर सेट नहीं किया गया है तो इसका उपयोग किया जाएगा।

### getExpiryDateFormat() {#getexpirydateformat}

समाप्ति तिथि प्रारूप की पहचान करता है।

### getLotNumber() {#getlotnumber}

लॉट या बैच नंबर की पहचान करता है। लॉट/बैच नंबर को अधिकतम 18 अक्षरों की अल्फ़ान्यूमेरिक स्ट्रिंग होना चाहिए। .

### getQuantity() {#getquantity}

मात्रा की पहचान करता है, जो 0 से 500 के बीच पूर्णांक मान होना चाहिए। इस फ़ील्ड का उपयोग न करने के लिए मात्रा को -1 पर सेट किया जा सकता है। डिफ़ॉल्ट मान: -1

### getSerialNumber() {#getserialnumber}

सीरियल नंबर की पहचान करता है। सीरियल नंबर को अधिकतम 18 अक्षरों की अल्फ़ान्यूमेरिक स्ट्रिंग होना चाहिए।

### hashCode() {#hashcode}

इस उदाहरण के लिए हैश कोड लौटाता है।

**Returns:** A 32-bit signed integer hash code.

### parseFromString(secondaryDataCodetext) {#parsefromstring}

HIBC LIC विनिर्देश के अनुसार स्ट्रिंग फ़ॉर्मेट से द्वितीयक और अतिरिक्त पूरक डेटा को इंस्टैंशिएट करता है।

| पैरामीटर | विवरण |
| --- | --- |
| secondaryDataCodetext | फ़ॉर्मेटेड स्ट्रिंग। |

### setDateOfManufacture() {#setdateofmanufacture}

निर्माण तिथि की पहचान करता है। निर्माण तिथि को इस फ़ील्ड का उपयोग न करने के लिए DateTime.MinValue पर सेट किया जा सकता है। डिफ़ॉल्ट मान: DateTime.MinValue

### setExpiryDate() {#setexpirydate}

समाप्ति तिथि की पहचान करता है। यदि ExpiryDateFormat को None पर सेट नहीं किया गया है तो इसका उपयोग किया जाएगा।

### setExpiryDateFormat() {#setexpirydateformat}

समाप्ति तिथि प्रारूप की पहचान करता है।

### setLotNumber() {#setlotnumber}

लॉट या बैच नंबर की पहचान करता है। लॉट/बैच नंबर को अधिकतम 18 अक्षरों की अल्फ़ान्यूमेरिक स्ट्रिंग होना चाहिए। .

### setQuantity() {#setquantity}

मात्रा की पहचान करता है, जो 0 से 500 के बीच पूर्णांक मान होना चाहिए। इस फ़ील्ड का उपयोग न करने के लिए मात्रा को -1 पर सेट किया जा सकता है। डिफ़ॉल्ट मान: -1

### setSerialNumber() {#setserialnumber}

सीरियल नंबर की पहचान करता है। सीरियल नंबर को अधिकतम 18 अक्षरों की अल्फ़ान्यूमेरिक स्ट्रिंग होना चाहिए।

### toString() {#tostring}

डेटा को HIBC LIC विनिर्देश के अनुसार स्ट्रिंग फ़ॉर्मेट में परिवर्तित करता है।

**Returns:** Formatted string.
