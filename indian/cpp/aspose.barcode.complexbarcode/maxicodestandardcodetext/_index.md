---
title: "Aspose::BarCode::ComplexBarcode::MaxiCodeStandardCodetext क्लास"
linktitle: "MaxiCodeStandardCodetext"
second_title: "Aspose.BarCode C++ के लिए API संदर्भ"
description: "Aspose::BarCode::ComplexBarcode::MaxiCodeStandardCodetext क्लास। C++ में मोड 4, 5 और 6 के लिए MaxiCode कोडटेक्स्ट को एन्कोड और डिकोड करने के लिए क्लास।"
type: docs
weight: 2000
url: /hi/cpp/aspose.barcode.complexbarcode/maxicodestandardcodetext/
---
## MaxiCodeStandardCodetext class


मोड 4, 5 और 6 के लिए MaxiCode कोडटेक्स्ट को एन्कोड और डिकोड करने के लिए क्लास.

```cpp
class MaxiCodeStandardCodetext : public Aspose::BarCode::ComplexBarcode::MaxiCodeCodetext
```

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [Equals](./equals/)(System::SharedPtr\<System::Object\>) override | एक मान लौटाता है जो दर्शाता है कि यह इंस्टेंस निर्दिष्ट [MaxiCodeStandardCodetext](./) मान के बराबर है या नहीं। |
| [get_ECIEncoding](../maxicodecodetext/get_eciencoding/)() const | ECI एन्कोडिंग प्राप्त करता है। जब MaxiCodeEncodeMode ऑटो हो तो उपयोग किया जाता है। डिफ़ॉल्ट मान: ISO-8859-1 |
| [get_EncodeMode](../maxicodecodetext/get_encodemode/)() const | MaxiCode एन्कोड मोड प्राप्त करता है। डिफ़ॉल्ट मान: ऑटो। |
| [get_Message](./get_message/)() const | संदेश प्राप्त करता है। |
| [get_Mode](./get_mode/)() | MaxiCode मोड प्राप्त करता है। मानक कोडटेक्स्ट केवल मोड 4, 5 और 6 के साथ उपयोग किया जा सकता है। |
| [GetBarcodeType](../maxicodecodetext/getbarcodetype/)() override | बारकोड प्रकार प्राप्त करता है। |
| [GetConstructedCodetext](./getconstructedcodetext/)() override | कोडटेक्स्ट बनाता है |
| [GetHashCode](./gethashcode/)() const override | इस इंस्टेंस के लिए हैश कोड लौटाता है। |
| [GetMode](./getmode/)() const override | MaxiCode मोड प्राप्त करता है। |
| [InitFromString](./initfromstring/)(System::String) override | निर्मित कोडटेक्स्ट से इंस्टेंस को इनिशियलाइज़ करता है। |
| [MaxiCodeCodetext](../maxicodecodetext/maxicodecodetext/)() |  |
| [MaxiCodeStandardCodetext](./maxicodestandardcodetext/)() |  |
| [set_ECIEncoding](../maxicodecodetext/set_eciencoding/)(Generation::ECIEncodings) | ECI एन्कोडिंग सेट करता है। जब MaxiCodeEncodeMode ऑटो हो तो उपयोग किया जाता है। डिफ़ॉल्ट मान: ISO-8859-1 |
| [set_EncodeMode](../maxicodecodetext/set_encodemode/)(Generation::MaxiCodeEncodeMode) | MaxiCode एन्कोड मोड सेट करता है। डिफ़ॉल्ट मान: ऑटो। |
| [set_Message](./set_message/)(System::String) | संदेश सेट करता है। |
| [set_Mode](./set_mode/)(Generation::MaxiCodeMode) | MaxiCode मोड सेट करता है। मानक कोडटेक्स्ट केवल मोड 4, 5 और 6 के साथ उपयोग किया जा सकता है। |
## टिप्पणियाँ


//Mode 4 [MaxiCodeStandardCodetext](./) maxiCodeCodetext = new [MaxiCodeStandardCodetext()](./maxicodestandardcodetext/); maxiCodeCodetext.Mode = MaxiCodeMode.Mode4; maxiCodeCodetext.Message = "Test message"; using ([ComplexBarcodeGenerator](../complexbarcodegenerator/) complexGenerator = new [ComplexBarcodeGenerator](../complexbarcodegenerator/)(maxiCodeCodetext.GetConstructedCodetext()) { complexGenerator.GenerateBarCodeImage(); } //Mode 5 [MaxiCodeStandardCodetext](./) maxiCodeCodetext = new [MaxiCodeStandardCodetext()](./maxicodestandardcodetext/); maxiCodeCodetext.Mode = MaxiCodeMode.Mode5; maxiCodeCodetext.Message = "Test message"; using ([ComplexBarcodeGenerator](../complexbarcodegenerator/) complexGenerator = new [ComplexBarcodeGenerator](../complexbarcodegenerator/)(maxiCodeCodetext.GetConstructedCodetext()) { complexGenerator.GenerateBarCodeImage(); } //Mode 6 [MaxiCodeStandardCodetext](./) maxiCodeCodetext = new [MaxiCodeStandardCodetext()](./maxicodestandardcodetext/); maxiCodeCodetext.Mode = MaxiCodeMode.Mode6; maxiCodeCodetext.Message = "Test message"; using ([ComplexBarcodeGenerator](../complexbarcodegenerator/) complexGenerator = new [ComplexBarcodeGenerator](../complexbarcodegenerator/)(maxiCodeCodetext.GetConstructedCodetext()) { complexGenerator.GenerateBarCodeImage(); }
## और देखें

* Class [MaxiCodeCodetext](../maxicodecodetext/)
* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
