---
title: "enum"
linktitle: "MaxiCodeMode"
second_title: "Aspose.BarCode C++ के लिए API संदर्भ"
description: "enum। C++ में MaxiCode बारकोड के लिए एन्कोडिंग मोड।"
type: docs
weight: 7600
url: /hi/cpp/aspose.barcode.generation/maxicodemode/
---
## MaxiCodeMode enum


MaxiCode बारकोड के लिए एन्कोडिंग मोड।

```cpp
enum class MaxiCodeMode
```

### मान

| नाम | मान | विवरण |
| --- | --- | --- |
| Mode2 | 2 | Mode 2 पहले संदेश में डाक जानकारी और दूसरे संदेश में डेटा एन्कोड करता है। इसमें 9 अंकों का पोस्टल कोड होता है (केवल USA में उपयोग किया जाता है)। |
| Mode3 | 3 | Mode 3 पहले संदेश में डाक जानकारी और दूसरे संदेश में डेटा एन्कोड करता है। इसमें 6 अल्फ़ान्यूमेरिक पोस्टल कोड होता है, जो विश्व में उपयोग किया जाता है। |
| Mode4 | 4 | Mode 4 पहले और दूसरे संदेश में डेटा एन्कोड करता है, जिसमें छोटा ECC सुधार होता है। |
| Mode5 | 5 | Mode 5 पहले और दूसरे संदेश में डेटा एन्कोड करता है, जिसमें लंबा ECC सुधार होता है। |
| Mode6 | 6 | Mode 6 पहले और दूसरे संदेश में डेटा एन्कोड करता है, जिसमें छोटा ECC सुधार होता है। डिवाइस को एन्कोड करने के लिए उपयोग किया जाता है। |

## टिप्पणियाँ


यह उदाहरण दिखाता है कि ComplexBarcodeGenerator का उपयोग करके MaxiCode बारकोड कैसे उत्पन्न करें।
```cpp
[C#]
//मोड 2 के साथ मानक दूसरा संदेश
MaxiCodeCodetextMode2 maxiCodeCodetext = new MaxiCodeCodetextMode2();
maxiCodeCodetext.PostalCode = "524032140";
maxiCodeCodetext.CountryCode = 056;
maxiCodeCodetext.ServiceCategory = 999;
MaxiCodeStandardSecondMessage maxiCodeStandardSecondMessage = new MaxiCodeStandardSecondMessage();
maxiCodeStandardSecondMessage.Message = "Test message";
maxiCodeCodetext.SecondMessage = maxiCodeStandardSecondMessage;
using (ComplexBarcodeGenerator complexGenerator = new ComplexBarcodeGenerator(maxiCodeCodetext))
{
    complexGenerator.GenerateBarCodeImage();
}
//मोड 2 के साथ संरचित दूसरा संदेश
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
//मोड 3 मानक दूसरे संदेश के साथ
MaxiCodeCodetextMode3 maxiCodeCodetext = new MaxiCodeCodetextMode3();
maxiCodeCodetext.PostalCode = "B1050";
maxiCodeCodetext.CountryCode = 056;
maxiCodeCodetext.ServiceCategory = 999;
MaxiCodeStandardSecondMessage maxiCodeStandardSecondMessage = new MaxiCodeStandardSecondMessage();
maxiCodeStandardSecondMessage.Message = "Test message";
maxiCodeCodetext.SecondMessage = maxiCodeStandardSecondMessage;
using (ComplexBarcodeGenerator complexGenerator = new ComplexBarcodeGenerator(maxiCodeCodetext))
{
    complexGenerator.GenerateBarCodeImage();
}
//मोड 3 संरचित दूसरे संदेश के साथ
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
//Mode 4
MaxiCodeStandardCodetext maxiCodeCodetext = new MaxiCodeStandardCodetext();
maxiCodeCodetext.Mode = MaxiCodeMode.Mode4;
maxiCodeCodetext.Message = "Test message";
using (ComplexBarcodeGenerator complexGenerator = new ComplexBarcodeGenerator(maxiCodeCodetext.GetConstructedCodetext())
{
    complexGenerator.GenerateBarCodeImage();
}
//Mode 5
MaxiCodeStandardCodetext maxiCodeCodetext = new MaxiCodeStandardCodetext();
maxiCodeCodetext.Mode = MaxiCodeMode.Mode5;
maxiCodeCodetext.Message = "Test message";
using (ComplexBarcodeGenerator complexGenerator = new ComplexBarcodeGenerator(maxiCodeCodetext.GetConstructedCodetext())
{
    complexGenerator.GenerateBarCodeImage();
}
//मोड 6
MaxiCodeStandardCodetext maxiCodeCodetext = new MaxiCodeStandardCodetext();
maxiCodeCodetext.Mode = MaxiCodeMode.Mode6;
maxiCodeCodetext.Message = "Test message";
using (ComplexBarcodeGenerator complexGenerator = new ComplexBarcodeGenerator(maxiCodeCodetext.GetConstructedCodetext())
{
    complexGenerator.GenerateBarCodeImage();
}
```

## और देखें

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
