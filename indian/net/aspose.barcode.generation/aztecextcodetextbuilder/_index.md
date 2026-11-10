---
title: "क्लास AztecExtCodetextBuilder"
second_title: "Aspose.BarCode for .NET API संदर्भ"
description: "Aspose.BarCode.Generation.AztecExtCodetextBuilder क्लास। Aztec बारकोड के लिए ExtendedCodetext मोड (AztecEncodeMode) में विस्तारित कोडटेक्स्ट जेनरेटर।"
type: docs
weight: 950
url: /hi/net/aspose.barcode.generation/aztecextcodetextbuilder/
---
## AztecExtCodetextBuilder class

AztecEncodeMode के ExtendedCodetext मोड के लिए Aztec बारकोड्स के विस्तारित कोडटेक्स्ट जेनरेटर।

BarcodeGenerator की TwoDDisplayText प्रॉपर्टी का उपयोग करके दृश्यमान टेक्स्ट को सेट करें ताकि प्रबंधन अक्षरों को हटाया जा सके।

```csharp
public class AztecExtCodetextBuilder : ExtCodetextBuilder
```

## निर्माता

| नाम | विवरण |
| --- | --- |
| [AztecExtCodetextBuilder](aztecextcodetextbuilder/)() | डिफ़ॉल्ट कन्स्ट्रक्टर। |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [AddECICodetext](../../aspose.barcode.generation/extcodetextbuilder/addecicodetext/)(ECIEncodings, string) | Extended Channel Identifier के साथ कोडटेक्स्ट जोड़ता है |
| [AddPlainCodetext](../../aspose.barcode.generation/extcodetextbuilder/addplaincodetext/)(string) | साधारण कोडटेक्स्ट को विस्तारित कोडटेक्स्ट आइटम्स में जोड़ता है |
| virtual [Clear](../../aspose.barcode.generation/extcodetextbuilder/clear/)() | विस्तारित कोडटेक्स्ट आइटम्स को साफ़ करता है |
| override [GetExtendedCodetext](../../aspose.barcode.generation/aztecextcodetextbuilder/getextendedcodetext/)() | विस्तारित कोडटेक्स्ट सूची से विस्तारित कोडटेक्स्ट उत्पन्न करता है। |

## उदाहरण

यह उदाहरण दिखाता है कि Extended मोड में AztecExtCodetextBuilder का उपयोग कैसे किया जाता है।

```csharp
[C#]
//कोडटेक्स्ट बनाएं
AztecExtCodetextBuilder textBuilder = new AztecExtCodetextBuilder();
textBuilder.AddECICodetext(ECIEncodings.Win1251, "Will");
textBuilder.AddECICodetext(ECIEncodings.UTF8, "犬Right狗");
textBuilder.AddECICodetext(ECIEncodings.UTF16BE, "犬Power狗");
textBuilder.AddPlainCodetext("Plain text");

//कोडटेक्स्ट उत्पन्न करें
string codetext = textBuilder.GetExtendedCodetext();    

//उत्पन्न करें
using(BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Aztec, codetext))
{
    generator.Parameters.Barcode.CodeTextParameters.TwoDDisplayText = "My Text";
	generator.Save("test.bmp");
}
```

### और देखें

* class [ExtCodetextBuilder](../extcodetextbuilder/)
* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


