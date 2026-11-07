---
title: "Aspose::BarCode::Generation::AztecParameters class"
linktitle: "AztecParameters"
second_title: "Aspose.BarCode C++ के लिए API संदर्भ"
description: "Aspose::BarCode::Generation::AztecParameters class. C++ में Aztec पैरामीटर।"
type: docs
weight: 300
url: /hi/cpp/aspose.barcode.generation/aztecparameters/
---
## AztecParameters class


Aztec पैरामीटर।

```cpp
class AztecParameters : public System::Object
```

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [get_AspectRatio](./get_aspectratio/)() const | 2D [BarCode](../../aspose.barcode/) मॉड्यूल का ऊँचाई/चौड़ाई अनुपात। |
| [get_ECIEncoding](./get_eciencoding/)() const | ECI एन्कोडिंग प्राप्त करता है। जब AztecEncodeMode Auto हो तो उपयोग किया जाता है। डिफ़ॉल्ट मान: ISO-8859-1। |
| [get_EncodeMode](./get_encodemode/)() const | Aztec एन्कोड मोड प्राप्त करता है। डिफ़ॉल्ट मान: Auto। |
| [get_ErrorLevel](./get_errorlevel/)() const | Aztec प्रकार के बारकोड की त्रुटि सुधार स्तर। मान 5 से 95 के बीच होना चाहिए। |
| [get_IsReaderInitialization](./get_isreaderinitialization/)() const | रीडर को यह निर्देश देने के लिए उपयोग किया जाता है कि प्रतीक में निहित डेटा को रीडर इनिशियलाइज़ेशन के लिए प्रोग्रामिंग के रूप में व्याख्या करे। |
| [get_LayersCount](./get_layerscount/)() const | Aztec प्रतीक की परतों की संख्या प्राप्त करता है। परतों की संख्या कॉम्पैक्ट मोड के लिए 1 से 3 और फुल रेंज मोड के लिए 1 से 32 के बीच होनी चाहिए। डिफ़ॉल्ट मान: 0 (ऑटो)। |
| [get_StructuredAppendBarcodeId](./get_structuredappendbarcodeid/)() const | Aztec बारकोड के स्ट्रक्चर्ड एपेंड मोड के लिए बारकोड आईडी। बारकोड आईडी 1 से बारकोड की संख्या के बीच होनी चाहिए। डिफ़ॉल्ट मान: 0 |
| [get_StructuredAppendBarcodesCount](./get_structuredappendbarcodescount/)() const | Aztec बारकोड के स्ट्रक्चर्ड एपेंड मोड के लिए बारकोड की संख्या। बारकोड की संख्या 1 से 26 के बीच होनी चाहिए। डिफ़ॉल्ट मान: 0 |
| [get_StructuredAppendFileId](./get_structuredappendfileid/)() const | Aztec बारकोड के स्ट्रक्चर्ड एपेंड मोड के लिए फ़ाइल आईडी (वैकल्पिक फ़ील्ड)। फ़ाइल आईडी में स्पेस नहीं होना चाहिए। डिफ़ॉल्ट मान: खाली स्ट्रिंग |
| [get_SymbolMode](./get_symbolmode/)() const | Aztec सिंबल मोड प्राप्त करता है। डिफ़ॉल्ट मान: [AztecSymbolMode.Auto](../aztecencodemode/). |
| [set_AspectRatio](./set_aspectratio/)(float) | 2D [BarCode](../../aspose.barcode/) मॉड्यूल का ऊँचाई/चौड़ाई अनुपात। |
| [set_ECIEncoding](./set_eciencoding/)(ECIEncodings) | ECI एन्कोडिंग सेट करता है। जब AztecEncodeMode ऑटो हो तब उपयोग किया जाता है। डिफ़ॉल्ट मान: ISO-8859-1 |
| [set_EncodeMode](./set_encodemode/)(AztecEncodeMode) | Aztec एन्कोड मोड सेट करता है। डिफ़ॉल्ट मान: ऑटो। |
| [set_ErrorLevel](./set_errorlevel/)(int32_t) | Aztec प्रकार के बारकोड की त्रुटि सुधार स्तर। मान 5 से 95 के बीच होना चाहिए। |
| [set_IsReaderInitialization](./set_isreaderinitialization/)(bool) | रीडर को यह निर्देश देने के लिए उपयोग किया जाता है कि प्रतीक में निहित डेटा को रीडर इनिशियलाइज़ेशन के लिए प्रोग्रामिंग के रूप में व्याख्या करे। |
| [set_LayersCount](./set_layerscount/)(int32_t) | Aztec प्रतीक की परतों की संख्या सेट करता है। परतों की संख्या कॉम्पैक्ट मोड के लिए 1 से 3 और फुल रेंज मोड के लिए 1 से 32 के बीच होनी चाहिए। डिफ़ॉल्ट मान: 0 (ऑटो)। |
| [set_StructuredAppendBarcodeId](./set_structuredappendbarcodeid/)(int32_t) | Aztec बारकोड के स्ट्रक्चर्ड एपेंड मोड के लिए बारकोड आईडी। बारकोड आईडी 1 से बारकोड की संख्या के बीच होनी चाहिए। डिफ़ॉल्ट मान: 0 |
| [set_StructuredAppendBarcodesCount](./set_structuredappendbarcodescount/)(int32_t) | Aztec बारकोड के स्ट्रक्चर्ड एपेंड मोड के लिए बारकोड की संख्या। बारकोड की संख्या 1 से 26 के बीच होनी चाहिए। डिफ़ॉल्ट मान: 0 |
| [set_StructuredAppendFileId](./set_structuredappendfileid/)(System::String) | Aztec बारकोड के स्ट्रक्चर्ड एपेंड मोड के लिए फ़ाइल आईडी (वैकल्पिक फ़ील्ड)। फ़ाइल आईडी में स्पेस नहीं होना चाहिए। डिफ़ॉल्ट मान: खाली स्ट्रिंग |
| [set_SymbolMode](./set_symbolmode/)(AztecSymbolMode) | Aztec सिंबल मोड सेट करता है। डिफ़ॉल्ट मान: [AztecSymbolMode.Auto](../aztecencodemode/). |
| [ToString](./tostring/)() const override | इस [AztecParameters](./) की मानव-पठनीय स्ट्रिंग प्रतिनिधित्व लौटाता है। |
## और देखें

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
