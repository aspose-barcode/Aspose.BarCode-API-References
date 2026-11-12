---
title: "DotCodeExtendedParameters"
linktitle: "DotCodeExtendedParameters"
second_title: "Aspose.BarCode के लिए Node.js via Java API संदर्भ"
description: "DotCode पहचाने गए बारकोड का विशेष डेटा संग्रहीत करता है यह उदाहरण दिखाता है कि DotCode कच्चे मान कैसे प्राप्त करें"
type: docs
weight: 380
url: /hi/nodejs/aspose.barcode/dotcodeextendedparameters/
---

## DotCodeExtendedParameters class

DotCode पहचाने गए बारकोड का विशेष डेटा संग्रहीत करता है यह उदाहरण दिखाता है कि DotCode कच्चे मान कैसे प्राप्त करें

```js
new DotCodeExtendedParameters()
```

**Example:**

```js
let generator = new BarcodeGenerator(EncodeTypes.DOT_CODE, "12345");
generator.save("test.png", BarCodeImageFormat.PNG);

let reader = new BarCodeReader("test.png", null, DecodeType.DOT_CODE);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
    let result = results[i];
    print("BarCode type: " + result.getCodeTypeName());
    print("BarCode codetext: " + result.getCodeText());
    print("DotCode barcode ID: " + result.getExtended().getDotCode().getDotCodeStructuredAppendModeBarcodeId());
    print("DotCode barcodes count: " + result.getExtended().getDotCode().getDotCodeStructuredAppendModeBarcodesCount());
}
```

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [equals(obj)](#equals) | एक मान लौटाता है जो दर्शाता है कि यह इंस्टेंस निर्दिष्ट `DotCodeExtendedParameters` मान के बराबर है या नहीं। |
| [getDotCodeIsReaderInitialization()](#getdotcodeisreaderinitialization) ~~(deprecated)~~ | यह दर्शाता है कि कोड का उपयोग रीडर को निम्न डेटा को प्रारंभिक निर्देशों के रूप में व्याख्या करने के लिए किया जाता है या |
| [getDotCodeStructuredAppendModeBarcodeId()](#getdotcodestructuredappendmodebarcodeid) ~~(deprecated)~~ | DotCode संरचित एपेंड मोड बारकोड का ID प्राप्त करता है। ID 1 से शुरू होती है और बारकोड की संख्या से कम या बराबर होनी चाहिए। |
| [getDotCodeStructuredAppendModeBarcodesCount()](#getdotcodestructuredappendmodebarcodescount) ~~(deprecated)~~ | DotCode संरचित एपेंड मोड बारकोड की गिनती प्राप्त करता है। डिफ़ॉल्ट मान -1 है। गिनती 1 से 35 के बीच का मान होना चाहिए। मान: |
| [getStructuredAppendModeBarcodeId()](#getstructuredappendmodebarcodeid) | DotCode संरचित एपेंड मोड बारकोड का ID प्राप्त करता है। ID 1 से शुरू होती है और बारकोड की संख्या से कम या बराबर होनी चाहिए। |
| [getStructuredAppendModeBarcodesCount()](#getstructuredappendmodebarcodescount) | DotCode संरचित एपेंड मोड बारकोड की गिनती प्राप्त करता है। डिफ़ॉल्ट मान -1 है। गिनती 1 से 35 के बीच का मान होना चाहिए। मान: |
| [hashCode()](#hashcode) | इस उदाहरण के लिए हैश कोड लौटाता है। |
| [isReaderInitialization()](#isreaderinitialization) | यह दर्शाता है कि कोड का उपयोग रीडर को निम्न डेटा को प्रारंभिक निर्देशों के रूप में व्याख्या करने के लिए किया जाता है या |
| [toString()](#tostring) | इस `DotCodeExtendedParameters` का मानव-पठनीय स्ट्रिंग प्रतिनिधित्व लौटाता है। |

### equals(obj) {#equals}

एक मान लौटाता है जो दर्शाता है कि यह इंस्टेंस निर्दिष्ट `DotCodeExtendedParameters` मान के बराबर है या नहीं।

| पैरामीटर | विवरण |
| --- | --- |
| obj | इस इंस्टेंस से तुलना करने के लिए एक System.Object मान। |

**Returns:** `true ` if obj has the same value as this instance; otherwise, `false `.

### getDotCodeIsReaderInitialization() {#getdotcodeisreaderinitialization}

> **Deprecated.** See method description for replacement.

यह दर्शाता है कि कोड का उपयोग रीडर को निम्न डेटा को प्रारंभिक या बारकोड रीडर के पुनःप्रोग्रामिंग निर्देशों के रूप में व्याख्या करने के लिए किया जाता है या नहीं। डिफ़ॉल्ट मान false है।

### getDotCodeStructuredAppendModeBarcodeId() {#getdotcodestructuredappendmodebarcodeid}

> **Deprecated.** See method description for replacement.

DotCode संरचित एपेंड मोड बारकोड का ID प्राप्त करता है। ID 1 से शुरू होती है और बारकोड की संख्या से कम या बराबर होनी चाहिए। डिफ़ॉल्ट मान -1 है। मान: DotCode संरचित एपेंड मोड बारकोड का ID।

### getDotCodeStructuredAppendModeBarcodesCount() {#getdotcodestructuredappendmodebarcodescount}

> **Deprecated.** See method description for replacement.

DotCode संरचित एपेंड मोड बारकोड की गिनती प्राप्त करता है। डिफ़ॉल्ट मान -1 है। गिनती 1 से 35 के बीच का मान होना चाहिए। मान: DotCode संरचित एपेंड मोड बारकोड की गिनती।

### getStructuredAppendModeBarcodeId() {#getstructuredappendmodebarcodeid}

DotCode संरचित एपेंड मोड बारकोड का ID प्राप्त करता है। ID 1 से शुरू होती है और बारकोड की संख्या से कम या बराबर होनी चाहिए। डिफ़ॉल्ट मान -1 है। मान: DotCode संरचित एपेंड मोड बारकोड का ID।

**Returns:** the ID of the DotCode structured append mode barcode.

### getStructuredAppendModeBarcodesCount() {#getstructuredappendmodebarcodescount}

DotCode संरचित एपेंड मोड बारकोड की गिनती प्राप्त करता है। डिफ़ॉल्ट मान -1 है। गिनती 1 से 35 के बीच का मान होना चाहिए। मान: DotCode संरचित एपेंड मोड बारकोड की गिनती।

**Returns:** the DotCode structured append mode barcodes count.

### hashCode() {#hashcode}

इस उदाहरण के लिए हैश कोड लौटाता है।

**Returns:** A 32-bit signed integer hash code.

### isReaderInitialization() {#isreaderinitialization}

यह दर्शाता है कि कोड का उपयोग रीडर को निम्न डेटा को प्रारंभिक या बारकोड रीडर के पुनःप्रोग्रामिंग निर्देशों के रूप में व्याख्या करने के लिए किया जाता है या नहीं। डिफ़ॉल्ट मान false है।

### toString() {#tostring}

इस `DotCodeExtendedParameters` का मानव-पठनीय स्ट्रिंग प्रतिनिधित्व लौटाता है।

**Returns:** A string that represents this `DotCodeExtendedParameters`.
