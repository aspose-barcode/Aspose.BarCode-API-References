---
title: BarcodeGenerator
second_title: Aspose.BarCode .NET API संदर्भ के लिए
description: बैकएंड बरकड इमेज जेनरेशन के लए बरकड जेनरेटर
type: docs
weight: 700
url: /hi/net/aspose.barcode.generation/barcodegenerator/
---
## BarcodeGenerator class

बैकएंड बारकोड इमेज जेनरेशन के लिए बारकोड जेनरेटर।

supported symbologies: 1D: Codabar, Code11, Code128, Code39Standard, Code39Extended Code93Standard, Code93Extended, EAN13, EAN8, Interleaved2of5, MSI, Standard2of5, UPCA, UPCE, ISBN, GS1Code128, Postnet, Planet EAN14, SCC14, SSCC18, ITF14 , SingaporePost ... 2D: Aztec, DataMatrix, PDf417, QR कोड ...

```csharp
public sealed class BarcodeGenerator : Component
```

## कंस्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [BarcodeGenerator](barcodegenerator/#constructor)(BaseEncodeType) | बारकोडजेनरेटर का एक उदाहरण बनाता है। |
| [BarcodeGenerator](barcodegenerator/#constructor_1)(BaseEncodeType, string) | बारकोडजेनरेटर का एक उदाहरण बनाता है। |

## गुण

| नाम | विवरण |
| --- | --- |
| [BarcodeType](../../aspose.barcode.generation/barcodegenerator/barcodetype/) { get; set; } | बारकोड सहजीवन प्रकार. |
| [CodeText](../../aspose.barcode.generation/barcodegenerator/codetext/) { get; set; } | एन्कोड किया जाने वाला टेक्स्ट. |
| [Parameters](../../aspose.barcode.generation/barcodegenerator/parameters/) { get; } | जनरेशन पैरामीटर. |

## तरीकों

| नाम | विवरण |
| --- | --- |
| static [ImportFromXml](../../aspose.barcode.generation/barcodegenerator/importfromxml/#importfromxml)(Stream) | निर्दिष्ट एक्सएमएल-स्ट्रीम से बारकोड गुण आयात करता है और बारकोड जेनरेटर उदाहरण बनाता है। |
| static [ImportFromXml](../../aspose.barcode.generation/barcodegenerator/importfromxml/#importfromxml_1)(string) | निर्दिष्ट एक्सएमएल-फाइल से बारकोड गुण आयात करता है और बारकोड जेनरेटर उदाहरण बनाता है। |
| [DrawWpf](../../aspose.barcode.generation/barcodegenerator/drawwpf/)(DrawingContext) | WPF कैनवास पर बारकोड छवि बनाता है। |
| [ExportToXml](../../aspose.barcode.generation/barcodegenerator/exporttoxml/#exporttoxml)(Stream) | बारकोड गुणों को एक्सएमएल-स्ट्रीम निर्दिष्ट में निर्यात करता है |
| [ExportToXml](../../aspose.barcode.generation/barcodegenerator/exporttoxml/#exporttoxml_1)(string) | बारकोड गुणों को xml-फ़ाइल निर्दिष्ट में निर्यात करता है |
| [GenerateBarCodeImage](../../aspose.barcode.generation/barcodegenerator/generatebarcodeimage/)() | वर्तमान सेटिंग्स के तहत बारकोड छवि उत्पन्न करें। |
| [Save](../../aspose.barcode.generation/barcodegenerator/save/#save_1)(string) | विशिष्ट फ़ाइल में बारकोड छवि सहेजें. |
| [Save](../../aspose.barcode.generation/barcodegenerator/save/#save)(Stream, BarCodeImageFormat) | विशिष्ट प्रारूप में स्ट्रीम करने के लिए बारकोड छवि सहेजें. |
| [Save](../../aspose.barcode.generation/barcodegenerator/save/#save_2)(string, BarCodeImageFormat) | विशिष्ट प्रारूप में बारकोड छवि को विशिष्ट फ़ाइल में सहेजें। |

### उदाहरण

यह नमूना बारकोड छवि बनाने और सहेजने का तरीका दिखाता है।

```csharp
[C#]
  using(var generator = new BarcodeGenerator(EncodeTypes.Code128))
  {
      generator.CodeText = "123ABC";
      generator.Save("code128.png");
  }
```

### यह सभी देखें

* नाम स्थान [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* सभा [Aspose.BarCode](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->