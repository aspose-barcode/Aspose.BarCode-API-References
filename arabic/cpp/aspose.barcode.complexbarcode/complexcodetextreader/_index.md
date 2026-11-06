---
title: "Aspose::BarCode::ComplexBarcode::ComplexCodetextReader فئة"
linktitle: "ComplexCodetextReader"
second_title: "Aspose.BarCode للـ C++ مرجع API"
description: "Aspose::BarCode::ComplexBarcode::ComplexCodetextReader فئة. ComplexCodetextReader يفك تشفير النص المشفر إلى نوع الباركود المعقد المحدد في C++."
type: docs
weight: 400
url: /ar/cpp/aspose.barcode.complexbarcode/complexcodetextreader/
---
## ComplexCodetextReader class


[ComplexCodetextReader](./) decodes codetext to specified complex barcode type.

```cpp
class ComplexCodetextReader : public System::Object
```

## الطرق

| طريقة | الوصف |
| --- | --- |
| static [TryDecodeGS1Codetext](./trydecodegs1codetext/)(System::String) | يفك تشفير نص GS1. |
| static [TryDecodeGS1DigitalLink](./trydecodegs1digitallink/)(System::String) | يفك تشفير رابط GS1 الرقمي. |
| static [TryDecodeHIBCLIC](./trydecodehibclic/)(System::String) | يفك تشفير نص HIBC LIC. |
| static [TryDecodeHIBCPAS](./trydecodehibcpas/)(System::String) | يفك تشفير نص HIBC PAS. |
| static [TryDecodeMailmark](./trydecodemailmark/)(System::String) | يفك تشفير نص باركود Mailmark C و L. |
| static [TryDecodeMailmark2D](./trydecodemailmark2d/)(System::String) | يفك تشفير نص Mailmark 2D الخاص بـ Royal Mail. |
| static [TryDecodeMaxiCode](./trydecodemaxicode/)(Generation::MaxiCodeMode, System::String) | يفك تشفير نص MaxiCode. |
| static [TryDecodeSwissQR](./trydecodeswissqr/)(System::String) | يفك تشفير نص SwissQR. |
| static [TryDecodeUSADriveId](./trydecodeusadriveid/)(System::String) | يفك تشفير نص USADriveId. |
## ملاحظات


يعرض هذا المثال كيفية التعرف على صورة SwissQR وفك تشفيرها.
```cpp
[C#]
  using (var cr = new BarCodeReader("SwissQRCodetext.png", DecodeType.QR))
  {
    cr.Read();
    SwissQRCodetext result = ComplexCodetextReader.TryDecodeSwissQR(cr.GetCodeText());
  }
```

## انظر أيضًا

* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
