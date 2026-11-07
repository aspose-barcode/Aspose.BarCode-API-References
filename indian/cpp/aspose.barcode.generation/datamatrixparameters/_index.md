---
title: "Aspose::BarCode::Generation::DataMatrixParameters class"
linktitle: "DataMatrixParameters"
second_title: "Aspose.BarCode C++ के लिए API संदर्भ"
description: "Aspose::BarCode::Generation::DataMatrixParameters क्लास। C++ में DataMatrix पैरामीटर।"
type: docs
weight: 2000
url: /hi/cpp/aspose.barcode.generation/datamatrixparameters/
---
## DataMatrixParameters class


डेटा मैट्रिक्स पैरामीटर।

```cpp
class DataMatrixParameters : public System::Object
```

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [get_AspectRatio](./get_aspectratio/)() const | 2D [BarCode](../../aspose.barcode/) मॉड्यूल का ऊँचाई/चौड़ाई अनुपात। |
| [get_EccType](./get_ecctype/)() const | एक Datamatrix ECC प्रकार प्राप्त करता है। डिफ़ॉल्ट मान: [DataMatrixEccType.Ecc200](../datamatrixecctype/). |
| [get_ECIEncoding](./get_eciencoding/)() const | ECI एन्कोडिंग प्राप्त करता है। जब EncodeMode Auto हो तो उपयोग किया जाता है। डिफ़ॉल्ट मान: ISO-8859-1 |
| [get_EncodeMode](./get_encodemode/)() const | Datamatrix बारकोड का एन्कोड मोड। डिफ़ॉल्ट मान: [EncodeMode.Auto](../aztecencodemode/). |
| [get_IsReaderProgramming](./get_isreaderprogramming/)() const | रीडर को यह निर्देश देने के लिए उपयोग किया जाता है कि वह प्रतीक में निहित डेटा को रीडर प्रारंभिककरण के लिए प्रोग्रामिंग के रूप में व्याख्या करे। डिफ़ॉल्ट मान: false |
| [get_MacroCharacters](./get_macrocharacters/)() const | Macro Characters 05 और 06 मान विशेष मोड में अधिक कॉम्पैक्ट एन्कोडिंग प्राप्त करने के लिए उपयोग किए जाते हैं। केवल [DataMatrixEccType.Ecc200](../datamatrixecctype/) या [DataMatrixEccType.EccAuto](../datamatrixecctype/) के साथ उपयोग किया जा सकता है। इसे [EncodeTypes.GS1DataMatrix](../encodetypes/gs1datamatrix/) के साथ उपयोग नहीं किया जा सकता। डिफ़ॉल्ट मान: [MacroCharacters.None](../barcodeclassifications/). |
| [get_StructuredAppendBarcodeId](./get_structuredappendbarcodeid/)() const | Datamatrix बारकोड के Structured Append मोड के लिए बारकोड ID। डिफ़ॉल्ट मान: 0 |
| [get_StructuredAppendBarcodesCount](./get_structuredappendbarcodescount/)() const | Datamatrix बारकोड के Structured Append मोड के लिए बारकोड की संख्या। डिफ़ॉल्ट मान: 0 |
| [get_StructuredAppendFileId](./get_structuredappendfileid/)() const | Datamatrix बारकोड के Structured Append मोड के लिए फ़ाइल आईडी। डिफ़ॉल्ट मान: 0 |
| [get_Version](./get_version/)() const | Datamatrix प्रतीक आकार प्राप्त करता है। डिफ़ॉल्ट मान: [Version.Auto](../aztecencodemode/). |
| [set_AspectRatio](./set_aspectratio/)(float) | 2D [BarCode](../../aspose.barcode/) मॉड्यूल का ऊँचाई/चौड़ाई अनुपात। |
| [set_EccType](./set_ecctype/)(DataMatrixEccType) | Datamatrix ECC प्रकार सेट करता है। डिफ़ॉल्ट मान: [DataMatrixEccType.Ecc200](../datamatrixecctype/). |
| [set_ECIEncoding](./set_eciencoding/)(ECIEncodings) | ECI एन्कोडिंग सेट करता है। जब EncodeMode Auto हो तो उपयोग किया जाता है। डिफ़ॉल्ट मान: ISO-8859-1 |
| [set_EncodeMode](./set_encodemode/)(DataMatrixEncodeMode) | Datamatrix बारकोड का एन्कोड मोड। डिफ़ॉल्ट मान: [EncodeMode.Auto](../aztecencodemode/). |
| [set_IsReaderProgramming](./set_isreaderprogramming/)(bool) | रीडर को यह निर्देश देने के लिए उपयोग किया जाता है कि वह प्रतीक में निहित डेटा को रीडर प्रारंभिककरण के लिए प्रोग्रामिंग के रूप में व्याख्या करे। डिफ़ॉल्ट मान: false |
| [set_MacroCharacters](./set_macrocharacters/)(MacroCharacter) | Macro Characters 05 और 06 मान विशेष मोड में अधिक कॉम्पैक्ट एन्कोडिंग प्राप्त करने के लिए उपयोग किए जाते हैं। केवल [DataMatrixEccType.Ecc200](../datamatrixecctype/) या [DataMatrixEccType.EccAuto](../datamatrixecctype/) के साथ उपयोग किया जा सकता है। इसे [EncodeTypes.GS1DataMatrix](../encodetypes/gs1datamatrix/) के साथ उपयोग नहीं किया जा सकता। डिफ़ॉल्ट मान: [MacroCharacters.None](../barcodeclassifications/). |
| [set_StructuredAppendBarcodeId](./set_structuredappendbarcodeid/)(int32_t) | Datamatrix बारकोड के Structured Append मोड के लिए बारकोड ID। डिफ़ॉल्ट मान: 0 |
| [set_StructuredAppendBarcodesCount](./set_structuredappendbarcodescount/)(int32_t) | Datamatrix बारकोड के Structured Append मोड के लिए बारकोड की संख्या। डिफ़ॉल्ट मान: 0 |
| [set_StructuredAppendFileId](./set_structuredappendfileid/)(int32_t) | Datamatrix बारकोड के Structured Append मोड के लिए फ़ाइल आईडी। डिफ़ॉल्ट मान: 0 |
| [set_Version](./set_version/)(DataMatrixVersion) | Datamatrix प्रतीक आकार सेट करता है। डिफ़ॉल्ट मान: [Version.Auto](../aztecencodemode/). |
| [ToString](./tostring/)() const override | इस [DataMatrixParameters](./) की मानव-पठनीय स्ट्रिंग प्रतिनिधित्व लौटाता है। |
## और देखें

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
