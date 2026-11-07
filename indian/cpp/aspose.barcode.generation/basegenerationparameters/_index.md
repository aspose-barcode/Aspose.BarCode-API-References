---
title: "Aspose::BarCode::Generation::BaseGenerationParameters क्लास"
linktitle: "BaseGenerationParameters"
second_title: "Aspose.BarCode C++ के लिए API संदर्भ"
description: "Aspose::BarCode::Generation::BaseGenerationParameters क्लास। C++ में बारकोड इमेज जेनरेशन पैरामीटर।"
type: docs
weight: 700
url: /hi/cpp/aspose.barcode.generation/basegenerationparameters/
---
## BaseGenerationParameters class


बारकोड इमेज निर्माण पैरामीटर।

```cpp
class BaseGenerationParameters : public System::Object
```

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [get_AutoSizeMode](./get_autosizemode/)() const | स्वचालित आकार निर्धारण मोड के विभिन्न प्रकारों को निर्दिष्ट करता है। डिफ़ॉल्ट मान: [AutoSizeMode.None](../autosizemode/). |
| [get_BackColor](./get_backcolor/)() const | बारकोड इमेज का पृष्ठभूमि रंग। डिफ़ॉल्ट मान: Color.White। देखें [Color](../). |
| [get_Barcode](./get_barcode/)() const | [BarcodeParameters](../barcodeparameters/) प्राप्त करता है जो सभी बारकोड गुणों को सम्मिलित करता है। |
| [get_Border](./get_border/)() const | [BorderParameters](../borderparameters/) प्राप्त करता है जो बारकोड बॉर्डर के सभी कॉन्फ़िगरेशन गुणों को सम्मिलित करता है। |
| [get_CaptionAbove](./get_captionabove/)() const | छवि के ऊपर कैप्शन [BarCode](../../aspose.barcode/) छवि। देखें [CaptionParameters](../captionparameters/). |
| [get_CaptionBelow](./get_captionbelow/)() const | छवि के नीचे कैप्शन [BarCode](../../aspose.barcode/) छवि। देखें [CaptionParameters](../captionparameters/). |
| [get_Image](./get_image/)() const | छवि पैरामीटर। देखें [ImageParameters](../imageparameters/). |
| [get_ImageHeight](./get_imageheight/)() const | [BarCode](../../aspose.barcode/) छवि की ऊँचाई जब [AutoSizeMode](../autosizemode/) प्रॉपर्टी को [AutoSizeMode.Nearest](../autosizemode/) या [AutoSizeMode.Interpolation](../autosizemode/) पर सेट किया जाता है। |
| [get_ImageWidth](./get_imagewidth/)() const | [BarCode](../../aspose.barcode/) छवि की चौड़ाई जब [AutoSizeMode](../autosizemode/) प्रॉपर्टी को [AutoSizeMode.Nearest](../autosizemode/) या [AutoSizeMode.Interpolation](../autosizemode/) पर सेट किया जाता है। |
| [get_Resolution](./get_resolution/)() const | प्राप्त करता है [BarCode](../../aspose.barcode/) छवि का रिज़ॉल्यूशन। दोनों आयामों के लिए एक ही मान। डिफ़ॉल्ट मान: 96 dpi. |
| [get_RotationAngle](./get_rotationangle/)() const | [BarCode](../../aspose.barcode/) छवि का घूर्णन कोण, डिग्री में मापा गया, उदाहरण के लिए RotationAngle = 0 या RotationAngle = 360 का अर्थ कोई घूर्णन नहीं है। यदि RotationAngle 90, 180, 270 या 0 के बराबर नहीं है, तो यह स्कैनर के लिए छवि पढ़ना कठिन बना सकता है। डिफ़ॉल्ट मान: 0. |
| [get_UseAntiAlias](./get_useantialias/)() const | प्राप्त करता है एक मान जो दर्शाता है कि क्या इमेज रेंडर करने के लिए एंटी-एलियासिंग मोड उपयोग किया गया है। |
| [set_AutoSizeMode](./set_autosizemode/)(Aspose::BarCode::Generation::AutoSizeMode) | स्वचालित आकार निर्धारण मोड के विभिन्न प्रकारों को निर्दिष्ट करता है। डिफ़ॉल्ट मान: [AutoSizeMode.None](../autosizemode/). |
| [set_BackColor](./set_backcolor/)(System::Drawing::Color) | बारकोड इमेज का पृष्ठभूमि रंग। डिफ़ॉल्ट मान: Color.White। देखें [Color](../). |
| [set_ImageHeight](./set_imageheight/)(System::SharedPtr\<Unit\>) | [BarCode](../../aspose.barcode/) छवि की ऊँचाई जब [AutoSizeMode](../autosizemode/) प्रॉपर्टी को [AutoSizeMode.Nearest](../autosizemode/) या [AutoSizeMode.Interpolation](../autosizemode/) पर सेट किया जाता है। |
| [set_ImageWidth](./set_imagewidth/)(System::SharedPtr\<Unit\>) | [BarCode](../../aspose.barcode/) छवि की चौड़ाई जब [AutoSizeMode](../autosizemode/) प्रॉपर्टी को [AutoSizeMode.Nearest](../autosizemode/) या [AutoSizeMode.Interpolation](../autosizemode/) पर सेट किया जाता है। |
| [set_Resolution](./set_resolution/)(float) | सेट करता है [BarCode](../../aspose.barcode/) छवि का रिज़ॉल्यूशन। दोनों आयामों के लिए एक ही मान। डिफ़ॉल्ट मान: 96 dpi. |
| [set_RotationAngle](./set_rotationangle/)(float) | [BarCode](../../aspose.barcode/) छवि का घूर्णन कोण, डिग्री में मापा गया, उदाहरण के लिए RotationAngle = 0 या RotationAngle = 360 का अर्थ कोई घूर्णन नहीं है। यदि RotationAngle 90, 180, 270 या 0 के बराबर नहीं है, तो यह स्कैनर के लिए छवि पढ़ना कठिन बना सकता है। डिफ़ॉल्ट मान: 0. |
| [set_UseAntiAlias](./set_useantialias/)(bool) | सेट करता है एक मान जो दर्शाता है कि क्या इमेज रेंडर करने के लिए एंटी-एलियासिंग मोड उपयोग किया गया है। |
## और देखें

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
