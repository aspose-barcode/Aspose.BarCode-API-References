---
title: "एनम MaxiCodeEncodeMode"
second_title: "Aspose.BarCode for .NET API संदर्भ"
description: "Aspose.BarCode.Generation.MaxiCodeEncodeMode एनम। MaxiCode बारकोड के लिए एन्कोडिंग मोड"
type: docs
weight: 1460
url: /hi/net/aspose.barcode.generation/maxicodeencodemode/
---
## MaxiCodeEncodeMode enumeration

MaxiCode बारकोड के लिए एन्कोडिंग मोड।

```csharp
public enum MaxiCodeEncodeMode
```

### मान

| नाम | मान | विवरण |
| --- | --- | --- |
| Auto | `0` | Auto मोड में, CodeText को अधिकतम डेटा संकुचन के साथ एन्कोड किया जाता है। Unicode अक्षरों को निर्दिष्ट ECIEncoding में पुनः एन्कोड किया जाता है और एक ECI पहचानकर्ता डाला जाता है। यदि कोई अक्षर पाया जाता है जो चयनित ECI एन्कोडिंग द्वारा समर्थित नहीं है, तो एक अपवाद फेंका जाता है। |
| Extended | `3` | विस्तारित मोड जो कई ECI मोडों का समर्थन करता है। |
| Binary | `4` | Binary मोड में, CodeText को अधिकतम डेटा संकुचन के साथ एन्कोड किया जाता है। यदि कोई Unicode अक्षर पाया जाता है, तो एक अपवाद फेंका जाता है। |
| ECI | `5` | ECI मोड में, पूरे संदेश को निर्दिष्ट ECIEncoding में पुनः एन्कोड किया जाता है और एक ECI पहचानकर्ता डाला जाता है। यदि कोई अक्षर पाया जाता है जो चयनित ECI एन्कोडिंग द्वारा समर्थित नहीं है, तो एक अपवाद फेंका जाता है। कृपया ध्यान दें कि कुछ पुराने (2006 से पूर्व) स्कैनर इस मोड का समर्थन नहीं कर सकते हैं। |

## उदाहरण

```csharp
[C#]
//Auto मोड
var codetext = "犬Right狗";
using (var generator = new BarcodeGenerator(EncodeTypes.MaxiCode, codetext))
{
    generator.Parameters.Barcode.MaxiCode.ECIEncoding = ECIEncodings.UTF8;
    generator.Save("test.bmp");
}

//Bytes मोड
byte[] encodedArr = { 0xFF, 0xFE, 0xFD, 0xFC, 0xFB, 0xFA, 0xF9 };
using (var generator = new BarcodeGenerator(EncodeTypes.MaxiCode))
{
    generator.SetCodetext(encodedArr);
    generator.Parameters.Barcode.MaxiCode.MaxiCodeEncodeMode = MaxiCodeEncodeMode.Binary;
    generator.Save("test.bmp");
}

//Extended कोडटेक्स्ट मोड
//कोडटेक्स्ट बनाएं
MaxiCodeExtCodetextBuilder textBuilder = new MaxiCodeExtCodetextBuilder();
textBuilder.AddECICodetext(ECIEncodings.Win1251, "Will");
textBuilder.AddECICodetext(ECIEncodings.UTF8, "犬Right狗");
textBuilder.AddECICodetext(ECIEncodings.UTF16BE, "犬Power狗");
textBuilder.AddPlainCodetext("Plain text");

//कोडटेक्स्ट उत्पन्न करें
string codetext = textBuilder.GetExtendedCodetext();    

//उत्पन्न करें
using(BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MaxiCode, codetext))
{
    generator.Parameters.Barcode.MaxiCode.MaxiCodeEncodeMode = MaxiCodeEncodeMode.Extended;
    generator.Parameters.Barcode.CodeTextParameters.TwoDDisplayText = "My Text";
	generator.Save("test.bmp");
}
```

### और देखें

* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


