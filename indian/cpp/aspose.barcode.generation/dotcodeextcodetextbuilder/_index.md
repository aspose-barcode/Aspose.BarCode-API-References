---
title: "Aspose::BarCode::Generation::DotCodeExtCodetextBuilder class"
linktitle: "DotCodeExtCodetextBuilder"
second_title: "Aspose.BarCode C++ के लिए API संदर्भ"
description: "C++ में Aspose::BarCode::Generation::DotCodeExtCodetextBuilder क्लास का उपयोग कैसे करें।"
type: docs
weight: 2100
url: /hi/cpp/aspose.barcode.generation/dotcodeextcodetextbuilder/
---
## DotCodeExtCodetextBuilder class




```cpp
class DotCodeExtCodetextBuilder : public Aspose::BarCode::Generation::ExtCodetextBuilder
```

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [AddECICodetext](../extcodetextbuilder/addecicodetext/)(ECIEncodings, System::String) | Extended Channel Identifier के साथ codetext जोड़ता है |
| [AddFNC1FormatIdentifier](./addfnc1formatidentifier/)() | विस्तारित कोडटेक्स्ट आइटम्स में FNC1 फ़ॉर्मेट पहचानकर्ता जोड़ता है। |
| [AddFNC3ReaderInitialization](./addfnc3readerinitialization/)() | विस्तारित कोडटेक्स्ट आइटम्स में FNC3 रीडर इनिशियलाइज़ेशन जोड़ता है। |
| [AddFNC3SymbolSeparator](./addfnc3symbolseparator/)() | विस्तारित कोडटेक्स्ट आइटम्स में FNC3 प्रतीक विभाजक जोड़ता है। |
| [AddPlainCodetext](../extcodetextbuilder/addplaincodetext/)(System::String) | साधारण codetext को विस्तारित codetext आइटम्स में जोड़ता है |
| [AddStructuredAppendMode](./addstructuredappendmode/)(int32_t, int32_t) | विस्तारित कोडटेक्स्ट आइटम्स में संरचित अपेंड मोड जोड़ता है। |
| virtual [Clear](../extcodetextbuilder/clear/)() | विस्तारित codetext आइटम्स को साफ़ करता है |
| [ExtCodetextBuilder](../extcodetextbuilder/extcodetextbuilder/)() |  |
| [GetExtendedCodetext](./getextendedcodetext/)() override | विस्तारित codetext सूची से Extended codetext उत्पन्न करता है। |
## टिप्पणियाँ


DotCodeEncodeMode के ExtendedCodetext मोड के लिए 2D DotCode बारकोड्स के लिए विस्तारित कोडटेक्स्ट जेनरेटर।


```cpp
[C#]
//विस्तारित codetext मोड
//codetext बनाएं
DotCodeExtCodetextBuilder textBuilder = new DotCodeExtCodetextBuilder();
textBuilder.AddFNC1FormatIdentifier();
textBuilder.AddECICodetext(ECIEncodings.Win1251, "Will");
textBuilder.AddFNC1FormatIdentifier();
textBuilder.AddECICodetext(ECIEncodings.UTF8, "犬Right狗");
textBuilder.AddFNC1FormatIdentifier();
textBuilder.AddECICodetext(ECIEncodings.UTF16BE, "犬Power狗");
textBuilder.AddPlainCodetext("Plain text");
textBuilder.AddFNC3SymbolSeparator();
textBuilder.AddFNC3ReaderInitialization();
textBuilder.AddPlainCodetext("Reader initialization info");

//codetext उत्पन्न करें
string codetext = textBuilder.GetExtendedCodetext();

//उत्पन्न करें
using(BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DotCode, codetext))
{
    generator.Parameters.Barcode.DotCode.DotCodeEncodeMode = DotCodeEncodeMode.ExtendedCodetext;
    generator.Save("test.bmp");
}
```

## और देखें

* Class [ExtCodetextBuilder](../extcodetextbuilder/)
* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
