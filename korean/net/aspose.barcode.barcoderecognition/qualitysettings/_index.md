---
title: "클래스 QualitySettings"
second_title: "Aspose.BarCode for .NET API 참조"
description: "Aspose.BarCode.BarCodeRecognition.QualitySettings 클래스. QualitySettings는 인식 품질과 속도를 수동으로 구성할 수 있게 합니다. 내장 프리셋 HighPerformance, NormalQuality, HighQuality, MaxQuality를 사용해 빠르게 설정하거나 개별 옵션을 수동으로 구성할 수 있습니다. QualitySettings의 기본값은 NormalQuality입니다."
type: docs
weight: 370
url: /ko/net/aspose.barcode.barcoderecognition/qualitysettings/
---
## QualitySettings class

QualitySettings는 인식 품질과 속도를 수동으로 구성할 수 있게 합니다. 내장된 프리셋인 HighPerformance, NormalQuality, HighQuality, MaxQuality를 사용하여 QualitySettings를 빠르게 설정할 수 있으며, 별도의 옵션을 수동으로 구성할 수도 있습니다. QualitySettings의 기본값은 NormalQuality입니다.

```csharp
public sealed class QualitySettings
```

## 속성

| 이름 | 설명 |
| --- | --- |
| static [HighPerformance](../../aspose.barcode.barcoderecognition/qualitysettings/highperformance/) { get; } | HighPerformance 인식 품질 프리셋. 이 모드에서는 고품질 바코드를 잘 인식합니다. |
| static [HighQuality](../../aspose.barcode.barcoderecognition/qualitysettings/highquality/) { get; } | HighQuality 인식 품질 프리셋. 이 프리셋은 저품질 바코드를 위해 개발되었습니다. 심하게 손상된 바코드도 감지할 수 있습니다. |
| static [MaxQuality](../../aspose.barcode.barcoderecognition/qualitysettings/maxquality/) { get; } | MaxQuality 인식 품질 프리셋. 이 프리셋은 잘못된 바코드까지 모든 가능한 바코드를 인식하도록 개발되었습니다. |
| static [NormalQuality](../../aspose.barcode.barcoderecognition/qualitysettings/normalquality/) { get; } | NormalQuality 인식 품질 프리셋. 대부분의 바코드에 적합합니다. |
| [AllowIncorrectBarcodes](../../aspose.barcode.barcoderecognition/qualitysettings/allowincorrectbarcodes/) { get; set; } | 엔진이 체크섬이 잘못되었거나 값이 올바르지 않은 바코드를 인식하도록 허용합니다. 이 모드는 텍스트가 잘못된 손상된 바코드를 인식하는 데 사용할 수 있습니다. |
| [BarcodeQuality](../../aspose.barcode.barcoderecognition/qualitysettings/barcodequality/) { get; set; } | 선택된 품질로 바코드 요소를 인식하는 메서드를 활성화하는 모드입니다. 품질이 낮은 바코드 요소는 더 많은 복잡한 메서드가 필요하여 인식 속도가 느려집니다. |
| [ComplexBackground](../../aspose.barcode.barcoderecognition/qualitysettings/complexbackground/) { get; set; } | 컬러 이미지에서 컬러 바코드의 추가 인식을 활성화하거나 비활성화하는 모드입니다. |
| [Deconvolution](../../aspose.barcode.barcoderecognition/qualitysettings/deconvolution/) { get; set; } | 이미지 퇴화 수준을 정의하는 디컨볼루션(이미지 복원) 모드입니다. 원래 디컨볼루션은 카메라로 이미지를 촬영할 때 흐림과 같은 자연 함수에 의해 퇴화(컨볼루션)된 이미지를 복원할 수 있는 기능입니다. 이미지 손상을 일으키는 함수를 감지할 수 없기 때문에, 우리는 샤프하거나 수학적 형태학과 같은 잘 알려진 함수를 확인해야 합니다. |
| [InverseImage](../../aspose.barcode.barcoderecognition/qualitysettings/inverseimage/) { get; set; } | 색상 반전(휘도)된 이미지에서 바코드의 추가 인식을 활성화하거나 비활성화하는 모드입니다. |
| [MinimalXDimension](../../aspose.barcode.barcoderecognition/qualitysettings/minimalxdimension/) { get; set; } | UseMinimalXDimension과 함께 사용되는 XDimension의 최소 픽셀 크기입니다. |
| [XDimension](../../aspose.barcode.barcoderecognition/qualitysettings/xdimension/) { get; set; } | 바코드 최소 요소(매트릭스 셀 또는 바)의 크기(1부터 무한대까지)를 설정하는 인식 모드입니다. |

## 예제

이 샘플은 BarCodeReader와 함께 QualitySettings를 사용하는 방법을 보여줍니다

```csharp
[C#]
//HighPerformance 인식 모드 설정
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings = QualitySettings.HighPerformance;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}

//HighQuality 인식 모드 설정
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings = QualitySettings.HighQuality;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}

//작은 크기의 바코드에 대한 HighPerformance 인식 모드 설정
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings = QualitySettings.HighPerformance;
    reader.QualitySettings.XDimension = XDimensionMode.Small;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}

//저품질 바코드에 대한 HighPerformance 인식 모드 설정
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings = QualitySettings.HighPerformance;
    reader.QualitySettings.BarcodeQuality = BarcodeQualityMode.Low;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}    
```

### 또 보기

* namespace [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../)


