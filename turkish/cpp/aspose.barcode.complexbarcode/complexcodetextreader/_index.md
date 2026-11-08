---
title: "Aspose::BarCode::ComplexBarcode::ComplexCodetextReader sınıfı"
linktitle: "ComplexCodetextReader"
second_title: "Aspose.BarCode for C++ API Referansı"
description: "Aspose::BarCode::ComplexBarcode::ComplexCodetextReader sınıfı. ComplexCodetextReader, C++'ta belirtilen karmaşık barkod türüne kodmetnini çözer."
type: docs
weight: 400
url: /tr/cpp/aspose.barcode.complexbarcode/complexcodetextreader/
---
## ComplexCodetextReader class


[ComplexCodetextReader](./) decodes codetext to specified complex barcode type.

```cpp
class ComplexCodetextReader : public System::Object
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| static [TryDecodeGS1Codetext](./trydecodegs1codetext/)(System::String) | GS1 kodmetnini çözer. |
| static [TryDecodeGS1DigitalLink](./trydecodegs1digitallink/)(System::String) | GS1 Digital Link'i çözer. |
| static [TryDecodeHIBCLIC](./trydecodehibclic/)(System::String) | HIBC LIC kodmetnini çözer. |
| static [TryDecodeHIBCPAS](./trydecodehibcpas/)(System::String) | HIBC PAS kodmetnini çözer. |
| static [TryDecodeMailmark](./trydecodemailmark/)(System::String) | Mailmark Barkod C ve L kodmetnini çözer. |
| static [TryDecodeMailmark2D](./trydecodemailmark2d/)(System::String) | Royal Mail Mailmark 2D kodmetnini çözer. |
| static [TryDecodeMaxiCode](./trydecodemaxicode/)(Generation::MaxiCodeMode, System::String) | MaxiCode kodmetnini çözer. |
| static [TryDecodeSwissQR](./trydecodeswissqr/)(System::String) | SwissQR kodmetnini çözer. |
| static [TryDecodeUSADriveId](./trydecodeusadriveid/)(System::String) | USADriveId kodmetnini çözer. |
## Açıklamalar


Bu örnek, SwissQR görüntüsünü tanıma ve çözme yöntemini gösterir.
```cpp
[C#]
  using (var cr = new BarCodeReader("SwissQRCodetext.png", DecodeType.QR))
  {
    cr.Read();
    SwissQRCodetext result = ComplexCodetextReader.TryDecodeSwissQR(cr.GetCodeText());
  }
```

## Ayrıca Bakınız

* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
