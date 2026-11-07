---
title: "Aspose::BarCode::ComplexBarcode::ComplexCodetextReader Klasse"
linktitle: "ComplexCodetextReader"
second_title: "Aspose.BarCode für C++ API-Referenz"
description: "Aspose::BarCode::ComplexBarcode::ComplexCodetextReader Klasse. ComplexCodetextReader dekodiert Codetext zu dem angegebenen komplexen Barcode-Typ in C++."
type: docs
weight: 400
url: /de/cpp/aspose.barcode.complexbarcode/complexcodetextreader/
---
## ComplexCodetextReader class


[ComplexCodetextReader](./) decodes codetext to specified complex barcode type.

```cpp
class ComplexCodetextReader : public System::Object
```

## Methods

| Method | Beschreibung |
| --- | --- |
| static [TryDecodeGS1Codetext](./trydecodegs1codetext/)(System::String) | Dekodiert GS1-Codetext. |
| static [TryDecodeGS1DigitalLink](./trydecodegs1digitallink/)(System::String) | Dekodiert GS1 Digital Link. |
| static [TryDecodeHIBCLIC](./trydecodehibclic/)(System::String) | Dekodiert HIBC LIC Codetext. |
| static [TryDecodeHIBCPAS](./trydecodehibcpas/)(System::String) | Dekodiert HIBC PAS Codetext. |
| static [TryDecodeMailmark](./trydecodemailmark/)(System::String) | Dekodiert Mailmark Barcode C und L Codetext. |
| static [TryDecodeMailmark2D](./trydecodemailmark2d/)(System::String) | Dekodiert Royal Mail Mailmark 2D Codetext. |
| static [TryDecodeMaxiCode](./trydecodemaxicode/)(Generation::MaxiCodeMode, System::String) | Dekodiert MaxiCode Codetext. |
| static [TryDecodeSwissQR](./trydecodeswissqr/)(System::String) | Dekodiert SwissQR Codetext. |
| static [TryDecodeUSADriveId](./trydecodeusadriveid/)(System::String) | Dekodiert USADriveId Codetext. |
## Hinweise


Dieses Beispiel zeigt, wie man ein SwissQR-Bild erkennt und dekodiert.
```cpp
[C#]
  using (var cr = new BarCodeReader("SwissQRCodetext.png", DecodeType.QR))
  {
    cr.Read();
    SwissQRCodetext result = ComplexCodetextReader.TryDecodeSwissQR(cr.GetCodeText());
  }
```

## Siehe auch

* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
