---
title: "Aspose::BarCode::ComplexBarcode::ComplexCodetextReader クラス"
linktitle: "ComplexCodetextReader"
second_title: "Aspose.BarCode for C++ API リファレンス"
description: "Aspose::BarCode::ComplexBarcode::ComplexCodetextReader クラス。ComplexCodetextReader は C++ で指定された複合バーコードタイプにコードテキストをデコードします。"
type: docs
weight: 400
url: /ja/cpp/aspose.barcode.complexbarcode/complexcodetextreader/
---
## ComplexCodetextReader class


[ComplexCodetextReader](./) decodes codetext to specified complex barcode type.

```cpp
class ComplexCodetextReader : public System::Object
```

## メソッド

| メソッド | 説明 |
| --- | --- |
| static [TryDecodeGS1Codetext](./trydecodegs1codetext/)(System::String) | GS1 コードテキストをデコードします。 |
| static [TryDecodeGS1DigitalLink](./trydecodegs1digitallink/)(System::String) | GS1 デジタルリンクをデコードします。 |
| static [TryDecodeHIBCLIC](./trydecodehibclic/)(System::String) | HIBC LIC コードテキストをデコードします。 |
| static [TryDecodeHIBCPAS](./trydecodehibcpas/)(System::String) | HIBC PAS コードテキストをデコードします。 |
| static [TryDecodeMailmark](./trydecodemailmark/)(System::String) | Mailmark バーコード C と L のコードテキストをデコードします。 |
| static [TryDecodeMailmark2D](./trydecodemailmark2d/)(System::String) | Royal Mail Mailmark 2D コードテキストをデコードします。 |
| static [TryDecodeMaxiCode](./trydecodemaxicode/)(Generation::MaxiCodeMode, System::String) | MaxiCode コードテキストをデコードします。 |
| static [TryDecodeSwissQR](./trydecodeswissqr/)(System::String) | SwissQR コードテキストをデコードします。 |
| static [TryDecodeUSADriveId](./trydecodeusadriveid/)(System::String) | USADriveId コードテキストをデコードします。 |
## 備考


このサンプルは SwissQR 画像を認識しデコードする方法を示しています。
```cpp
[C#]
  using (var cr = new BarCodeReader("SwissQRCodetext.png", DecodeType.QR))
  {
    cr.Read();
    SwissQRCodetext result = ComplexCodetextReader.TryDecodeSwissQR(cr.GetCodeText());
  }
```

## 関連項目

* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
