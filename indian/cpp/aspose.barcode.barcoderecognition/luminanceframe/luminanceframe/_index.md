---
title: "constructor"
linktitle: "LuminanceFrame"
second_title: "Aspose.BarCode C++ के लिए API संदर्भ"
description: "कन्स्ट्रक्टर। LuminanceFrame क्लास की नई इंस्टेंस को पंक्तियों के बीच पैडिंग के बिना प्रारंभ करता है। सन्निहित पंक्तियों के बीच दूरी width के बराबर है C++ में।"
type: docs
weight: 600
url: /hi/cpp/aspose.barcode.barcoderecognition/luminanceframe/luminanceframe/
---
## LuminanceFrame::LuminanceFrame(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, int32_t) constructor


नई इंस्टेंस को प्रारंभ करता है [LuminanceFrame](../) क्लास की पंक्तियों के बीच पैडिंग के बिना। सन्निहित पंक्तियों के बीच दूरी *width* के बराबर है।

```cpp
Aspose::BarCode::BarCodeRecognition::LuminanceFrame::LuminanceFrame(System::ArrayPtr<uint8_t> data, int32_t width, int32_t height, int32_t rotationDegrees=0)
```


| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| data | System::ArrayPtr\<uint8_t\> | प्रकाशमान डेटा जिसमें प्रत्येक पिक्सेल के लिए एक बाइट होता है। |
| width | int32_t | फ़्रेम की चौड़ाई पिक्सेल में। |
| height | int32_t | फ़्रेम की ऊँचाई पिक्सेल में। |
| rotationDegrees | int32_t | फ़्रेम को सीधा दिखाने के लिए आवश्यक घड़ी की दिशा में घुमाव। समर्थित मान 0, 90, 180 और 270 हैं। डिफ़ॉल्ट मान 0 है। |

## और देखें

* Class [LuminanceFrame](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
## LuminanceFrame::LuminanceFrame(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, int32_t, int32_t) constructor


निर्दिष्ट रो स्ट्राइड के साथ नई इंस्टेंस को प्रारंभ करता है [LuminanceFrame](../) क्लास की।

```cpp
Aspose::BarCode::BarCodeRecognition::LuminanceFrame::LuminanceFrame(System::ArrayPtr<uint8_t> data, int32_t width, int32_t height, int32_t rowStride, int32_t rotationDegrees)
```


| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| data | System::ArrayPtr\<uint8_t\> | प्रकाशमान डेटा जिसमें प्रत्येक पिक्सेल के लिए एक बाइट होता है। |
| width | int32_t | फ़्रेम की चौड़ाई पिक्सेल में। |
| height | int32_t | फ़्रेम की ऊँचाई पिक्सेल में। |
| rowStride | int32_t | दो क्रमिक पंक्तियों की शुरुआत के बीच बाइट में दूरी। मान *width* से कम नहीं हो सकता। |
| rotationDegrees | int32_t | फ़्रेम को सीधा दिखाने के लिए आवश्यक घड़ी की दिशा में घुमाव। समर्थित मान 0, 90, 180 और 270 हैं। |

## और देखें

* Class [LuminanceFrame](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
