---
title: "Aspose::BarCode::ComplexBarcode::ComplexCodetextReader class"
linktitle: "ComplexCodetextReader"
second_title: "Aspose.BarCode for C++ API-referentie"
description: "Aspose::BarCode::ComplexBarcode::ComplexCodetextReader class. ComplexCodetextReader decodeert codetext naar het opgegeven complexe barcode-type in C++."
type: docs
weight: 400
url: /nl/cpp/aspose.barcode.complexbarcode/complexcodetextreader/
---
## ComplexCodetextReader class


[ComplexCodetextReader](./) decodes codetext to specified complex barcode type.

```cpp
class ComplexCodetextReader : public System::Object
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| static [TryDecodeGS1Codetext](./trydecodegs1codetext/)(System::String) | Decodeert GS1-codetext. |
| static [TryDecodeGS1DigitalLink](./trydecodegs1digitallink/)(System::String) | Decodeert GS1 Digital Link. |
| static [TryDecodeHIBCLIC](./trydecodehibclic/)(System::String) | Decodeert HIBC LIC-codetext. |
| static [TryDecodeHIBCPAS](./trydecodehibcpas/)(System::String) | Decodeert HIBC PAS-codetext. |
| static [TryDecodeMailmark](./trydecodemailmark/)(System::String) | Decodeert Mailmark Barcode C en L codetext. |
| static [TryDecodeMailmark2D](./trydecodemailmark2d/)(System::String) | Decodeert Royal Mail Mailmark 2D-codetext. |
| static [TryDecodeMaxiCode](./trydecodemaxicode/)(Generation::MaxiCodeMode, System::String) | Decodeert MaxiCode-codetext. |
| static [TryDecodeSwissQR](./trydecodeswissqr/)(System::String) | Decodeert SwissQR-codetext. |
| static [TryDecodeUSADriveId](./trydecodeusadriveid/)(System::String) | Decodeert USADriveId-codetext. |
## Opmerkingen


Dit voorbeeld toont hoe een SwissQR-afbeelding te herkennen en te decoderen.
```cpp
[C#]
  using (var cr = new BarCodeReader("SwissQRCodetext.png", DecodeType.QR))
  {
    cr.Read();
    SwissQRCodetext result = ComplexCodetextReader.TryDecodeSwissQR(cr.GetCodeText());
  }
```

## Zie ook

* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
