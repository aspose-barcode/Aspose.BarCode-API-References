---
title: "क्लास ComplexBarcodeGenerator"
second_title: "Aspose.BarCode for .NET API संदर्भ"
description: "Aspose.BarCode.ComplexBarcode.ComplexBarcodeGenerator क्लास। बैकएंड जटिल बारकोड के लिए ComplexBarcodeGenerator, उदाहरण के लिए SwissQR छवि निर्माण"
type: docs
weight: 510
url: /hi/net/aspose.barcode.complexbarcode/complexbarcodegenerator/
---
## ComplexBarcodeGenerator class

बैकएंड जटिल बारकोड (जैसे SwissQR) छवियों के जनरेशन के लिए ComplexBarcodeGenerator।

```csharp
public sealed class ComplexBarcodeGenerator : Component
```

## निर्माता

| नाम | विवरण |
| --- | --- |
| [ComplexBarcodeGenerator](complexbarcodegenerator/)(IComplexCodetext) | ComplexBarcodeGenerator का एक इंस्टेंस बनाता है। |

## गुण

| नाम | विवरण |
| --- | --- |
| [Parameters](../../aspose.barcode.complexbarcode/complexbarcodegenerator/parameters/) { get; } | जनरेशन पैरामीटर। |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [GenerateBarCodeImage](../../aspose.barcode.complexbarcode/complexbarcodegenerator/generatebarcodeimage/)() | वर्तमान सेटिंग्स के तहत जटिल बारकोड छवि उत्पन्न करता है। |
| [Save](../../aspose.barcode.complexbarcode/complexbarcodegenerator/save/#save_1)(string) | वर्तमान सेटिंग्स के तहत जटिल बारकोड छवि उत्पन्न करता है और सहेजता है। |
| [Save](../../aspose.barcode.complexbarcode/complexbarcodegenerator/save/#save)(Stream, BarCodeImageFormat) | वर्तमान सेटिंग्स के तहत जटिल बारकोड छवि उत्पन्न करता है और सहेजता है। |
| [Save](../../aspose.barcode.complexbarcode/complexbarcodegenerator/save/#save_2)(string, BarCodeImageFormat) | वर्तमान सेटिंग्स के तहत जटिल बारकोड छवि उत्पन्न करता है और सहेजता है। |

## उदाहरण

यह नमूना दर्शाता है कि SwissQR छवि कैसे बनाएं और सहेजें।

```csharp
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

### और देखें

* namespace [Aspose.BarCode.ComplexBarcode](../../aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](../../)


