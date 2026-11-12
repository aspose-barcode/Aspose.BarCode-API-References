---
title: "HIBCPASCodetext"
linktitle: "HIBCPASCodetext"
second_title: "Aspose.BarCode के लिए Node.js via Java API संदर्भ"
description: "HIBC PAS कोड में एम्बेडेड टेक्स्ट को एन्कोड और डिकोड करने के लिए क्लास।"
type: docs
weight: 480
url: /hi/nodejs/aspose.barcode/hibcpascodetext/
---

## HIBCPASCodetext class

HIBC PAS कोड में एम्बेडेड टेक्स्ट को एन्कोड और डिकोड करने के लिए क्लास।

```js
new HIBCPASCodetext()
```

**Example:**

```js
This sample shows how to encode and decode HIBC PAS using HIBCPASCodetext.

 let complexCodetext = new HIBCPASComplexCodetext();
 complexCodetext.setDataLocation(HIBCPASDataLocation.PATIENT);
 complexCodetext.addRecord(HIBCPASDataType.LABELER_IDENTIFICATION_CODE, "A123");
 complexCodetext.addRecord(HIBCPASDataType.MANUFACTURER_SERIAL_NUMBER, "SERIAL123");
 complexCodetext.setBarcodeType(EncodeTypes.HIBC_DATA_MATRIX_PAS);
 let generator = new ComplexBarcodeGenerator(complexCodetext);
 BarCodeReader reader = new BarCodeReader(generator.generateBarCodeImage(BarCodeImageFormat.PNG), null, DecodeType.HIBC_DATA_MATRIX_PAS);
 reader.readBarCodes();
 let codetext = reader.getFoundBarCodes()[0].getCodeText();
	let readCodetext = ComplexCodetextReader.tryDecodeHIBCPAS(codetext);
 print("Data location: " + readCodetext.getDataLocation());
 print("Data type: " + readCodetext.getRecords()[0].getDataType());
 print("Data: " + readCodetext.getRecords()[0].getData());
 print("Data type: " + readCodetext.getRecords()[1].getDataType());
 print("Data: " + readCodetext.getRecords()[1].getData());
```

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [_fromMwObject()](#-frommwobject) *(static)* | HIBCPASRecord कन्स्ट्रक्टर |
| [addHIBCPASRecord(record)](#addhibcpasrecord) | नया रिकॉर्ड जोड़ता है |
| [addRecord(dataType, data)](#addrecord) | नया रिकॉर्ड जोड़ता है |
| [clear()](#clear) | रिकॉर्ड सूची को साफ़ करता है |
| [equals(obj)](#equals) | एक मान लौटाता है जो दर्शाता है कि यह उदाहरण निर्दिष्ट `HIBCPASCodetext` मान के बराबर है या नहीं। |
| [getBarcodeType()](#getbarcodetype) | बारकोड प्रकार प्राप्त करता है। |
| [getConstructedCodetext()](#getconstructedcodetext) | कोडटेक्स्ट बनाता है |
| [getDataLocation()](#getdatalocation) | डेटा स्थान की पहचान करता है। |
| [getRecords()](#getrecords) | रिकॉर्ड सूची प्राप्त करता है |
| [hashCode()](#hashcode) | इस उदाहरण के लिए हैश कोड लौटाता है। |
| [initFromString(constructedCodetext)](#initfromstring) | निर्मित कोडटेक्स्ट से उदाहरण को प्रारंभ करता है। |
| [setBarcodeType()](#setbarcodetype) | बारकोड प्रकार प्राप्त करता है या सेट करता है। HIBC PAS कोडटेक्स्ट को HIBCCode39PAS, HIBCCode128PAS, HIBCAztec:PAS, HIBCData का उपयोग करके एन्कोड किया जा सकता है। |
| [setDataLocation()](#setdatalocation) | डेटा स्थान की पहचान करता है। |

### _fromMwObject() (static) {#-frommwobject}

HIBCPASRecord कन्स्ट्रक्टर

### addHIBCPASRecord(record) {#addhibcpasrecord}

नया रिकॉर्ड जोड़ता है

| पैरामीटर | विवरण |
| --- | --- |
| रिकॉर्ड | जोड़ने के लिए रिकॉर्ड |

### addRecord(dataType, data) {#addrecord}

नया रिकॉर्ड जोड़ता है

| पैरामीटर | विवरण |
| --- | --- |
| डेटा प्रकार | डेटा का प्रकार |
| डेटा | डेटा स्ट्रिंग |

### clear() {#clear}

रिकॉर्ड सूची को साफ़ करता है

### equals(obj) {#equals}

एक मान लौटाता है जो दर्शाता है कि यह उदाहरण निर्दिष्ट `HIBCPASCodetext` मान के बराबर है या नहीं।

| पैरामीटर | विवरण |
| --- | --- |
| obj | इस उदाहरण से तुलना करने के लिए एक `HIBCPASCodetext` मान। |

**Returns:** `true ` if obj has the same value as this instance; otherwise, `false `.

### getBarcodeType() {#getbarcodetype}

बारकोड प्रकार प्राप्त करता है।

**Returns:** Barcode type.

### getConstructedCodetext() {#getconstructedcodetext}

कोडटेक्स्ट बनाता है

**Returns:** Constructed codetext

### getDataLocation() {#getdatalocation}

डेटा स्थान की पहचान करता है।

### getRecords() {#getrecords}

रिकॉर्ड सूची प्राप्त करता है

**Returns:** List of records

### hashCode() {#hashcode}

इस उदाहरण के लिए हैश कोड लौटाता है।

**Returns:** A 32-bit signed integer hash code.

### initFromString(constructedCodetext) {#initfromstring}

निर्मित कोडटेक्स्ट से उदाहरण को प्रारंभ करता है।

| पैरामीटर | विवरण |
| --- | --- |
| constructedCodetext | निर्मित कोडटेक्स्ट। |

### setBarcodeType() {#setbarcodetype}

बारकोड प्रकार प्राप्त करता है या सेट करता है। HIBC PAS कोडटेक्स्ट को HIBCCode39PAS, HIBCCode128PAS, HIBCAztec:PAS, HIBCDataMatrixPAS और HIBCQRPAS एन्कोड प्रकारों का उपयोग करके एन्कोड किया जा सकता है। डिफ़ॉल्ट मान: HIBCCode39PAS।

**Returns:** Barcode type.

### setDataLocation() {#setdatalocation}

डेटा स्थान की पहचान करता है।
