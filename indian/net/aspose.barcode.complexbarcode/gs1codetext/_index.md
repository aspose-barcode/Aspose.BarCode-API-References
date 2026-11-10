---
title: "क्लास GS1Codetext"
second_title: "Aspose.BarCode for .NET API संदर्भ"
description: "Aspose.BarCode.ComplexBarcode.GS1Codetext क्लास। एप्लिकेशन आइडेंटिफायर तत्वों के क्रमबद्ध अनुक्रम के रूप में एन्कोडिंग और डिकोडिंग के लिए GS1 कोडटेक्स्ट का प्रतिनिधित्व करता है। स्रोत क्रम और दोहराए गए एप्लिकेशन आइडेंटिफायर संरक्षित रहते हैं। कोष्ठकित प्रतिनिधित्व का रूप AIvalueAIvalue है। किसी मान के भीतर एक लिटरल ओपनिंग पैरेंथिसिस को लिखना चाहिए \\\\(; यह एकमात्र समर्थित एस्केप सीक्वेंस है। किसी मान के भीतर क्लोजिंग पैरेंथिसिस को एस्केप करने की आवश्यकता नहीं है।"
type: docs
weight: 530
url: /hi/net/aspose.barcode.complexbarcode/gs1codetext/
---
## GS1Codetext class

GS1 कोडटेक्स्ट को एन्कोडिंग और डिकोडिंग के लिए एप्लिकेशन आइडेंटिफ़ायर तत्वों की क्रमबद्ध श्रृंखला के रूप में दर्शाता है। स्रोत क्रम और दोहराए गए एप्लिकेशन आइडेंटिफ़ायर संरक्षित रहते हैं। कोष्ठकित प्रतिनिधित्व का रूप (AI)value(AI)value है। मान के भीतर एक लिटरल ओपनिंग कोष्ठक '(' को \\\\(; के रूप में लिखा जाना चाहिए; यह एकमात्र समर्थित एस्केप सीक्वेंस है। मान के भीतर क्लोज़िंग कोष्ठक ')' को एस्केप करने की आवश्यकता नहीं है।

```csharp
public sealed class GS1Codetext : IComplexCodetext
```

## निर्माता

| नाम | विवरण |
| --- | --- |
| [GS1Codetext](gs1codetext/)() | डिफ़ॉल्ट कन्स्ट्रक्टर। |

## गुण

| नाम | विवरण |
| --- | --- |
| [BarcodeType](../../aspose.barcode.complexbarcode/gs1codetext/barcodetype/) { get; set; } | इस GS1 कोडटेक्स्ट को एन्कोड करने के लिए उपयोग किए जाने वाले बारकोड प्रकार को प्राप्त करता है या सेट करता है। समर्थित प्रकार हैं GS1Aztec, GS1CodablockF, GS1Code128, GS1DataMatrix, GS1DotCode, GS1HanXin, GS1MicroPdf417, GS1QR और GS1 DataBar प्रकार। डिफ़ॉल्ट मान GS1Code128 है। |
| [Count](../../aspose.barcode.complexbarcode/gs1codetext/count/) { get; } | एप्लिकेशन आइडेंटिफायर तत्वों की संख्या प्राप्त करता है। |
| [Elements](../../aspose.barcode.complexbarcode/gs1codetext/elements/) { get; } | स्रोत क्रम में सभी तत्वों की एक प्रति प्राप्त करता है। |
| [Item](../../aspose.barcode.complexbarcode/gs1codetext/item/) { get; } | क्रमबद्ध अनुक्रम में उसकी स्थिति के अनुसार एक तत्व प्राप्त करता है। |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| static [Parse](../../aspose.barcode.complexbarcode/gs1codetext/parse/)(string) | एक कोष्ठकित GS1 तत्व स्ट्रिंग को (AI)value(AI)value रूप में पार्स करता है। किसी मान के भीतर लिटरल '(' को लिखना चाहिए \\(; अन्य कोई एस्केप सीक्वेंस समर्थित नहीं है, और ')' को एस्केप करने की आवश्यकता नहीं है। |
| [Add](../../aspose.barcode.complexbarcode/gs1codetext/add/)(string, string) | एक मान्यीकृत एप्लिकेशन आइडेंटिफायर तत्व जोड़ता है। |
| [GetAll](../../aspose.barcode.complexbarcode/gs1codetext/getall/)(string) | स्रोत क्रम में एक एप्लिकेशन आइडेंटिफायर के सभी मान प्राप्त करता है। |
| [GetBarcodeType](../../aspose.barcode.complexbarcode/gs1codetext/getbarcodetype/)() | इस GS1 कोडटेक्स्ट को एन्कोड करने के लिए उपयोग किए जाने वाले बारकोड प्रकार को प्राप्त करता है। |
| [GetConstructedCodetext](../../aspose.barcode.complexbarcode/gs1codetext/getconstructedcodetext/)() | ब्रैकेटेड GS1 कोडटेक्स्ट को (AI)value(AI)value के रूप में बनाता है। मानों में शाब्दिक खुली कोष्ठक को \\( के रूप में एस्केप किया जाता है। |
| [GetFirst](../../aspose.barcode.complexbarcode/gs1codetext/getfirst/)(string) | एक एप्लिकेशन आइडेंटिफायर के लिए पहला मान प्राप्त करता है। |
| [InitFromString](../../aspose.barcode.complexbarcode/gs1codetext/initfromstring/)(string) | इस इंस्टेंस को (AI)value(AI)value के रूप में ब्रैकेटेड GS1 कोडटेक्स्ट से प्रारंभ करता है। मौजूदा तत्व केवल तब प्रतिस्थापित होते हैं जब प्रदान किया गया कोडटेक्स्ट सफलतापूर्वक पार्स हो गया हो। |
| override [ToString](../../aspose.barcode.complexbarcode/gs1codetext/tostring/)() | ब्रैकेटेड GS1 प्रतिनिधित्व को (AI)value(AI)value के रूप में लौटाता है। |
| static [TryParse](../../aspose.barcode.complexbarcode/gs1codetext/tryparse/)(string, out GS1Codetext, out GS1ValidationResult) | ब्रैकेटेड GS1 तत्व स्ट्रिंग को (AI)value(AI)value के रूप में पार्स करने का प्रयास करता है और संरचित वैधता त्रुटियाँ लौटाता है। मान के भीतर शाब्दिक '(' को \\( के रूप में लिखा जाना चाहिए; कोई अन्य एस्केप सीक्वेंस समर्थित नहीं है, और ')' को एस्केप करने की आवश्यकता नहीं है। |
| static [Validate](../../aspose.barcode.complexbarcode/gs1codetext/validate/)(string) | ब्रैकेटेड GS1 तत्व स्ट्रिंग को (AI)value(AI)value के रूप में वैधता जांचता है बिना ऑब्जेक्ट बनाए। मान के भीतर शाब्दिक '(' को \\( के रूप में लिखा जाना चाहिए; कोई अन्य एस्केप सीक्वेंस समर्थित नहीं है, और ')' को एस्केप करने की आवश्यकता नहीं है। |

### और देखें

* interface [IComplexCodetext](../icomplexcodetext/)
* namespace [Aspose.BarCode.ComplexBarcode](../../aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](../../)


