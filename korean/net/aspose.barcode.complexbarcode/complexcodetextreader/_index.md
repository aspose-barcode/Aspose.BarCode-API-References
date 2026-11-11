---
title: "클래스 ComplexCodetextReader"
second_title: "Aspose.BarCode for .NET API 참조"
description: "Aspose.BarCode.ComplexBarcode.ComplexCodetextReader 클래스. ComplexCodetextReader는 코덱스트를 지정된 복합 바코드 유형으로 디코딩합니다."
type: docs
weight: 520
url: /ko/net/aspose.barcode.complexbarcode/complexcodetextreader/
---
## ComplexCodetextReader class

ComplexCodetextReader는 코드텍스트를 지정된 복합 바코드 유형으로 디코딩합니다.

```csharp
public sealed class ComplexCodetextReader
```

## 메서드

| 이름 | 설명 |
| --- | --- |
| static [TryDecodeGS1Codetext](../../aspose.barcode.complexbarcode/complexcodetextreader/trydecodegs1codetext/)(string) | GS1 코덱스트를 디코딩합니다. |
| static [TryDecodeGS1DigitalLink](../../aspose.barcode.complexbarcode/complexcodetextreader/trydecodegs1digitallink/)(string) | GS1 Digital Link를 디코딩합니다. |
| static [TryDecodeHIBCLIC](../../aspose.barcode.complexbarcode/complexcodetextreader/trydecodehibclic/)(string) | HIBC LIC 코드텍스트를 디코딩합니다. |
| static [TryDecodeHIBCPAS](../../aspose.barcode.complexbarcode/complexcodetextreader/trydecodehibcpas/)(string) | HIBC PAS 코드텍스트를 디코딩합니다. |
| static [TryDecodeMailmark](../../aspose.barcode.complexbarcode/complexcodetextreader/trydecodemailmark/)(string) | Mailmark 바코드 C 및 L 코드텍스트를 디코딩합니다. |
| static [TryDecodeMailmark2D](../../aspose.barcode.complexbarcode/complexcodetextreader/trydecodemailmark2d/)(string) | Royal Mail Mailmark 2D 코드텍스트를 디코딩합니다. |
| static [TryDecodeMaxiCode](../../aspose.barcode.complexbarcode/complexcodetextreader/trydecodemaxicode/)(MaxiCodeMode, string) | MaxiCode 코드텍스트를 디코딩합니다. |
| static [TryDecodeSwissQR](../../aspose.barcode.complexbarcode/complexcodetextreader/trydecodeswissqr/)(string) | SwissQR 코드텍스트를 디코딩합니다. |
| static [TryDecodeUSADriveId](../../aspose.barcode.complexbarcode/complexcodetextreader/trydecodeusadriveid/)(string) | USADriveId 코드텍스트를 디코딩합니다. |

## 예제

이 샘플은 SwissQR 이미지를 인식하고 디코딩하는 방법을 보여줍니다.

```csharp
[C#]
  using (var cr = new BarCodeReader("SwissQRCodetext.png", DecodeType.QR))
  {
    cr.Read();
    SwissQRCodetext result = ComplexCodetextReader.TryDecodeSwissQR(cr.GetCodeText());
  }
```

### 또 보기

* namespace [Aspose.BarCode.ComplexBarcode](../../aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](../../)


