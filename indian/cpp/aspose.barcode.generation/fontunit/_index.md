---
title: "Aspose::BarCode::Generation::FontUnit क्लास"
linktitle: "FontUnit"
second_title: "Aspose.BarCode C++ के लिए API संदर्भ"
description: "Aspose::BarCode::Generation::FontUnit क्लास। टेक्स्ट के लिए एक विशिष्ट प्रारूप को परिभाषित करता है, जिसमें फ़ॉन्ट फ़ेस, आकार, और शैली गुण शामिल हैं जहाँ आकार C++ में Unit मान प्रॉपर्टी में होता है।"
type: docs
weight: 2500
url: /hi/cpp/aspose.barcode.generation/fontunit/
---
## FontUnit class


टेक्स्ट के लिए एक विशिष्ट प्रारूप को परिभाषित करता है, जिसमें फ़ॉन्ट फ़ेस, आकार, और शैली गुण शामिल हैं जहाँ आकार [Unit](../unit/) मान प्रॉपर्टी में होता है।

```cpp
class FontUnit : public System::Object
```

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [get_FamilyName](./get_familyname/)() const | इस फ़ॉन्ट का फ़ेस नाम प्राप्त करता है। |
| [get_Size](./get_size/)() const | इस [FontUnit](./) का आकार [Unit](../unit/) मान में प्राप्त करता है। |
| [get_Style](./get_style/)() const | इस [FontUnit](./) के लिए शैली जानकारी प्राप्त करता है। |
| [set_FamilyName](./set_familyname/)(System::String) | इस फ़ॉन्ट का फ़ेस नाम सेट करता है। |
| [set_Style](./set_style/)(System::Drawing::FontStyle) | इस [FontUnit](./) के लिए शैली जानकारी सेट करता है। |
## टिप्पणियाँ


यह उदाहरण दिखाता है कि कैसे एक [BarCode](../../aspose.barcode/) छवि बनाएं और सहेजें।
```cpp
[C#]
      using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Code128))
      {
      generator.CodeTextStyle.Font.Style = FontStyle.Italic;
      generator.CodeTextStyle.Font.Size.Point = 18;
      generator.Save("test.png");
  }
```

## और देखें

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
