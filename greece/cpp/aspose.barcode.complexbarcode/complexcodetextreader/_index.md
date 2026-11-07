---
title: "Aspose::BarCode::ComplexBarcode::ComplexCodetextReader class"
linktitle: "ComplexCodetextReader"
second_title: "Aspose.BarCode για C++ Αναφορά API"
description: "Aspose::BarCode::ComplexBarcode::ComplexCodetextReader class. ComplexCodetextReader αποκωδικοποιεί το κείμενο κώδικα σε συγκεκριμένο σύνθετο τύπο barcode σε C++."
type: docs
weight: 400
url: /el/cpp/aspose.barcode.complexbarcode/complexcodetextreader/
---
## ComplexCodetextReader class


[ComplexCodetextReader](./) decodes codetext to specified complex barcode type.

```cpp
class ComplexCodetextReader : public System::Object
```

## Methods

| Method | Περιγραφή |
| --- | --- |
| static [TryDecodeGS1Codetext](./trydecodegs1codetext/)(System::String) | Αποκωδικοποιεί το κείμενο κώδικα GS1. |
| static [TryDecodeGS1DigitalLink](./trydecodegs1digitallink/)(System::String) | Αποκωδικοποιεί το GS1 Digital Link. |
| static [TryDecodeHIBCLIC](./trydecodehibclic/)(System::String) | Αποκωδικοποιεί το κείμενο κώδικα HIBC LIC. |
| static [TryDecodeHIBCPAS](./trydecodehibcpas/)(System::String) | Αποκωδικοποιεί το κείμενο κώδικα HIBC PAS. |
| static [TryDecodeMailmark](./trydecodemailmark/)(System::String) | Αποκωδικοποιεί το κείμενο κώδικα Mailmark Barcode C και L. |
| static [TryDecodeMailmark2D](./trydecodemailmark2d/)(System::String) | Αποκωδικοποιεί το κείμενο κώδικα Royal Mail Mailmark 2D. |
| static [TryDecodeMaxiCode](./trydecodemaxicode/)(Generation::MaxiCodeMode, System::String) | Αποκωδικοποιεί το κείμενο κώδικα MaxiCode. |
| static [TryDecodeSwissQR](./trydecodeswissqr/)(System::String) | Αποκωδικοποιεί το κείμενο κώδικα SwissQR. |
| static [TryDecodeUSADriveId](./trydecodeusadriveid/)(System::String) | Αποκωδικοποιεί το κείμενο κώδικα USADriveId. |
## Σχόλια


Αυτό το παράδειγμα δείχνει πώς να αναγνωρίσετε και να αποκωδικοποιήσετε την εικόνα SwissQR.
```cpp
[C#]
  using (var cr = new BarCodeReader("SwissQRCodetext.png", DecodeType.QR))
  {
    cr.Read();
    SwissQRCodetext result = ComplexCodetextReader.TryDecodeSwissQR(cr.GetCodeText());
  }
```

## Δείτε επίσης

* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
