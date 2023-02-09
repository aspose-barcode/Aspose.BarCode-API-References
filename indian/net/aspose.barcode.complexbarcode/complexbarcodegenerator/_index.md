---
title: ComplexBarcodeGenerator
second_title: Aspose.BarCode .NET API संदर्भ के लिए
description: कम्प्लेक्स बरकड जेनरेटर बैकएंड कम्प्लेक्स बरकड जैसे स्वसक्यूआर इमेज जेनरेशन के लए
type: docs
weight: 350
url: /hi/net/aspose.barcode.complexbarcode/complexbarcodegenerator/
---
## ComplexBarcodeGenerator class

कॉम्प्लेक्स बारकोड जेनरेटर बैकएंड कॉम्प्लेक्स बारकोड (जैसे स्विसक्यूआर) इमेज जेनरेशन के लिए।

```csharp
public sealed class ComplexBarcodeGenerator : Component
```

## कंस्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [ComplexBarcodeGenerator](complexbarcodegenerator/)(IComplexCodetext) | ComplexBarcodeGenerator. का उदाहरण बनाता है |

## गुण

| नाम | विवरण |
| --- | --- |
| [Parameters](../../aspose.barcode.complexbarcode/complexbarcodegenerator/parameters/) { get; } | जनरेशन पैरामीटर. |

## तरीकों

| नाम | विवरण |
| --- | --- |
| [GenerateBarCodeImage](../../aspose.barcode.complexbarcode/complexbarcodegenerator/generatebarcodeimage/)() | वर्तमान सेटिंग्स के तहत जटिल बारकोड छवि उत्पन्न करता है। |
| [Save](../../aspose.barcode.complexbarcode/complexbarcodegenerator/save/#save_1)(string) | वर्तमान सेटिंग्स के तहत जटिल बारकोड छवि बनाता है और सहेजता है। |
| [Save](../../aspose.barcode.complexbarcode/complexbarcodegenerator/save/#save)(Stream, BarCodeImageFormat) | वर्तमान सेटिंग्स के तहत जटिल बारकोड छवि बनाता है और सहेजता है। |
| [Save](../../aspose.barcode.complexbarcode/complexbarcodegenerator/save/#save_2)(string, BarCodeImageFormat) | वर्तमान सेटिंग्स के तहत जटिल बारकोड छवि बनाता है और सहेजता है। |

### उदाहरण

यह नमूना दिखाता है कि स्विसक्यूआर छवि कैसे बनाई और सहेजी जाती है।

```csharp
[C#]
  var swissQRCodetext = new SwissQRCodetext();
  swissQRCodetext.Bill.Account = "Account";
  swissQRCodetext.Bill.BillInformation = "BillInformation";
  // बाकी क्षेत्रों में प्रवेश करें
  using (var cg = new ComplexBarcodeGenerator(swissQRCodetext))
  {
    var res = cg.GenerateBarCodeImage();
  }
```

### यह सभी देखें

* नाम स्थान [Aspose.BarCode.ComplexBarcode](../../aspose.barcode.complexbarcode/)
* सभा [Aspose.BarCode](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->