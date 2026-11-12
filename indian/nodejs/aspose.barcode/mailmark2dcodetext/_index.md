---
title: "Mailmark2DCodetext"
linktitle: "Mailmark2DCodetext"
second_title: "Aspose.BarCode के लिए Node.js via Java API संदर्भ"
description: "Royal Mail 2D Mailmark कोड में एम्बेडेड टेक्स्ट को एन्कोड और डिकोड करने के लिए क्लास।"
type: docs
weight: 570
url: /hi/nodejs/aspose.barcode/mailmark2dcodetext/
---

## Mailmark2DCodetext class

Royal Mail 2D Mailmark कोड में एम्बेडेड टेक्स्ट को एन्कोड और डिकोड करने के लिए क्लास।

```js
new Mailmark2DCodetext()
```

Mailmark2DCodetext क्लास का डिफ़ॉल्ट इंस्टेंस बनाएं।

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [getBarcodeType()](#getbarcodetype) | बारकोड प्रकार प्राप्त करता है। |
| [getClass_()](#getclass-) | आइटम की क्लास की पहचान करता है। वैध मान: '1' - 1C (रिटेल) '2' - 2C (रिटेल) '3' - इकॉनमी (रिटेल) '5' - Deffere |
| [getConstructedCodetext()](#getconstructedcodetext) | Mailmark डेटा से कोडटेक्स्ट बनाएं। |
| [getCustomerContent()](#getcustomercontent) | ग्राहक द्वारा उपयोग के लिए वैकल्पिक स्पेस। प्रकार के अनुसार अधिकतम लंबाई: टाइप 7: 6 अक्षर, टाइप 9: 45 अक्षर, टाइप 29: 25 अक्षर। |
| [getCustomerContentEncodeMode()](#getcustomercontentencodemode) | Datamatrix बारकोड का एन्कोड मोड। डिफ़ॉल्ट मान: DataMatrixEncodeMode.C40। |
| [getDataMatrixType()](#getdatamatrixtype) | 2D Mailmark प्रकार Data Matrix बारकोड का आकार निर्धारित करता है। |
| [getDestinationPostCodeAndDPS()](#getdestinationpostcodeanddps) | डिलीवरी एड्रेस के पोस्टकोड को DPS के साथ शामिल करता है। यदि इनलैंड है तो पोस्टकोड/DP में निम्नलिखित संख्या के अक्षर होते हैं। |
| [getInformationTypeID()](#getinformationtypeid) | प्रत्येक प्रोडक्ट टाइप के लिए रॉयल मेल मेलमार्क बारकोड पेलोड की पहचान करता है। वैध मान: '0' - डोमेस्टिक सॉर्टेड और अनसॉर्टेड। |
| [getItemID()](#getitemid) | Supply Chain ID के भीतर अद्वितीय आइटम की पहचान करता है। प्रत्येक Mailmark बारकोड को एक ID ले जाना आवश्यक है ताकि इसे अन... |
| [getReturnToSenderPostCode()](#getreturntosenderpostcode) | Return to Sender पोस्ट कोड शामिल करता है लेकिन DPS नहीं। PC (बिना DPS) को PAF® फ़ॉर्मेट का पालन करना चाहिए। |
| [getRTSFlag()](#getrtsflag) | फ़्लैग जो दर्शाता है कि किस स्तर की Return to Sender सेवा का अनुरोध किया जा रहा है। |
| [getSupplyChainID()](#getsupplychainid) | मेलिंग में शामिल ग्राहकों के अद्वितीय समूह की पहचान करता है। अधिकतम मान: 9999999। |
| [getUPUCountryID()](#getupucountryid) | UPU Country ID की पहचान करता है। अधिकतम लंबाई: 4 अक्षर। |
| [getVersionID()](#getversionid) | प्रत्येक Information Type ID के अनुसार बारकोड संस्करण की पहचान करता है। मान्य मान: वर्तमान में '1'। '0' और '2' से '9' और ... |
| [initFromString(constructedCodetext)](#initfromstring) | निर्मित कोडटेक्स्ट से Mailmark डेटा को आरंभ करता है। |
| [setClass_(value)](#setclass-) | आइटम की क्लास की पहचान करता है। वैध मान: '1' - 1C (रिटेल) '2' - 2C (रिटेल) '3' - इकॉनमी (रिटेल) '5' - Deffere |
| [setCustomerContent(value)](#setcustomercontent) | ग्राहक द्वारा उपयोग के लिए वैकल्पिक स्पेस। प्रकार के अनुसार अधिकतम लंबाई: टाइप 7: 6 अक्षर, टाइप 9: 45 अक्षर, टाइप 29: 25 अक्षर। |
| [setCustomerContentEncodeMode(value)](#setcustomercontentencodemode) | Datamatrix बारकोड का एन्कोड मोड। डिफ़ॉल्ट मान: DataMatrixEncodeMode.C40। |
| [setDataMatrixType(value)](#setdatamatrixtype) | 2D Mailmark प्रकार Data Matrix बारकोड का आकार निर्धारित करता है। |
| [setDestinationPostCodeAndDPS(value)](#setdestinationpostcodeanddps) | डिलीवरी एड्रेस के पोस्टकोड को DPS के साथ शामिल करता है। यदि इनलैंड है तो पोस्टकोड/DP में निम्नलिखित संख्या के अक्षर होते हैं। |
| [setInformationTypeID(value)](#setinformationtypeid) | प्रत्येक प्रोडक्ट टाइप के लिए रॉयल मेल मेलमार्क बारकोड पेलोड की पहचान करता है। वैध मान: '0' - डोमेस्टिक सॉर्टेड और अनसॉर्टेड। |
| [setItemID(value)](#setitemid) | Supply Chain ID के भीतर अद्वितीय आइटम की पहचान करता है। प्रत्येक Mailmark बारकोड को एक ID ले जाना आवश्यक है ताकि इसे अन... |
| [setReturnToSenderPostCode(value)](#setreturntosenderpostcode) | Return to Sender पोस्ट कोड शामिल करता है लेकिन DPS नहीं। PC (बिना DPS) को PAF® फ़ॉर्मेट का पालन करना चाहिए। |
| [setRTSFlag()](#setrtsflag) | फ़्लैग जो दर्शाता है कि किस स्तर की Return to Sender सेवा का अनुरोध किया जा रहा है। |
| [setSupplyChainID(value)](#setsupplychainid) | मेलिंग में शामिल ग्राहकों के अद्वितीय समूह की पहचान करता है। अधिकतम मान: 9999999। |
| [setUPUCountryID(value)](#setupucountryid) | UPU Country ID की पहचान करता है। अधिकतम लंबाई: 4 अक्षर। |
| [setVersionID(value)](#setversionid) | प्रत्येक Information Type ID के अनुसार बारकोड संस्करण की पहचान करता है। मान्य मान: वर्तमान में '1'। '0' और '2' से '9' और ... |

### getBarcodeType() {#getbarcodetype}

बारकोड प्रकार प्राप्त करता है।

**Returns:** Barcode type.

### getClass_() {#getclass-}

आइटम की क्लास की पहचान करता है। मान्य मान: '1' - 1C (Retail), '2' - 2C (Retail), '3' - Economy (Retail), '5' - Deffered (Retail), '8' - Premium (Network Access), '9' - Standard (Network Access).

**Returns:** class of the item

### getConstructedCodetext() {#getconstructedcodetext}

Mailmark डेटा से कोडटेक्स्ट बनाएं।

**Returns:** Constructed codetext

### getCustomerContent() {#getcustomercontent}

ग्राहक द्वारा उपयोग के लिए वैकल्पिक स्थान। प्रकार के अनुसार अधिकतम लंबाई: Type 7: 6 अक्षर, Type 9: 45 अक्षर, Type 29: 25 अक्षर।

**Returns:** Customer content

### getCustomerContentEncodeMode() {#getcustomercontentencodemode}

Datamatrix बारकोड का एन्कोड मोड। डिफ़ॉल्ट मान: DataMatrixEncodeMode.C40।

**Returns:** Encode mode of Datamatrix barcode.

### getDataMatrixType() {#getdatamatrixtype}

2D Mailmark प्रकार Data Matrix बारकोड का आकार निर्धारित करता है।

**Returns:** Size of Data Matrix barcode

### getDestinationPostCodeAndDPS() {#getdestinationpostcodeanddps}

डिलीवरी पते के पोस्टकोड को DPS के साथ शामिल करता है। यदि अंतर्देशीय है तो पोस्टकोड/DP में निम्नलिखित संख्या में अक्षर होते हैं। Area (1 या 2 अक्षर) District (1 या 2 अक्षर) Sector (1 अक्षर) Unit (2 अक्षर) DPS (2 अक्षर)। पोस्टकोड और DPS को एक मान्य PAF® फ़ॉर्मेट का पालन करना चाहिए।

**Returns:** the Postcode of the Delivery Address with DPS

### getInformationTypeID() {#getinformationtypeid}

प्रत्येक उत्पाद प्रकार के लिए Royal Mail Mailmark बारकोड पेलोड की पहचान करता है। मान्य मान: '0' - Domestic Sorted & Unsorted, 'A' - Online Postage, 'B' - Franking, 'C' - Consolidation।

**Returns:** Information type ID

### getItemID() {#getitemid}

Supply Chain ID के भीतर अद्वितीय आइटम की पहचान करता है। प्रत्येक Mailmark बारकोड को एक ID ले जाना आवश्यक है ताकि इसे कम से कम 90 दिनों के लिए अद्वितीय रूप से पहचाना जा सके। अधिकतम मान: 99999999।

**Returns:** item within the Supply Chain ID

### getReturnToSenderPostCode() {#getreturntosenderpostcode}

Return to Sender पोस्ट कोड शामिल करता है लेकिन DPS नहीं। PC (बिना DPS) को PAF® फ़ॉर्मेट का पालन करना चाहिए।

**Returns:** Return to Sender Post Code but no DPS

### getRTSFlag() {#getrtsflag}

फ़्लैग जो दर्शाता है कि किस स्तर की Return to Sender सेवा का अनुरोध किया जा रहा है।

**Returns:** RTS Flag

### getSupplyChainID() {#getsupplychainid}

मेलिंग में शामिल ग्राहकों के अद्वितीय समूह की पहचान करता है। अधिकतम मान: 9999999।

**Returns:** Supply chain ID

### getUPUCountryID() {#getupucountryid}

UPU Country ID की पहचान करता है। अधिकतम लंबाई: 4 अक्षर।

**Returns:** Country ID

### getVersionID() {#getversionid}

प्रत्येक Information Type ID के अनुसार बारकोड संस्करण की पहचान करता है। मान्य मान: वर्तमान में '1'। '0' और '2' से '9' तथा 'A' से 'Z' भविष्य में संभावित उपयोग के लिए आरक्षित हैं।

**Returns:** Version ID

### initFromString(constructedCodetext) {#initfromstring}

निर्मित कोडटेक्स्ट से Mailmark डेटा को आरंभ करता है।

| पैरामीटर | विवरण |
| --- | --- |
| constructedCodetext | निर्मित कोडटेक्स्ट। |

### setClass_(value) {#setclass-}

आइटम की क्लास की पहचान करता है। मान्य मान: '1' - 1C (Retail), '2' - 2C (Retail), '3' - Economy (Retail), '5' - Deffered (Retail), '8' - Premium (Network Access), '9' - Standard (Network Access).

| पैरामीटर | विवरण |
| --- | --- |
| मान | आइटम की क्लास |

### setCustomerContent(value) {#setcustomercontent}

ग्राहक द्वारा उपयोग के लिए वैकल्पिक स्थान। प्रकार के अनुसार अधिकतम लंबाई: Type 7: 6 अक्षर, Type 9: 45 अक्षर, Type 29: 25 अक्षर।

| पैरामीटर | विवरण |
| --- | --- |
| मान | ग्राहक सामग्री |

### setCustomerContentEncodeMode(value) {#setcustomercontentencodemode}

Datamatrix बारकोड का एन्कोड मोड। डिफ़ॉल्ट मान: DataMatrixEncodeMode.C40।

| पैरामीटर | विवरण |
| --- | --- |
| मान | Datamatrix बारकोड का एन्कोड मोड। |

### setDataMatrixType(value) {#setdatamatrixtype}

2D Mailmark प्रकार Data Matrix बारकोड का आकार निर्धारित करता है।

| पैरामीटर | विवरण |
| --- | --- |
| मान | Data Matrix बारकोड का आकार |

### setDestinationPostCodeAndDPS(value) {#setdestinationpostcodeanddps}

डिलीवरी पते के पोस्टकोड को DPS के साथ शामिल करता है। यदि अंतर्देशीय है तो पोस्टकोड/DP में निम्नलिखित संख्या में अक्षर होते हैं। Area (1 या 2 अक्षर) District (1 या 2 अक्षर) Sector (1 अक्षर) Unit (2 अक्षर) DPS (2 अक्षर)। पोस्टकोड और DPS को एक मान्य PAF® फ़ॉर्मेट का पालन करना चाहिए।

| पैरामीटर | विवरण |
| --- | --- |
| मान | DPS के साथ डिलीवरी पते का पोस्टकोड |

### setInformationTypeID(value) {#setinformationtypeid}

प्रत्येक उत्पाद प्रकार के लिए Royal Mail Mailmark बारकोड पेलोड की पहचान करता है। मान्य मान: '0' - Domestic Sorted & Unsorted, 'A' - Online Postage, 'B' - Franking, 'C' - Consolidation।

| पैरामीटर | विवरण |
| --- | --- |
| मान | Information type ID |

### setItemID(value) {#setitemid}

Supply Chain ID के भीतर अद्वितीय आइटम की पहचान करता है। प्रत्येक Mailmark बारकोड को एक ID ले जाना आवश्यक है ताकि इसे कम से कम 90 दिनों के लिए अद्वितीय रूप से पहचाना जा सके। अधिकतम मान: 99999999।

| पैरामीटर | विवरण |
| --- | --- |
| मान | Supply Chain ID के भीतर आइटम |

### setReturnToSenderPostCode(value) {#setreturntosenderpostcode}

Return to Sender पोस्ट कोड शामिल करता है लेकिन DPS नहीं। PC (बिना DPS) को PAF® फ़ॉर्मेट का पालन करना चाहिए।

| पैरामीटर | विवरण |
| --- | --- |
| मान | Return to Sender पोस्ट कोड लेकिन DPS नहीं |

### setRTSFlag() {#setrtsflag}

फ़्लैग जो दर्शाता है कि किस स्तर की Return to Sender सेवा का अनुरोध किया जा रहा है।

**Returns:** RTS Flag

### setSupplyChainID(value) {#setsupplychainid}

मेलिंग में शामिल ग्राहकों के अद्वितीय समूह की पहचान करता है। अधिकतम मान: 9999999।

| पैरामीटर | विवरण |
| --- | --- |
| मान | Supply chain ID |

### setUPUCountryID(value) {#setupucountryid}

UPU Country ID की पहचान करता है। अधिकतम लंबाई: 4 अक्षर।

| पैरामीटर | विवरण |
| --- | --- |
| मान | Country ID |

### setVersionID(value) {#setversionid}

प्रत्येक Information Type ID के अनुसार बारकोड संस्करण की पहचान करता है। मान्य मान: वर्तमान में '1'। '0' और '2' से '9' तथा 'A' से 'Z' भविष्य में संभावित उपयोग के लिए आरक्षित हैं।

| पैरामीटर | विवरण |
| --- | --- |
| मान | Version ID |
