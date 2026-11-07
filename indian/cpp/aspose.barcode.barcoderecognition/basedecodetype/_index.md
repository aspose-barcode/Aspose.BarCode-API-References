---
title: "Aspose::BarCode::BarCodeRecognition::BaseDecodeType क्लास"
linktitle: "BaseDecodeType"
second_title: "Aspose.BarCode C++ के लिए API संदर्भ"
description: "Aspose::BarCode::BarCodeRecognition::BaseDecodeType क्लास। C++ में MultiDecodeType और SingleDecodeType के लिए बेस क्लास।"
type: docs
weight: 900
url: /hi/cpp/aspose.barcode.barcoderecognition/basedecodetype/
---
## BaseDecodeType class


[MultiDecodeType](../multidecodetype/) और [SingleDecodeType](../singledecodetype/) के लिए बेस क्लास।

```cpp
class BaseDecodeType : public virtual System::IEquatable<System::SharedPtr<BaseDecodeType>>
```

## विधियाँ

| विधि | विवरण |
| --- | --- |
| virtual [ContainsAny](./containsany/)(const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) | निर्धारित करता है कि दिए गए डिकोड प्रकारों में से कोई भी शामिल है या नहीं |
| virtual [Equals](./equals/)(System::SharedPtr\<SingleDecodeType\>) | एक मान लौटाता है जो दर्शाता है कि यह इंस्टेंस निर्दिष्ट [SingleDecodeType](../singledecodetype/) मान के बराबर है या नहीं। |
| virtual [Equals](./equals/)(System::SharedPtr\<MultiDecodeType\>) | एक मान लौटाता है जो दर्शाता है कि यह इंस्टेंस निर्दिष्ट [MultiDecodeType](../multidecodetype/) मान के बराबर है या नहीं। |
| [Equals](./equals/)(System::SharedPtr\<BaseDecodeType\>) override | एक मान लौटाता है जो दर्शाता है कि यह उदाहरण निर्दिष्ट [BaseDecodeType](./) मान के बराबर है या नहीं। |
| [GetHashCode](./gethashcode/)() const override | इस इंस्टेंस के लिए हैश कोड लौटाता है। |
| static [TryParse](./tryparse/)(System::String, System::SharedPtr\<SingleDecodeType\>\&) | [SingleDecodeType](../singledecodetype/) की स्ट्रिंग प्रतिनिधित्व को उसके उदाहरण में बदलता है। एक लौटाया गया मान दर्शाता है कि परिवर्तन सफल हुआ या विफल। |
| static [TryParse](./tryparse/)(System::String, System::SharedPtr\<MultiDecodeType\>\&) | [MultiDecodeType](../multidecodetype/) की स्ट्रिंग प्रतिनिधित्व को उसकी इंस्टेंस में बदलता है। लौटाया गया मान दर्शाता है कि परिवर्तन सफल हुआ या विफल। |
| static [TryParse](./tryparse/)(System::String, System::SharedPtr\<BaseDecodeType\>\&) | [BaseDecodeType](./) की स्ट्रिंग प्रतिनिधित्व को उसके उदाहरण में बदलता है, वास्तविक प्रकार निर्धारित करने के बाद। एक लौटाया गया मान दर्शाता है कि परिवर्तन सफल हुआ या विफल। |
## टिप्पणियाँ


यह उदाहरण दर्शाता है कि [BaseDecodeType](./) को [SingleDecodeType](../singledecodetype/) और [MultiDecodeType](../multidecodetype/) के साथ कैसे उपयोग किया जाए।
```cpp
[C#]
BaseDecodeType decodeOne = DecodeType.Code128;
BaseDecodeType decodeTwo = new MultiDecodeType(DecodeType.Code128, DecodeType.Code39, DecodeType.Code39FullASCII);
[VB.NET]
Dim decodeOne As BaseDecodeType = DecodeType.Code128
Dim decodeTwo As BaseDecodeType = New MultiDecodeType(DecodeType.Code128, DecodeType.Code39, DecodeType.Code39FullASCII)
```

## और देखें

* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
