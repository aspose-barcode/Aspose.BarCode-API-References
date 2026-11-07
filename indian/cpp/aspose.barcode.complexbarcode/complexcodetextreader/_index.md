---
title: "Aspose::BarCode::ComplexBarcode::ComplexCodetextReader class"
linktitle: "ComplexCodetextReader"
second_title: "Aspose.BarCode C++ के लिए API संदर्भ"
description: "Aspose::BarCode::ComplexBarcode::ComplexCodetextReader class. ComplexCodetextReader निर्दिष्ट जटिल बारकोड प्रकार में कोडटेक्स्ट को C++ में डिकोड करता है।"
type: docs
weight: 400
url: /hi/cpp/aspose.barcode.complexbarcode/complexcodetextreader/
---
## ComplexCodetextReader class


[ComplexCodetextReader](./) decodes codetext to specified complex barcode type.

```cpp
class ComplexCodetextReader : public System::Object
```

## विधियाँ

| विधि | विवरण |
| --- | --- |
| static [TryDecodeGS1Codetext](./trydecodegs1codetext/)(System::String) | GS1 कोडटेक्स्ट को डिकोड करता है। |
| static [TryDecodeGS1DigitalLink](./trydecodegs1digitallink/)(System::String) | GS1 डिजिटल लिंक को डिकोड करता है। |
| static [TryDecodeHIBCLIC](./trydecodehibclic/)(System::String) | HIBC LIC कोडटेक्स्ट को डिकोड करता है। |
| static [TryDecodeHIBCPAS](./trydecodehibcpas/)(System::String) | HIBC PAS कोडटेक्स्ट को डिकोड करता है। |
| static [TryDecodeMailmark](./trydecodemailmark/)(System::String) | Mailmark बारकोड C और L कोडटेक्स्ट को डिकोड करता है। |
| static [TryDecodeMailmark2D](./trydecodemailmark2d/)(System::String) | Royal Mail Mailmark 2D कोडटेक्स्ट को डिकोड करता है। |
| static [TryDecodeMaxiCode](./trydecodemaxicode/)(Generation::MaxiCodeMode, System::String) | MaxiCode कोडटेक्स्ट को डिकोड करता है। |
| static [TryDecodeSwissQR](./trydecodeswissqr/)(System::String) | SwissQR कोडटेक्स्ट को डिकोड करता है। |
| static [TryDecodeUSADriveId](./trydecodeusadriveid/)(System::String) | USADriveId कोडटेक्स्ट को डिकोड करता है। |
## टिप्पणियाँ


यह नमूना दिखाता है कि SwissQR छवि को कैसे पहचानें और डिकोड करें।
```cpp
[C#]
  using (var cr = new BarCodeReader("SwissQRCodetext.png", DecodeType.QR))
  {
    cr.Read();
    SwissQRCodetext result = ComplexCodetextReader.TryDecodeSwissQR(cr.GetCodeText());
  }
```

## और देखें

* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
