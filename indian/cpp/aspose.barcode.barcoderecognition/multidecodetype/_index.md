---
title: "Aspose::BarCode::BarCodeRecognition::MultiDecodeType क्लास"
linktitle: "MultiDecodeType"
second_title: "Aspose.BarCode C++ के लिए API संदर्भ"
description: "Aspose::BarCode::BarCodeRecognition::MultiDecodeType क्लास. C++ में संयुक्त डिकोड प्रकार।"
type: docs
weight: 2600
url: /hi/cpp/aspose.barcode.barcoderecognition/multidecodetype/
---
## MultiDecodeType class


संयुक्त डिकोड प्रकार।

```cpp
class MultiDecodeType : public Aspose::BarCode::BarCodeRecognition::BaseDecodeType,
                        public System::IEquatable<System::SharedPtr<MultiDecodeType>>
```

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [Add](./add/)(System::SharedPtr\<SingleDecodeType\>) | एक और [SingleDecodeType](../singledecodetype/) को [MultiDecodeType](./) में जोड़ता है। |
| [ContainsAll](./containsall/)(const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) | जाँचें कि क्या यह बारकोड प्रकारों के सभी प्रकारों को शामिल करता है। |
| [ContainsAny](./containsany/)(const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) override | क्या यह किसी प्रकार को शामिल करता है। |
| [Equals](./equals/)(System::SharedPtr\<MultiDecodeType\>) override | एक मान लौटाता है जो दर्शाता है कि यह इंस्टेंस निर्दिष्ट [MultiDecodeType](./) मान के बराबर है या नहीं। |
| [Equals](./equals/)(System::SharedPtr\<SingleDecodeType\>) override | एक मान लौटाता है जो दर्शाता है कि यह डिकोड प्रकार संग्रह केवल निर्दिष्ट [SingleDecodeType](../singledecodetype/) मान को ही शामिल करता है या नहीं। |
| [Equals](./equals/)(System::SharedPtr\<System::Object\>) override | एक मान लौटाता है जो दर्शाता है कि यह इंस्टेंस निर्दिष्ट [MultiDecodeType](./) मान के बराबर है या नहीं। |
| [Equals](../basedecodetype/equals/)(System::SharedPtr\<BaseDecodeType\>) override | एक मान लौटाता है जो दर्शाता है कि यह इंस्टेंस निर्दिष्ट [BaseDecodeType](../basedecodetype/) मान के बराबर है या नहीं। |
| [Exclude](./exclude/)(System::SharedPtr\<SingleDecodeType\>) | [SingleDecodeType](../singledecodetype/) को [MultiDecodeType](./) से बाहर करता है और नया [MultiDecodeType](./) इंस्टेंस लौटाता है। |
| [get_GetSingleTypesCount](./get_getsingletypescount/)() | एकल प्रकारों की संख्या लौटाता है। |
| [GetHashCode](./gethashcode/)() const override | इस इंस्टेंस के लिए हैश कोड लौटाता है। |
| [GetSingleTypes](./getsingletypes/)() | एकल प्रकारों की सूची का प्रतिनिधित्व करता है। |
| [MultiDecodeType](./multidecodetype/)(const System::ArrayPtr\<System::SharedPtr\<SingleDecodeType\>>\&) | [MultiDecodeType](./) क्लास का नया इंस्टेंस प्रारंभ करता है। |
| [MultiDecodeType](./multidecodetype/)(const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) | [MultiDecodeType](./) क्लास का नया इंस्टेंस प्रारंभ करता है। |
| [ToString](./tostring/)() const override | [MultiDecodeType](./) को स्ट्रिंग के रूप में दर्शाने वाली ओवरराइडेड मेथड। |
| static [TryParse](./tryparse/)(System::String, System::SharedPtr\<MultiDecodeType\>\&) | [MultiDecodeType](./) की स्ट्रिंग प्रतिनिधित्व को उसके इंस्टेंस में परिवर्तित करता है। एक रिटर्न वैल्यू दर्शाता है कि परिवर्तन सफल हुआ या विफल। |
| static [TryParse](../basedecodetype/tryparse/)(System::String, System::SharedPtr\<SingleDecodeType\>\&) | [SingleDecodeType](../singledecodetype/) की स्ट्रिंग प्रतिनिधित्व को उसके उदाहरण में बदलता है। एक लौटाया गया मान दर्शाता है कि परिवर्तन सफल हुआ या विफल। |
| static [TryParse](../basedecodetype/tryparse/)(System::String, System::SharedPtr\<BaseDecodeType\>\&) | [BaseDecodeType](../basedecodetype/) की स्ट्रिंग प्रतिनिधित्व को उसकी इंस्टेंस में बदलता है, ठोस प्रकार निर्धारित करने के बाद। लौटाया गया मान दर्शाता है कि परिवर्तन सफल हुआ या विफल। |
## टिप्पणियाँ


यह उदाहरण दिखाता है कि कैसे सम्मिलित MultiDecode प्रकार बनाएँ जो [SingleDecodeType](../singledecodetype/) और MultiDecode प्रकारों को संयोजित करते हैं।
```cpp
[C#]
MultiDecodeType types1 = new MultiDecodeType(DecodeType.QR, DecodeType.DataMatrix);
MultiDecodeType types2 = new MultiDecodeType(types1, DecodeType.Code128, DecodeType.Code39);
[VB.NET]
Dim multiType1 As MultiDecodeType
multiType1 = New MultiDecodeType(DecodeType.QR, DecodeType.DataMatrix)
Dim multiType2 As MultiDecodeType
multiType2 = New MultiDecodeType(multiType1, DecodeType.Code128, DecodeType.Code39)
```

## और देखें

* Class [BaseDecodeType](../basedecodetype/)
* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
