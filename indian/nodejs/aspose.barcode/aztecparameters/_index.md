---
title: "AztecParameters"
linktitle: "AztecParameters"
second_title: "Aspose.BarCode के लिए Node.js via Java API संदर्भ"
description: "Aztec पैरामीटर।"
type: docs
weight: 70
url: /hi/nodejs/aspose.barcode/aztecparameters/
---

## AztecParameters class

Aztec पैरामीटर।

```js
new AztecParameters()
```

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [getAspectRatio()](#getaspectratio) | 2D बारकोड मॉड्यूल की ऊँचाई/चौड़ाई अनुपात। |
| [getAztecEncodeMode()](#getaztecencodemode) ~~(deprecated)~~ | Aztec एन्कोड मोड प्राप्त करता है। डिफ़ॉल्ट मान: Auto. |
| [getAztecErrorLevel()](#getaztecerrorlevel) ~~(deprecated)~~ | Aztec प्रकार के बारकोड की त्रुटि सुधार स्तर। मान 5 से 95 के बीच होना चाहिए। |
| [getAztecSymbolMode()](#getaztecsymbolmode) ~~(deprecated)~~ | Aztec सिम्बॉल मोड प्राप्त करता है। डिफ़ॉल्ट मान: AztecSymbolMode.Auto. |
| [getECIEncoding()](#geteciencoding) | ECI एन्कोडिंग प्राप्त करता है। जब AztecEncodeMode Auto हो तो उपयोग किया जाता है। डिफ़ॉल्ट मान: ISO-8859-1 |
| [getEncodeMode()](#getencodemode) | Aztec एन्कोड मोड प्राप्त करता है। डिफ़ॉल्ट मान: Auto. |
| [getErrorLevel()](#geterrorlevel) | Aztec प्रकार के बारकोड की त्रुटि सुधार स्तर। मान 5 से 95 के बीच होना चाहिए। |
| [getLayersCount()](#getlayerscount) | Aztec सिम्बॉल की लेयर गिनती प्राप्त करता है। कॉम्पैक्ट मोड के लिए लेयर गिनती 1 से 3 के बीच होनी चाहिए और सामान्य मोड में भी 1 से 3 के बीच। |
| [getStructuredAppendBarcodeId()](#getstructuredappendbarcodeid) | Aztec बारकोड के स्ट्रक्चर्ड अपेंड मोड के लिए बारकोड ID। बारकोड ID 1 से बारकोड की कुल संख्या तक के दायरे में होना चाहिए। डिफ़ॉल्ट |
| [getStructuredAppendBarcodesCount()](#getstructuredappendbarcodescount) | Aztec बारकोड के Structured Append मोड के लिए बारकोड की संख्या। बारकोड की संख्या 1 से 26 की सीमा में होनी चाहिए। डिफ़ॉल्ट मान |
| [getStructuredAppendFileId()](#getstructuredappendfileid) | Aztec बारकोड के Structured Append मोड के लिए फ़ाइल आईडी (वैकल्पिक फ़ील्ड)। फ़ाइल आईडी में स्पेस नहीं होना चाहिए। डिफ़ॉल्ट मान: |
| [getSymbolMode()](#getsymbolmode) | Aztec सिम्बॉल मोड प्राप्त करता है। डिफ़ॉल्ट मान: AztecSymbolMode.Auto. |
| [isReaderInitialization()](#isreaderinitialization) | रीडर को यह निर्देश देने के लिए उपयोग किया जाता है कि वह प्रतीक में निहित डेटा को रीडर प्रारंभिककरण के लिए प्रोग्रामिंग के रूप में व्याख्या करे। |
| [setAspectRatio()](#setaspectratio) | 2D बारकोड मॉड्यूल की ऊँचाई/चौड़ाई अनुपात। |
| [setAztecEncodeMode()](#setaztecencodemode) ~~(deprecated)~~ | Aztec एन्कोड मोड सेट करता है। डिफ़ॉल्ट मान: Auto. |
| [setAztecErrorLevel()](#setaztecerrorlevel) ~~(deprecated)~~ | Aztec प्रकार के बारकोड की त्रुटि सुधार स्तर। मान 5 से 95 के बीच होना चाहिए। |
| [setAztecSymbolMode()](#setaztecsymbolmode) ~~(deprecated)~~ | Aztec सिम्बल मोड सेट करता है। डिफ़ॉल्ट मान: AztecSymbolMode.Auto. |
| [setECIEncoding()](#seteciencoding) | ECI एन्कोडिंग सेट करता है। जब AztecEncodeMode Auto हो तब उपयोग किया जाता है। डिफ़ॉल्ट मान: ISO-8859-1 |
| [setEncodeMode(value)](#setencodemode) | Aztec एन्कोड मोड सेट करता है। डिफ़ॉल्ट मान: Auto. |
| [setErrorLevel()](#seterrorlevel) | Aztec प्रकार के बारकोड की त्रुटि सुधार स्तर। मान 5 से 95 के बीच होना चाहिए। |
| [setLayersCount()](#setlayerscount) | Aztec सिम्बल की लेयर्स की संख्या सेट करता है। कॉम्पैक्ट मोड के लिए लेयर्स की संख्या 1 से 3 की सीमा में और 1 से 3 की सीमा में होनी चाहिए |
| [setReaderInitialization()](#setreaderinitialization) | रीडर को यह निर्देश देने के लिए उपयोग किया जाता है कि वह प्रतीक में निहित डेटा को रीडर प्रारंभिककरण के लिए प्रोग्रामिंग के रूप में व्याख्या करे। |
| [setStructuredAppendBarcodeId()](#setstructuredappendbarcodeid) | Aztec बारकोड के स्ट्रक्चर्ड अपेंड मोड के लिए बारकोड ID। बारकोड ID 1 से बारकोड की कुल संख्या तक के दायरे में होना चाहिए। डिफ़ॉल्ट |
| [setStructuredAppendBarcodesCount()](#setstructuredappendbarcodescount) | Aztec बारकोड के Structured Append मोड के लिए बारकोड की संख्या। बारकोड की संख्या 1 से 26 की सीमा में होनी चाहिए। डिफ़ॉल्ट मान |
| [setStructuredAppendFileId()](#setstructuredappendfileid) | Aztec बारकोड के Structured Append मोड के लिए फ़ाइल आईडी (वैकल्पिक फ़ील्ड)। फ़ाइल आईडी में स्पेस नहीं होना चाहिए। डिफ़ॉल्ट मान: |
| [setSymbolMode(value)](#setsymbolmode) | Aztec सिम्बल मोड सेट करता है। डिफ़ॉल्ट मान: AztecSymbolMode.Auto. |
| [toString()](#tostring) | इस `AztecParameters` की मानव-पठनीय स्ट्रिंग प्रतिनिधित्व लौटाता है। |

### getAspectRatio() {#getaspectratio}

2D बारकोड मॉड्यूल की ऊँचाई/चौड़ाई अनुपात।

### getAztecEncodeMode() {#getaztecencodemode}

> **Deprecated.** See method description for replacement.

Aztec एन्कोड मोड प्राप्त करता है। डिफ़ॉल्ट मान: Auto.

### getAztecErrorLevel() {#getaztecerrorlevel}

> **Deprecated.** See method description for replacement.

Aztec प्रकार के बारकोड की त्रुटि सुधार स्तर। मान 5 से 95 के बीच होना चाहिए।

### getAztecSymbolMode() {#getaztecsymbolmode}

> **Deprecated.** See method description for replacement.

Aztec सिम्बॉल मोड प्राप्त करता है। डिफ़ॉल्ट मान: AztecSymbolMode.Auto.

### getECIEncoding() {#geteciencoding}

ECI एन्कोडिंग प्राप्त करता है। जब AztecEncodeMode Auto हो तो उपयोग किया जाता है। डिफ़ॉल्ट मान: ISO-8859-1

### getEncodeMode() {#getencodemode}

Aztec एन्कोड मोड प्राप्त करता है। डिफ़ॉल्ट मान: Auto.

**Returns:** a Aztec encode mode.

### getErrorLevel() {#geterrorlevel}

Aztec प्रकार के बारकोड की त्रुटि सुधार स्तर। मान 5 से 95 के बीच होना चाहिए।

### getLayersCount() {#getlayerscount}

Aztec सिम्बल की लेयर्स की संख्या प्राप्त करता है। कॉम्पैक्ट मोड के लिए लेयर्स की संख्या 1 से 3 की सीमा में और फुल रेंज मोड के लिए 1 से 32 की सीमा में होनी चाहिए। डिफ़ॉल्ट मान: 0 (auto)।

### getStructuredAppendBarcodeId() {#getstructuredappendbarcodeid}

Aztec बारकोड के Structured Append मोड के लिए बारकोड आईडी। बारकोड आईडी 1 से बारकोड की संख्या की सीमा में होनी चाहिए। डिफ़ॉल्ट मान: 0

### getStructuredAppendBarcodesCount() {#getstructuredappendbarcodescount}

Aztec बारकोड के Structured Append मोड के लिए बारकोड की संख्या। बारकोड की संख्या 1 से 26 की सीमा में होनी चाहिए। डिफ़ॉल्ट मान: 0

### getStructuredAppendFileId() {#getstructuredappendfileid}

Aztec बारकोड के Structured Append मोड के लिए फ़ाइल आईडी (वैकल्पिक फ़ील्ड)। फ़ाइल आईडी में स्पेस नहीं होना चाहिए। डिफ़ॉल्ट मान: खाली स्ट्रिंग

### getSymbolMode() {#getsymbolmode}

Aztec सिम्बॉल मोड प्राप्त करता है। डिफ़ॉल्ट मान: AztecSymbolMode.Auto.

**Returns:** a Aztec Symbol mode.

### isReaderInitialization() {#isreaderinitialization}

रीडर को यह निर्देश देने के लिए उपयोग किया जाता है कि वह प्रतीक में निहित डेटा को रीडर प्रारंभिककरण के लिए प्रोग्रामिंग के रूप में व्याख्या करे।

### setAspectRatio() {#setaspectratio}

2D बारकोड मॉड्यूल की ऊँचाई/चौड़ाई अनुपात।

### setAztecEncodeMode() {#setaztecencodemode}

> **Deprecated.** See method description for replacement.

Aztec एन्कोड मोड सेट करता है। डिफ़ॉल्ट मान: Auto.

### setAztecErrorLevel() {#setaztecerrorlevel}

> **Deprecated.** See method description for replacement.

Aztec प्रकार के बारकोड की त्रुटि सुधार स्तर। मान 5 से 95 के बीच होना चाहिए।

### setAztecSymbolMode() {#setaztecsymbolmode}

> **Deprecated.** See method description for replacement.

Aztec सिम्बल मोड सेट करता है। डिफ़ॉल्ट मान: AztecSymbolMode.Auto.

### setECIEncoding() {#seteciencoding}

ECI एन्कोडिंग सेट करता है। जब AztecEncodeMode Auto हो तब उपयोग किया जाता है। डिफ़ॉल्ट मान: ISO-8859-1

### setEncodeMode(value) {#setencodemode}

Aztec एन्कोड मोड सेट करता है। डिफ़ॉल्ट मान: Auto.

| पैरामीटर | विवरण |
| --- | --- |
| मान | एक Aztec एन्कोड मोड। |

### setErrorLevel() {#seterrorlevel}

Aztec प्रकार के बारकोड की त्रुटि सुधार स्तर। मान 5 से 95 के बीच होना चाहिए।

### setLayersCount() {#setlayerscount}

Aztec सिम्बल की लेयर्स की संख्या सेट करता है। कॉम्पैक्ट मोड के लिए लेयर्स की संख्या 1 से 3 की सीमा में और फुल रेंज मोड के लिए 1 से 32 की सीमा में होनी चाहिए। डिफ़ॉल्ट मान: 0 (auto)।

### setReaderInitialization() {#setreaderinitialization}

रीडर को यह निर्देश देने के लिए उपयोग किया जाता है कि वह प्रतीक में निहित डेटा को रीडर प्रारंभिककरण के लिए प्रोग्रामिंग के रूप में व्याख्या करे।

### setStructuredAppendBarcodeId() {#setstructuredappendbarcodeid}

Aztec बारकोड के Structured Append मोड के लिए बारकोड आईडी। बारकोड आईडी 1 से बारकोड की संख्या की सीमा में होनी चाहिए। डिफ़ॉल्ट मान: 0

### setStructuredAppendBarcodesCount() {#setstructuredappendbarcodescount}

Aztec बारकोड के Structured Append मोड के लिए बारकोड की संख्या। बारकोड की संख्या 1 से 26 की सीमा में होनी चाहिए। डिफ़ॉल्ट मान: 0

### setStructuredAppendFileId() {#setstructuredappendfileid}

Aztec बारकोड के Structured Append मोड के लिए फ़ाइल आईडी (वैकल्पिक फ़ील्ड)। फ़ाइल आईडी में स्पेस नहीं होना चाहिए। डिफ़ॉल्ट मान: खाली स्ट्रिंग

### setSymbolMode(value) {#setsymbolmode}

Aztec सिम्बल मोड सेट करता है। डिफ़ॉल्ट मान: AztecSymbolMode.Auto.

| पैरामीटर | विवरण |
| --- | --- |
| मान | एक Aztec सिम्बल मोड। |

### toString() {#tostring}

इस `AztecParameters` की मानव-पठनीय स्ट्रिंग प्रतिनिधित्व लौटाता है।

**Returns:** A string that represents this `AztecParameters`.
