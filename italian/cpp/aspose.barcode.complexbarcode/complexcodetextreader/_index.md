---
title: "Aspose::BarCode::ComplexBarcode::ComplexCodetextReader classe"
linktitle: "ComplexCodetextReader"
second_title: "Aspose.BarCode for C++ Riferimento API"
description: "Aspose::BarCode::ComplexBarcode::ComplexCodetextReader classe. ComplexCodetextReader decodifica il codetext nel tipo di codice a barre complesso specificato in C++."
type: docs
weight: 400
url: /it/cpp/aspose.barcode.complexbarcode/complexcodetextreader/
---
## ComplexCodetextReader class


[ComplexCodetextReader](./) decodes codetext to specified complex barcode type.

```cpp
class ComplexCodetextReader : public System::Object
```

## Metodi

| Metodo | Descrizione |
| --- | --- |
| static [TryDecodeGS1Codetext](./trydecodegs1codetext/)(System::String) | Decodifica il codetext GS1. |
| static [TryDecodeGS1DigitalLink](./trydecodegs1digitallink/)(System::String) | Decodifica GS1 Digital Link. |
| static [TryDecodeHIBCLIC](./trydecodehibclic/)(System::String) | Decodifica il codetext HIBC LIC. |
| static [TryDecodeHIBCPAS](./trydecodehibcpas/)(System::String) | Decodifica il codetext HIBC PAS. |
| static [TryDecodeMailmark](./trydecodemailmark/)(System::String) | Decodifica il codetext del codice a barre Mailmark C e L. |
| static [TryDecodeMailmark2D](./trydecodemailmark2d/)(System::String) | Decodifica il codetext Mailmark 2D di Royal Mail. |
| static [TryDecodeMaxiCode](./trydecodemaxicode/)(Generation::MaxiCodeMode, System::String) | Decodifica il codetext MaxiCode. |
| static [TryDecodeSwissQR](./trydecodeswissqr/)(System::String) | Decodifica il codetext SwissQR. |
| static [TryDecodeUSADriveId](./trydecodeusadriveid/)(System::String) | Decodifica il codetext USADriveId. |
## Osservazioni


Questo esempio mostra come riconoscere e decodificare l'immagine SwissQR.
```cpp
[C#]
  using (var cr = new BarCodeReader("SwissQRCodetext.png", DecodeType.QR))
  {
    cr.Read();
    SwissQRCodetext result = ComplexCodetextReader.TryDecodeSwissQR(cr.GetCodeText());
  }
```

## Vedi anche

* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
