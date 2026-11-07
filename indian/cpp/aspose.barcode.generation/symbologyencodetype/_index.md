---
title: "Aspose::BarCode::Generation::SymbologyEncodeType क्लास"
linktitle: "SymbologyEncodeType"
second_title: "Aspose.BarCode C++ के लिए API संदर्भ"
description: "Aspose::BarCode::Generation::SymbologyEncodeType क्लास। सिम्बोलॉजी एन्कोड प्रकार। C++ में इंस्टेंस प्राप्त करने के लिए EncodeTypes देखें।"
type: docs
weight: 4900
url: /hi/cpp/aspose.barcode.generation/symbologyencodetype/
---
## SymbologyEncodeType class


सिम्बोलॉजी एन्कोड प्रकार। इंस्टेंस प्राप्त करने के लिए [EncodeTypes](../encodetypes/) देखें।

```cpp
class SymbologyEncodeType : public Aspose::BarCode::Generation::BaseEncodeType
```

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [Equals](../baseencodetype/equals/)(System::SharedPtr\<BaseEncodeType\>) override | एक मान लौटाता है जो दर्शाता है कि यह इंस्टेंस निर्दिष्ट [BaseEncodeType](../baseencodetype/) मान के बराबर है या नहीं। |
| [get_Classification](../baseencodetype/get_classification/)() const | इस सिम्बोलॉजी का वर्गीकरण प्राप्त करता है। |
| [get_TypeIndex](../baseencodetype/get_typeindex/)() const | एन्कोड प्रकार का इंडेक्स प्राप्त करता है |
| [get_TypeName](../baseencodetype/get_typename/)() const | एन्कोड प्रकार का नाम प्राप्त करता है |
| [GetHashCode](../baseencodetype/gethashcode/)() const override | इस इंस्टेंस के लिए हैश कोड लौटाता है। |
| [GetString](../baseencodetype/getstring/)() | [BaseEncodeType](../baseencodetype/) की इंस्टेंस को उसके समतुल्य स्ट्रिंग प्रतिनिधित्व में बदलता है। स्ट्रिंग फ़ॉर्मेट है: "Index:0; Name:Codabar"। |
| static [GetString](../baseencodetype/getstring/)(System::SharedPtr\<BaseEncodeType\>) | [BaseEncodeType](../baseencodetype/) की इंस्टेंस को उसके समतुल्य स्ट्रिंग प्रतिनिधित्व में बदलता है। स्ट्रिंग फ़ॉर्मेट है: "Index:-1; Name:None"। |
| static [Parse](../baseencodetype/parse/)(System::String) | [BaseEncodeType](../baseencodetype/) के नाम की स्ट्रिंग प्रतिनिधित्व को उसकी इंस्टेंस में बदलता है। |
| [ToString](../baseencodetype/tostring/)() const override | दिए गए [BaseEncodeType](../baseencodetype/) का नाम स्ट्रिंग के रूप में लौटाता है। |
| static [TryParse](../baseencodetype/tryparse/)(System::String, System::SharedPtr\<BaseEncodeType\>\&) | [BaseEncodeType](../baseencodetype/) की स्ट्रिंग प्रतिनिधित्व को उसकी इंस्टेंस में बदलता है। एक रिटर्न वैल्यू दर्शाता है कि परिवर्तन सफल हुआ या विफल। |
| static [TryParse](../baseencodetype/tryparse/)(System::String, System::SharedPtr\<SymbologyEncodeType\>\&) | [BaseEncodeType](../baseencodetype/) की स्ट्रिंग प्रतिनिधित्व को उसकी इंस्टेंस में बदलता है। एक रिटर्न वैल्यू दर्शाता है कि परिवर्तन सफल हुआ या विफल। |
## टिप्पणियाँ


यह नमूना दिखाता है कि कैसे [SymbologyEncodeType](./) क्लास का उदाहरण प्राप्त किया जाए।
```cpp
[C#]
SymbologyEncodeType symbologyType = EncodeTypes.QR

[VB.NET]
Dim symbologyType As SymbologyEncodeType
symbologyType = EncodeTypes.QR
```

## और देखें

* Class [BaseEncodeType](../baseencodetype/)
* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
