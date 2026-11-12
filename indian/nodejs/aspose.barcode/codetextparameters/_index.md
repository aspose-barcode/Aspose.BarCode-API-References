---
title: "CodetextParameters"
linktitle: "CodetextParameters"
second_title: "Aspose.BarCode के लिए Node.js via Java API संदर्भ"
description: "कोडटेक्स्ट पैरामीटर।"
type: docs
weight: 270
url: /hi/nodejs/aspose.barcode/codetextparameters/
---

## CodetextParameters class

कोडटेक्स्ट पैरामीटर।

```js
new CodetextParameters()
```

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [getAlignment()](#getalignment) | कोड टेक्स्ट की संरेखण प्राप्त करता है। डिफ़ॉल्ट मान: TextAlignment.CENTER। |
| [getColor()](#getcolor) | CodeText के प्रदर्शित रंग को निर्दिष्ट करें। डिफ़ॉल्ट मान BLACK। |
| [getFont()](#getfont) | CodeText के प्रदर्शित फ़ॉन्ट को निर्दिष्ट करें। डिफ़ॉल्ट मान: Arial 5pt regular। यदि FontMode को FontMode.AUTO पर सेट किया गया है तो यह अनदेखा किया जाएगा। |
| [getFontMode()](#getfontmode) | FontMode निर्दिष्ट करें। यदि FontMode को Auto पर सेट किया जाता है, तो फ़ॉन्ट आकार xDimension मान के आधार पर स्वचालित रूप से गणना किया जाएगा। It i |
| [getLocation()](#getlocation) | CodeText के प्रदर्शित स्थान को निर्दिष्ट करें, CodeText को छिपाने के लिए CodeLocation.NONE सेट करें। डिफ़ॉल्ट मान: CodeLocation.BELOW। |
| [getNoWrap()](#getnowrap) | पाठ के भीतर शब्द रैप (लाइन ब्रेक) निर्दिष्ट करें। डिफ़ॉल्ट मान: false। |
| [getSpace()](#getspace) | CodeText और BarCode के बीच यूनिट मान में अंतर। डिफ़ॉल्ट मान: 2pt। EAN8, EAN13, UPCE, UPCA, ISBN के लिए अनदेखा किया जाता है। |
| [getTwoDDisplayText()](#gettwoddisplaytext) | 2D बारकोड में codetext के बजाय प्रदर्शित किया जाने वाला टेक्स्ट। उपयोग किया जाता है: Aztec, Pdf417, DataMatrix, QR, MaxiCode, DotCo |
| [setAlignment()](#setalignment) | कोड टेक्स्ट की संरेखण सेट करता है। डिफ़ॉल्ट मान: TextAlignment.CENTER। |
| [setColor()](#setcolor) | CodeText के प्रदर्शित रंग को निर्दिष्ट करें। डिफ़ॉल्ट मान BLACK। |
| [setFont()](#setfont) | CodeText के प्रदर्शित फ़ॉन्ट को निर्दिष्ट करें। डिफ़ॉल्ट मान: Arial 5pt regular। यदि FontMode को FontMode.AUTO पर सेट किया गया है तो यह अनदेखा किया जाएगा। |
| [setFontMode()](#setfontmode) | FontMode निर्दिष्ट करें। यदि FontMode को Auto पर सेट किया जाता है, तो फ़ॉन्ट आकार xDimension मान के आधार पर स्वचालित रूप से गणना किया जाएगा। It i |
| [setLocation()](#setlocation) | CodeText के प्रदर्शित स्थान को निर्दिष्ट करें, CodeText को छिपाने के लिए CodeLocation.NONE सेट करें। डिफ़ॉल्ट मान: CodeLocation.NONE। |
| [setNoWrap()](#setnowrap) | पाठ के भीतर शब्द रैप (लाइन ब्रेक) निर्दिष्ट करें। डिफ़ॉल्ट मान: false। |
| [setSpace()](#setspace) | CodeText और BarCode के बीच यूनिट मान में अंतर। डिफ़ॉल्ट मान: 2pt। EAN8, EAN13, UPCE, UPCA, ISBN के लिए अनदेखा किया जाता है। |
| [setTwoDDisplayText()](#settwoddisplaytext) | 2D बारकोड में codetext के बजाय प्रदर्शित किया जाने वाला टेक्स्ट। उपयोग किया जाता है: Aztec, Pdf417, DataMatrix, QR, MaxiCode, DotCo |
| [toString()](#tostring) | इस CodetextParameters का मानव-पठनीय स्ट्रिंग प्रतिनिधित्व लौटाता है। |

### getAlignment() {#getalignment}

कोड टेक्स्ट की संरेखण प्राप्त करता है। डिफ़ॉल्ट मान: TextAlignment.CENTER।

### getColor() {#getcolor}

CodeText के प्रदर्शित रंग को निर्दिष्ट करें। डिफ़ॉल्ट मान BLACK।

### getFont() {#getfont}

CodeText के प्रदर्शित फ़ॉन्ट को निर्दिष्ट करें। डिफ़ॉल्ट मान: Arial 5pt regular। यदि FontMode को FontMode.AUTO पर सेट किया गया है तो यह अनदेखा किया जाएगा।

### getFontMode() {#getfontmode}

FontMode निर्दिष्ट करें। यदि FontMode को Auto पर सेट किया जाता है, तो फ़ॉन्ट आकार xDimension मान के आधार पर स्वचालित रूप से गणना किया जाएगा। AutoSizeMode.NEAREST या AutoSizeMode.INTERPOLATION में विशेष रूप से FontMode.AUTO का उपयोग करने की सलाह दी जाती है। डिफ़ॉल्ट मान: FontMode.AUTO।

### getLocation() {#getlocation}

CodeText के प्रदर्शित स्थान को निर्दिष्ट करें, CodeText को छिपाने के लिए CodeLocation.NONE सेट करें। डिफ़ॉल्ट मान: CodeLocation.BELOW।

### getNoWrap() {#getnowrap}

पाठ के भीतर शब्द रैप (लाइन ब्रेक) निर्दिष्ट करें। डिफ़ॉल्ट मान: false।

### getSpace() {#getspace}

CodeText और BarCode के बीच यूनिट मान में अंतर। डिफ़ॉल्ट मान: 2pt। EAN8, EAN13, UPCE, UPCA, ISBN, ISMN, ISSN, UpcaGs1DatabarCoupon के लिए अनदेखा किया जाता है।

### getTwoDDisplayText() {#gettwoddisplaytext}

कोडटेक्स्ट के बजाय 2D बारकोड में प्रदर्शित किया जाने वाला टेक्स्ट। उपयोग किया जाता है: Aztec, Pdf417, DataMatrix, QR, MaxiCode, DotCode

### setAlignment() {#setalignment}

कोड टेक्स्ट की संरेखण सेट करता है। डिफ़ॉल्ट मान: TextAlignment.CENTER।

### setColor() {#setcolor}

CodeText के प्रदर्शित रंग को निर्दिष्ट करें। डिफ़ॉल्ट मान BLACK।

### setFont() {#setfont}

CodeText के प्रदर्शित फ़ॉन्ट को निर्दिष्ट करें। डिफ़ॉल्ट मान: Arial 5pt regular। यदि FontMode को FontMode.AUTO पर सेट किया गया है तो यह अनदेखा किया जाएगा।

### setFontMode() {#setfontmode}

FontMode निर्दिष्ट करें। यदि FontMode को Auto पर सेट किया जाता है, तो फ़ॉन्ट आकार xDimension मान के आधार पर स्वचालित रूप से गणना किया जाएगा। AutoSizeMode.NEAREST या AutoSizeMode.INTERPOLATION में विशेष रूप से FontMode.AUTO का उपयोग करने की सलाह दी जाती है। डिफ़ॉल्ट मान: FontMode.AUTO।

### setLocation() {#setlocation}

CodeText के प्रदर्शित स्थान को निर्दिष्ट करें, CodeText को छिपाने के लिए CodeLocation.NONE सेट करें। डिफ़ॉल्ट मान: CodeLocation.NONE।

### setNoWrap() {#setnowrap}

पाठ के भीतर शब्द रैप (लाइन ब्रेक) निर्दिष्ट करें। डिफ़ॉल्ट मान: false।

### setSpace() {#setspace}

CodeText और BarCode के बीच यूनिट मान में अंतर। डिफ़ॉल्ट मान: 2pt। EAN8, EAN13, UPCE, UPCA, ISBN, ISMN, ISSN, UpcaGs1DatabarCoupon के लिए अनदेखा किया जाता है।

### setTwoDDisplayText() {#settwoddisplaytext}

कोडटेक्स्ट के बजाय 2D बारकोड में प्रदर्शित किया जाने वाला टेक्स्ट। उपयोग किया जाता है: Aztec, Pdf417, DataMatrix, QR, MaxiCode, DotCode

### toString() {#tostring}

इस CodetextParameters का मानव-पठनीय स्ट्रिंग प्रतिनिधित्व लौटाता है।

**Returns:** A string that represents this CodetextParameters.
