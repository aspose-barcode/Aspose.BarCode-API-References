---
title: "ExtCodetextBuilder"
linktitle: "ExtCodetextBuilder"
second_title: "Aspose.BarCode के लिए Node.js via Java API संदर्भ"
description: "Extended Codetext Mode की स्वचालित कोडटेक्स्ट जनरेशन के लिए हेल्पर क्लास"
type: docs
weight: 400
url: /hi/nodejs/aspose.barcode/extcodetextbuilder/
---

## ExtCodetextBuilder class

Extended Codetext Mode की स्वचालित कोडटेक्स्ट जनरेशन के लिए हेल्पर क्लास

```js
new ExtCodetextBuilder()
```

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [addECICodetext(ECIEncoding, codetext)](#addecicodetext) | Extended Channel Identifier के साथ कोडटेक्स्ट जोड़ता है |
| [addPlainCodetext(codetext)](#addplaincodetext) | साधारण कोडटेक्स्ट को विस्तारित कोडटेक्स्ट आइटम्स में जोड़ता है |
| [clear()](#clear) | विस्तारित कोडटेक्स्ट आइटम्स को साफ़ करता है |
| [getExtendedCodetext()](#getextendedcodetext) | जनरेशन आइटम्स सूची से विस्तारित कोडटेक्स्ट उत्पन्न करता है |

### addECICodetext(ECIEncoding, codetext) {#addecicodetext}

Extended Channel Identifier के साथ कोडटेक्स्ट जोड़ता है

| पैरामीटर | विवरण |
| --- | --- |
| ECIEncoding | विस्तारित चैनल पहचानकर्ता |
| codetext | Unicode में कोडटेक्स्ट को Extended Channel Identifier के साथ विस्तारित कोडटेक्स्ट आइटम के रूप में जोड़ने के लिए |

### addPlainCodetext(codetext) {#addplaincodetext}

साधारण कोडटेक्स्ट को विस्तारित कोडटेक्स्ट आइटम्स में जोड़ता है

| पैरामीटर | विवरण |
| --- | --- |
| codetext | विस्तारित कोडटेक्स्ट आइटम के रूप में जोड़ने के लिए यूनिकोड में कोडटेक्स्ट |

### clear() {#clear}

विस्तारित कोडटेक्स्ट आइटम्स को साफ़ करता है

### getExtendedCodetext() {#getextendedcodetext}

जनरेशन आइटम्स सूची से विस्तारित कोडटेक्स्ट उत्पन्न करता है

**Returns:** Return string of extended codetext
