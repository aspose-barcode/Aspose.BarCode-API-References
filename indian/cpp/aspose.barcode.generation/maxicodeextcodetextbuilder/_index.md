---
title: "Aspose::BarCode::Generation::MaxiCodeExtCodetextBuilder क्लास"
linktitle: "MaxiCodeExtCodetextBuilder"
second_title: "Aspose.BarCode C++ के लिए API संदर्भ"
description: "C++ में Aspose::BarCode::Generation::MaxiCodeExtCodetextBuilder क्लास का उपयोग कैसे करें।"
type: docs
weight: 3500
url: /hi/cpp/aspose.barcode.generation/maxicodeextcodetextbuilder/
---
## MaxiCodeExtCodetextBuilder class




```cpp
class MaxiCodeExtCodetextBuilder : public Aspose::BarCode::Generation::ExtCodetextBuilder
```

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [AddECICodetext](../extcodetextbuilder/addecicodetext/)(ECIEncodings, System::String) | Extended Channel Identifier के साथ codetext जोड़ता है |
| [AddPlainCodetext](../extcodetextbuilder/addplaincodetext/)(System::String) | साधारण codetext को विस्तारित codetext आइटम्स में जोड़ता है |
| virtual [Clear](../extcodetextbuilder/clear/)() | विस्तारित codetext आइटम्स को साफ़ करता है |
| [ExtCodetextBuilder](../extcodetextbuilder/extcodetextbuilder/)() |  |
| [GetExtendedCodetext](./getextendedcodetext/)() override | विस्तारित codetext सूची से Extended codetext उत्पन्न करता है। |
## टिप्पणियाँ


MaxiCodeEncodeMode के ExtendedCodetext मोड के लिए MaxiCode बारकोड के विस्तारित कोडटेक्स्ट जेनरेटर

दृश्यमान टेक्स्ट को प्रबंधित अक्षरों को हटाने के लिए सेट करने हेतु [BarcodeGenerator](../barcodegenerator/) की TwoDDisplayText प्रॉपर्टी का उपयोग करें।

यह उदाहरण दिखाता है कि विस्तारित मोड में [MaxiCodeExtCodetextBuilder](./) का उपयोग कैसे करें।
```cpp
[C#]
//codetext बनाएं
MaxiCodeExtCodetextBuilder textBuilder = new MaxiCodeExtCodetextBuilder();
textBuilder.AddECICodetext(ECIEncodings.Win1251, "Will");
textBuilder.AddECICodetext(ECIEncodings.UTF8, "犬Right狗");
textBuilder.AddECICodetext(ECIEncodings.UTF16BE, "犬Power狗");
textBuilder.AddPlainCodetext("Plain text");

//codetext उत्पन्न करें
string codetext = textBuilder.GetExtendedCodetext();

//उत्पन्न करें
using(BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MaxiCode, codetext))
{
    generator.Parameters.Barcode.CodeTextParameters.TwoDDisplayText = "My Text";
    generator.Save("test.bmp");
}
```

## और देखें

* Class [ExtCodetextBuilder](../extcodetextbuilder/)
* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
