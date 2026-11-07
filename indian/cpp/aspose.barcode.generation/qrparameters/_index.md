---
title: "Aspose::BarCode::Generation::QrParameters class"
linktitle: "QrParameters"
second_title: "Aspose.BarCode C++ के लिए API संदर्भ"
description: "Aspose::BarCode::Generation::QrParameters क्लास। C++ में QR पैरामीटर।"
type: docs
weight: 4400
url: /hi/cpp/aspose.barcode.generation/qrparameters/
---
## QrParameters class


QR पैरामीटर।

```cpp
class QrParameters : public System::Object
```

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [get_AspectRatio](./get_aspectratio/)() const | 2D [BarCode](../../aspose.barcode/) मॉड्यूल का ऊँचाई/चौड़ाई अनुपात। |
| [get_ECIEncoding](./get_eciencoding/)() const | Extended Channel Interpretation Identifiers. यह बारकोड रीडर को प्रतीक में डेटा एन्कोड करने के लिए उपयोग किए गए संदर्भों के बारे में विवरण बताने के लिए उपयोग किया जाता है। वर्तमान कार्यान्वयन सभी ज्ञात कैरेक्टरसेट एन्कोडिंग्स को शामिल करता है। MicroQR द्वारा समर्थित नहीं है। |
| [get_EncodeGS1SeparatorInByteMode](./get_encodegs1separatorinbytemode/)() const |  |
| [get_EncodeMode](./get_encodemode/)() const | QR सिम्बोलॉजी प्रकार [BarCode](../../aspose.barcode/) के एन्कोडिंग मोड का। डिफ़ॉल्ट मान: [QREncodeMode.Auto](../aztecencodemode/). |
| [get_ErrorLevel](./get_errorlevel/)() const | QR, MicroQR और RectMicroQR बारकोड के लिए Reed-Solomon त्रुटि सुधार का स्तर। कम से उच्च: LevelL, LevelM, LevelQ, LevelH। देखें QRErrorLevel। |
| [get_MicroQRVersion](./get_microqrversion/)() const | MicroQR कोड का संस्करण। संस्करण M1 से संस्करण M4 तक। डिफ़ॉल्ट मान है [MicroQRVersion.Auto](../aztecencodemode/). |
| [get_RectMicroQrVersion](./get_rectmicroqrversion/)() const | RectMicroQR कोड का संस्करण। संस्करण R7x59 से संस्करण R17x139 तक। डिफ़ॉल्ट मान है [RectMicroQRVersion.Auto](../aztecencodemode/). |
| [get_StructuredAppend](./get_structuredappend/)() const | QR संरचित एपेंड पैरामीटर। संरचित एपेंड मोड MicroQR और RectMicroQR बारकोड द्वारा समर्थित नहीं है। |
| [get_Version](./get_version/)() const | QR कोड का संस्करण। संस्करण 1 से संस्करण 40 तक। डिफ़ॉल्ट मान है [QRVersion.Auto](../aztecencodemode/). |
| [set_AspectRatio](./set_aspectratio/)(float) | 2D [BarCode](../../aspose.barcode/) मॉड्यूल का ऊँचाई/चौड़ाई अनुपात। |
| [set_ECIEncoding](./set_eciencoding/)(ECIEncodings) | Extended Channel Interpretation Identifiers. यह बारकोड रीडर को प्रतीक में डेटा एन्कोड करने के लिए उपयोग किए गए संदर्भों के बारे में विवरण बताने के लिए उपयोग किया जाता है। वर्तमान कार्यान्वयन सभी ज्ञात कैरेक्टरसेट एन्कोडिंग्स को शामिल करता है। MicroQR द्वारा समर्थित नहीं है। |
| [set_EncodeGS1SeparatorInByteMode](./set_encodegs1separatorinbytemode/)(bool) |  |
| [set_EncodeMode](./set_encodemode/)(QREncodeMode) | QR सिम्बोलॉजी प्रकार [BarCode](../../aspose.barcode/) के एन्कोडिंग मोड का। डिफ़ॉल्ट मान: [QREncodeMode.Auto](../aztecencodemode/). |
| [set_ErrorLevel](./set_errorlevel/)(QRErrorLevel) | QR, MicroQR और RectMicroQR बारकोड के लिए Reed-Solomon त्रुटि सुधार का स्तर। कम से उच्च: LevelL, LevelM, LevelQ, LevelH। देखें QRErrorLevel। |
| [set_MicroQRVersion](./set_microqrversion/)(Aspose::BarCode::Generation::MicroQRVersion) | MicroQR कोड का संस्करण। संस्करण M1 से संस्करण M4 तक। डिफ़ॉल्ट मान है [MicroQRVersion.Auto](../aztecencodemode/). |
| [set_RectMicroQrVersion](./set_rectmicroqrversion/)(RectMicroQRVersion) | RectMicroQR कोड का संस्करण। संस्करण R7x59 से संस्करण R17x139 तक। डिफ़ॉल्ट मान है [RectMicroQRVersion.Auto](../aztecencodemode/). |
| [set_StructuredAppend](./set_structuredappend/)(System::SharedPtr\<QrStructuredAppendParameters\>) | QR संरचित एपेंड पैरामीटर। संरचित एपेंड मोड MicroQR और RectMicroQR बारकोड द्वारा समर्थित नहीं है। |
| [set_Version](./set_version/)(QRVersion) | QR कोड का संस्करण। संस्करण 1 से संस्करण 40 तक। डिफ़ॉल्ट मान है [QRVersion.Auto](../aztecencodemode/). |
| [ToString](./tostring/)() const override | इस [QrParameters](./) की मानव-पठनीय स्ट्रिंग प्रतिनिधित्व लौटाता है। |
## और देखें

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
