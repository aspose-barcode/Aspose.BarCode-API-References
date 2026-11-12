---
title: "QrExtCodetextBuilder"
linktitle: "QrExtCodetextBuilder"
second_title: "Aspose.BarCode के लिए Node.js via Java API संदर्भ"
description: "ExtendedCodetext मोड के लिए 2D QR बारकोड के लिए विस्तारित कोडटेक्स्ट जेनरेटर QREncodeMode का उपयोग करता है। BarCodeBuilder की Display2DText प्रॉपर्टी का उपयोग करके दृश्यमान टेक्स्ट को rem पर सेट करें।"
type: docs
weight: 820
url: /hi/nodejs/aspose.barcode/qrextcodetextbuilder/
---

## QrExtCodetextBuilder class

ExtendedCodetext मोड के लिए 2D QR बारकोड के लिए विस्तारित कोडटेक्स्ट जेनरेटर QREncodeMode का उपयोग करता है। BarCodeBuilder की Display2DText प्रॉपर्टी का उपयोग करके दृश्यमान टेक्स्ट को प्रबंधकीय अक्षरों को हटाते हुए सेट करें।

```js
new QrExtCodetextBuilder()
```

**Example:**

```js
//Example how to generate FNC1 first position for Extended Mode
 //create codetext
 const lTextBuilder = new QrExtCodetextBuilder();
 lTextBuilder.addFNC1FirstPosition();
 lTextBuilder.addPlainCodetext("000%89%%0");
 lTextBuilder.addFNC1GroupSeparator();
 lTextBuilder.addPlainCodetext("12345&lt;FNC1&gt;");
 //generate codetext
 const lCodetext = lTextBuilder.getExtendedCodetext();
```

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [addCodetextWithCompactionMode(mode, codetext)](#addcodetextwithcompactionmode) | निर्दिष्ट QR संपीड़न मोड के साथ कोडटेक्स्ट को विस्तारित कोडटेक्स्ट आइटम्स में जोड़ता है। |
| [addFNC1FirstPosition()](#addfnc1firstposition) | विस्तारित कोडटेक्स्ट आइटम्स में पहले स्थान पर FNC1 जोड़ता है। |
| [addFNC1GroupSeparator()](#addfnc1groupseparator) | विस्तारित कोडटेक्स्ट आइटम्स में ग्रुप सेपरेटर (GS - '\\u001D') जोड़ता है। |
| [addFNC1SecondPosition(codetext)](#addfnc1secondposition) | विस्तारित कोडटेक्स्ट आइटम्स में दूसरे स्थान पर FNC1 जोड़ता है। |
| [clear()](#clear) | विस्तारित कोडटेक्स्ट आइटम्स को साफ़ करता है |
| [getExtendedCodetext()](#getextendedcodetext) | Extended codetext सूची से Extended codetext उत्पन्न करता है। |

### addCodetextWithCompactionMode(mode, codetext) {#addcodetextwithcompactionmode}

निर्दिष्ट QR संपीड़न मोड के साथ कोडटेक्स्ट को विस्तारित कोडटेक्स्ट आइटम्स में जोड़ता है।

| पैरामीटर | विवरण |
| --- | --- |
| मोड | कोडटेक्स्ट के लिए QR संपीड़न मोड। |
| codetext | Unicode में कोडटेक्स्ट जिसे विस्तारित कोडटेक्स्ट आइटम के रूप में जोड़ा जाए। |

**Throws:** IllegalArgumentException The specified codetext cannot be encoded in the selected QR compaction mode.

### addFNC1FirstPosition() {#addfnc1firstposition}

विस्तारित कोडटेक्स्ट आइटम्स में पहले स्थान पर FNC1 जोड़ता है।

### addFNC1GroupSeparator() {#addfnc1groupseparator}

विस्तारित कोडटेक्स्ट आइटम्स में ग्रुप सेपरेटर (GS - '\\u001D') जोड़ता है।

### addFNC1SecondPosition(codetext) {#addfnc1secondposition}

विस्तारित कोडटेक्स्ट आइटम्स में दूसरे स्थान पर FNC1 जोड़ता है।

| पैरामीटर | विवरण |
| --- | --- |
| codetext | दूसरे स्थान पर FNC1 का मान |

### clear() {#clear}

विस्तारित कोडटेक्स्ट आइटम्स को साफ़ करता है

### getExtendedCodetext() {#getextendedcodetext}

Extended codetext सूची से Extended codetext उत्पन्न करता है।

**Returns:** Extended codetext as string
