---
title: "Enum DataMatrixEncodeMode"
second_title: "Aspose.BarCode for .NET API संदर्भ"
description: "Aspose.BarCode.Generation.DataMatrixEncodeMode enum. DataMatrix एन्कोडर का एन्कोडिंग मोड डिफ़ॉल्ट रूप से Auto है।"
type: docs
weight: 1200
url: /hi/net/aspose.barcode.generation/datamatrixencodemode/
---
## DataMatrixEncodeMode enumeration

डेटा मैट्रिक्स एन्कोडर का एन्कोडिंग मोड, डिफ़ॉल्ट रूप से ऑटो।

```csharp
public enum DataMatrixEncodeMode
```

### मान

| नाम | मान | विवरण |
| --- | --- | --- |
| Auto | `0` | Auto मोड में, CodeText को अधिकतम डेटा संकुचन के साथ एन्कोड किया जाता है। Unicode अक्षरों को निर्दिष्ट ECIEncoding में पुनः एन्कोड किया जाता है और एक ECI पहचानकर्ता डाला जाता है। यदि कोई अक्षर पाया जाता है जो चयनित ECI एन्कोडिंग द्वारा समर्थित नहीं है, तो एक अपवाद फेंका जाता है। |
| ASCII | `1` | प्रति बाइट एक अल्फ़ान्यूमेरिक या दो संख्यात्मक अक्षर एन्कोड करता है। |
| C40 | `8` | C40 एन्कोडिंग का उपयोग करता है। बड़े अक्षर अल्फ़ान्यूमेरिक, छोटे अक्षर और विशेष अक्षरों को एन्कोड करता है। |
| Text | `9` | Text एन्कोडिंग का उपयोग करता है। छोटे अक्षर अल्फ़ान्यूमेरिक, बड़े अक्षर और विशेष अक्षरों को एन्कोड करता है। |
| EDIFACT | `10` | EDIFACT एन्कोडिंग का उपयोग करता है। प्रत्येक अक्षर के लिए छह बिट्स उपयोग करता है, अंकों, बड़े अक्षरों और कई विराम चिह्नों को एन्कोड करता है, लेकिन छोटे अक्षरों का समर्थन नहीं करता। |
| ANSIX12 | `11` | ANSI X12 एन्कोडिंग का उपयोग करता है। |
| Extended | `13` | ExtendedCodetext मोड कोडटेक्स्ट में एन्कोडेशन योजनाओं और ECI एन्कोडिंग को मैन्युअल रूप से स्विच करने की अनुमति देता है। |
| Base256 | `14` | 8 बिट मानों को एन्कोड करें। |
| Binary | `15` | Binary मोड में, CodeText को अधिकतम डेटा संकुचन के साथ एन्कोड किया जाता है। यदि कोई Unicode अक्षर पाया जाता है, तो एक अपवाद फेंका जाता है। |
| ECI | `16` | ECI मोड में, पूरे संदेश को निर्दिष्ट ECIEncoding में पुनः एन्कोड किया जाता है और एक ECI पहचानकर्ता डाला जाता है। यदि कोई अक्षर पाया जाता है जो चयनित ECI एन्कोडिंग द्वारा समर्थित नहीं है, तो एक अपवाद फेंका जाता है। कृपया ध्यान दें कि कुछ पुराने (2006 से पूर्व) स्कैनर इस मोड का समर्थन नहीं कर सकते हैं। |

## उदाहरण

यह उदाहरण दिखाता है कि Extended मोड में कोडटेक्स्ट कैसे किया जाता है।

```csharp
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


//Extended कोडटेक्स्ट मोड
//कोडटेक्स्ट बनाएं
DataMatrixExtCodetextBuilder textBuilder = new DataMatrixExtCodetextBuilder();
codetextBuilder.AddECICodetextWithEncodeMode(ECIEncodings.Win1251, EncodeMode.Bytes, "World");
codetextBuilder.AddPlainCodetext("Will");
codetextBuilder.AddECICodetext(ECIEncodings.UTF8, "犬Right狗");
codetextBuilder.AddCodetextWithEncodeMode(EncodeMode.C40, "ABCDE");

//कोडटेक्स्ट उत्पन्न करें
string codetext = textBuilder.GetExtendedCodetext();    

//उत्पन्न करें
using(BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DataMatrix, codetext))
{
    generator.Parameters.Barcode.DataMatrix.EncodeMode = EncodeMode.Extended;
	generator.Save("test.bmp");
}
```

### और देखें

* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


