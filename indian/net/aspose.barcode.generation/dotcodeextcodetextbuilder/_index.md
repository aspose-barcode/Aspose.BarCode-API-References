---
title: "क्लास DotCodeExtCodetextBuilder"
second_title: "Aspose.BarCode for .NET API संदर्भ"
description: "Aspose.BarCode.Generation.DotCodeExtCodetextBuilder क्लास। 2D DotCode बारकोड के लिए ExtendedCodetext मोड के DotCodeEncodeMode में विस्तारित कोडटेक्स्ट जेनरेटर।"
type: docs
weight: 1250
url: /hi/net/aspose.barcode.generation/dotcodeextcodetextbuilder/
---
## DotCodeExtCodetextBuilder class

विस्तारित कोडटेक्स्ट जेनरेटर 2D DotCode बारकोड के लिए DotCodeEncodeMode के ExtendedCodetext मोड के लिए

```csharp
public class DotCodeExtCodetextBuilder : ExtCodetextBuilder
```

## निर्माता

| नाम | विवरण |
| --- | --- |
| [DotCodeExtCodetextBuilder](dotcodeextcodetextbuilder/)() | डिफ़ॉल्ट कन्स्ट्रक्टर। |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [AddECICodetext](../../aspose.barcode.generation/extcodetextbuilder/addecicodetext/)(ECIEncodings, string) | Extended Channel Identifier के साथ कोडटेक्स्ट जोड़ता है |
| [AddFNC1FormatIdentifier](../../aspose.barcode.generation/dotcodeextcodetextbuilder/addfnc1formatidentifier/)() | विस्तारित कोडटेक्स्ट आइटम्स में FNC1 फ़ॉर्मेट पहचानकर्ता जोड़ता है। |
| [AddFNC3ReaderInitialization](../../aspose.barcode.generation/dotcodeextcodetextbuilder/addfnc3readerinitialization/)() | विस्तारित कोडटेक्स्ट आइटम्स में FNC3 रीडर इनिशियलाइज़ेशन जोड़ता है। |
| [AddFNC3SymbolSeparator](../../aspose.barcode.generation/dotcodeextcodetextbuilder/addfnc3symbolseparator/)() | विस्तारित कोडटेक्स्ट आइटम्स में FNC3 सिंबल सेपरेटर जोड़ता है। |
| [AddPlainCodetext](../../aspose.barcode.generation/extcodetextbuilder/addplaincodetext/)(string) | साधारण कोडटेक्स्ट को विस्तारित कोडटेक्स्ट आइटम्स में जोड़ता है |
| [AddStructuredAppendMode](../../aspose.barcode.generation/dotcodeextcodetextbuilder/addstructuredappendmode/)(int, int) | विस्तारित कोडटेक्स्ट आइटम्स में स्ट्रक्चर्ड अपेंड मोड जोड़ता है। |
| virtual [Clear](../../aspose.barcode.generation/extcodetextbuilder/clear/)() | विस्तारित कोडटेक्स्ट आइटम्स को साफ़ करता है |
| override [GetExtendedCodetext](../../aspose.barcode.generation/dotcodeextcodetextbuilder/getextendedcodetext/)() | विस्तारित कोडटेक्स्ट सूची से विस्तारित कोडटेक्स्ट उत्पन्न करता है। |

## उदाहरण

```csharp
[C#]
//Extended कोडटेक्स्ट मोड
//कोडटेक्स्ट बनाएं
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

//कोडटेक्स्ट उत्पन्न करें
string codetext = textBuilder.GetExtendedCodetext();    

//उत्पन्न करें
using(BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DotCode, codetext))
{
    generator.Parameters.Barcode.DotCode.DotCodeEncodeMode = DotCodeEncodeMode.ExtendedCodetext;
	generator.Save("test.bmp");
}
```

### और देखें

* class [ExtCodetextBuilder](../extcodetextbuilder/)
* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


