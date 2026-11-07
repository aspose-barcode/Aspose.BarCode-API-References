---
title: "Aspose::BarCode::ComplexBarcode::ComplexBarcodeGenerator क्लास"
linktitle: "ComplexBarcodeGenerator"
second_title: "Aspose.BarCode C++ के लिए API संदर्भ"
description: "Aspose::BarCode::ComplexBarcode::ComplexBarcodeGenerator क्लास. C++ में बैकएंड जटिल बारकोड (जैसे SwissQR) छवियों के निर्माण के लिए ComplexBarcodeGenerator।"
type: docs
weight: 300
url: /hi/cpp/aspose.barcode.complexbarcode/complexbarcodegenerator/
---
## ComplexBarcodeGenerator class


[ComplexBarcodeGenerator](./) for backend complex barcode (e.g. SwissQR) images generation.

```cpp
class ComplexBarcodeGenerator : public System::IDisposable
```

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [ComplexBarcodeGenerator](./complexbarcodegenerator/)(System::SharedPtr\<IComplexCodetext\>) | एक [ComplexBarcodeGenerator](./) का इंस्टेंस बनाता है। |
| [Dispose](./dispose/)() override | उपयोग में मौजूद किसी भी संसाधन को साफ़ करें। |
| [GenerateBarCodeImage](./generatebarcodeimage/)() | वर्तमान सेटिंग्स के तहत जटिल बारकोड छवि उत्पन्न करता है। |
| [get_Parameters](./get_parameters/)() | [Generation](../../aspose.barcode.generation/) पैरामीटर। |
| [Save](./save/)(System::SharedPtr\<System::IO::Stream\>, Generation::BarCodeImageFormat) | वर्तमान सेटिंग्स के तहत जटिल बारकोड छवि उत्पन्न और सहेजता है। |
| [Save](./save/)(System::String, Generation::BarCodeImageFormat) | वर्तमान सेटिंग्स के तहत जटिल बारकोड छवि उत्पन्न और सहेजता है। |
| [Save](./save/)(System::String) | वर्तमान सेटिंग्स के तहत जटिल बारकोड छवि उत्पन्न और सहेजता है। |
## टिप्पणियाँ


यह उदाहरण दिखाता है कि SwissQR छवि कैसे बनाएं और सहेजें।
```cpp
[C#]
  var swissQRCodetext = new SwissQRCodetext();
  swissQRCodetext.Bill.Account = "Account";
  swissQRCodetext.Bill.BillInformation = "BillInformation";
  // बाकी फ़ील्ड्स को प्रारंभ करें
  using (var cg = new ComplexBarcodeGenerator(swissQRCodetext))
  {
    var res = cg.GenerateBarCodeImage();
  }
```

## और देखें

* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
