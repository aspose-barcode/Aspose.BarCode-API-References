---
title: "Aspose::BarCode::ComplexBarcode::GS1Codetext class"
linktitle: "GS1Codetext"
second_title: "Aspose.BarCode C++ के लिए API संदर्भ"
description: "Aspose::BarCode::ComplexBarcode::GS1Codetext class. GS1 कोडटेक्स्ट को एन्कोडिंग और डिकोडिंग के लिए एप्लिकेशन पहचानकर्ता तत्वों के क्रमबद्ध अनुक्रम के रूप में दर्शाता है। स्रोत क्रम और दोहराए गए एप्लिकेशन पहचानकर्ता संरक्षित रहते हैं। कोष्ठकित प्रतिनिधित्व का रूप (AI)value(AI)value है। एक शाब्दिक खुला कोष्ठक ''('' को मान के भीतर ( के रूप में लिखा जाना चाहिए; यह एकमात्र समर्थित एस्केप अनुक्रम है। एक शाब्दिक बंद कोष्ठक '')'' को मान के भीतर C++ में एस्केप करने की आवश्यकता नहीं है।"
type: docs
weight: 500
url: /hi/cpp/aspose.barcode.complexbarcode/gs1codetext/
---
## GS1Codetext class


GS1 कोडटेक्स्ट को एन्कोडिंग और डिकोडिंग के लिए एप्लिकेशन आइडेंटिफायर तत्वों की क्रमबद्ध श्रृंखला के रूप में दर्शाता है। स्रोत क्रम और दोहराए गए एप्लिकेशन आइडेंटिफायर संरक्षित रहते हैं। कोष्ठकित प्रतिनिधित्व का रूप (AI)value(AI)value है। मान के भीतर एक साधारण खुला कोष्ठक '(' को (; के रूप में लिखा जाना चाहिए; यह एकमात्र समर्थित एस्केप सीक्वेंस है। मान के भीतर बंद कोष्ठक ')' को एस्केप करने की आवश्यकता नहीं है।

```cpp
class GS1Codetext : public Aspose::BarCode::ComplexBarcode::IComplexCodetext
```

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [Add](./add/)(System::String, System::String) | एक मान्यताप्राप्त Application Identifier तत्व जोड़ता है। |
| [get_BarcodeType](./get_barcodetype/)() const | इस GS1 कोडटेक्स्ट को एन्कोड करने के लिए उपयोग किए गए बारकोड प्रकार को प्राप्त करता है। समर्थित प्रकार GS1Aztec, GS1CodablockF, GS1Code128, GS1DataMatrix, GS1DotCode, GS1HanXin, GS1MicroPdf417, GS1QR और GS1 DataBar प्रकार हैं। डिफ़ॉल्ट मान GS1Code128 है। |
| [get_Count](./get_count/)() | Application Identifier तत्वों की संख्या प्राप्त करता है। |
| [get_Elements](./get_elements/)() | स्रोत क्रम में सभी तत्वों की एक प्रति प्राप्त करता है। |
| [GetAll](./getall/)(System::String) | स्रोत क्रम में एक एप्लिकेशन पहचानकर्ता के सभी मान प्राप्त करता है। |
| [GetBarcodeType](./getbarcodetype/)() override | इस GS1 कोडटेक्स्ट को एन्कोड करने के लिए उपयोग किए गए बारकोड प्रकार को प्राप्त करता है। |
| [GetConstructedCodetext](./getconstructedcodetext/)() override | कोष्ठकित GS1 कोडटेक्स्ट को (AI)value(AI)value रूप में बनाता है। मानों में शाब्दिक खुलते कोष्ठक को ( के रूप में एस्केप किया जाता है। |
| [GetFirst](./getfirst/)(System::String) | एक एप्लिकेशन पहचानकर्ता के लिए पहला मान प्राप्त करता है। |
| [GS1Codetext](./gs1codetext/)() | एक खाली GS1 कोडटेक्स्ट को प्रारंभ करता है। |
| [idx_get](./idx_get/)(int32_t) | क्रमबद्ध अनुक्रम में उसकी स्थिति के अनुसार एक तत्व प्राप्त करता है। |
| [InitFromString](./initfromstring/)(System::String) override | इस उदाहरण को (AI)value(AI)value रूप में कोष्ठकित GS1 कोडटेक्स्ट से प्रारंभ करता है। प्रदान किए गए कोडटेक्स्ट को सफलतापूर्वक पार्स करने के बाद ही मौजूदा तत्वों को बदल दिया जाता है। |
| static [Parse](./parse/)(System::String) | कोष्ठकित (AI)value(AI)value रूप में GS1 तत्व स्ट्रिंग को पार्स करता है। मान के भीतर शाब्दिक '(' को ( के रूप में लिखा जाना चाहिए; कोई अन्य एस्केप अनुक्रम समर्थित नहीं है, और ')' को एस्केप करने की आवश्यकता नहीं है। |
| [set_BarcodeType](./set_barcodetype/)(System::SharedPtr\<Generation::BaseEncodeType\>) | इस GS1 कोडटेक्स्ट को एन्कोड करने के लिए उपयोग किए जाने वाले बारकोड प्रकार को सेट करता है। समर्थित प्रकार GS1Aztec, GS1CodablockF, GS1Code128, GS1DataMatrix, GS1DotCode, GS1HanXin, GS1MicroPdf417, GS1QR और GS1 DataBar प्रकार हैं। डिफ़ॉल्ट मान GS1Code128 है। |
| [ToString](./tostring/)() const override | ब्रैकेटेड GS1 प्रतिनिधित्व को (AI)value(AI)value के रूप में लौटाता है। |
| static [TryParse](./tryparse/)(System::String, System::SharedPtr\<GS1Codetext\>\&, System::SharedPtr\<Common::GS1ValidationResult\>\&) | ब्रैकेटेड GS1 तत्व स्ट्रिंग को (AI)value(AI)value के रूप में पार्स करने का प्रयास करता है और संरचित सत्यापन त्रुटियां लौटाता है। मान के भीतर एक साधारण '(' को (; के रूप में लिखा जाना चाहिए; कोई अन्य एस्केप सीक्वेंस समर्थित नहीं है, और ')' को एस्केप करने की आवश्यकता नहीं है। |
| static [Validate](./validate/)(System::String) | ब्रैकेटेड GS1 तत्व स्ट्रिंग को (AI)value(AI)value के रूप में वस्तु बनाए बिना सत्यापित करता है। मान के भीतर एक साधारण '(' को (; के रूप में लिखा जाना चाहिए; कोई अन्य एस्केप सीक्वेंस समर्थित नहीं है, और ')' को एस्केप करने की आवश्यकता नहीं है। |
## और देखें

* Class [IComplexCodetext](../icomplexcodetext/)
* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
