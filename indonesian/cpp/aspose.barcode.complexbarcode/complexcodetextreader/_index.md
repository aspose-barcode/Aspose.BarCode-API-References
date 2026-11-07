---
title: "Aspose::BarCode::ComplexBarcode::ComplexCodetextReader kelas"
linktitle: "ComplexCodetextReader"
second_title: "Aspose.BarCode for C++ Referensi API"
description: "Aspose::BarCode::ComplexBarcode::ComplexCodetextReader kelas. ComplexCodetextReader mendekode codetext ke tipe barcode kompleks yang ditentukan dalam C++."
type: docs
weight: 400
url: /id/cpp/aspose.barcode.complexbarcode/complexcodetextreader/
---
## ComplexCodetextReader class


[ComplexCodetextReader](./) decodes codetext to specified complex barcode type.

```cpp
class ComplexCodetextReader : public System::Object
```

## Metode

| Metode | Deskripsi |
| --- | --- |
| static [TryDecodeGS1Codetext](./trydecodegs1codetext/)(System::String) | Mendekode codetext GS1. |
| static [TryDecodeGS1DigitalLink](./trydecodegs1digitallink/)(System::String) | Mendekode GS1 Digital Link. |
| static [TryDecodeHIBCLIC](./trydecodehibclic/)(System::String) | Mendekode codetext HIBC LIC. |
| static [TryDecodeHIBCPAS](./trydecodehibcpas/)(System::String) | Mendekode codetext HIBC PAS. |
| static [TryDecodeMailmark](./trydecodemailmark/)(System::String) | Mendekode codetext Mailmark Barcode C dan L. |
| static [TryDecodeMailmark2D](./trydecodemailmark2d/)(System::String) | Mendekode codetext Royal Mail Mailmark 2D. |
| static [TryDecodeMaxiCode](./trydecodemaxicode/)(Generation::MaxiCodeMode, System::String) | Mendekode codetext MaxiCode. |
| static [TryDecodeSwissQR](./trydecodeswissqr/)(System::String) | Mendekode codetext SwissQR. |
| static [TryDecodeUSADriveId](./trydecodeusadriveid/)(System::String) | Mendekode codetext USADriveId. |
## Catatan


Contoh ini menunjukkan cara mengenali dan mendekode gambar SwissQR.
```cpp
[C#]
  using (var cr = new BarCodeReader("SwissQRCodetext.png", DecodeType.QR))
  {
    cr.Read();
    SwissQRCodetext result = ComplexCodetextReader.TryDecodeSwissQR(cr.GetCodeText());
  }
```

## Lihat Juga

* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
