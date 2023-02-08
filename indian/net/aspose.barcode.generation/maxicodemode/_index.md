---
title: MaxiCodeMode
second_title: Aspose.BarCode .NET API संदर्भ के लिए
description: मैक्सकड बरकड के लए एन्कडंग मड.
type: docs
weight: 1050
url: /hi/net/aspose.barcode.generation/maxicodemode/
---
## MaxiCodeMode enumeration

मैक्सीकोड बारकोड के लिए एन्कोडिंग मोड.

```csharp
public enum MaxiCodeMode
```

### मान

| नाम | कीमत | विवरण |
| --- | --- | --- |
| Mode2 | `2` | मोड 2 डाक सूचना को पहले संदेश में और डेटा को दूसरे संदेश में कूटबद्ध करता है। में 9 अंकों का डाक कोड है (केवल यूएसए में उपयोग किया जाता है)। |
| Mode3 | `3` | मोड 3 डाक सूचना को पहले संदेश में और डेटा को दूसरे संदेश में कूटबद्ध करता है। में 6 अल्फ़ान्यूमेरिक पोस्टल कोड हैं, जो दुनिया में उपयोग किए जाते हैं। |
| Mode4 | `4` | मोड 4 पहले और दूसरे संदेश में डेटा को संक्षिप्त ईसीसी सुधार के साथ एन्कोड करता है। |
| Mode5 | `5` | मोड 5 लंबे ईसीसी सुधार के साथ पहले और दूसरे संदेश में डेटा को एनकोड करता है। |
| Mode6 | `6` | मोड 6 पहले और दूसरे संदेश में डेटा को संक्षिप्त ईसीसी सुधार के साथ एन्कोड करता है। डिवाइस को एन्कोड करने के लिए उपयोग किया जाता है। |

### उदाहरण

यह नमूना दिखाता है कि कॉम्प्लेक्सबारकोड जेनरेटर का उपयोग करके मैक्सीकोड बारकोड कैसे उत्पन्न करें

```csharp
[C#]
// मोड 2 standart दूसरे संदेश के साथ
MaxiCodeCodetextMode2 maxiCodeCodetext = new MaxiCodeCodetextMode2();
maxiCodeCodetext.PostalCode = "524032140";
maxiCodeCodetext.CountryCode = 056;
maxiCodeCodetext.ServiceCategory = 999;
MaxiCodeStandartSecondMessage maxiCodeStandartSecondMessage = new MaxiCodeStandartSecondMessage();
maxiCodeStandartSecondMessage.Message = "Test message";
maxiCodeCodetext.SecondMessage = maxiCodeStandartSecondMessage;
using (ComplexBarcodeGenerator complexGenerator = new ComplexBarcodeGenerator(maxiCodeCodetext))
{
    complexGenerator.GenerateBarCodeImage();
}
// मोड 2 संरचित दूसरे संदेश के साथ
MaxiCodeCodetextMode2 maxiCodeCodetext = new MaxiCodeCodetextMode2();
maxiCodeCodetext.PostalCode = "524032140";
maxiCodeCodetext.CountryCode = 056;
maxiCodeCodetext.ServiceCategory = 999;
MaxiCodeStructuredSecondMessage maxiCodeStructuredSecondMessage = new MaxiCodeStructuredSecondMessage();
maxiCodeStructuredSecondMessage.Add("634 ALPHA DRIVE");
maxiCodeStructuredSecondMessage.Add("PITTSBURGH");
maxiCodeStructuredSecondMessage.Add("PA");
maxiCodeStructuredSecondMessage.Year = 99;
maxiCodeCodetext.SecondMessage = maxiCodeStructuredSecondMessage;
using (ComplexBarcodeGenerator complexGenerator = new ComplexBarcodeGenerator(maxiCodeCodetext))
{
    complexGenerator.GenerateBarCodeImage();
}
// मोड 3 standart दूसरे संदेश के साथ
MaxiCodeCodetextMode3 maxiCodeCodetext = new MaxiCodeCodetextMode3();
maxiCodeCodetext.PostalCode = "B1050";
maxiCodeCodetext.CountryCode = 056;
maxiCodeCodetext.ServiceCategory = 999;
MaxiCodeStandartSecondMessage maxiCodeStandartSecondMessage = new MaxiCodeStandartSecondMessage();
maxiCodeStandartSecondMessage.Message = "Test message";
maxiCodeCodetext.SecondMessage = maxiCodeStandartSecondMessage;
using (ComplexBarcodeGenerator complexGenerator = new ComplexBarcodeGenerator(maxiCodeCodetext))
{
    complexGenerator.GenerateBarCodeImage();
}
// मोड 3 संरचित दूसरे संदेश के साथ
MaxiCodeCodetextMode3 maxiCodeCodetext = new MaxiCodeCodetextMode3();
maxiCodeCodetext.PostalCode = "B1050";
maxiCodeCodetext.CountryCode = 056;
maxiCodeCodetext.ServiceCategory = 999;
MaxiCodeStructuredSecondMessage maxiCodeStructuredSecondMessage = new MaxiCodeStructuredSecondMessage();
maxiCodeStructuredSecondMessage.Add("634 ALPHA DRIVE");
maxiCodeStructuredSecondMessage.Add("PITTSBURGH");
maxiCodeStructuredSecondMessage.Add("PA");
maxiCodeStructuredSecondMessage.Year = 99;
maxiCodeCodetext.SecondMessage = maxiCodeStructuredSecondMessage;
using (ComplexBarcodeGenerator complexGenerator = new ComplexBarcodeGenerator(maxiCodeCodetext.GetConstructedCodetext())
{
    complexGenerator.GenerateBarCodeImage();
}
// मोड 4
MaxiCodeStandardCodetext maxiCodeCodetext = new MaxiCodeStandardCodetext();
maxiCodeCodetext.Mode = MaxiCodeMode.Mode4;
maxiCodeCodetext.Message = "Test message";
using (ComplexBarcodeGenerator complexGenerator = new ComplexBarcodeGenerator(maxiCodeCodetext.GetConstructedCodetext())
{
    complexGenerator.GenerateBarCodeImage();
}
// मोड 5
MaxiCodeStandardCodetext maxiCodeCodetext = new MaxiCodeStandardCodetext();
maxiCodeCodetext.Mode = MaxiCodeMode.Mode5;
maxiCodeCodetext.Message = "Test message";
using (ComplexBarcodeGenerator complexGenerator = new ComplexBarcodeGenerator(maxiCodeCodetext.GetConstructedCodetext())
{
    complexGenerator.GenerateBarCodeImage();
} 
// मोड 6
MaxiCodeStandardCodetext maxiCodeCodetext = new MaxiCodeStandardCodetext();
maxiCodeCodetext.Mode = MaxiCodeMode.Mode6;
maxiCodeCodetext.Message = "Test message";
using (ComplexBarcodeGenerator complexGenerator = new ComplexBarcodeGenerator(maxiCodeCodetext.GetConstructedCodetext())
{
    complexGenerator.GenerateBarCodeImage();
} 
```

### यह सभी देखें

* नाम स्थान [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* सभा [Aspose.BarCode](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->
