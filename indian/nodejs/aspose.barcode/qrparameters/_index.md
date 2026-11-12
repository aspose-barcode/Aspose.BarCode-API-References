---
title: "QrParameters"
linktitle: "QrParameters"
second_title: "Aspose.BarCode के लिए Node.js via Java API संदर्भ"
description: "QR पैरामीटर।"
type: docs
weight: 830
url: /hi/nodejs/aspose.barcode/qrparameters/
---

## QrParameters class

QR पैरामीटर।

```js
new QrParameters()
```

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [getAspectRatio()](#getaspectratio) | 2D बारकोड मॉड्यूल की ऊँचाई/चौड़ाई अनुपात। |
| [getECIEncoding()](#geteciencoding) | विस्तारित चैनल इंटरप्रिटेशन पहचानकर्ता। इसका उपयोग बारकोड रीडर को उपयोग किए गए संदर्भों के बारे में विवरण बताने के लिए किया जाता है। |
| [getEncodeGS1SeparatorInByteMode()](#getencodegs1separatorinbytemode) | QR और RectMicroQR बार के लिए बाइट मोड में GS1 विशेष अक्षरों को एन्कोड किया जाना चाहिए या नहीं, यह दर्शाने वाला मान प्राप्त करता है या सेट करता है। |
| [getEncodeMode()](#getencodemode) | बारकोड की एन्कोडिंग मोड का QR प्रतीक प्रकार। डिफ़ॉल्ट मान: QREncodeMode.Auto. |
| [getErrorLevel()](#geterrorlevel) | QR, MicroQR और RectMicroQR बारकोड के लिए रीड़-सोलोमन त्रुटि सुधार का स्तर। कम से उच्च: LevelL, LevelM, LevelQ |
| [getMicroQRVersion()](#getmicroqrversion) | MicroQR कोड का संस्करण। संस्करण M1 से संस्करण M4 तक। डिफ़ॉल्ट मान: MicroQRVersion.Auto. |
| [getQrECIEncoding()](#getqreciencoding) ~~(deprecated)~~ | विस्तारित चैनल इंटरप्रिटेशन पहचानकर्ता। इसका उपयोग बारकोड रीडर को उपयोग किए गए संदर्भों के बारे में विवरण बताने के लिए किया जाता है। |
| [getQrEncodeMode()](#getqrencodemode) | बारकोड की एन्कोडिंग मोड का QR प्रतीक प्रकार। डिफ़ॉल्ट मान: QREncodeMode.AUTO. |
| [getQrEncodeType()](#getqrencodetype) ~~(deprecated)~~ | QR / MicroQR चयनकर्ता मोड। मानक QR प्रतीकों के लिए ForceQR चुनें, MicroQR के लिए Auto। |
| [getQrErrorLevel()](#getqrerrorlevel) ~~(deprecated)~~ | QR बारकोड के लिए रीड़-सोलोमन त्रुटि सुधार का स्तर। कम से उच्च: LEVEL_L, LEVEL_M, LEVEL_Q, LEVEL_H। देखें QRError |
| [getQrVersion()](#getqrversion) ~~(deprecated)~~ | QR कोड का संस्करण। QR कोड के लिए Version1 से Version40 तक और MicroQr के लिए M1 से M4 तक। डिफ़ॉल्ट मान: QRVersion.AUT |
| [getRectMicroQrVersion()](#getrectmicroqrversion) | RectMicroQR कोड का संस्करण। संस्करण R7x59 से संस्करण R17x139 तक। डिफ़ॉल्ट मान: RectMicroQRVersion.Auto. |
| [getStructuredAppend()](#getstructuredappend) | QR Structured Append पैरामीटर। |
| [getVersion()](#getversion) | QR कोड का संस्करण। Version1 से Version40 तक। डिफ़ॉल्ट मान: QRVersion.Auto. |
| [setAspectRatio()](#setaspectratio) | 2D बारकोड मॉड्यूल की ऊँचाई/चौड़ाई अनुपात। |
| [setECIEncoding()](#seteciencoding) | विस्तारित चैनल इंटरप्रिटेशन पहचानकर्ता। इसका उपयोग बारकोड रीडर को उपयोग किए गए संदर्भों के बारे में विवरण बताने के लिए किया जाता है। |
| [setEncodeGS1SeparatorInByteMode(value)](#setencodegs1separatorinbytemode) | QR और RectMicroQR बार के लिए बाइट मोड में GS1 विशेष अक्षरों को एन्कोड किया जाना चाहिए या नहीं, यह दर्शाने वाला मान प्राप्त करता है या सेट करता है। |
| [setEncodeMode()](#setencodemode) | बारकोड की एन्कोडिंग मोड का QR प्रतीक प्रकार। डिफ़ॉल्ट मान: QREncodeMode.Auto. |
| [setErrorLevel()](#seterrorlevel) | QR, MicroQR और RectMicroQR बारकोड के लिए रीड़-सोलोमन त्रुटि सुधार का स्तर। कम से उच्च: LevelL, LevelM, LevelQ |
| [setMicroQRVersion()](#setmicroqrversion) | MicroQR कोड का संस्करण। संस्करण M1 से संस्करण M4 तक। डिफ़ॉल्ट मान: MicroQRVersion.Auto. |
| [setQrECIEncoding()](#setqreciencoding) ~~(deprecated)~~ | विस्तारित चैनल इंटरप्रिटेशन पहचानकर्ता। इसका उपयोग बारकोड रीडर को उपयोग किए गए संदर्भों के बारे में विवरण बताने के लिए किया जाता है। |
| [setQrEncodeMode()](#setqrencodemode) ~~(deprecated)~~ | बारकोड की एन्कोडिंग मोड का QR प्रतीक प्रकार। डिफ़ॉल्ट मान: QREncodeMode.AUTO. |
| [setQrEncodeType()](#setqrencodetype) ~~(deprecated)~~ | QR / MicroQR चयनकर्ता मोड। मानक QR प्रतीकों के लिए ForceQR चुनें, MicroQR के लिए Auto। |
| [setQrErrorLevel()](#setqrerrorlevel) ~~(deprecated)~~ | QR बारकोड के लिए रीड़-सोलोमन त्रुटि सुधार का स्तर। कम से उच्च: LEVEL_L, LEVEL_M, LEVEL_Q, LEVEL_H। देखें QRError |
| [setQrVersion()](#setqrversion) ~~(deprecated)~~ | QR कोड का संस्करण। QR कोड के लिए Version1 से Version40 तक और MicroQr के लिए M1 से M4 तक। डिफ़ॉल्ट मान: QRVersion.AUT |
| [setRectMicroQrVersion()](#setrectmicroqrversion) | RectMicroQR कोड का संस्करण। संस्करण R7x59 से संस्करण R17x139 तक। डिफ़ॉल्ट मान: RectMicroQRVersion.Auto. |
| [setStructuredAppend()](#setstructuredappend) | QR Structured Append पैरामीटर। |
| [setVersion()](#setversion) | QR कोड का संस्करण। Version1 से Version40 तक। डिफ़ॉल्ट मान: QRVersion.Auto. |
| [toString()](#tostring) | इस QrParameters की मानव-पठनीय स्ट्रिंग प्रतिनिधित्व लौटाता है। |

### getAspectRatio() {#getaspectratio}

2D बारकोड मॉड्यूल की ऊँचाई/चौड़ाई अनुपात।

### getECIEncoding() {#geteciencoding}

विस्तारित चैनल इंटरप्रिटेशन पहचानकर्ता। यह बारकोड रीडर को प्रतीक में डेटा एन्कोड करने के लिए उपयोग किए गए संदर्भों के बारे में विवरण बताने के लिए उपयोग किया जाता है। वर्तमान कार्यान्वयन सभी ज्ञात कैरेक्टरसेट एन्कोडिंग्स को शामिल करता है। MicroQR द्वारा समर्थित नहीं।

### getEncodeGS1SeparatorInByteMode() {#getencodegs1separatorinbytemode}

QR और RectMicroQR बारकोड के लिए बाइट मोड में GS1 विशेष अक्षरों को एन्कोड किया जाना चाहिए या नहीं, यह दर्शाने वाला मान प्राप्त करता है या सेट करता है। यदि false है, तो QR विनिर्देश के अनुसार अल्फ़ान्यूमेरिक मोड में GS1 विभाजकों को '%' के रूप में एन्कोड किया जा सकता है। यदि true है, तो GS1 समूह विभाजकों को 0x1D अक्षर के रूप में बाइट मोड में एन्कोड किया जाता है, और '%' अक्षरों को भी डेटा के रूप में संरक्षित रखने के लिए बाइट मोड में एन्कोड किया जाता है। यह विकल्प उन डिकोडरों के साथ संगतता को सुधार सकता है जो बाइट-स्तर के GS1 समूह विभाजकों की अपेक्षा करते हैं और '%' डेटा अक्षरों को GS1 विभाजकों के रूप में व्याख्या होने से रोकता है।

**Returns:** a value indicating whether GS1 special characters should be encoded in Byte mode for QR and RectMicroQR barcodes.

### getEncodeMode() {#getencodemode}

बारकोड की एन्कोडिंग मोड का QR प्रतीक प्रकार। डिफ़ॉल्ट मान: QREncodeMode.Auto.

### getErrorLevel() {#geterrorlevel}

QR, MicroQR और RectMicroQR बारकोड के लिए रीड़-सोलोमन त्रुटि सुधार का स्तर। कम से उच्च: LevelL, LevelM, LevelQ, LevelH। देखें QRErrorLevel.

### getMicroQRVersion() {#getmicroqrversion}

MicroQR कोड का संस्करण। संस्करण M1 से संस्करण M4 तक। डिफ़ॉल्ट मान: MicroQRVersion.Auto.

### getQrECIEncoding() {#getqreciencoding}

> **Deprecated.** See method description for replacement.

विस्तारित चैनल इंटरप्रिटेशन पहचानकर्ता। यह बारकोड रीडर को प्रतीक में डेटा एन्कोड करने के लिए उपयोग किए गए संदर्भों के बारे में विवरण बताने के लिए उपयोग किया जाता है। वर्तमान कार्यान्वयन सभी ज्ञात कैरेक्टरसेट एन्कोडिंग से बना है।

### getQrEncodeMode() {#getqrencodemode}

बारकोड की एन्कोडिंग मोड का QR प्रतीक प्रकार। डिफ़ॉल्ट मान: QREncodeMode.AUTO.

### getQrEncodeType() {#getqrencodetype}

> **Deprecated.** See method description for replacement.

QR / MicroQR चयनकर्ता मोड। मानक QR प्रतीकों के लिए ForceQR चुनें, MicroQR के लिए Auto।

### getQrErrorLevel() {#getqrerrorlevel}

> **Deprecated.** See method description for replacement.

QR बारकोड के लिए रीड़-सोलोमन त्रुटि सुधार का स्तर। कम से उच्च: LEVEL_L, LEVEL_M, LEVEL_Q, LEVEL_H। देखें QRErrorLevel.

### getQrVersion() {#getqrversion}

> **Deprecated.** See method description for replacement.

QR कोड का संस्करण। QR कोड के लिए Version1 से Version40 तक और MicroQr के लिए M1 से M4 तक। डिफ़ॉल्ट मान: QRVersion.AUTO.

### getRectMicroQrVersion() {#getrectmicroqrversion}

RectMicroQR कोड का संस्करण। संस्करण R7x59 से संस्करण R17x139 तक। डिफ़ॉल्ट मान: RectMicroQRVersion.Auto.

### getStructuredAppend() {#getstructuredappend}

QR Structured Append पैरामीटर।

### getVersion() {#getversion}

QR कोड का संस्करण। Version1 से Version40 तक। डिफ़ॉल्ट मान: QRVersion.Auto.

### setAspectRatio() {#setaspectratio}

2D बारकोड मॉड्यूल की ऊँचाई/चौड़ाई अनुपात।

### setECIEncoding() {#seteciencoding}

विस्तारित चैनल इंटरप्रिटेशन पहचानकर्ता। यह बारकोड रीडर को प्रतीक में डेटा एन्कोड करने के लिए उपयोग किए गए संदर्भों के बारे में विवरण बताने के लिए उपयोग किया जाता है। वर्तमान कार्यान्वयन सभी ज्ञात कैरेक्टरसेट एन्कोडिंग्स को शामिल करता है। MicroQR द्वारा समर्थित नहीं।

### setEncodeGS1SeparatorInByteMode(value) {#setencodegs1separatorinbytemode}

QR और RectMicroQR बारकोड के लिए बाइट मोड में GS1 विशेष अक्षरों को एन्कोड किया जाना चाहिए या नहीं, यह दर्शाने वाला मान प्राप्त करता है या सेट करता है। यदि false है, तो QR विनिर्देश के अनुसार अल्फ़ान्यूमेरिक मोड में GS1 विभाजकों को '%' के रूप में एन्कोड किया जा सकता है। यदि true है, तो GS1 समूह विभाजकों को 0x1D अक्षर के रूप में बाइट मोड में एन्कोड किया जाता है, और '%' अक्षरों को भी डेटा के रूप में संरक्षित रखने के लिए बाइट मोड में एन्कोड किया जाता है। यह विकल्प उन डिकोडरों के साथ संगतता को सुधार सकता है जो बाइट-स्तर के GS1 समूह विभाजकों की अपेक्षा करते हैं और '%' डेटा अक्षरों को GS1 विभाजकों के रूप में व्याख्या होने से रोकता है।

| पैरामीटर | विवरण |
| --- | --- |
| मान | QR और RectMicroQR बारकोड के लिए बाइट मोड में GS1 विशेष अक्षरों को एन्कोड किया जाना चाहिए या नहीं, यह दर्शाने वाला मान। |

### setEncodeMode() {#setencodemode}

बारकोड की एन्कोडिंग मोड का QR प्रतीक प्रकार। डिफ़ॉल्ट मान: QREncodeMode.Auto.

### setErrorLevel() {#seterrorlevel}

QR, MicroQR और RectMicroQR बारकोड के लिए रीड़-सोलोमन त्रुटि सुधार का स्तर। कम से उच्च: LevelL, LevelM, LevelQ, LevelH। देखें QRErrorLevel.

### setMicroQRVersion() {#setmicroqrversion}

MicroQR कोड का संस्करण। संस्करण M1 से संस्करण M4 तक। डिफ़ॉल्ट मान: MicroQRVersion.Auto.

### setQrECIEncoding() {#setqreciencoding}

> **Deprecated.** See method description for replacement.

विस्तारित चैनल इंटरप्रिटेशन पहचानकर्ता। यह बारकोड रीडर को प्रतीक में डेटा एन्कोड करने के लिए उपयोग किए गए संदर्भों के बारे में विवरण बताने के लिए उपयोग किया जाता है। वर्तमान कार्यान्वयन सभी ज्ञात कैरेक्टरसेट एन्कोडिंग से बना है।

### setQrEncodeMode() {#setqrencodemode}

> **Deprecated.** See method description for replacement.

बारकोड की एन्कोडिंग मोड का QR प्रतीक प्रकार। डिफ़ॉल्ट मान: QREncodeMode.AUTO.

### setQrEncodeType() {#setqrencodetype}

> **Deprecated.** See method description for replacement.

QR / MicroQR चयनकर्ता मोड। मानक QR प्रतीकों के लिए ForceQR चुनें, MicroQR के लिए Auto।

### setQrErrorLevel() {#setqrerrorlevel}

> **Deprecated.** See method description for replacement.

QR बारकोड के लिए रीड़-सोलोमन त्रुटि सुधार का स्तर। कम से उच्च: LEVEL_L, LEVEL_M, LEVEL_Q, LEVEL_H। देखें QRErrorLevel.

### setQrVersion() {#setqrversion}

> **Deprecated.** See method description for replacement.

QR कोड का संस्करण। QR कोड के लिए Version1 से Version40 तक और MicroQr के लिए M1 से M4 तक। डिफ़ॉल्ट मान: QRVersion.AUTO.

### setRectMicroQrVersion() {#setrectmicroqrversion}

RectMicroQR कोड का संस्करण। संस्करण R7x59 से संस्करण R17x139 तक। डिफ़ॉल्ट मान: RectMicroQRVersion.Auto.

### setStructuredAppend() {#setstructuredappend}

QR Structured Append पैरामीटर।

### setVersion() {#setversion}

QR कोड का संस्करण। Version1 से Version40 तक। डिफ़ॉल्ट मान: QRVersion.Auto.

### toString() {#tostring}

इस QrParameters की मानव-पठनीय स्ट्रिंग प्रतिनिधित्व लौटाता है।

**Returns:** A string that represents this QrParameters.
