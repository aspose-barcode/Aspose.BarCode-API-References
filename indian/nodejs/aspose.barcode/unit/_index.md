---
title: "Unit"
linktitle: "Unit"
second_title: "Aspose.BarCode के लिए Node.js via Java API संदर्भ"
description: "विभिन्न इकाइयों (पिक्सेल, इंच, आदि) में आकार मान निर्दिष्ट करता है।"
type: docs
weight: 960
url: /hi/nodejs/aspose.barcode/unit/
---

## Unit class

विभिन्न इकाइयों (पिक्सेल, इंच, आदि) में आकार मान निर्दिष्ट करता है।

```js
new Unit()
```

**Example:**

```js
//This sample shows how to create and save a BarCode image.
   let generator = new BarcodeGenerator(EncodeTypes.CODE_128);
   generator.getParameters().getBarcode().getBarHeight().setMillimeters(10);
   generator.save("test.png", BarcodeImageFormat.PNG);
```

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [equals(obj)](#equals) | निर्धारित करता है कि यह इंस्टेंस और निर्दिष्ट ऑब्जेक्ट, जो भी एक Unit ऑब्जेक्ट होना चाहिए, समान मान रखते हैं या नहीं। |
| [getDocument()](#getdocument) | डॉक्यूमेंट यूनिट्स में आकार मान प्राप्त करता है। |
| [getInches()](#getinches) | इंच में आकार मान प्राप्त करता है। |
| [getMillimeters()](#getmillimeters) | मिलीमीटर में आकार मान प्राप्त करता है। |
| [getPixels()](#getpixels) | पिक्सेल में आकार मान प्राप्त करता है। |
| [getPoint()](#getpoint) | पॉइंट में आकार मान प्राप्त करता है। |
| [setDocument()](#setdocument) | डॉक्यूमेंट यूनिट्स में आकार मान सेट करता है। |
| [setInches()](#setinches) | इंच में आकार मान सेट करता है। |
| [setMillimeters()](#setmillimeters) | मिलीमीटर में आकार मान सेट करता है। |
| [setPixels()](#setpixels) | पिक्सेल में आकार मान सेट करता है। |
| [setPoint()](#setpoint) | पॉइंट में आकार मान सेट करता है। |
| [toString()](#tostring) | इस Unit का मानव-पठनीय स्ट्रिंग प्रतिनिधित्व लौटाता है। |

### equals(obj) {#equals}

निर्धारित करता है कि यह इंस्टेंस और निर्दिष्ट ऑब्जेक्ट, जो भी एक Unit ऑब्जेक्ट होना चाहिए, समान मान रखते हैं या नहीं।

| पैरामीटर | विवरण |
| --- | --- |
| obj | इस इंस्टेंस से तुलना करने के लिए Unit। |

**Returns:** true if obj is a Unit and its value is the same as this instance; otherwise, false. If obj is null, the method returns false.

### getDocument() {#getdocument}

डॉक्यूमेंट यूनिट्स में आकार मान प्राप्त करता है।

### getInches() {#getinches}

इंच में आकार मान प्राप्त करता है।

### getMillimeters() {#getmillimeters}

मिलीमीटर में आकार मान प्राप्त करता है।

### getPixels() {#getpixels}

पिक्सेल में आकार मान प्राप्त करता है।

### getPoint() {#getpoint}

पॉइंट में आकार मान प्राप्त करता है।

### setDocument() {#setdocument}

डॉक्यूमेंट यूनिट्स में आकार मान सेट करता है।

### setInches() {#setinches}

इंच में आकार मान सेट करता है।

### setMillimeters() {#setmillimeters}

मिलीमीटर में आकार मान सेट करता है।

### setPixels() {#setpixels}

पिक्सेल में आकार मान सेट करता है।

### setPoint() {#setpoint}

पॉइंट में आकार मान सेट करता है।

### toString() {#tostring}

इस Unit का मानव-पठनीय स्ट्रिंग प्रतिनिधित्व लौटाता है।

**Returns:** A string that represents this Unit.
