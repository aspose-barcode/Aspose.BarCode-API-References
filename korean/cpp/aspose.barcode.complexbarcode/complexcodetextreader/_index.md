---
title: "Aspose::BarCode::ComplexBarcode::ComplexCodetextReader 클래스"
linktitle: "ComplexCodetextReader"
second_title: "Aspose.BarCode for C++ API 레퍼런스"
description: "Aspose::BarCode::ComplexBarcode::ComplexCodetextReader 클래스. ComplexCodetextReader는 C++에서 지정된 복합 바코드 유형으로 코덱스트를 디코드합니다."
type: docs
weight: 400
url: /ko/cpp/aspose.barcode.complexbarcode/complexcodetextreader/
---
## ComplexCodetextReader class


[ComplexCodetextReader](./) decodes codetext to specified complex barcode type.

```cpp
class ComplexCodetextReader : public System::Object
```

## 메서드

| 메서드 | 설명 |
| --- | --- |
| static [TryDecodeGS1Codetext](./trydecodegs1codetext/)(System::String) | GS1 코덱스트를 디코드합니다. |
| static [TryDecodeGS1DigitalLink](./trydecodegs1digitallink/)(System::String) | GS1 Digital Link를 디코드합니다. |
| static [TryDecodeHIBCLIC](./trydecodehibclic/)(System::String) | HIBC LIC 코덱스트를 디코드합니다. |
| static [TryDecodeHIBCPAS](./trydecodehibcpas/)(System::String) | HIBC PAS 코덱스트를 디코드합니다. |
| static [TryDecodeMailmark](./trydecodemailmark/)(System::String) | Mailmark Barcode C 및 L 코덱스트를 디코드합니다. |
| static [TryDecodeMailmark2D](./trydecodemailmark2d/)(System::String) | Royal Mail Mailmark 2D 코덱스트를 디코드합니다. |
| static [TryDecodeMaxiCode](./trydecodemaxicode/)(Generation::MaxiCodeMode, System::String) | MaxiCode 코덱스트를 디코드합니다. |
| static [TryDecodeSwissQR](./trydecodeswissqr/)(System::String) | SwissQR 코덱스트를 디코드합니다. |
| static [TryDecodeUSADriveId](./trydecodeusadriveid/)(System::String) | USADriveId 코덱스트를 디코드합니다. |
## 비고


이 샘플은 SwissQR 이미지를 인식하고 디코드하는 방법을 보여줍니다.
```cpp
[C#]
  using (var cr = new BarCodeReader("SwissQRCodetext.png", DecodeType.QR))
  {
    cr.Read();
    SwissQRCodetext result = ComplexCodetextReader.TryDecodeSwissQR(cr.GetCodeText());
  }
```

## 또 보기

* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
