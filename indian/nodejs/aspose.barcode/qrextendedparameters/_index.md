---
title: "QRExtendedParameters"
linktitle: "QRExtendedParameters"
second_title: "Aspose.BarCode के लिए Node.js via Java API संदर्भ"
description: "पहचाने गए बारकोड की QR Structured Append जानकारी संग्रहीत करता है"
type: docs
weight: 810
url: /hi/nodejs/aspose.barcode/qrextendedparameters/
---

## QRExtendedParameters class

पहचाने गए बारकोड की QR Structured Append जानकारी संग्रहीत करता है

```js
new QRExtendedParameters()
```

**Example:**

```js
//This sample shows how to get QR Structured Append data

let reader = new BarCodeReader("test.png", null,  DecodeType.QR);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
   let result = results[i];
   console.log("BarCode Type: " + result.getCodeTypeName());
   console.log("BarCode CodeText: " + result.getCodeText());
   console.log("QR Structured Append Quantity: " + result.getExtended().getQR().getQRStructuredAppendModeBarCodesQuantity());
   console.log("QR Structured Append Index: " + result.getExtended().getQR().getQRStructuredAppendModeBarCodeIndex());
   console.log("QR Structured Append ParityData: " + result.getExtended().getQR().getQRStructuredAppendModeParityData());
}
```

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [equals(obj)](#equals) | एक मान लौटाता है जो दर्शाता है कि यह इंस्टेंस निर्दिष्ट QRExtendedParameters मान के बराबर है या नहीं। |
| [getErrorLevel()](#geterrorlevel) | पहचाने गए बारकोड का Reed-Solomon त्रुटि सुधार स्तर। कम से उच्च: LevelL, LevelM, LevelQ, LevelH। |
| [getMicroQRVersion()](#getmicroqrversion) | पहचाने गए MicroQR कोड का संस्करण। M1 से M4 तक। |
| [getQRErrorLevel()](#getqrerrorlevel) ~~(deprecated)~~ | पहचाने गए बारकोड का Reed-Solomon त्रुटि सुधार स्तर। कम से उच्च: LevelL, LevelM, LevelQ, LevelH। |
| [getQRStructuredAppendModeBarCodeIndex()](#getqrstructuredappendmodebarcodeindex) ~~(deprecated)~~ | QR संरचित एपेंड मोड बारकोड का सूचकांक प्राप्त करता है। सूचकांक 0 से शुरू होता है। डिफ़ॉल्ट मान -1 है। मान: मात्रा का |
| [getQRStructuredAppendModeBarCodesQuantity()](#getqrstructuredappendmodebarcodesquantity) ~~(deprecated)~~ | QR संरचित एपेंड मोड बारकोड की मात्रा प्राप्त करता है। डिफ़ॉल्ट मान -1 है। मान: QR संरचित एपेंड की मात्रा |
| [getQRStructuredAppendModeParityData()](#getqrstructuredappendmodeparitydata) ~~(deprecated)~~ | QR संरचित एपेंड मोड पैरिटी डेटा प्राप्त करता है। डिफ़ॉल्ट मान -1 है। मान: QR संरचित एपेंड मोड बारकोड का सूचकांक |
| [getQRVersion()](#getqrversion) ~~(deprecated)~~ | पहचाने गए QR कोड का संस्करण। Version1 से Version40 तक। |
| [getRectMicroQRVersion()](#getrectmicroqrversion) | पहचाने गए RectMicroQR कोड का संस्करण। R7x43 से R17x139 तक। |
| [getStructuredAppendModeBarCodeIndex()](#getstructuredappendmodebarcodeindex) | QR संरचित एपेंड मोड बारकोड का सूचकांक प्राप्त करता है। सूचकांक 0 से शुरू होता है। डिफ़ॉल्ट मान -1 है। मान: मात्रा का |
| [getStructuredAppendModeBarCodesQuantity()](#getstructuredappendmodebarcodesquantity) | QR संरचित एपेंड मोड बारकोड की मात्रा प्राप्त करता है। डिफ़ॉल्ट मान -1 है। मान: QR संरचित एपेंड की मात्रा |
| [getStructuredAppendModeParityData()](#getstructuredappendmodeparitydata) | QR संरचित एपेंड मोड पैरिटी डेटा प्राप्त करता है। डिफ़ॉल्ट मान -1 है। मान: QR संरचित एपेंड मोड बारकोड का सूचकांक |
| [getVersion()](#getversion) | पहचाने गए QR कोड का संस्करण। Version1 से Version40 तक। |
| [hashCode()](#hashcode) | इस उदाहरण के लिए हैश कोड लौटाता है। |
| [isEmpty()](#isempty) | परीक्षण करता है कि क्या सभी पैरामीटर केवल डिफ़ॉल्ट मान रखते हैं। मान |
| [toString()](#tostring) | इस QRExtendedParameters की मानव-पठनीय स्ट्रिंग प्रतिनिधित्व लौटाता है। |

### equals(obj) {#equals}

एक मान लौटाता है जो दर्शाता है कि यह इंस्टेंस निर्दिष्ट QRExtendedParameters मान के बराबर है या नहीं।

| पैरामीटर | विवरण |
| --- | --- |
| obj | इस इंस्टेंस से तुलना करने के लिए एक ऑब्जेक्ट मान। |

**Returns:** true if obj has the same value as this instance; otherwise, false.

### getErrorLevel() {#geterrorlevel}

पहचाने गए बारकोड का Reed-Solomon त्रुटि सुधार स्तर। कम से उच्च: LevelL, LevelM, LevelQ, LevelH।

### getMicroQRVersion() {#getmicroqrversion}

पहचाने गए MicroQR कोड का संस्करण। M1 से M4 तक।

**Returns:** Version of recognized MicroQR Code. From M1 to M4.

### getQRErrorLevel() {#getqrerrorlevel}

> **Deprecated.** See method description for replacement.

पहचाने गए बारकोड का Reed-Solomon त्रुटि सुधार स्तर। कम से उच्च: LevelL, LevelM, LevelQ, LevelH।

**Returns:** Reed-Solomon error correction level of recognized barcode.

### getQRStructuredAppendModeBarCodeIndex() {#getqrstructuredappendmodebarcodeindex}

> **Deprecated.** See method description for replacement.

QR संरचित अपेंड मोड बारकोड का सूचकांक प्राप्त करता है। सूचकांक 0 से शुरू होता है। डिफ़ॉल्ट मान -1. मान: QR संरचित अपेंड मोड बारकोड की मात्रा।

### getQRStructuredAppendModeBarCodesQuantity() {#getqrstructuredappendmodebarcodesquantity}

> **Deprecated.** See method description for replacement.

QR संरचित अपेंड मोड बारकोड की मात्रा प्राप्त करता है। डिफ़ॉल्ट मान -1. मान: QR संरचित अपेंड मोड बारकोड की मात्रा।

### getQRStructuredAppendModeParityData() {#getqrstructuredappendmodeparitydata}

> **Deprecated.** See method description for replacement.

QR संरचित अपेंड मोड पैरिटी डेटा प्राप्त करता है। डिफ़ॉल्ट मान -1. मान: QR संरचित अपेंड मोड बारकोड का सूचकांक।

### getQRVersion() {#getqrversion}

> **Deprecated.** See method description for replacement.

पहचाने गए QR कोड का संस्करण। Version1 से Version40 तक।

**Returns:** Version of recognized QR Code

### getRectMicroQRVersion() {#getrectmicroqrversion}

पहचाने गए RectMicroQR कोड का संस्करण। R7x43 से R17x139 तक।

**Returns:** Version of recognized RectMicroQR Code

### getStructuredAppendModeBarCodeIndex() {#getstructuredappendmodebarcodeindex}

QR संरचित अपेंड मोड बारकोड का सूचकांक प्राप्त करता है। सूचकांक 0 से शुरू होता है। डिफ़ॉल्ट मान -1. मान: QR संरचित अपेंड मोड बारकोड की मात्रा।

**Returns:** the index of the QR structured append mode barcode.

### getStructuredAppendModeBarCodesQuantity() {#getstructuredappendmodebarcodesquantity}

QR संरचित अपेंड मोड बारकोड की मात्रा प्राप्त करता है। डिफ़ॉल्ट मान -1. मान: QR संरचित अपेंड मोड बारकोड की मात्रा।

**Returns:** the QR structured append mode barcodes quantity.

### getStructuredAppendModeParityData() {#getstructuredappendmodeparitydata}

QR संरचित अपेंड मोड पैरिटी डेटा प्राप्त करता है। डिफ़ॉल्ट मान -1. मान: QR संरचित अपेंड मोड बारकोड का सूचकांक।

**Returns:** the QR structured append mode parity data.

### getVersion() {#getversion}

पहचाने गए QR कोड का संस्करण। Version1 से Version40 तक।

### hashCode() {#hashcode}

इस उदाहरण के लिए हैश कोड लौटाता है।

**Returns:** A 32-bit signed integer hash code.

### isEmpty() {#isempty}

परीक्षण करता है कि क्या सभी पैरामीटर केवल डिफ़ॉल्ट मान रखते हैं। मान

**Returns:** true if all parameters has only default values; otherwise, `false `.

### toString() {#tostring}

इस QRExtendedParameters की मानव-पठनीय स्ट्रिंग प्रतिनिधित्व लौटाता है।

**Returns:** A string that represents this QRExtendedParameters.
