---
title: "enum"
linktitle: "AztecEncodeMode"
second_title: "Aspose.BarCode C++ के लिए API संदर्भ"
description: "enum। C++ में Aztec बारकोड के लिए एन्कोडिंग मोड।"
type: docs
weight: 5300
url: /hi/cpp/aspose.barcode.generation/aztecencodemode/
---
## AztecEncodeMode enum


Aztec बारकोड के लिए एन्कोडिंग मोड।

```cpp
enum class AztecEncodeMode
```

### मान

| नाम | मान | विवरण |
| --- | --- | --- |
| ऑटो | 0 | Auto मोड में, CodeText को अधिकतम डेटा संकुचन के साथ एन्कोड किया जाता है। यूनिकोड अक्षरों को निर्दिष्ट ECIEncoding में पुनः एन्कोड किया जाता है और ECI पहचानकर्ता डाला जाता है। यदि कोई ऐसा अक्षर मिलता है जो चयनित ECI एन्कोडिंग द्वारा समर्थित नहीं है, तो एक exception फेंका जाता है। |
| Extended | 3 |  |
| Binary | 4 | Binary मोड में, CodeText को अधिकतम डेटा संकुचन के साथ एन्कोड किया जाता है। यदि कोई यूनिकोड अक्षर मिलता है, तो एक exception फेंका जाता है। |
| ECI | 5 | ECI मोड में, संपूर्ण संदेश को निर्दिष्ट ECIEncoding में पुनः एन्कोड किया जाता है और ECI पहचानकर्ता डाला जाता है। यदि कोई ऐसा अक्षर मिलता है जो चयनित ECI एन्कोडिंग द्वारा समर्थित नहीं है, तो एक exception फेंका जाता है। कृपया ध्यान दें कि कुछ पुराने (2006 से पहले) स्कैनर इस मोड का समर्थन नहीं कर सकते हैं। |

## टिप्पणियाँ



```cpp
[C#]
//Auto मोड
var codetext = "犬Right狗";
using (var generator = new BarcodeGenerator(EncodeTypes.Aztec, codetext))
{
    generator.Parameters.Barcode.Aztec.ECIEncoding = ECIEncodings.UTF8;
    generator.Save("test.bmp");
}

byte[] encodedArr = { 0xFF, 0xFE, 0xFD, 0xFC, 0xFB, 0xFA, 0xF9 };
using (var generator = new BarcodeGenerator(EncodeTypes.Aztec))
{
    generator.SetCodetext(encodedArr);
    generator.Parameters.Barcode.Aztec.AztecEncodeMode = AztecEncodeMode.Binary;
    generator.Save("test.bmp");
}

//Extended मोड
//codetext बनाएं
AztecExtCodetextBuilder textBuilder = new AztecExtCodetextBuilder();
textBuilder.AddECICodetext(ECIEncodings.Win1251, "Will");
textBuilder.AddECICodetext(ECIEncodings.UTF8, "犬Right狗");
textBuilder.AddECICodetext(ECIEncodings.UTF16BE, "犬Power狗");
textBuilder.AddPlainCodetext("Plain text");

//codetext उत्पन्न करें
string codetext = textBuilder.GetExtendedCodetext();

//उत्पन्न करें
using(BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Aztec, codetext))
{
    generator.Parameters.Barcode.Aztec.AztecEncodeMode = AztecEncodeMode.Extended;
    generator.Parameters.Barcode.CodeTextParameters.TwoDDisplayText = "My Text";
    generator.Save("test.bmp");
}
```

## और देखें

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
