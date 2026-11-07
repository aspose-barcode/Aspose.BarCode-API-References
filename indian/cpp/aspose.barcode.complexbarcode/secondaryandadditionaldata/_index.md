---
title: "Aspose::BarCode::ComplexBarcode::SecondaryAndAdditionalData class"
linktitle: "SecondaryAndAdditionalData"
second_title: "Aspose.BarCode C++ के लिए API संदर्भ"
description: "Aspose::BarCode::ComplexBarcode::SecondaryAndAdditionalData class. C++ में HIBC LIC द्वितीयक और अतिरिक्त डेटा संग्रहीत करने के लिए क्लास."
type: docs
weight: 2600
url: /hi/cpp/aspose.barcode.complexbarcode/secondaryandadditionaldata/
---
## SecondaryAndAdditionalData class


HIBC LIC सेकेंडरी और अतिरिक्त डेटा को स्टोर करने के लिए क्लास.

```cpp
class SecondaryAndAdditionalData : public System::Object
```

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [Equals](./equals/)(System::SharedPtr\<System::Object\>) override | एक मान लौटाता है जो दर्शाता है कि यह इंस्टेंस निर्दिष्ट [SecondaryAndAdditionalData](./) मान के बराबर है या नहीं. |
| [get_DateOfManufacture](./get_dateofmanufacture/)() const | निर्माण तिथि की पहचान करता है। इस फ़ील्ड का उपयोग न करने के लिए निर्माण तिथि को DateTime.MinValue पर सेट किया जा सकता है। डिफ़ॉल्ट मान: DateTime.MinValue |
| [get_ExpiryDate](./get_expirydate/)() const | समाप्ति तिथि की पहचान करता है। यदि ExpiryDateFormat को None पर सेट नहीं किया गया है तो इसका उपयोग किया जाएगा। |
| [get_ExpiryDateFormat](./get_expirydateformat/)() const | समाप्ति तिथि प्रारूप की पहचान करता है। |
| [get_LotNumber](./get_lotnumber/)() const | लॉट या बैच नंबर की पहचान करता है। लॉट/बैच नंबर अल्फ़ान्यूमेरिक स्ट्रिंग होना चाहिए जिसकी अधिकतम लंबाई 18 अक्षर हो। |
| [get_Quantity](./get_quantity/)() const | मात्रा की पहचान करता है, यह 0 से 500 के बीच पूर्णांक मान होना चाहिए। इस फ़ील्ड का उपयोग न करने के लिए मात्रा को -1 पर सेट किया जा सकता है। डिफ़ॉल्ट मान: -1 |
| [get_SerialNumber](./get_serialnumber/)() const | सीरियल नंबर की पहचान करता है। सीरियल नंबर अल्फ़ान्यूमेरिक स्ट्रिंग होना चाहिए जिसकी अधिकतम लंबाई 18 अक्षर हो। |
| [GetHashCode](./gethashcode/)() const override | इस इंस्टेंस के लिए हैश कोड लौटाता है। |
| [ParseFromString](./parsefromstring/)(System::String) | HIBC LIC विनिर्देश के अनुसार स्ट्रिंग फ़ॉर्मेट से द्वितीयक और अतिरिक्त पूरक डेटा को इंस्टैंशिएट करता है। |
| [SecondaryAndAdditionalData](./secondaryandadditionaldata/)() |  |
| [set_DateOfManufacture](./set_dateofmanufacture/)(System::DateTime) | निर्माण तिथि की पहचान करता है। इस फ़ील्ड का उपयोग न करने के लिए निर्माण तिथि को DateTime.MinValue पर सेट किया जा सकता है। डिफ़ॉल्ट मान: DateTime.MinValue |
| [set_ExpiryDate](./set_expirydate/)(System::DateTime) | समाप्ति तिथि की पहचान करता है। यदि ExpiryDateFormat को None पर सेट नहीं किया गया है तो इसका उपयोग किया जाएगा। |
| [set_ExpiryDateFormat](./set_expirydateformat/)(HIBCLICDateFormat) | समाप्ति तिथि प्रारूप की पहचान करता है। |
| [set_LotNumber](./set_lotnumber/)(System::String) | लॉट या बैच नंबर की पहचान करता है। लॉट/बैच नंबर अल्फ़ान्यूमेरिक स्ट्रिंग होना चाहिए जिसकी अधिकतम लंबाई 18 अक्षर हो। |
| [set_Quantity](./set_quantity/)(int32_t) | मात्रा की पहचान करता है, यह 0 से 500 के बीच पूर्णांक मान होना चाहिए। इस फ़ील्ड का उपयोग न करने के लिए मात्रा को -1 पर सेट किया जा सकता है। डिफ़ॉल्ट मान: -1 |
| [set_SerialNumber](./set_serialnumber/)(System::String) | सीरियल नंबर की पहचान करता है। सीरियल नंबर अल्फ़ान्यूमेरिक स्ट्रिंग होना चाहिए जिसकी अधिकतम लंबाई 18 अक्षर हो। |
| [ToString](./tostring/)() const override | डेटा को HIBC LIC विनिर्देशन के अनुसार स्ट्रिंग फ़ॉर्मेट में परिवर्तित करता है। |
## और देखें

* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
