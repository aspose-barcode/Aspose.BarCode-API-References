---
title: "열거형 MaxiCodeMode"
second_title: "Aspose.BarCode for .NET API 참조"
description: "Aspose.BarCode.Generation.MaxiCodeMode 열거형. MaxiCode 바코드의 인코딩 모드"
type: docs
weight: 1480
url: /ko/net/aspose.barcode.generation/maxicodemode/
---
## MaxiCodeMode enumeration

MaxiCode 바코드의 인코딩 모드.

```csharp
public enum MaxiCodeMode
```

### 값

| 이름 | 값 | 설명 |
| --- | --- | --- |
| Mode2 | `2` | 모드 2는 첫 번째 메시지에 우편 정보를, 두 번째 메시지에 데이터를 인코딩합니다. 9자리 우편 번호를 갖으며 (미국에서만 사용됩니다). |
| Mode3 | `3` | 모드 3은 첫 번째 메시지에 우편 정보를, 두 번째 메시지에 데이터를 인코딩합니다. 전 세계에서 사용되는 6자리 알파벳-숫자 조합 우편 번호를 갖습니다. |
| Mode4 | `4` | 모드 4는 첫 번째와 두 번째 메시지에 데이터를 인코딩하며, 짧은 ECC 보정을 사용합니다. |
| Mode5 | `5` | 모드 5는 첫 번째와 두 번째 메시지에 데이터를 인코딩하며, 긴 ECC 보정을 사용합니다. |
| Mode6 | `6` | 모드 6은 첫 번째와 두 번째 메시지에 데이터를 인코딩하며, 짧은 ECC 보정을 사용합니다. 장치를 인코딩하는 데 사용됩니다. |

## 예제

이 샘플은 ComplexBarcodeGenerator를 사용하여 MaxiCode 바코드를 생성하는 방법을 보여줍니다.

```csharp
[C#]
//표준 두 번째 메시지가 있는 모드 2
MaxiCodeCodetextMode2 maxiCodeCodetext = new MaxiCodeCodetextMode2();
maxiCodeCodetext.PostalCode = "524032140";
maxiCodeCodetext.CountryCode = 056;
maxiCodeCodetext.ServiceCategory = 999;
MaxiCodeStandardSecondMessage maxiCodeStandardSecondMessage = new MaxiCodeStandardSecondMessage();
maxiCodeStandardSecondMessage.Message = "Test message";
maxiCodeCodetext.SecondMessage = maxiCodeStandardSecondMessage;
using (ComplexBarcodeGenerator complexGenerator = new ComplexBarcodeGenerator(maxiCodeCodetext))
{
    complexGenerator.GenerateBarCodeImage();
}
//구조화된 두 번째 메시지가 있는 모드 2
MaxiCodeCodetextMode2 maxiCodeCodetext = new MaxiCodeCodetextMode2();
maxiCodeCodetext.PostalCode = "524032140";
maxiCodeCodetext.CountryCode = 056;
maxiCodeCodetext.ServiceCategory = 999;
MaxiCodeStructuredSecondMessage maxiCodeStructuredSecondMessage = new MaxiCodeStructuredSecondMessage();
maxiCodeStructuredSecondMessage.Add("634 ALPHA DRIVE");
maxiCodeStructuredSecondMessage.Add("PITTSBURGH");
maxiCodeStructuredSecondMessage.Add("PA");
maxiCodeStructuredSecondMessage.Year = 99;
maxiCodeCodetext.SecondMessage = maxiCodeStructuredSecondMessage;
using (ComplexBarcodeGenerator complexGenerator = new ComplexBarcodeGenerator(maxiCodeCodetext))
{
    complexGenerator.GenerateBarCodeImage();
}
//표준 두 번째 메시지가 있는 모드 3
MaxiCodeCodetextMode3 maxiCodeCodetext = new MaxiCodeCodetextMode3();
maxiCodeCodetext.PostalCode = "B1050";
maxiCodeCodetext.CountryCode = 056;
maxiCodeCodetext.ServiceCategory = 999;
MaxiCodeStandardSecondMessage maxiCodeStandardSecondMessage = new MaxiCodeStandardSecondMessage();
maxiCodeStandardSecondMessage.Message = "Test message";
maxiCodeCodetext.SecondMessage = maxiCodeStandardSecondMessage;
using (ComplexBarcodeGenerator complexGenerator = new ComplexBarcodeGenerator(maxiCodeCodetext))
{
    complexGenerator.GenerateBarCodeImage();
}
//구조화된 두 번째 메시지가 있는 모드 3
MaxiCodeCodetextMode3 maxiCodeCodetext = new MaxiCodeCodetextMode3();
maxiCodeCodetext.PostalCode = "B1050";
maxiCodeCodetext.CountryCode = 056;
maxiCodeCodetext.ServiceCategory = 999;
MaxiCodeStructuredSecondMessage maxiCodeStructuredSecondMessage = new MaxiCodeStructuredSecondMessage();
maxiCodeStructuredSecondMessage.Add("634 ALPHA DRIVE");
maxiCodeStructuredSecondMessage.Add("PITTSBURGH");
maxiCodeStructuredSecondMessage.Add("PA");
maxiCodeStructuredSecondMessage.Year = 99;
maxiCodeCodetext.SecondMessage = maxiCodeStructuredSecondMessage;
using (ComplexBarcodeGenerator complexGenerator = new ComplexBarcodeGenerator(maxiCodeCodetext.GetConstructedCodetext())
{
    complexGenerator.GenerateBarCodeImage();
}
//모드 4
MaxiCodeStandardCodetext maxiCodeCodetext = new MaxiCodeStandardCodetext();
maxiCodeCodetext.Mode = MaxiCodeMode.Mode4;
maxiCodeCodetext.Message = "Test message";
using (ComplexBarcodeGenerator complexGenerator = new ComplexBarcodeGenerator(maxiCodeCodetext.GetConstructedCodetext())
{
    complexGenerator.GenerateBarCodeImage();
}
//모드 5
MaxiCodeStandardCodetext maxiCodeCodetext = new MaxiCodeStandardCodetext();
maxiCodeCodetext.Mode = MaxiCodeMode.Mode5;
maxiCodeCodetext.Message = "Test message";
using (ComplexBarcodeGenerator complexGenerator = new ComplexBarcodeGenerator(maxiCodeCodetext.GetConstructedCodetext())
{
    complexGenerator.GenerateBarCodeImage();
} 
//모드 6
MaxiCodeStandardCodetext maxiCodeCodetext = new MaxiCodeStandardCodetext();
maxiCodeCodetext.Mode = MaxiCodeMode.Mode6;
maxiCodeCodetext.Message = "Test message";
using (ComplexBarcodeGenerator complexGenerator = new ComplexBarcodeGenerator(maxiCodeCodetext.GetConstructedCodetext())
{
    complexGenerator.GenerateBarCodeImage();
} 
```

### 또 보기

* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


