---
title: Aspose::BarCode::ComplexBarcode::ComplexCodetextReader class
linktitle: ComplexCodetextReader
second_title: Aspose.BarCode for C++ API Reference
description: 'Aspose::BarCode::ComplexBarcode::ComplexCodetextReader class. ComplexCodetextReader decodes codetext to specified complex barcode type in C++.'
type: docs
weight: 400
url: /cpp/aspose.barcode.complexbarcode/complexcodetextreader/
---
## ComplexCodetextReader class


[ComplexCodetextReader](./) decodes codetext to specified complex barcode type.

```cpp
class ComplexCodetextReader : public System::Object
```

## Methods

| Method | Description |
| --- | --- |
| static [TryDecodeHIBCLIC](./trydecodehibclic/)(System::String) | Decodes HIBC LIC codetext. |
| static [TryDecodeHIBCPAS](./trydecodehibcpas/)(System::String) | Decodes HIBC PAS codetext. |
| static [TryDecodeMailmark](./trydecodemailmark/)(System::String) | Decodes Mailmark Barcode C and L codetext. |
| static [TryDecodeMailmark2D](./trydecodemailmark2d/)(System::String) | Decodes Royal Mail Mailmark 2D codetext. |
| static [TryDecodeMaxiCode](./trydecodemaxicode/)(Aspose::BarCode::Generation::MaxiCodeMode, System::String) | Decodes MaxiCode codetext. |
| static [TryDecodeSwissQR](./trydecodeswissqr/)(System::String) | Decodes SwissQR codetext. |
| static [TryDecodeUSADriveId](./trydecodeusadriveid/)(System::String) | Decodes USADriveId codetext. |
## Remarks


This sample shows how to recognize and decode SwissQR image. 
```cpp
[C#]
  using (var cr = new BarCodeReader("SwissQRCodetext.png", DecodeType.QR))
  {
    cr.Read();
    SwissQRCodetext result = ComplexCodetextReader.TryDecodeSwissQR(cr.GetCodeText());
  }
```

## See Also

* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
