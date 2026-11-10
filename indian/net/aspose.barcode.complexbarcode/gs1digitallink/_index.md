---
title: "क्लास GS1DigitalLink"
second_title: "Aspose.BarCode for .NET API संदर्भ"
description: "Aspose.BarCode.ComplexBarcode.GS1DigitalLink क्लास। एन्कोडिंग और डिकोडिंग के लिए GS1 Digital Link कोडटेक्स्ट का प्रतिनिधित्व करता है, जो एप्लिकेशन आइडेंटिफ़ायर तत्वों की क्रमबद्ध श्रृंखला के रूप में होता है। स्रोत क्रम और दोहराए गए एप्लिकेशन आइडेंटिफ़ायर संरक्षित रहते हैं। निर्मित कोडटेक्स्ट एक अनकम्प्रेस्ड GS1 Digital Link URI है। पार्सिंग के दौरान NonGS1 क्वेरी पैरामीटर और URI फ्रैगमेंट को नजरअंदाज किया जाता है।"
type: docs
weight: 540
url: /hi/net/aspose.barcode.complexbarcode/gs1digitallink/
---
## GS1DigitalLink class

GS1 डिजिटल लिंक कोडटेक्स्ट को एन्कोडिंग और डिकोडिंग के लिए एप्लिकेशन आइडेंटिफ़ायर तत्वों की क्रमबद्ध श्रृंखला के रूप में दर्शाता है। स्रोत क्रम और दोहराए गए एप्लिकेशन आइडेंटिफ़ायर संरक्षित रहते हैं। निर्मित कोडटेक्स्ट एक अनकंप्रेस्ड GS1 डिजिटल लिंक URI है। पार्सिंग के समय गैर-GS1 क्वेरी पैरामीटर और URI फ्रैगमेंट को नजरअंदाज़ किया जाता है।

```csharp
public sealed class GS1DigitalLink : IComplexCodetext
```

## निर्माता

| नाम | विवरण |
| --- | --- |
| [GS1DigitalLink](gs1digitallink/#constructor)(string) | निर्दिष्ट URI स्टेम के साथ एक खाली GS1 Digital Link को प्रारंभ करता है। जब ठीक एक प्राइमरी-की उम्मीदवार मौजूद हो तो प्राइमरी की स्वचालित रूप से चयनित की जाती है। |
| [GS1DigitalLink](gs1digitallink/#constructor_1)(string, string) | निर्दिष्ट URI स्टेम और प्राइमरी की के साथ एक खाली GS1 Digital Link को प्रारंभ करता है। |

## गुण

| नाम | विवरण |
| --- | --- |
| [BarcodeType](../../aspose.barcode.complexbarcode/gs1digitallink/barcodetype/) { get; set; } | इस GS1 Digital Link को एन्कोड करने के लिए उपयोग किए जाने वाले बारकोड प्रकार को प्राप्त करता है या सेट करता है। समर्थित प्रकार हैं QR, DataMatrix, Aztec, Pdf417, MicroPdf417, DotCode, HanXin, CodablockF और Code128। डिफ़ॉल्ट मान QR है। |
| [Count](../../aspose.barcode.complexbarcode/gs1digitallink/count/) { get; } | एप्लिकेशन आइडेंटिफायर तत्वों की संख्या प्राप्त करता है। |
| [Elements](../../aspose.barcode.complexbarcode/gs1digitallink/elements/) { get; } | स्रोत क्रम में सभी तत्वों की एक प्रति प्राप्त करता है। |
| [Item](../../aspose.barcode.complexbarcode/gs1digitallink/item/) { get; } | क्रमबद्ध अनुक्रम में उसकी स्थिति के अनुसार एक तत्व प्राप्त करता है। |
| [PrimaryApplicationIdentifier](../../aspose.barcode.complexbarcode/gs1digitallink/primaryapplicationidentifier/) { get; } | डिजिटल लिंक प्राथमिक कुंजी के रूप में उपयोग किए जाने वाले एप्लिकेशन आइडेंटिफायर को प्राप्त करता है। Null का अर्थ है कि URI निर्मित होने पर प्राथमिक कुंजी स्वचालित रूप से चयनित की जाती है। |
| [UriStem](../../aspose.barcode.complexbarcode/gs1digitallink/uristem/) { get; } | GS1 प्राथमिक कुंजी पाथ खंड से पहले पूर्ण URI उपसर्ग प्राप्त करता है। इस स्टेम में कोई क्वेरी स्ट्रिंग या फ्रैगमेंट नहीं होता। |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| static [Create](../../aspose.barcode.complexbarcode/gs1digitallink/create/#create)(string, GS1Codetext) | GS1 कोडटेक्स्ट से सभी तत्वों को कॉपी करके और उपलब्ध एकमात्र प्राथमिक कुंजी का चयन करके एक GS1 Digital Link बनाता है। |
| static [Create](../../aspose.barcode.complexbarcode/gs1digitallink/create/#create_1)(string, GS1Codetext, string) | GS1 कोडटेक्स्ट से सभी तत्वों को कॉपी करके और निर्दिष्ट प्राथमिक कुंजी का उपयोग करके एक GS1 Digital Link बनाता है। |
| static [Parse](../../aspose.barcode.complexbarcode/gs1digitallink/parse/)(string) | एक अनकम्प्रेस्ड GS1 Digital Link URI को पार्स करता है। |
| [Add](../../aspose.barcode.complexbarcode/gs1digitallink/add/)(string, string) | एक मान्यीकृत एप्लिकेशन आइडेंटिफायर तत्व जोड़ता है। |
| [GetAll](../../aspose.barcode.complexbarcode/gs1digitallink/getall/)(string) | स्रोत क्रम में एक एप्लिकेशन आइडेंटिफायर के सभी मान प्राप्त करता है। |
| [GetBarcodeType](../../aspose.barcode.complexbarcode/gs1digitallink/getbarcodetype/)() | इस GS1 Digital Link को एन्कोड करने के लिए उपयोग किए जाने वाले बारकोड प्रकार को प्राप्त करता है। |
| [GetConstructedCodetext](../../aspose.barcode.complexbarcode/gs1digitallink/getconstructedcodetext/)() | अनकम्प्रेस्ड GS1 Digital Link URI का निर्माण करता है। |
| [GetFirst](../../aspose.barcode.complexbarcode/gs1digitallink/getfirst/)(string) | एक एप्लिकेशन आइडेंटिफायर के लिए पहला मान प्राप्त करता है। |
| [InitFromString](../../aspose.barcode.complexbarcode/gs1digitallink/initfromstring/)(string) | इस इंस्टेंस को एक अनकम्प्रेस्ड GS1 Digital Link URI से प्रारंभ करता है। प्रदान किए गए URI को सफलतापूर्वक पार्स करने के बाद ही मौजूदा स्थिति को बदल दिया जाता है। चयनित बारकोड प्रकार संरक्षित रहता है। |
| [ToGS1Codetext](../../aspose.barcode.complexbarcode/gs1digitallink/togs1codetext/)() | वर्तमान GS1 तत्वों को शामिल करने वाला एक स्वतंत्र GS1 कोडटेक्स्ट बनाता है। केवल URI की जानकारी शामिल नहीं की जाती। |
| override [ToString](../../aspose.barcode.complexbarcode/gs1digitallink/tostring/)() | अनकम्प्रेस्ड GS1 Digital Link URI लौटाता है। |
| [ToUriString](../../aspose.barcode.complexbarcode/gs1digitallink/touristring/)() | वर्तमान ऑब्जेक्ट की स्थिति को एक अनकम्प्रेस्ड GS1 Digital Link URI के रूप में फ़ॉर्मेट करता है। |
| static [TryParse](../../aspose.barcode.complexbarcode/gs1digitallink/tryparse/)(string, out GS1DigitalLink, out GS1ValidationResult) | एक अनकम्प्रेस्ड GS1 Digital Link URI को पार्स करने का प्रयास करता है और संरचित वैधता त्रुटियों को लौटाता है। |
| static [Validate](../../aspose.barcode.complexbarcode/gs1digitallink/validate/)(string) | ऑब्जेक्ट बनाए बिना एक अनकम्प्रेस्ड GS1 Digital Link URI को वैध करता है। |

### और देखें

* interface [IComplexCodetext](../icomplexcodetext/)
* namespace [Aspose.BarCode.ComplexBarcode](../../aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](../../)


