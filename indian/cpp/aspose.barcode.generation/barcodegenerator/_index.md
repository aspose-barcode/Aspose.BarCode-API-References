---
title: "Aspose::BarCode::Generation::BarcodeGenerator क्लास"
linktitle: "BarcodeGenerator"
second_title: "Aspose.BarCode C++ के लिए API संदर्भ"
description: "Aspose::BarCode::Generation::BarcodeGenerator क्लास। C++ में बैकएंड बारकोड छवियों के जनरेशन के लिए BarcodeGenerator।"
type: docs
weight: 400
url: /hi/cpp/aspose.barcode.generation/barcodegenerator/
---
## BarcodeGenerator class


[BarcodeGenerator](./) for backend barcode images generation.

```cpp
class BarcodeGenerator : public System::IDisposable
```

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [BarcodeGenerator](./barcodegenerator/)(System::SharedPtr\<BaseEncodeType\>) | एक उदाहरण बनाता है [BarcodeGenerator](./). |
| [BarcodeGenerator](./barcodegenerator/)(System::SharedPtr\<BaseEncodeType\>, System::String) | एक उदाहरण बनाता है [BarcodeGenerator](./). |
| [Dispose](./dispose/)() override | उपयोग में मौजूद किसी भी संसाधन को साफ़ करें। |
| [ExportToXml](./exporttoxml/)(System::String) | [BarCode](../../aspose.barcode/) गुणों को निर्दिष्ट XML फ़ाइल में निर्यात करता है |
| [ExportToXml](./exporttoxml/)(System::SharedPtr\<System::IO::Stream\>) | [BarCode](../../aspose.barcode/) गुणों को निर्दिष्ट XML स्ट्रीम में निर्यात करता है |
| [GenerateBarCodeImage](./generatebarcodeimage/)() | वर्तमान सेटिंग्स के तहत बारकोड छवि उत्पन्न करें। |
| [get_BarcodeType](./get_barcodetype/)() | बारकोड प्रतीक प्रकार। |
| [get_CodeText](./get_codetext/)() | एन्कोड करने के लिए पाठ। |
| [get_Parameters](./get_parameters/)() const | [Generation](../) पैरामीटर। |
| static [ImportFromXml](./importfromxml/)(System::String) | निर्दिष्ट xml-फ़ाइल से [BarCode](../../aspose.barcode/) गुण आयात करता है और [BarcodeGenerator](./) उदाहरण बनाता है। |
| static [ImportFromXml](./importfromxml/)(System::SharedPtr\<System::IO::Stream\>) | निर्दिष्ट xml-स्ट्रीम से [BarCode](../../aspose.barcode/) गुण आयात करता है और [BarcodeGenerator](./) उदाहरण बनाता है। |
| [Save](./save/)(System::SharedPtr\<System::IO::Stream\>, BarCodeImageFormat) | बारकोड छवि को विशिष्ट प्रारूप में स्ट्रीम पर सहेजें। |
| [Save](./save/)(System::String, BarCodeImageFormat) | बारकोड छवि को विशिष्ट फ़ाइल में विशिष्ट प्रारूप में सहेजें। |
| [Save](./save/)(System::String) | बारकोड छवि को विशिष्ट फ़ाइल में सहेजें। |
| [set_BarcodeType](./set_barcodetype/)(System::SharedPtr\<BaseEncodeType\>) | बारकोड प्रतीक प्रकार। |
| [set_CodeText](./set_codetext/)(System::String) | एन्कोड करने के लिए पाठ। |
| [SetCodeText](./setcodetext/)(System::ArrayPtr\<uint8_t\>) | कोडटेक्स्ट को बाइट्स की श्रृंखला के रूप में सेट करें। |
| [SetCodeText](./setcodetext/)(System::String, System::SharedPtr\<System::Text::Encoding\>) |  |
| [SetCodeText](./setcodetext/)(System::String, System::SharedPtr\<System::Text::Encoding\>, bool) |  |
## टिप्पणियाँ


समर्थित प्रतीक: 1D: Codabar, Code11, Code128, Code39, Code39FullASCII Code93, EAN13, EAN8, Interleaved2of5, MSI, Standard2of5, UPCA, UPCE, ISBN, GS1Code128, Postnet, Planet EAN14, SCC14, SSCC18, ITF14, SingaporePost ... 2D: Aztec, DataMatrix, PDf417, QR code ...

यह नमूना दिखाता है कि बारकोड छवि कैसे बनाएं और सहेजें।
```cpp
[C#]
      using(var generator = new BarcodeGenerator(EncodeTypes.Code128))
      {
      generator.CodeText = "123ABC";
      generator.Save("code128.png");
  }
```

## और देखें

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
