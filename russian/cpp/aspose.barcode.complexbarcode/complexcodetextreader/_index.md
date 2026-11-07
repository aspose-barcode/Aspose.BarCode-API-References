---
title: "Aspose::BarCode::ComplexBarcode::ComplexCodetextReader class"
linktitle: "ComplexCodetextReader"
second_title: "Aspose.BarCode для C++ справочник API"
description: "Aspose::BarCode::ComplexBarcode::ComplexCodetextReader class. ComplexCodetextReader декодирует кодовый текст в указанный тип сложного штрихкода в C++."
type: docs
weight: 400
url: /ru/cpp/aspose.barcode.complexbarcode/complexcodetextreader/
---
## ComplexCodetextReader class


[ComplexCodetextReader](./) decodes codetext to specified complex barcode type.

```cpp
class ComplexCodetextReader : public System::Object
```

## Methods

| Method | Описание |
| --- | --- |
| static [TryDecodeGS1Codetext](./trydecodegs1codetext/)(System::String) | Декодирует кодовый текст GS1. |
| static [TryDecodeGS1DigitalLink](./trydecodegs1digitallink/)(System::String) | Декодирует GS1 Digital Link. |
| static [TryDecodeHIBCLIC](./trydecodehibclic/)(System::String) | Декодирует кодовый текст HIBC LIC. |
| static [TryDecodeHIBCPAS](./trydecodehibcpas/)(System::String) | Декодирует кодовый текст HIBC PAS. |
| static [TryDecodeMailmark](./trydecodemailmark/)(System::String) | Декодирует кодовый текст Mailmark Barcode C и L. |
| static [TryDecodeMailmark2D](./trydecodemailmark2d/)(System::String) | Декодирует кодовый текст Royal Mail Mailmark 2D. |
| static [TryDecodeMaxiCode](./trydecodemaxicode/)(Generation::MaxiCodeMode, System::String) | Декодирует кодовый текст MaxiCode. |
| static [TryDecodeSwissQR](./trydecodeswissqr/)(System::String) | Декодирует кодовый текст SwissQR. |
| static [TryDecodeUSADriveId](./trydecodeusadriveid/)(System::String) | Декодирует кодовый текст USADriveId. |
## Примечания


Этот пример показывает, как распознать и декодировать изображение SwissQR.
```cpp
[C#]
  using (var cr = new BarCodeReader("SwissQRCodetext.png", DecodeType.QR))
  {
    cr.Read();
    SwissQRCodetext result = ComplexCodetextReader.TryDecodeSwissQR(cr.GetCodeText());
  }
```

## См. также

* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
