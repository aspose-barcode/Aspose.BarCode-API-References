---
title: "MailmarkCodetext"
linktitle: "MailmarkCodetext"
second_title: "Aspose.BarCode के लिए Node.js via Java API संदर्भ"
description: "4-स्टेट Royal Mailmark कोड में एम्बेडेड टेक्स्ट को एन्कोड और डिकोड करने के लिए क्लास।"
type: docs
weight: 580
url: /hi/nodejs/aspose.barcode/mailmarkcodetext/
---

## MailmarkCodetext class

4-स्टेट Royal Mailmark कोड में एम्बेडेड टेक्स्ट को एन्कोड और डिकोड करने के लिए क्लास।

```js
new MailmarkCodetext()
```

एक नया उदाहरण `MailmarkCodetext` क्लास का आरंभ करता है।

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [getBarcodeType()](#getbarcodetype) | बारकोड प्रकार प्राप्त करता है। |
| [getClass_()](#getclass-) | "0" - शून्य या परीक्षण "1" - 1C (रिटेल) "2" - 2C (रिटेल) "3" - 3C (रिटेल) "4" - प्रीमियम (रिटेलपब्लिशिंग मेल) (भविष्य के उपयोग के लिए) |
| [getConstructedCodetext()](#getconstructedcodetext) | Mailmark डेटा से कोडटेक्स्ट बनाएं। |
| [getDestinationPostCodePlusDPS()](#getdestinationpostcodeplusdps) | PC और DP को PAF फ़ॉर्मेट का पालन करना चाहिए। अंतरराष्ट्रीय "XY11 " को दर्शाने वाली नौ अक्षरों की स्ट्रिंग (ध्यान दें कि 5 ट्रेलिंग s |
| [getFormat()](#getformat) | "0" – शून्य या परीक्षण "1" – अक्षर "2" – बड़ा अक्षर |
| [getItemID()](#getitemid) | अधिकतम मान 99999999 है। |
| [getSupplychainID()](#getsupplychainid) | अधिकतम मान Barcode C के लिए 99 और Barcode L के लिए 999999 हैं। |
| [getVersionID()](#getversionid) | वर्तमान में "1" – Mailmark बारकोड के लिए (0 और 2 से 9 तथा A से Z भविष्य के उपयोग के लिए आरक्षित) |
| [initFromString(constructedCodetext)](#initfromstring) | निर्मित कोडटेक्स्ट से Mailmark डेटा को आरंभ करता है। |
| [setClass_()](#setclass-) | "0" - शून्य या परीक्षण "1" - 1C (रिटेल) "2" - 2C (रिटेल) "3" - 3C (रिटेल) "4" - प्रीमियम (रिटेलपब्लिशिंग मेल) (भविष्य के उपयोग के लिए) |
| [setDestinationPostCodePlusDPS()](#setdestinationpostcodeplusdps) | PC और DP को PAF फ़ॉर्मेट का पालन करना चाहिए। अंतरराष्ट्रीय "XY11 " को दर्शाने वाली नौ अक्षरों की स्ट्रिंग (ध्यान दें कि 5 ट्रेलिंग s |
| [setFormat()](#setformat) | "0" – शून्य या परीक्षण "1" – LetterN "2" – बड़ा अक्षर |
| [setItemID()](#setitemid) | अधिकतम मान 99999999 है। |
| [setSupplychainID()](#setsupplychainid) | अधिकतम मान Barcode C के लिए 99 और Barcode L के लिए 999999 हैं। |
| [setVersionID()](#setversionid) | वर्तमान में "1" – Mailmark बारकोड के लिए (0 और 2 से 9 तथा A से Z भविष्य के उपयोग के लिए आरक्षित) |

### getBarcodeType() {#getbarcodetype}

बारकोड प्रकार प्राप्त करता है।

**Returns:** Barcode type.

### getClass_() {#getclass-}

"0" - शून्य या परीक्षण "1" - 1C (रिटेल) "2" - 2C (रिटेल) "3" - 3C (रिटेल) "4" - प्रीमियम (रिटेलपब्लिशिंग मेल) (संभावित भविष्य उपयोग के लिए) "5" - डिफर्ड (रिटेल) "6" - एयर (रिटेल) (संभावित भविष्य उपयोग के लिए) "7" - सरफेस (रिटेल) (संभावित भविष्य उपयोग के लिए) "8" - प्रीमियम (नेटवर्क एक्सेस) "9" - स्टैंडर्ड (नेटवर्क एक्सेस)

### getConstructedCodetext() {#getconstructedcodetext}

Mailmark डेटा से कोडटेक्स्ट बनाएं।

**Returns:** Constructed codetext

### getDestinationPostCodePlusDPS() {#getdestinationpostcodeplusdps}

PC और DP को PAF फ़ॉर्मेट का पालन करना चाहिए। अंतरराष्ट्रीय "XY11 " को दर्शाने वाली नौ अक्षरों की स्ट्रिंग (ध्यान दें कि 5 ट्रेलिंग स्पेस) या घरेलू सॉर्टिंग कोड को दर्शाने वाले अक्षरों का पैटर्न। एक घरेलू सॉर्टिंग कोड में आउटवर्ड पोस्टकोड, इनवर्ड पोस्टकोड, और डिलीवरी पॉइंट सफ़िक्स शामिल होते हैं।

### getFormat() {#getformat}

"0" – शून्य या परीक्षण "1" – अक्षर "2" – बड़ा अक्षर

### getItemID() {#getitemid}

अधिकतम मान 99999999 है।

### getSupplychainID() {#getsupplychainid}

अधिकतम मान Barcode C के लिए 99 और Barcode L के लिए 999999 हैं।

### getVersionID() {#getversionid}

वर्तमान में "1" – Mailmark बारकोड के लिए (0 और 2 से 9 तथा A से Z भविष्य के उपयोग के लिए आरक्षित)

### initFromString(constructedCodetext) {#initfromstring}

निर्मित कोडटेक्स्ट से Mailmark डेटा को आरंभ करता है।

| पैरामीटर | विवरण |
| --- | --- |
| constructedCodetext | निर्मित कोडटेक्स्ट। |

### setClass_() {#setclass-}

"0" - शून्य या परीक्षण "1" - 1C (रिटेल) "2" - 2C (रिटेल) "3" - 3C (रिटेल) "4" - प्रीमियम (रिटेलपब्लिशिंग मेल) (संभावित भविष्य उपयोग के लिए) "5" - डिफर्ड (रिटेल) "6" - एयर (रिटेल) (संभावित भविष्य उपयोग के लिए) "7" - सरफेस (रिटेल) (संभावित भविष्य उपयोग के लिए) "8" - प्रीमियम (नेटवर्क एक्सेस) "9" - स्टैंडर्ड (नेटवर्क एक्सेस)

### setDestinationPostCodePlusDPS() {#setdestinationpostcodeplusdps}

PC और DP को PAF फ़ॉर्मेट का पालन करना चाहिए। अंतरराष्ट्रीय "XY11 " को दर्शाने वाली नौ अक्षरों की स्ट्रिंग (ध्यान दें कि 5 ट्रेलिंग स्पेस) या घरेलू सॉर्टिंग कोड को दर्शाने वाले अक्षरों का पैटर्न। एक घरेलू सॉर्टिंग कोड में आउटवर्ड पोस्टकोड, इनवर्ड पोस्टकोड, और डिलीवरी पॉइंट सफ़िक्स शामिल होते हैं।

### setFormat() {#setformat}

"0" – शून्य या परीक्षण "1" – LetterN "2" – बड़ा अक्षर

### setItemID() {#setitemid}

अधिकतम मान 99999999 है।

### setSupplychainID() {#setsupplychainid}

अधिकतम मान Barcode C के लिए 99 और Barcode L के लिए 999999 हैं।

### setVersionID() {#setversionid}

वर्तमान में "1" – Mailmark बारकोड के लिए (0 और 2 से 9 तथा A से Z भविष्य के उपयोग के लिए आरक्षित)
