---
title: "Aspose::BarCode::ComplexBarcode::GS1DigitalLink class"
linktitle: "GS1DigitalLink"
second_title: "Aspose.BarCode C++ के लिए API संदर्भ"
description: "Aspose::BarCode::ComplexBarcode::GS1DigitalLink class. एन्कोडिंग और डिकोडिंग के लिए Application Identifier तत्वों के क्रमबद्ध अनुक्रम के रूप में GS1 Digital Link codetext को दर्शाता है। स्रोत क्रम और दोहराए गए Application Identifiers संरक्षित रहते हैं। निर्मित codetext एक अनकम्प्रेस्ड GS1 Digital Link URI है। C++ में पार्स करते समय Non-GS1 query parameters और URI fragments को अनदेखा किया जाता है।"
type: docs
weight: 600
url: /hi/cpp/aspose.barcode.complexbarcode/gs1digitallink/
---
## GS1DigitalLink class


GS1 डिजिटल लिंक कोडटेक्स्ट को एन्कोडिंग और डिकोडिंग के लिए एप्लिकेशन आइडेंटिफायर तत्वों की क्रमबद्ध श्रृंखला के रूप में दर्शाता है। स्रोत क्रम और दोहराए गए एप्लिकेशन आइडेंटिफायर संरक्षित रहते हैं। निर्मित कोडटेक्स्ट एक अनकम्प्रेस्ड GS1 डिजिटल लिंक URI है। पार्सिंग के दौरान गैर-GS1 क्वेरी पैरामीटर और URI फ्रैगमेंट को नजरअंदाज किया जाता है।

```cpp
class GS1DigitalLink : public Aspose::BarCode::ComplexBarcode::IComplexCodetext
```

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [Add](./add/)(System::String, System::String) | एक मान्यताप्राप्त Application Identifier तत्व जोड़ता है। |
| static [Create](./create/)(System::String, System::SharedPtr\<GS1Codetext\>) | GS1 codetext से सभी तत्वों को कॉपी करके और केवल उपलब्ध प्राथमिक कुंजी का चयन करके एक GS1 Digital Link बनाता है। |
| static [Create](./create/)(System::String, System::SharedPtr\<GS1Codetext\>, System::String) | GS1 codetext से सभी तत्वों को कॉपी करके और निर्दिष्ट प्राथमिक कुंजी का उपयोग करके एक GS1 Digital Link बनाता है। |
| [get_BarcodeType](./get_barcodetype/)() const | इस GS1 Digital Link को एन्कोड करने के लिए उपयोग किए जाने वाले बारकोड प्रकार को प्राप्त करता है। समर्थित प्रकार हैं QR, DataMatrix, Aztec, Pdf417, MicroPdf417, DotCode, HanXin, CodablockF और Code128। डिफ़ॉल्ट मान QR है। |
| [get_Count](./get_count/)() | Application Identifier तत्वों की संख्या प्राप्त करता है। |
| [get_Elements](./get_elements/)() | स्रोत क्रम में सभी तत्वों की एक प्रति प्राप्त करता है। |
| [get_PrimaryApplicationIdentifier](./get_primaryapplicationidentifier/)() const | Digital Link प्राथमिक कुंजी के रूप में उपयोग किए गए Application Identifier को प्राप्त करता है। Null का अर्थ है कि URI निर्मित होने पर प्राथमिक कुंजी स्वचालित रूप से चयनित की जाती है। |
| [get_UriStem](./get_uristem/)() const | GS1 प्राथमिक कुंजी पाथ सेगमेंट से पहले के पूर्ण URI उपसर्ग को प्राप्त करता है। स्टेम में कोई क्वेरी स्ट्रिंग या फ्रैगमेंट नहीं होता। |
| [GetAll](./getall/)(System::String) | स्रोत क्रम में एक एप्लिकेशन पहचानकर्ता के सभी मान प्राप्त करता है। |
| [GetBarcodeType](./getbarcodetype/)() override | इस GS1 डिजिटल लिंक को एन्कोड करने के लिए उपयोग किए गए बारकोड प्रकार को प्राप्त करता है। |
| [GetConstructedCodetext](./getconstructedcodetext/)() override | असंपीड़ित GS1 डिजिटल लिंक URI बनाता है। |
| [GetFirst](./getfirst/)(System::String) | एक एप्लिकेशन पहचानकर्ता के लिए पहला मान प्राप्त करता है। |
| [GS1DigitalLink](./gs1digitallink/)(System::String) | निर्दिष्ट URI स्टेम के साथ एक खाली GS1 डिजिटल लिंक को प्रारंभ करता है। जब ठीक एक प्राथमिक कुंजी उम्मीदवार मौजूद हो, तो प्राथमिक कुंजी स्वचालित रूप से चयनित की जाती है। |
| [GS1DigitalLink](./gs1digitallink/)(System::String, System::String) | निर्दिष्ट URI स्टेम और प्राथमिक कुंजी के साथ एक खाली GS1 डिजिटल लिंक को प्रारंभ करता है। |
| [idx_get](./idx_get/)(int32_t) | क्रमबद्ध अनुक्रम में उसकी स्थिति के अनुसार एक तत्व प्राप्त करता है। |
| [InitFromString](./initfromstring/)(System::String) override | इस उदाहरण को एक असंपीड़ित GS1 डिजिटल लिंक URI से प्रारंभ करता है। प्रदान किए गए URI को सफलतापूर्वक पार्स करने के बाद ही मौजूदा स्थिति को बदल दिया जाता है। चयनित बारकोड प्रकार संरक्षित रहता है। |
| static [Parse](./parse/)(System::String) | एक असंपीड़ित GS1 डिजिटल लिंक URI को पार्स करता है। |
| [set_BarcodeType](./set_barcodetype/)(System::SharedPtr\<Generation::BaseEncodeType\>) | इस GS1 डिजिटल लिंक को एन्कोड करने के लिए उपयोग किए जाने वाले बारकोड प्रकार को सेट करता है। समर्थित प्रकार QR, DataMatrix, Aztec, Pdf417, MicroPdf417, DotCode, HanXin, CodablockF और Code128 हैं। डिफ़ॉल्ट मान QR है। |
| [ToGS1Codetext](./togs1codetext/)() | वर्तमान GS1 तत्वों को शामिल करने वाला एक स्वतंत्र GS1 कोडटेक्स्ट बनाता है। केवल URI की जानकारी शामिल नहीं की गई है। |
| [ToString](./tostring/)() const override | असंपीड़ित GS1 डिजिटल लिंक URI लौटाता है। |
| [ToUriString](./touristring/)() | वर्तमान ऑब्जेक्ट स्थिति को असंपीड़ित GS1 डिजिटल लिंक URI के रूप में स्वरूपित करता है। |
| static [TryParse](./tryparse/)(System::String, System::SharedPtr\<GS1DigitalLink\>\&, System::SharedPtr\<Common::GS1ValidationResult\>\&) | एक असंपीड़ित GS1 डिजिटल लिंक URI को पार्स करने का प्रयास करता है और संरचित मान्यकरण त्रुटियों को लौटाता है। |
| static [Validate](./validate/)(System::String) | एक ऑब्जेक्ट बनाए बिना असंपीड़ित GS1 डिजिटल लिंक URI को मान्य करता है। |
## और देखें

* Class [IComplexCodetext](../icomplexcodetext/)
* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
