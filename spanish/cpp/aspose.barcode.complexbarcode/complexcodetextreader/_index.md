---
title: "Aspose::BarCode::ComplexBarcode::ComplexCodetextReader class"
linktitle: "ComplexCodetextReader"
second_title: "Aspose.BarCode for C++ Referencia de API"
description: "Aspose::BarCode::ComplexBarcode::ComplexCodetextReader class. ComplexCodetextReader decodifica el texto del código al tipo de código de barras complejo especificado en C++."
type: docs
weight: 400
url: /es/cpp/aspose.barcode.complexbarcode/complexcodetextreader/
---
## ComplexCodetextReader class


[ComplexCodetextReader](./) decodes codetext to specified complex barcode type.

```cpp
class ComplexCodetextReader : public System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| static [TryDecodeGS1Codetext](./trydecodegs1codetext/)(System::String) | Decodifica el texto del código GS1. |
| static [TryDecodeGS1DigitalLink](./trydecodegs1digitallink/)(System::String) | Decodifica GS1 Digital Link. |
| static [TryDecodeHIBCLIC](./trydecodehibclic/)(System::String) | Decodifica el texto del código HIBC LIC. |
| static [TryDecodeHIBCPAS](./trydecodehibcpas/)(System::String) | Decodifica el texto del código HIBC PAS. |
| static [TryDecodeMailmark](./trydecodemailmark/)(System::String) | Decodifica el texto del código de barras Mailmark C y L. |
| static [TryDecodeMailmark2D](./trydecodemailmark2d/)(System::String) | Decodifica el texto del código 2D Mailmark de Royal Mail. |
| static [TryDecodeMaxiCode](./trydecodemaxicode/)(Generation::MaxiCodeMode, System::String) | Decodifica el texto del código MaxiCode. |
| static [TryDecodeSwissQR](./trydecodeswissqr/)(System::String) | Decodifica el texto del código SwissQR. |
| static [TryDecodeUSADriveId](./trydecodeusadriveid/)(System::String) | Decodifica el texto del código USADriveId. |
## Observaciones


Este ejemplo muestra cómo reconocer y decodificar una imagen SwissQR.
```cpp
[C#]
  using (var cr = new BarCodeReader("SwissQRCodetext.png", DecodeType.QR))
  {
    cr.Read();
    SwissQRCodetext result = ComplexCodetextReader.TryDecodeSwissQR(cr.GetCodeText());
  }
```

## Ver también

* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
