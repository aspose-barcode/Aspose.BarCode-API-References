---
title: "Aspose::BarCode::BarCodeRecognition::SingleDecodeType क्लास"
linktitle: "SingleDecodeType"
second_title: "Aspose.BarCode C++ के लिए API संदर्भ"
description: "Aspose::BarCode::BarCodeRecognition::SingleDecodeType क्लास। सिंगल डिकोड प्रकार। C++ में इंस्टेंस प्राप्त करने के लिए डिकोड प्रकार देखें।"
type: docs
weight: 3200
url: /hi/cpp/aspose.barcode.barcoderecognition/singledecodetype/
---
## SingleDecodeType class


एकल डिकोड प्रकार। उदाहरण प्राप्त करने के लिए डिकोड प्रकार देखें।

```cpp
class SingleDecodeType : public Aspose::BarCode::BarCodeRecognition::BaseDecodeType,
                         public System::IEquatable<System::SharedPtr<SingleDecodeType>>
```

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [ContainsAny](./containsany/)(const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) override | एक मान लौटाता है जो दर्शाता है कि यह इंस्टेंस निर्दिष्ट सूची में शामिल है या नहीं। |
| [Equals](./equals/)(System::SharedPtr\<SingleDecodeType\>) override | एक मान लौटाता है जो दर्शाता है कि यह इंस्टेंस निर्दिष्ट [SingleDecodeType](./) मान के बराबर है या नहीं। |
| [Equals](./equals/)(System::SharedPtr\<MultiDecodeType\>) override | एक मान लौटाता है जो दर्शाता है कि निर्दिष्ट [MultiDecodeType](../multidecodetype/) संग्रह केवल इस डिकोड प्रकार को ही शामिल करता है या नहीं। |
| [Equals](./equals/)(System::SharedPtr\<System::Object\>) override | एक मान लौटाता है जो दर्शाता है कि यह इंस्टेंस निर्दिष्ट [SingleDecodeType](./) मान के बराबर है या नहीं। |
| [Equals](../basedecodetype/equals/)(System::SharedPtr\<BaseDecodeType\>) override | एक मान लौटाता है जो दर्शाता है कि यह इंस्टेंस निर्दिष्ट [BaseDecodeType](../basedecodetype/) मान के बराबर है या नहीं। |
| [get_TypeIndex](./get_typeindex/)() const | डिकोड प्रकार का सूचकांक प्राप्त करता है |
| [get_TypeName](./get_typename/)() const | डिकोड प्रकार का नाम प्राप्त करता है |
| [GetHashCode](./gethashcode/)() const override | इस इंस्टेंस के लिए हैश कोड लौटाता है। |
| [GetString](./getstring/)() | [SingleDecodeType](./) की इंस्टेंस को उसके समतुल्य स्ट्रिंग प्रतिनिधित्व में बदलता है। स्ट्रिंग प्रारूप है: "Index:-1; Name:None"। |
| static [GetString](./getstring/)(System::SharedPtr\<SingleDecodeType\>) | [SingleDecodeType](./) की इंस्टेंस को उसके समतुल्य स्ट्रिंग प्रतिनिधित्व में बदलता है। स्ट्रिंग प्रारूप है: "Index:-1; Name:None"। |
| static [Parse](./parse/)(System::String) | [SingleDecodeType](./) के नाम की स्ट्रिंग प्रतिनिधित्व को उसकी इंस्टेंस में बदलता है। |
| [ToString](./tostring/)() const override | दिए गए [SingleDecodeType](./) का नाम स्ट्रिंग के रूप में लौटाता है। |
| static [TryParse](../basedecodetype/tryparse/)(System::String, System::SharedPtr\<SingleDecodeType\>\&) | [SingleDecodeType](./) की स्ट्रिंग प्रतिनिधित्व को उसकी इंस्टेंस में बदलता है। लौटाया गया मान दर्शाता है कि परिवर्तन सफल हुआ या विफल। |
| static [TryParse](../basedecodetype/tryparse/)(System::String, System::SharedPtr\<MultiDecodeType\>\&) | [MultiDecodeType](../multidecodetype/) की स्ट्रिंग प्रतिनिधित्व को उसकी इंस्टेंस में बदलता है। लौटाया गया मान दर्शाता है कि परिवर्तन सफल हुआ या विफल। |
| static [TryParse](../basedecodetype/tryparse/)(System::String, System::SharedPtr\<BaseDecodeType\>\&) | [BaseDecodeType](../basedecodetype/) की स्ट्रिंग प्रतिनिधित्व को उसकी इंस्टेंस में बदलता है, ठोस प्रकार निर्धारित करने के बाद। लौटाया गया मान दर्शाता है कि परिवर्तन सफल हुआ या विफल। |
## टिप्पणियाँ


यह उदाहरण दिखाता है कि सिंगल डिकोड प्रकार की इंस्टेंस कैसे प्राप्त की जाए।
```cpp
[C#]
SingleDecodeType singleType = DecodeType.QR

[VB.NET]
Dim singleType As SingleDecodeType
singleType = DecodeType.QR
```

## और देखें

* Class [BaseDecodeType](../basedecodetype/)
* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
