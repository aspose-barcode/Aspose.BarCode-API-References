---
title: "Aspose::BarCode::Generation::DataMatrixExtCodetextBuilder class"
linktitle: "DataMatrixExtCodetextBuilder"
second_title: "Aspose.BarCode C++ के लिए API संदर्भ"
description: "C++ में Aspose::BarCode::Generation::DataMatrixExtCodetextBuilder class का उपयोग कैसे करें।"
type: docs
weight: 1900
url: /hi/cpp/aspose.barcode.generation/datamatrixextcodetextbuilder/
---
## DataMatrixExtCodetextBuilder class




```cpp
class DataMatrixExtCodetextBuilder : public Aspose::BarCode::Generation::ExtCodetextBuilder
```

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [AddCodetextWithEncodeMode](./addcodetextwithencodemode/)(DataMatrixEncodeMode, System::String) | परिभाषित एन्कोड मोड के साथ कोडटेक्स्ट को विस्तारित कोडटेक्स्ट आइटम्स में जोड़ता है। |
| [AddECICodetext](../extcodetextbuilder/addecicodetext/)(ECIEncodings, System::String) | Extended Channel Identifier के साथ codetext जोड़ता है |
| [AddECICodetextWithEncodeMode](./addecicodetextwithencodemode/)(ECIEncodings, DataMatrixEncodeMode, System::String) | परिभाषित एन्कोड मोड के साथ विस्तारित चैनल पहचानकर्ता के साथ कोडटेक्स्ट जोड़ता है। |
| [AddPlainCodetext](../extcodetextbuilder/addplaincodetext/)(System::String) | साधारण codetext को विस्तारित codetext आइटम्स में जोड़ता है |
| virtual [Clear](../extcodetextbuilder/clear/)() | विस्तारित codetext आइटम्स को साफ़ करता है |
| [ExtCodetextBuilder](../extcodetextbuilder/extcodetextbuilder/)() |  |
| [GetExtendedCodetext](./getextendedcodetext/)() override | विस्तारित codetext सूची से Extended codetext उत्पन्न करता है। |
## टिप्पणियाँ


EncodeMode के ExtendedCodetext मोड के लिए 2D DataMatrix बारकोड के लिए विस्तारित कोडटेक्स्ट जेनरेटर।


```cpp
[C#]
//विस्तारित codetext मोड

//codetext बनाएं
DataMatrixExtCodetextBuilder textBuilder = new DataMatrixExtCodetextBuilder();
codetextBuilder.AddECICodetextWithEncodeMode(ECIEncodings.Win1251, EncodeMode.Bytes, "World");
codetextBuilder.AddPlainCodetext("Will");
codetextBuilder.AddECICodetext(ECIEncodings.UTF8, "犬Right狗");
codetextBuilder.AddCodetextWithEncodeMode(EncodeMode.C40, "ABCDE");

//codetext उत्पन्न करें
string codetext = textBuilder.GetExtendedCodetext();

//उत्पन्न करें
using(BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DataMatrix, codetext))
{
    generator.Parameters.Barcode.DataMatrix.EncodeMode = EncodeMode.ExtendedCodetext;
    generator.Save("test.bmp");
}
```

## और देखें

* Class [ExtCodetextBuilder](../extcodetextbuilder/)
* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
