---
title: "AztecExtendedParameters"
linktitle: "AztecExtendedParameters"
second_title: "Aspose.BarCode के लिए Node.js via Java API संदर्भ"
description: "Aztec पहचाने गए बारकोड का विशेष डेटा संग्रहीत करता है। यह उदाहरण दिखाता है कि Aztec कच्चे मान कैसे प्राप्त करें let generator = new BarcodeGenerator(EncodeTypes.AZTEC, \"12345\"); "
type: docs
weight: 60
url: /hi/nodejs/aspose.barcode/aztecextendedparameters/
---

## AztecExtendedParameters class

Aztec पहचाने गए बारकोड का विशेष डेटा संग्रहीत करता है। यह उदाहरण दिखाता है कि Aztec कच्चे मान कैसे प्राप्त करें let generator = new BarcodeGenerator(EncodeTypes.AZTEC, "12345"); generator.save("test.png", BarcodeImageFormat.PNG);

```js
new AztecExtendedParameters()
```

**Example:**

```js
BarCodeReader reader = new BarCodeReader("test.png", null, DecodeType.AZTEC);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
    let result = results[i];
    console.log("BarCode type: " + result.getCodeTypeName());
    console.log("BarCode codetext: " + result.getCodeText());
    console.log("Aztec barcode ID: " + result.getExtended().getAztec().getStructuredAppendBarcodeId());
    console.log("Aztec barcodes count: " + result.getExtended().getAztec().getStructuredAppendBarcodesCount());
    console.log("Aztec file ID: " + result.getExtended().getAztec().getStructuredAppendFileId());
    console.log("Aztec is reader initialization: " + result.getExtended().getAztec().isReaderInitialization());
}
</pre>
</pre></blockquote></hr></p>
```

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [equals(obj)](#equals) | `AztecExtendedParameters` मान के साथ यह इंस्टेंस समान है या नहीं, यह दर्शाने वाला मान लौटाता है। |
| [getStructuredAppendBarcodeId()](#getstructuredappendbarcodeid) | Aztec स्ट्रक्चर्ड अपेंड मोड बारकोड का ID प्राप्त करता है। ID 1 से शुरू होती है और बारकोड की संख्या से कम या बराबर होनी चाहिए। D |
| [getStructuredAppendBarcodesCount()](#getstructuredappendbarcodescount) | Aztec स्ट्रक्चर्ड अपेंड मोड बारकोड की गिनती प्राप्त करता है। डिफ़ॉल्ट मान 0 है। गिनती 1 से 26 के बीच का मान होना चाहिए। Value: The |
| [getStructuredAppendFileId()](#getstructuredappendfileid) | Aztec स्ट्रक्चर्ड अपेंड मोड का फ़ाइल ID प्राप्त करता है। डिफ़ॉल्ट मान खाली स्ट्रिंग है। Value: The File ID of the Aztec stru |
| [hashCode()](#hashcode) | इस उदाहरण के लिए हैश कोड लौटाता है। |
| [isReaderInitialization()](#isreaderinitialization) | यह दर्शाता है कि कोड का उपयोग रीडर को निम्न डेटा को प्रारंभिक निर्देशों के रूप में व्याख्या करने के लिए किया जाता है या |
| [toString()](#tostring) | इस `AztecExtendedParameters` की मानव-पठनीय स्ट्रिंग प्रतिनिधित्व लौटाता है। |

### equals(obj) {#equals}

`AztecExtendedParameters` मान के साथ यह इंस्टेंस समान है या नहीं, यह दर्शाने वाला मान लौटाता है।

| पैरामीटर | विवरण |
| --- | --- |
| obj | इस इंस्टेंस से तुलना करने के लिए एक System.Object मान। |

**Returns:** `true ` if obj has the same value as this instance; otherwise, `false `.

### getStructuredAppendBarcodeId() {#getstructuredappendbarcodeid}

Aztec स्ट्रक्चर्ड अपेंड मोड बारकोड का ID प्राप्त करता है। ID 1 से शुरू होती है और बारकोड की संख्या से कम या बराबर होनी चाहिए। डिफ़ॉल्ट मान 0 है। Value: The barcode ID of the Aztec structured append mode.

### getStructuredAppendBarcodesCount() {#getstructuredappendbarcodescount}

Aztec स्ट्रक्चर्ड अपेंड मोड बारकोड की गिनती प्राप्त करता है। डिफ़ॉल्ट मान 0 है। गिनती 1 से 26 के बीच का मान होना चाहिए। Value: The barcodes count of the Aztec structured append mode.

### getStructuredAppendFileId() {#getstructuredappendfileid}

Aztec स्ट्रक्चर्ड अपेंड मोड का फ़ाइल ID प्राप्त करता है। डिफ़ॉल्ट मान खाली स्ट्रिंग है। Value: The File ID of the Aztec structured append mode.

### hashCode() {#hashcode}

इस उदाहरण के लिए हैश कोड लौटाता है।

**Returns:** 32-bit signed integer hash code.

### isReaderInitialization() {#isreaderinitialization}

यह दर्शाता है कि कोड का उपयोग रीडर को निम्न डेटा को प्रारंभिक या बारकोड रीडर के पुनःप्रोग्रामिंग निर्देशों के रूप में व्याख्या करने के लिए किया जाता है या नहीं। डिफ़ॉल्ट मान false है।

### toString() {#tostring}

इस `AztecExtendedParameters` की मानव-पठनीय स्ट्रिंग प्रतिनिधित्व लौटाता है।

**Returns:** A string that represents this `AztecExtendedParameters`.
