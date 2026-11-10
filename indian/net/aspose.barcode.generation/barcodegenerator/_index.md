---
title: "क्लास BarcodeGenerator"
second_title: "Aspose.BarCode for .NET API संदर्भ"
description: "Aspose.BarCode.Generation.BarcodeGenerator क्लास। बैकएंड बारकोड छवियों के निर्माण के लिए BarcodeGenerator"
type: docs
weight: 1000
url: /hi/net/aspose.barcode.generation/barcodegenerator/
---
## BarcodeGenerator class

बैकएंड बारकोड इमेज जनरेशन के लिए BarcodeGenerator।

समर्थित प्रतीकात्मकताएँ: 1D: Codabar, Code11, Code128, Code39, Code39FullASCII Code93, EAN13, EAN8, Interleaved2of5, MSI, Standard2of5, UPCA, UPCE, ISBN, GS1Code128, Postnet, Planet EAN14, SCC14, SSCC18, ITF14, SingaporePost ... 2D: Aztec, DataMatrix, PDf417, QR code ...

```csharp
public sealed class BarcodeGenerator : Component
```

## निर्माता

| नाम | विवरण |
| --- | --- |
| [BarcodeGenerator](barcodegenerator/#constructor)(BaseEncodeType) | BarcodeGenerator का एक उदाहरण बनाता है। |
| [BarcodeGenerator](barcodegenerator/#constructor_1)(BaseEncodeType, string) | BarcodeGenerator का एक उदाहरण बनाता है। |

## गुण

| नाम | विवरण |
| --- | --- |
| [BarcodeType](../../aspose.barcode.generation/barcodegenerator/barcodetype/) { get; set; } | बारकोड प्रतीकात्मकता प्रकार। |
| [CodeText](../../aspose.barcode.generation/barcodegenerator/codetext/) { get; set; } | एन्कोड करने के लिए पाठ। |
| [Parameters](../../aspose.barcode.generation/barcodegenerator/parameters/) { get; } | जनरेशन पैरामीटर। |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| static [ImportFromXml](../../aspose.barcode.generation/barcodegenerator/importfromxml/#importfromxml)(Stream) | निर्दिष्ट xml-stream से BarCode गुण आयात करता है और BarcodeGenerator का उदाहरण बनाता है। |
| static [ImportFromXml](../../aspose.barcode.generation/barcodegenerator/importfromxml/#importfromxml_1)(string) | निर्दिष्ट xml-file से BarCode गुण आयात करता है और BarcodeGenerator का उदाहरण बनाता है। |
| [DrawWpf](../../aspose.barcode.generation/barcodegenerator/drawwpf/)(DrawingContext) | WPF कैनवास पर बारकोड छवि बनाता है। |
| [ExportToXml](../../aspose.barcode.generation/barcodegenerator/exporttoxml/#exporttoxml)(Stream) | निर्दिष्ट xml-stream में BarCode प्रॉपर्टीज़ एक्सपोर्ट करता है |
| [ExportToXml](../../aspose.barcode.generation/barcodegenerator/exporttoxml/#exporttoxml_1)(string) | निर्दिष्ट xml-file में BarCode प्रॉपर्टीज़ एक्सपोर्ट करता है |
| [GenerateBarCodeImage](../../aspose.barcode.generation/barcodegenerator/generatebarcodeimage/)() | वर्तमान सेटिंग्स के तहत बारकोड छवि उत्पन्न करें। |
| [Save](../../aspose.barcode.generation/barcodegenerator/save/#save_1)(string) | बारकोड छवि को निर्दिष्ट फ़ाइल में सहेजें। |
| [Save](../../aspose.barcode.generation/barcodegenerator/save/#save)(Stream, BarCodeImageFormat) | बारकोड छवि को निर्दिष्ट प्रारूप में स्ट्रीम पर सहेजें। |
| [Save](../../aspose.barcode.generation/barcodegenerator/save/#save_2)(string, BarCodeImageFormat) | बारकोड छवि को निर्दिष्ट फ़ाइल में निर्दिष्ट प्रारूप में सहेजें। |
| [SetCodeText](../../aspose.barcode.generation/barcodegenerator/setcodetext/#setcodetext)(byte[]) | codetext को बाइट अनुक्रम के रूप में सेट करें। |
| [SetCodeText](../../aspose.barcode.generation/barcodegenerator/setcodetext/#setcodetext_1)(string, Encoding) | निर्दिष्ट **encoding** का उपयोग करके Unicode **codeText** को बाइट अनुक्रम में एन्कोड करता है। UTF-8 सबसे अधिक उपयोग किया जाने वाला एन्कोडिंग है। यदि एन्कोडिंग इसे समर्थन करता है, तो फ़ंक्शन स्वचालित रूप से एक [byte order mark (BOM)](https://en.wikipedia.org/wiki/Byte_order_mark#Byte-order_marks_by_encoding) सम्मिलित करता है। |
| [SetCodeText](../../aspose.barcode.generation/barcodegenerator/setcodetext/#setcodetext_2)(string, Encoding, bool) | निर्दिष्ट **encoding** का उपयोग करके Unicode **codeText** को बाइट अनुक्रम में एन्कोड करता है। UTF-8 सबसे अधिक उपयोग किया जाने वाला एन्कोडिंग है। यदि एन्कोडिंग इसे समर्थन करता है और **insertBOM** `true` पर सेट है, तो फ़ंक्शन एक [byte order mark (BOM)](https://en.wikipedia.org/wiki/Byte_order_mark#Byte-order_marks_by_encoding) शामिल करता है। |

## उदाहरण

यह उदाहरण दिखाता है कि बारकोड छवि कैसे बनाएं और सहेजें।

```csharp
[C#]
  using(var generator = new BarcodeGenerator(EncodeTypes.Code128))
  {
      generator.CodeText = "123ABC";
      generator.Save("code128.png");
  }
```

### और देखें

* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


