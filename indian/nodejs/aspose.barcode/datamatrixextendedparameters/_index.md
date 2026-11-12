---
title: "DataMatrixExtendedParameters"
linktitle: "DataMatrixExtendedParameters"
second_title: "Aspose.BarCode के लिए Node.js via Java API संदर्भ"
description: "DataMatrix पहचाने गए बारकोड का विशेष डेटा संग्रहीत करता है यह उदाहरण दिखाता है कि DataMatrix कच्चे मान कैसे प्राप्त करें let generator = new BarcodeGenerator(EncodeTypes.DATA_MA"
type: docs
weight: 350
url: /hi/nodejs/aspose.barcode/datamatrixextendedparameters/
---

## DataMatrixExtendedParameters class

DataMatrix पहचाने गए बारकोड का विशेष डेटा संग्रहीत करता है यह उदाहरण दिखाता है कि DataMatrix कच्चे मान कैसे प्राप्त करें let generator = new BarcodeGenerator(EncodeTypes.DATA_MATRIX, "12345")) generator.save("test.png", BarcodeImageFormat.PNG); let reader = new BarCodeReader("test.png", null, DecodeType.DATA_MATRIX)) let results = reader.readBarCodes(); for(let i = 0; i < results.length; i++) { let result = results[i]; console.log("BarCode type: " + result.getCodeTypeName()); console.log("BarCode codetext: " + result.getCodeText()); console.log("DataMatrix barcode ID: " + result.getExtended().getDataMatrix().getStructuredAppendBarcodeId()); console.log("DataMatrix barcodes count: " + result.getExtended().getDataMatrix().getStructuredAppendBarcodesCount()); console.log("DataMatrix file ID: " + result.getExtended().getDataMatrix().getStructuredAppendFileId()); console.log("DataMatrix is reader programming: " + result.getExtended().getDataMatrix().isReaderProgramming()); }

```js
new DataMatrixExtendedParameters()
```

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [equals(obj)](#equals) | यह दर्शाने वाला मान लौटाता है कि यह इंस्टेंस निर्दिष्ट `DataMatrixExtendedParameters` मान के बराबर है या नहीं। |
| [getStructuredAppendBarcodeId()](#getstructuredappendbarcodeid) | DataMatrix संरचित अपेंड मोड बारकोड का ID प्राप्त करता है। ID 1 से शुरू होती है और बारकोड की संख्या से कम या बराबर होनी चाहिए |
| [getStructuredAppendBarcodesCount()](#getstructuredappendbarcodescount) | DataMatrix संरचित अपेंड मोड बारकोड की गिनती प्राप्त करता है। डिफ़ॉल्ट मान -1 है। गिनती 1 से 35 के बीच का मान होना चाहिए। Valu |
| [getStructuredAppendFileId()](#getstructuredappendfileid) | DataMatrix संरचित अपेंड मोड बारकोड का ID प्राप्त करता है। ID 1 से शुरू होती है और बारकोड की संख्या से कम या बराबर होनी चाहिए |
| [hashCode()](#hashcode) | इस उदाहरण के लिए हैश कोड लौटाता है। |
| [isReaderProgramming()](#isreaderprogramming) | यह दर्शाता है कि कोड का उपयोग रीडर को निम्न डेटा को प्रारंभिक निर्देशों के रूप में व्याख्या करने के लिए किया जाता है या |
| [toString()](#tostring) | इस `DataMatrixExtendedParameters` का मानव-पठनीय स्ट्रिंग प्रतिनिधित्व लौटाता है। |

### equals(obj) {#equals}

यह दर्शाने वाला मान लौटाता है कि यह इंस्टेंस निर्दिष्ट `DataMatrixExtendedParameters` मान के बराबर है या नहीं।

| पैरामीटर | विवरण |
| --- | --- |
| obj | इस इंस्टेंस से तुलना करने के लिए एक System.Object मान। |

**Returns:** `true ` if obj has the same value as this instance; otherwise, `false `.

### getStructuredAppendBarcodeId() {#getstructuredappendbarcodeid}

DataMatrix संरचित अपेंड मोड बारकोड का ID प्राप्त करता है। ID 1 से शुरू होती है और बारकोड की गिनती से कम या बराबर होनी चाहिए। डिफ़ॉल्ट मान -1 है। मान: DataMatrix संरचित अपेंड मोड बारकोड का ID।

### getStructuredAppendBarcodesCount() {#getstructuredappendbarcodescount}

DataMatrix संरचित अपेंड मोड बारकोड की गिनती प्राप्त करता है। डिफ़ॉल्ट मान -1 है। गिनती 1 से 35 के बीच का मान होना चाहिए। मान: DataMatrix संरचित अपेंड मोड बारकोड की गिनती।

### getStructuredAppendFileId() {#getstructuredappendfileid}

DataMatrix संरचित अपेंड मोड बारकोड का ID प्राप्त करता है। ID 1 से शुरू होती है और बारकोड की गिनती से कम या बराबर होनी चाहिए। डिफ़ॉल्ट मान -1 है। मान: DataMatrix संरचित अपेंड मोड बारकोड का ID।

### hashCode() {#hashcode}

इस उदाहरण के लिए हैश कोड लौटाता है।

**Returns:** A 32-bit signed integer hash code.

### isReaderProgramming() {#isreaderprogramming}

यह दर्शाता है कि कोड का उपयोग रीडर को निम्न डेटा को प्रारंभिक या बारकोड रीडर के पुनःप्रोग्रामिंग निर्देशों के रूप में व्याख्या करने के लिए किया जाता है या नहीं। डिफ़ॉल्ट मान false है।

### toString() {#tostring}

इस `DataMatrixExtendedParameters` का मानव-पठनीय स्ट्रिंग प्रतिनिधित्व लौटाता है।

**Returns:** A string that represents this `DataMatrixExtendedParameters`.
