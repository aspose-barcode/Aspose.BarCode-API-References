---
title: "क्लास QrExtCodetextBuilder"
second_title: "Aspose.BarCode for .NET API संदर्भ"
description: "Aspose.BarCode.Generation.QrExtCodetextBuilder class. विस्तारित कोडटेक्स्ट जेनरेटर 2D QR बारकोड के लिए ExtendedCodetext मोड के EncodeMode में"
type: docs
weight: 1630
url: /hi/net/aspose.barcode.generation/qrextcodetextbuilder/
---
## QrExtCodetextBuilder class

विस्तारित कोडटेक्स्ट जेनरेटर 2D QR बारकोड के लिए EncodeMode के ExtendedCodetext मोड के लिए

BarcodeGenerator की TwoDDisplayText प्रॉपर्टी का उपयोग करके दृश्यमान टेक्स्ट को सेट करें ताकि प्रबंधन अक्षरों को हटाया जा सके।

```csharp
public class QrExtCodetextBuilder : ExtCodetextBuilder
```

## निर्माता

| नाम | विवरण |
| --- | --- |
| [QrExtCodetextBuilder](qrextcodetextbuilder/)() | डिफ़ॉल्ट कन्स्ट्रक्टर। |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [AddCodetextWithCompactionMode](../../aspose.barcode.generation/qrextcodetextbuilder/addcodetextwithcompactionmode/)(QrExtCompactionMode, string) | निर्दिष्ट QR संपीड़न मोड के साथ कोडटेक्स्ट को विस्तारित कोडटेक्स्ट आइटम्स में जोड़ता है। |
| [AddECICodetext](../../aspose.barcode.generation/extcodetextbuilder/addecicodetext/)(ECIEncodings, string) | Extended Channel Identifier के साथ कोडटेक्स्ट जोड़ता है |
| [AddFNC1FirstPosition](../../aspose.barcode.generation/qrextcodetextbuilder/addfnc1firstposition/)() | पहले स्थान पर FNC1 सेट करता है। यदि पहले कोई अन्य FNC1 मोड सेट किया गया था, तो उसे बदल दिया जाता है। |
| [AddFNC1GroupSeparator](../../aspose.barcode.generation/qrextcodetextbuilder/addfnc1groupseparator/)() | विस्तारित कोडटेक्स्ट आइटम्स में ग्रुप सेपरेटर (GS - '\\u001D') जोड़ता है |
| [AddFNC1SecondPosition](../../aspose.barcode.generation/qrextcodetextbuilder/addfnc1secondposition/)(string) | दूसरे स्थान पर FNC1 सेट करता है। यदि पहले कोई अन्य FNC1 मोड सेट किया गया था, तो उसे बदल दिया जाता है। |
| [AddPlainCodetext](../../aspose.barcode.generation/extcodetextbuilder/addplaincodetext/)(string) | साधारण कोडटेक्स्ट को विस्तारित कोडटेक्स्ट आइटम्स में जोड़ता है |
| override [Clear](../../aspose.barcode.generation/qrextcodetextbuilder/clear/)() | विस्तारित कोडटेक्स्ट आइटम्स को साफ़ करता है |
| override [GetExtendedCodetext](../../aspose.barcode.generation/qrextcodetextbuilder/getextendedcodetext/)() | विस्तारित कोडटेक्स्ट सूची से विस्तारित कोडटेक्स्ट उत्पन्न करता है। |

## उदाहरण

यह नमूना दिखाता है कि विस्तारित मोड में FNC1 पहली स्थिति का उपयोग कैसे किया जाए।

```csharp
[C#]
//कोडटेक्स्ट बनाएं
QrExtCodetextBuilder TextBuilder = new QrExtCodetextBuilder();
TextBuilder.AddFNC1FirstPosition();
TextBuilder.AddPlainCodetext("000%89%%0");
TextBuilder.AddFNC1GroupSeparator();
TextBuilder.AddPlainCodetext("12345<FNC1>");

//कोडटेक्स्ट उत्पन्न करें
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

यह नमूना दिखाता है कि विस्तारित मोड में FNC1 दूसरी स्थिति का उपयोग कैसे किया जाए।

```csharp
[C#]
//कोडटेक्स्ट बनाएं
QrExtCodetextBuilder TextBuilder = new QrExtCodetextBuilder();
TextBuilder.AddFNC1SecondPosition("12");
TextBuilder.AddPlainCodetext("TRUE3456"); 

//कोडटेक्स्ट उत्पन्न करें
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

```csharp
[C#]
//कोडटेक्स्ट बनाएं
QrExtCodetextBuilder TextBuilder = new QrExtCodetextBuilder();
TextBuilder.AddECICodetext(ECIEncodings.Win1251, "Will");
TextBuilder.AddECICodetext(ECIEncodings.UTF8, "Right");
TextBuilder.AddECICodetext(ECIEncodings.UTF16BE, "Power");
TextBuilder.AddPlainCodetext(@"t\e\\st");
TextBuilder.AddCodetextWithCompactionMode(QrExtCompactionMode.AlphaNumeric, @"ASPOSE2001");
TextBuilder.AddCodetextWithCompactionMode(QrExtCompactionMode.Numeric, @"20012026");

//कोडटेक्स्ट उत्पन्न करें
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

### और देखें

* class [ExtCodetextBuilder](../extcodetextbuilder/)
* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


