---
title: "Aspose::BarCode::ComplexBarcode::ComplexCodetextReader klass"
linktitle: "ComplexCodetextReader"
second_title: "Aspose.BarCode for C++ API-referens"
description: "Aspose::BarCode::ComplexBarcode::ComplexCodetextReader klass. ComplexCodetextReader avkodar kodtext till angiven komplex streckkodstyp i C++."
type: docs
weight: 400
url: /sv/cpp/aspose.barcode.complexbarcode/complexcodetextreader/
---
## ComplexCodetextReader class


[ComplexCodetextReader](./) decodes codetext to specified complex barcode type.

```cpp
class ComplexCodetextReader : public System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| static [TryDecodeGS1Codetext](./trydecodegs1codetext/)(System::String) | Avkodar GS1-kodtext. |
| static [TryDecodeGS1DigitalLink](./trydecodegs1digitallink/)(System::String) | Avkodar GS1 Digital Link. |
| static [TryDecodeHIBCLIC](./trydecodehibclic/)(System::String) | Avkodar HIBC LIC-kodtext. |
| static [TryDecodeHIBCPAS](./trydecodehibcpas/)(System::String) | Avkodar HIBC PAS-kodtext. |
| static [TryDecodeMailmark](./trydecodemailmark/)(System::String) | Avkodar Mailmark Barcode C- och L-kodtext. |
| static [TryDecodeMailmark2D](./trydecodemailmark2d/)(System::String) | Avkodar Royal Mail Mailmark 2D-kodtext. |
| static [TryDecodeMaxiCode](./trydecodemaxicode/)(Generation::MaxiCodeMode, System::String) | Avkodar MaxiCode-kodtext. |
| static [TryDecodeSwissQR](./trydecodeswissqr/)(System::String) | Avkodar SwissQR-kodtext. |
| static [TryDecodeUSADriveId](./trydecodeusadriveid/)(System::String) | Avkodar USADriveId-kodtext. |
## Anmärkningar


Detta exempel visar hur man känner igen och avkodar SwissQR-bild.
```cpp
[C#]
  using (var cr = new BarCodeReader("SwissQRCodetext.png", DecodeType.QR))
  {
    cr.Read();
    SwissQRCodetext result = ComplexCodetextReader.TryDecodeSwissQR(cr.GetCodeText());
  }
```

## Se även

* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
