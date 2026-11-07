---
title: "विधि"
linktitle: "SetLicense"
second_title: "Aspose.BarCode C++ के लिए API संदर्भ"
description: " method. लाइब्रेरी को C++ में लाइसेंस करता है।"
type: docs
weight: 200
url: /hi/cpp/aspose.barcode/license/setlicense/
---
## License::SetLicense(System::String) method


लाइब्रेरी को लाइसेंस करता है।

```cpp
void Aspose::BarCode::License::SetLicense(System::String licenseName)
```


| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| licenseName | System::String | यह पूर्ण या संक्षिप्त फ़ाइल नाम या एम्बेडेड रिसोर्स का नाम हो सकता है। |
## टिप्पणियाँ


लाइसेंस को निम्नलिखित स्थानों में खोजने का प्रयास करता है:

1. स्पष्ट पथ।

2. फ़ोल्डर जिसमें **Aspose** कंपोनेंट असेंबली है।

3. फ़ोल्डर जिसमें क्लाइंट की कॉलिंग असेंबली है।

4. फ़ोल्डर जिसमें एंट्री (स्टार्टअप) असेंबली है।

5. क्लाइंट की कॉलिंग असेंबली में एक एम्बेडेड रिसोर्स।

**Note:**On the .NET Compact Framework, tries to find the license only in these locations:

1. स्पष्ट पथ।

2. क्लाइंट की कॉलिंग असेंबली में एक एम्बेडेड रिसोर्स।

इस उदाहरण में, घटक वाली फ़ोल्डर में, कॉलिंग असेंबली वाली फ़ोल्डर में, एंट्री असेंबली वाली फ़ोल्डर में और फिर कॉलिंग असेंबली के एम्बेडेड रिसोर्सेज़ में MyLicense.lic नामक लाइसेंस फ़ाइल को खोजने का प्रयास किया जाएगा।
```cpp
[C#]
@verbatim
License license = new License();
license.SetLicense("MyLicense.lic");


[Visual Basic]

Dim license As License = New License
license.SetLicense("MyLicense.lic")
@endverbatim
```


## और देखें

* Class [License](../)
* Namespace [Aspose::BarCode](../../)
* Library [Aspose.BarCode for C++](../../../)
## License::SetLicense(System::SharedPtr\<System::IO::Stream\>) method


लाइब्रेरी को लाइसेंस करता है।

```cpp
void Aspose::BarCode::License::SetLicense(System::SharedPtr<System::IO::Stream> stream)
```


| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| stream | System::SharedPtr\<System::IO::Stream\> | एक स्ट्रीम जिसमें लाइसेंस है। |
## टिप्पणियाँ



स्ट्रीम से लाइसेंस लोड करने के लिए इस मेथड का उपयोग करें।


```cpp
[C#]

License license = new License();
license.SetLicense(myStream);


[Visual Basic]

Dim license as License = new License
license.SetLicense(myStream)
```

## और देखें

* Class [License](../)
* Namespace [Aspose::BarCode](../../)
* Library [Aspose.BarCode for C++](../../../)
