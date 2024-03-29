---
title: ComplexCodetextReader
second_title: .NET API 참조용 Aspose.BarCode
description: ComplexCodetextReader는 코드 텍스트를 지정된 복잡한 바코드 유형으로 디코딩합니다.
type: docs
weight: 360
url: /ko/net/aspose.barcode.complexbarcode/complexcodetextreader/
---
## ComplexCodetextReader class

ComplexCodetextReader는 코드 텍스트를 지정된 복잡한 바코드 유형으로 디코딩합니다.

```csharp
public sealed class ComplexCodetextReader
```

## 행동 양식

| 이름 | 설명 |
| --- | --- |
| static [TryDecodeHIBCLIC](../../aspose.barcode.complexbarcode/complexcodetextreader/trydecodehibclic/)(string) | HIBC LIC 코드 텍스트를 디코딩합니다. |
| static [TryDecodeHIBCPAS](../../aspose.barcode.complexbarcode/complexcodetextreader/trydecodehibcpas/)(string) | HIBC PAS 코드 텍스트를 디코딩합니다. |
| static [TryDecodeMailmark](../../aspose.barcode.complexbarcode/complexcodetextreader/trydecodemailmark/)(string) | 메일마크 바코드 C 및 L 코드 텍스트를 해독합니다. |
| static [TryDecodeMailmark2D](../../aspose.barcode.complexbarcode/complexcodetextreader/trydecodemailmark2d/)(string) | Royal Mail Mailmark 2D 코드 텍스트를 해독합니다. |
| static [TryDecodeMaxiCode](../../aspose.barcode.complexbarcode/complexcodetextreader/trydecodemaxicode/)(MaxiCodeMode, string) | MaxiCode 코드 텍스트를 디코딩합니다. |
| static [TryDecodeSwissQR](../../aspose.barcode.complexbarcode/complexcodetextreader/trydecodeswissqr/)(string) | SwissQR 코드 텍스트를 디코딩합니다. |

### 예

이 샘플은 SwissQR 이미지를 인식하고 디코딩하는 방법을 보여줍니다.

```csharp
[C#]
  using (var cr = new BarCodeReader("SwissQRCodetext.png", DecodeType.QR))
  {
    cr.Read();
    SwissQRCodetext result = ComplexCodetextReader.TryDecodeSwissQR(cr.GetCodeText());
  }
```

### 또한보십시오

* 네임스페이스 [Aspose.BarCode.ComplexBarcode](../../aspose.barcode.complexbarcode/)
* 집회 [Aspose.BarCode](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->
