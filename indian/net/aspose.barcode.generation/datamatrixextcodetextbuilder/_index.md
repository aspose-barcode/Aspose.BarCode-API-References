---
title: "क्लास DataMatrixExtCodetextBuilder"
second_title: "Aspose.BarCode for .NET API संदर्भ"
description: "Aspose.BarCode.Generation.DataMatrixExtCodetextBuilder क्लास। 2D DataMatrix बारकोड के लिए ExtendedCodetext मोड (EncodeMode) में विस्तारित कोडटेक्स्ट जेनरेटर।"
type: docs
weight: 1210
url: /hi/net/aspose.barcode.generation/datamatrixextcodetextbuilder/
---
## DataMatrixExtCodetextBuilder class

विस्तारित कोडटेक्स्ट जेनरेटर 2D DataMatrix बारकोड के लिए EncodeMode के ExtendedCodetext मोड के लिए

```csharp
public class DataMatrixExtCodetextBuilder : ExtCodetextBuilder
```

## निर्माता

| नाम | विवरण |
| --- | --- |
| [DataMatrixExtCodetextBuilder](datamatrixextcodetextbuilder/)() | डिफ़ॉल्ट कन्स्ट्रक्टर। |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [AddCodetextWithEncodeMode](../../aspose.barcode.generation/datamatrixextcodetextbuilder/addcodetextwithencodemode/)(DataMatrixEncodeMode, string) | परिभाषित एन्कोड मोड के साथ कोडटेक्स्ट को विस्तारित कोडटेक्स्ट आइटम्स में जोड़ता है |
| [AddECICodetext](../../aspose.barcode.generation/extcodetextbuilder/addecicodetext/)(ECIEncodings, string) | Extended Channel Identifier के साथ कोडटेक्स्ट जोड़ता है |
| [AddECICodetextWithEncodeMode](../../aspose.barcode.generation/datamatrixextcodetextbuilder/addecicodetextwithencodemode/)(ECIEncodings, DataMatrixEncodeMode, string) | परिभाषित एन्कोड मोड के साथ Extended Channel Identifier के साथ कोडटेक्स्ट जोड़ता है |
| [AddPlainCodetext](../../aspose.barcode.generation/extcodetextbuilder/addplaincodetext/)(string) | साधारण कोडटेक्स्ट को विस्तारित कोडटेक्स्ट आइटम्स में जोड़ता है |
| virtual [Clear](../../aspose.barcode.generation/extcodetextbuilder/clear/)() | विस्तारित कोडटेक्स्ट आइटम्स को साफ़ करता है |
| override [GetExtendedCodetext](../../aspose.barcode.generation/datamatrixextcodetextbuilder/getextendedcodetext/)() | विस्तारित कोडटेक्स्ट सूची से विस्तारित कोडटेक्स्ट उत्पन्न करता है। |

## उदाहरण

```csharp
[C#]
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
    generator.Parameters.Barcode.DataMatrix.EncodeMode = EncodeMode.ExtendedCodetext;
	generator.Save("test.bmp");
}
```

### और देखें

* class [ExtCodetextBuilder](../extcodetextbuilder/)
* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


