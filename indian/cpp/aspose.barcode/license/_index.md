---
title: "Aspose::BarCode::License क्लास"
linktitle: "लाइसेंस"
second_title: "Aspose.BarCode C++ के लिए API संदर्भ"
description: "Aspose::BarCode::License क्लास. C++ में घटक को लाइसेंस करने के लिए विधियाँ प्रदान करता है।"
type: docs
weight: 300
url: /hi/cpp/aspose.barcode/license/
---
## License class


घटक को लाइसेंस करने के लिए मेथड प्रदान करता है।

```cpp
class License : public System::Object
```

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [License](./license/)() | इस क्लास की नई इंस्टेंस को इनिशियलाइज़ करता है। |
| [SetLicense](./setlicense/)(System::String) | लाइब्रेरी को लाइसेंस करता है। |
| [SetLicense](./setlicense/)(System::SharedPtr\<System::IO::Stream\>) | लाइब्रेरी को लाइसेंस करता है। |
## टिप्पणियाँ


इस उदाहरण में, घटक वाली फ़ोल्डर में, कॉलिंग असेंबली वाली फ़ोल्डर में, एंट्री असेंबली वाली फ़ोल्डर में और फिर कॉलिंग असेंबली के एम्बेडेड रिसोर्सेज़ में MyLicense.lic नामक लाइसेंस फ़ाइल को खोजने का प्रयास किया जाएगा।
```cpp
[C#]
@verbatim
License license = new License();
license.SetLicense("MyLicense.lic");


[Visual Basic]

Dim license As license = New license
License.SetLicense("MyLicense.lic")
@endverbatim
```

## और देखें

* Namespace [Aspose::BarCode](../)
* Library [Aspose.BarCode for C++](../../)
