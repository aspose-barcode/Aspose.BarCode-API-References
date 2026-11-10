---
title: "क्लास ComplexCodetextReader"
second_title: "Aspose.BarCode for .NET API संदर्भ"
description: "Aspose.BarCode.ComplexBarcode.ComplexCodetextReader क्लास। ComplexCodetextReader कोडटेक्स्ट को निर्दिष्ट जटिल बारकोड प्रकार में डिकोड करता है।"
type: docs
weight: 520
url: /hi/net/aspose.barcode.complexbarcode/complexcodetextreader/
---
## ComplexCodetextReader class

ComplexCodetextReader कोडटेक्स्ट को निर्दिष्ट जटिल बारकोड प्रकार में डिकोड करता है।

```csharp
public sealed class ComplexCodetextReader
```

## विधियाँ

| नाम | विवरण |
| --- | --- |
| static [TryDecodeGS1Codetext](../../aspose.barcode.complexbarcode/complexcodetextreader/trydecodegs1codetext/)(string) | GS1 कोडटेक्स्ट को डिकोड करता है। |
| static [TryDecodeGS1DigitalLink](../../aspose.barcode.complexbarcode/complexcodetextreader/trydecodegs1digitallink/)(string) | GS1 डिजिटल लिंक को डिकोड करता है। |
| static [TryDecodeHIBCLIC](../../aspose.barcode.complexbarcode/complexcodetextreader/trydecodehibclic/)(string) | HIBC LIC कोडटेक्स्ट को डिकोड करता है। |
| static [TryDecodeHIBCPAS](../../aspose.barcode.complexbarcode/complexcodetextreader/trydecodehibcpas/)(string) | HIBC PAS कोडटेक्स्ट को डिकोड करता है। |
| static [TryDecodeMailmark](../../aspose.barcode.complexbarcode/complexcodetextreader/trydecodemailmark/)(string) | Mailmark बारकोड C और L कोडटेक्स्ट को डिकोड करता है। |
| static [TryDecodeMailmark2D](../../aspose.barcode.complexbarcode/complexcodetextreader/trydecodemailmark2d/)(string) | Royal Mail Mailmark 2D कोडटेक्स्ट को डिकोड करता है। |
| static [TryDecodeMaxiCode](../../aspose.barcode.complexbarcode/complexcodetextreader/trydecodemaxicode/)(MaxiCodeMode, string) | MaxiCode कोडटेक्स्ट को डिकोड करता है। |
| static [TryDecodeSwissQR](../../aspose.barcode.complexbarcode/complexcodetextreader/trydecodeswissqr/)(string) | SwissQR कोडटेक्स्ट को डिकोड करता है। |
| static [TryDecodeUSADriveId](../../aspose.barcode.complexbarcode/complexcodetextreader/trydecodeusadriveid/)(string) | USADriveId कोडटेक्स्ट को डिकोड करता है। |

## उदाहरण

यह नमूना दिखाता है कि SwissQR छवि को कैसे पहचानें और डिकोड करें।

```csharp
[C#]
  using (var cr = new BarCodeReader("SwissQRCodetext.png", DecodeType.QR))
  {
    cr.Read();
    SwissQRCodetext result = ComplexCodetextReader.TryDecodeSwissQR(cr.GetCodeText());
  }
```

### और देखें

* namespace [Aspose.BarCode.ComplexBarcode](../../aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](../../)


