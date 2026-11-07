---
title: "enum"
linktitle: "DataMatrixEncodeMode"
second_title: "Aspose.BarCode C++ के लिए API संदर्भ"
description: "enum। DataMatrix एन्कोडर का एन्कोडिंग मोड, C++ में डिफ़ॉल्ट रूप से Auto।"
type: docs
weight: 6300
url: /hi/cpp/aspose.barcode.generation/datamatrixencodemode/
---
## DataMatrixEncodeMode enum


DataMatrix एन्कोडर का एन्कोडिंग मोड, डिफ़ॉल्ट रूप से Auto

```cpp
enum class DataMatrixEncodeMode
```

### मान

| नाम | मान | विवरण |
| --- | --- | --- |
| ऑटो | 0 | Auto मोड में, CodeText को अधिकतम डेटा संकुचन के साथ एन्कोड किया जाता है। यूनिकोड अक्षरों को निर्दिष्ट ECIEncoding में पुनः एन्कोड किया जाता है और ECI पहचानकर्ता डाला जाता है। यदि कोई ऐसा अक्षर मिलता है जो चयनित ECI एन्कोडिंग द्वारा समर्थित नहीं है, तो एक exception फेंका जाता है। |
| ASCII | 1 | प्रति बाइट एक अल्फ़ान्यूमेरिक या दो संख्यात्मक अक्षर एन्कोड करता है। |
| C40 | 8 | C40 एन्कोडिंग का उपयोग करता है। अपर केस अल्फ़ान्यूमेरिक, लोअर केस और विशेष अक्षरों को एन्कोड करता है। |
| पाठ | 9 | Text एन्कोडिंग का उपयोग करता है। लोअर केस अल्फ़ान्यूमेरिक, अपर केस और विशेष अक्षरों को एन्कोड करता है। |
| EDIFACT | 10 | EDIFACT एन्कोडिंग का उपयोग करता है। प्रत्येक अक्षर के लिए छह बिट्स उपयोग करता है, अंकों, अपर केस अक्षरों और कई विराम चिह्नों को एन्कोड करता है, लेकिन लोअर केस अक्षरों का समर्थन नहीं करता। |
| ANSIX12 | 11 | ANSI X12 एन्कोडिंग का उपयोग करता है। |
| Extended | 13 |  |
| Base256 | 14 | 8 बिट मान एन्कोड करता है। |
| Binary | 15 | Binary मोड में, CodeText को अधिकतम डेटा संकुचन के साथ एन्कोड किया जाता है। यदि कोई यूनिकोड अक्षर मिलता है, तो एक exception फेंका जाता है। |
| ECI | 16 | ECI मोड में, संपूर्ण संदेश को निर्दिष्ट ECIEncoding में पुनः एन्कोड किया जाता है और ECI पहचानकर्ता डाला जाता है। यदि कोई ऐसा अक्षर मिलता है जो चयनित ECI एन्कोडिंग द्वारा समर्थित नहीं है, तो एक exception फेंका जाता है। कृपया ध्यान दें कि कुछ पुराने (2006 से पहले) स्कैनर इस मोड का समर्थन नहीं कर सकते हैं। |

## टिप्पणियाँ


यह उदाहरण दिखाता है कि Extended मोड में codetext कैसे किया जाता है।
```cpp
[C#]
//Auto मोड
string codetext = "犬Right狗";
using (var generator = new BarcodeGenerator(EncodeTypes.DataMatrix, codetext))
{
    generator.Parameters.Barcode.DataMatrix.ECIEncoding = ECIEncodings.UTF8;
    generator.Save("test.bmp");
}

//Bytes मोड
byte[] encodedArr = { 0xFF, 0xFE, 0xFD, 0xFC, 0xFB, 0xFA, 0xF9 };
using (var generator = new BarcodeGenerator(EncodeTypes.DataMatrix))
{
    generator.SetCodetext(encodedArr);
    generator.Parameters.Barcode.DataMatrix.EncodeMode = EncodeMode.Binary;
    generator.Save("test.bmp");
}


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
    generator.Parameters.Barcode.DataMatrix.EncodeMode = EncodeMode.Extended;
    generator.Save("test.bmp");
}
```

## और देखें

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
