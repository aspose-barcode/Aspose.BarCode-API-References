---
title: "Aspose::BarCode::Generation::Unit क्लास"
linktitle: "Unit"
second_title: "Aspose.BarCode C++ के लिए API संदर्भ"
description: "Aspose::BarCode::Generation::Unit क्लास। विभिन्न इकाइयों (पिक्सेल, इंच, आदि) में आकार मान निर्दिष्ट करता है C++ में।"
type: docs
weight: 5000
url: /hi/cpp/aspose.barcode.generation/unit/
---
## Unit class


विभिन्न इकाइयों (पिक्सेल, इंच आदि) में आकार मान निर्दिष्ट करता है।

```cpp
class Unit : public System::Object
```

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [Equals](./equals/)(System::SharedPtr\<System::Object\>) override | निर्धारित करता है कि यह इंस्टेंस और निर्दिष्ट ऑब्जेक्ट, जो भी एक [Unit](./) ऑब्जेक्ट होना चाहिए, का मान समान है या नहीं। |
| [get_Document](./get_document/)() | दस्तावेज़ इकाइयों में आकार मान प्राप्त करता है। |
| [get_Inches](./get_inches/)() | इंच में आकार मान प्राप्त करता है। |
| [get_Millimeters](./get_millimeters/)() | मिलीमीटर में आकार मान प्राप्त करता है। |
| [get_Pixels](./get_pixels/)() | पिक्सेल में आकार मान प्राप्त करता है। |
| [get_Point](./get_point/)() | पॉइंट में आकार मान प्राप्त करता है। |
| [get_Resolution](./get_resolution/)() const | रिज़ॉल्यूशन |
| [GetHashCode](./gethashcode/)() const override | इस ऑब्जेक्ट के लिए हैश कोड लौटाता है। |
| [set_Document](./set_document/)(float) | दस्तावेज़ इकाइयों में आकार मान सेट करता है। |
| [set_Inches](./set_inches/)(float) | इंच में आकार मान सेट करता है। |
| [set_Millimeters](./set_millimeters/)(float) | मिलीमीटर में आकार मान सेट करता है। |
| [set_Pixels](./set_pixels/)(float) | पिक्सेल में आकार मान सेट करता है। |
| [set_Point](./set_point/)(float) | पॉइंट में आकार मान सेट करता है। |
| [ToString](./tostring/)() const override | इस [Unit](./) की मानव-पठनीय स्ट्रिंग प्रतिनिधित्व लौटाता है। |
## टिप्पणियाँ


यह उदाहरण दिखाता है कि कैसे एक [BarCode](../../aspose.barcode/) छवि बनाएं और सहेजें।
```cpp
[C#]
      using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Code128))
      {
      generator.Parameters.Barcode.BarHeight.Millimeters = 10;
      generator.Save("test.png");
  }
```

## और देखें

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
