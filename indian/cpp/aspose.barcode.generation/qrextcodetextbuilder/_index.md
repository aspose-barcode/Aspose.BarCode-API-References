---
title: "Aspose::BarCode::Generation::QrExtCodetextBuilder class"
linktitle: "QrExtCodetextBuilder"
second_title: "Aspose.BarCode C++ के लिए API संदर्भ"
description: "C++ में Aspose::BarCode::Generation::QrExtCodetextBuilder क्लास का उपयोग कैसे करें।"
type: docs
weight: 4300
url: /hi/cpp/aspose.barcode.generation/qrextcodetextbuilder/
---
## QrExtCodetextBuilder class




```cpp
class QrExtCodetextBuilder : public Aspose::BarCode::Generation::ExtCodetextBuilder
```

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [AddCodetextWithCompactionMode](./addcodetextwithcompactionmode/)(QrExtCompactionMode, System::String) | निर्दिष्ट QR संपीड़न मोड के साथ कोडटेक्स्ट को विस्तारित कोडटेक्स्ट आइटम्स में जोड़ता है। |
| [AddECICodetext](../extcodetextbuilder/addecicodetext/)(ECIEncodings, System::String) | Extended Channel Identifier के साथ codetext जोड़ता है |
| [AddFNC1FirstPosition](./addfnc1firstposition/)() | पहले स्थान पर FNC1 सेट करता है। यदि पहले कोई अन्य FNC1 मोड सेट किया गया था, तो इसे बदल दिया जाता है। |
| [AddFNC1GroupSeparator](./addfnc1groupseparator/)() | विस्तारित कोडटेक्स्ट आइटम्स में ग्रुप सेपरेटर (GS - '\u001D') जोड़ता है। |
| [AddFNC1SecondPosition](./addfnc1secondposition/)(System::String) | दूसरे स्थान पर FNC1 सेट करता है। यदि पहले कोई अन्य FNC1 मोड सेट किया गया था, तो इसे बदल दिया जाता है। |
| [AddPlainCodetext](../extcodetextbuilder/addplaincodetext/)(System::String) | साधारण codetext को विस्तारित codetext आइटम्स में जोड़ता है |
| [Clear](./clear/)() override | विस्तारित codetext आइटम्स को साफ़ करता है |
| [ExtCodetextBuilder](../extcodetextbuilder/extcodetextbuilder/)() |  |
| [GetExtendedCodetext](./getextendedcodetext/)() override | विस्तारित codetext सूची से Extended codetext उत्पन्न करता है। |
| [QrExtCodetextBuilder](./qrextcodetextbuilder/)() |  |
## टिप्पणियाँ


EncodeMode के ExtendedCodetext मोड के लिए 2D QR बारकोड्स का विस्तारित कोडटेक्स्ट जेनरेटर।

दृश्यमान टेक्स्ट को प्रबंधित अक्षरों को हटाने के लिए सेट करने हेतु [BarcodeGenerator](../barcodegenerator/) की TwoDDisplayText प्रॉपर्टी का उपयोग करें।

यह नमूना दिखाता है कि विस्तारित मोड में FNC1 की पहली स्थिति का उपयोग कैसे किया जाए।
```cpp
[C#]
//codetext बनाएं
QrExtCodetextBuilder TextBuilder = new QrExtCodetextBuilder();
TextBuilder.AddFNC1FirstPosition();
TextBuilder.AddPlainCodetext("000%89%%0");
TextBuilder.AddFNC1GroupSeparator();
TextBuilder.AddPlainCodetext("12345<FNC1>");

//codetext उत्पन्न करें
string codetext = TextBuilder.GetExtendedCodetext();

//उत्पन्न करें
using(BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.QR))
{
    generator.Parameters.Barcode.QR.EncodeMode = QREncodeMode.ExtendedCodetext;
    generator.Parameters.Barcode.QR.ErrorLevel = QRErrorLevel.LevelL;
    generator.CodeText = codetext;
    generator.Parameters.Barcode.CodeTextParameters.TwoDDisplayText = "My Text";
    generator.Save("test.bmp");
}
```


यह नमूना दिखाता है कि विस्तारित मोड में FNC1 की दूसरी स्थिति का उपयोग कैसे किया जाए।
```cpp
[C#]
//codetext बनाएं
QrExtCodetextBuilder TextBuilder = new QrExtCodetextBuilder();
TextBuilder.AddFNC1SecondPosition("12");
TextBuilder.AddPlainCodetext("TRUE3456");

//codetext उत्पन्न करें
string codetext = TextBuilder.GetExtendedCodetext();

//उत्पन्न करें
using(BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.QR))
{
    generator.Parameters.Barcode.QR.EncodeMode = QREncodeMode.ExtendedCodetext;
    generator.Parameters.Barcode.QR.ErrorLevel = QRErrorLevel.LevelL;
    generator.CodeText = codetext;
    generator.Parameters.Barcode.CodeTextParameters.TwoDDisplayText = "My Text";
    generator.Save("test.bmp");
}
```


यह नमूना दिखाता है कि विस्तारित मोड में मल्टी ECI मोड का उपयोग कैसे किया जाए।
```cpp
[C#]
//codetext बनाएं
QrExtCodetextBuilder TextBuilder = new QrExtCodetextBuilder();
TextBuilder.AddECICodetext(ECIEncodings.Win1251, "Will");
TextBuilder.AddECICodetext(ECIEncodings.UTF8, "Right");
TextBuilder.AddECICodetext(ECIEncodings.UTF16BE, "Power");
TextBuilder.AddPlainCodetext(@"t\e\\st");
TextBuilder.AddCodetextWithCompactionMode(QrExtCompactionMode.AlphaNumeric, @"ASPOSE2001");
TextBuilder.AddCodetextWithCompactionMode(QrExtCompactionMode.Numeric, @"20012026");

//codetext उत्पन्न करें
string codetext = TextBuilder.GetExtendedCodetext();

//उत्पन्न करें
using(BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.QR))
{
    generator.Parameters.Barcode.QR.EncodeMode = QREncodeMode.ExtendedCodetext;
    generator.Parameters.Barcode.QR.ErrorLevel = QRErrorLevel.LevelL;
    generator.CodeText = codetext;
    generator.Parameters.Barcode.CodeTextParameters.TwoDDisplayText = "My Text";
    generator.Save("test.bmp");
}
```

## और देखें

* Class [ExtCodetextBuilder](../extcodetextbuilder/)
* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
