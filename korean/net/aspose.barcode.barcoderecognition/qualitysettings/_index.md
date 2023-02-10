---
title: QualitySettings
second_title: .NET API 참조용 Aspose.BarCode
description: QualitySettings를 사용하면 인식 품질과 속도를 수동으로 구성할 수 있습니다. 포함된 사전 설정으로 QualitySettings를 빠르게 설정할 수 있습니다 HighPerformance NormalQuality HighQuality MaxBarCodes 또는 개별 옵션을 수동으로 구성할 수 있습니다. QualitySettings의 기본값은 NormalQuality입니다.
type: docs
weight: 270
url: /ko/net/aspose.barcode.barcoderecognition/qualitysettings/
---
## QualitySettings class

QualitySettings를 사용하면 인식 품질과 속도를 수동으로 구성할 수 있습니다. 포함된 사전 설정으로 QualitySettings를 빠르게 설정할 수 있습니다: HighPerformance, NormalQuality, HighQuality, MaxBarCodes 또는 개별 옵션을 수동으로 구성할 수 있습니다. QualitySettings의 기본값은 NormalQuality입니다.

```csharp
public sealed class QualitySettings
```

## 속성

| 이름 | 설명 |
| --- | --- |
| static [HighPerformance](../../aspose.barcode.barcoderecognition/qualitysettings/highperformance/) { get; } | HighPerformance 인식 품질 사전 설정. 이 모드에서는 고품질 바코드가 잘 인식됩니다. |
| static [HighQuality](../../aspose.barcode.barcoderecognition/qualitysettings/highquality/) { get; } | HighQuality 인식 품질 사전 설정. 이 사전 설정은 저품질 바코드용으로 개발되었습니다. 대각선 및 심하게 손상된 바코드를 감지할 수 있습니다. |
| static [HighQualityDetection](../../aspose.barcode.barcoderecognition/qualitysettings/highqualitydetection/) { get; } | HighQualityDetection 인식 품질 사전 설정. NormalQuality와 동일하지만 고품질[`DetectorSettings`](./detectorsettings/) |
| static [MaxBarCodes](../../aspose.barcode.barcoderecognition/qualitysettings/maxbarcodes/) { get; } | MaxBarCodes 인식 품질 사전 설정. 이 사전 설정은 잘못된 바코드를 포함하여 가능한 모든 바코드를 인식하도록 개발되었습니다. |
| static [MaxQualityDetection](../../aspose.barcode.barcoderecognition/qualitysettings/maxqualitydetection/) { get; } | MaxQualityDetection 인식 품질 사전 설정. NormalQuality와 동일하지만 최고 품질[`DetectorSettings`](./detectorsettings/) . 대각선 및 손상된 바코드를 감지할 수 있습니다. |
| static [NormalQuality](../../aspose.barcode.barcoderecognition/qualitysettings/normalquality/) { get; } | NormalQuality 인식 품질 사전 설정. 대부분의 바코드에 적합 |
| [AllowComplexBackground](../../aspose.barcode.barcoderecognition/qualitysettings/allowcomplexbackground/) { get; set; } | 엔진이 컬러 배경의 컬러 바코드를 추가 스캔으로 인식할 수 있습니다. 매우 느린 모드. |
| [AllowDatamatrixIndustrialBarcodes](../../aspose.barcode.barcoderecognition/qualitysettings/allowdatamatrixindustrialbarcodes/) { get; set; } | Datamatrix용 엔진이 대시 산업용 Datamatrix 바코드를 인식할 수 있습니다. 스폿으로 구성된 점선 바코드에만 도움이 되는 저속 모드입니다. |
| [AllowDecreasedImage](../../aspose.barcode.barcoderecognition/qualitysettings/allowdecreasedimage/) { get; set; } | 엔진이 축소된 이미지를 추가 스캔으로 인식하도록 허용합니다. 축소할 크기는 내부 엔진 알고리즘에 의해 선택됩니다. 모드는 노이즈가 있고 흐릿하지만 고해상도로 캡처되는 바코드를 인식하는 데 도움이 됩니다. |
| [AllowDetectScanGap](../../aspose.barcode.barcoderecognition/qualitysettings/allowdetectscangap/) { get; set; } | 엔진이 스캔 사이의 간격을 사용하여 인식 속도를 높일 수 있습니다. 모드는 높이가 낮은 바코드로 인식 문제를 일으킬 수 있습니다. |
| [AllowIncorrectBarcodes](../../aspose.barcode.barcoderecognition/qualitysettings/allowincorrectbarcodes/) { get; set; } | 엔진이 잘못된 체크섬 또는 잘못된 값이 있는 바코드를 인식할 수 있습니다. 모드는 잘못된 텍스트로 손상된 바코드를 인식하는 데 사용할 수 있습니다. |
| [AllowInvertImage](../../aspose.barcode.barcoderecognition/qualitysettings/allowinvertimage/) { get; set; } | 엔진이 반전 컬러 이미지를 추가 스캔으로 인식하도록 허용합니다. 바코드가 검정색 배경에 흰색일 때 사용할 수 있는 모드입니다. |
| [AllowMedianSmoothing](../../aspose.barcode.barcoderecognition/qualitysettings/allowmediansmoothing/) { get; set; } | 엔진이 추가 스캔으로 중앙값 스무딩을 활성화할 수 있습니다. 모드는 잡음이 있는 바코드를 인식하는 데 도움이 됩니다. |
| [AllowMicroWhiteSpotsRemoving](../../aspose.barcode.barcoderecognition/qualitysettings/allowmicrowhitespotsremoving/) { get; set; } | Postal 바코드용 엔진이 약간 노이즈가 있는 이미지를 인식할 수 있습니다. 모드는 약간 손상된 우편 바코드를 인식하는 데 도움이 됩니다. |
| [AllowOneDFastBarcodesDetector](../../aspose.barcode.barcoderecognition/qualitysettings/allowonedfastbarcodesdetector/) { get; set; } | 1D 바코드용 엔진은 거의 전체 이미지를 채우는 고품질 바코드를 빠르게 인식할 수 있습니다. 모드는 인터넷에서 생성된 바코드를 빠르게 인식하도록 도와줍니다. |
| [AllowOneDWipedBarsRestoration](../../aspose.barcode.barcoderecognition/qualitysettings/allowonedwipedbarsrestoration/) { get; set; } | 1D 바코드용 엔진이 패턴에 단일 와이핑/접착 막대가 있는 바코드를 인식할 수 있습니다. |
| [AllowQRMicroQrRestoration](../../aspose.barcode.barcoderecognition/qualitysettings/allowqrmicroqrrestoration/) { get; set; } | QR/MicroQR용 엔진이 손상된 MicroQR 바코드를 인식하도록 합니다. |
| [AllowRegularImage](../../aspose.barcode.barcoderecognition/qualitysettings/allowregularimage/) { get; set; } | 엔진이 복원이 없는 일반 이미지를 기본 스캔으로 인식할 수 있습니다. 이미지를 있는 그대로 인식하는 모드. |
| [AllowSaltAndPaperFiltering](../../aspose.barcode.barcoderecognition/qualitysettings/allowsaltandpaperfiltering/) { get; set; } | 엔진이 소금 및 종이 노이즈 유형의 바코드를 인식할 수 있습니다. 모드는 흰색과 검은색 점으로 작은 노이즈를 제거할 수 있습니다. |
| [AllowWhiteSpotsRemoving](../../aspose.barcode.barcoderecognition/qualitysettings/allowwhitespotsremoving/) { get; set; } | 엔진이 작은 흰색 점이 없는 이미지를 추가 스캔으로 인식할 수 있습니다. 모드는 중간 스무딩 필터링뿐만 아니라 노이즈 이미지를 인식하는 데 도움이 됩니다. |
| [CheckMore1DVariants](../../aspose.barcode.barcoderecognition/qualitysettings/checkmore1dvariants/) { get; set; } | 엔진이 더 많은 인식 변형을 확인하여 체크섬이 있는 1D 바코드를 인식할 수 있습니다. 기본값: False. |
| [DetectorSettings](../../aspose.barcode.barcoderecognition/qualitysettings/detectorsettings/) { get; set; } | 바코드 감지기 설정. |
| [FastScanOnly](../../aspose.barcode.barcoderecognition/qualitysettings/fastscanonly/) { get; set; } | 1D 바코드용 엔진은 이미지의 중간 조각을 빠르게 인식하고 시간 소모적인 알고리즘을 사용하지 않고 결과를 반환할 수 있습니다. |
| [MedianSmoothingWindowSize](../../aspose.barcode.barcoderecognition/qualitysettings/mediansmoothingwindowsize/) { get; set; } | 중간 평활화를 위한 창 크기. 일반적인 값은 3 또는 4입니다. 기본값은 3입니다. AllowMedianSmoothing을 설정해야 합니다. |
| [ReadTinyBarcodes](../../aspose.barcode.barcoderecognition/qualitysettings/readtinybarcodes/) { get; set; } | 엔진이 큰 이미지에서 작은 바코드를 인식할 수 있습니다. 무시되는 경우[`AllowIncorrectBarcodes`](./allowincorrectbarcodes/) True로 설정됩니다. 기본값: False. |
| [UseOldBarcodeDetector](../../aspose.barcode.barcoderecognition/qualitysettings/useoldbarcodedetector/) { get; set; } | 이전 바코드 감지기로 전환합니다. |

### 예

이 샘플은 BarCodeReader 와 함께 QualitySettings를 사용하는 방법을 보여줍니다.

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Standard, DecodeType.Code128))
{
   //고성능 모드 설정
   reader.QualitySettings = QualitySettings.HighPerformance;
   foreach (BarCodeResult result in reader.ReadBarCodes())
      Console.WriteLine("BarCode CodeText: " + result.CodeText);
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Standard, DecodeType.Code128))
{
   //일반 품질 모드는 기본적으로 설정됩니다.
   foreach (BarCodeResult result in reader.ReadBarCodes())
      Console.WriteLine("BarCode CodeText: " + result.CodeText);
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Standard, DecodeType.Code128))
{
   //저속 인식으로 고품질 모드 설정 
   reader.QualitySettings = QualitySettings.HighQuality;
   foreach (BarCodeResult result in reader.ReadBarCodes())
      Console.WriteLine("BarCode CodeText: " + result.CodeText);
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Standard, DecodeType.Code128))
{
   //가능한 모든 바코드를 찾으려고 시도하는 최대 바코드 모드를 설정합니다. 가장 느린 인식 모드
   reader.QualitySettings = QualitySettings.MaxBarCodes;
   foreach (BarCodeResult result in reader.ReadBarCodes())
      Console.WriteLine("BarCode CodeText: " + result.CodeText);
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Standard, DecodeType.Code128))
{
   //고성능 모드 설정
   reader.QualitySettings = QualitySettings.HighPerformance;
   // 별도의 옵션 설정
   reader.QualitySettings.AllowMedianSmoothing = true;
   reader.QualitySettings.MedianSmoothingWindowSize = 5;
   foreach (BarCodeResult result in reader.ReadBarCodes())
      Console.WriteLine("BarCode CodeText: " + result.CodeText);
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Standard, DecodeType.Code128))
{
   //기본 모드는 NormalQuality입니다.
   // 별도의 옵션 설정
   reader.QualitySettings.AllowMedianSmoothing = true;
   reader.QualitySettings.MedianSmoothingWindowSize = 5;
   foreach (BarCodeResult result in reader.ReadBarCodes())
      Console.WriteLine("BarCode CodeText: " + result.CodeText);
}
[VB.NET]
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39Standard, DecodeType.Code128)
    '고성능 모드 설정
    reader.QualitySettings = QualitySettings.HighPerformance
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
    Next
End Using
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39Standard, DecodeType.Code128)
    '일반 품질 모드는 기본적으로 설정됩니다.
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
    Next
End Using
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39Standard, DecodeType.Code128)
    '저속 인식으로 고품질 모드 설정
    reader.QualitySettings = QualitySettings.HighQuality
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
    Next
End Using
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39Standard, DecodeType.Code128)
    '올바르지 않더라도 가능한 모든 바코드를 찾으려고 시도하는 최대 바코드 모드를 설정합니다. 가장 느린 인식 모드
    reader.QualitySettings = QualitySettings.MaxBarCodes
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
    Next
End Using
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39Standard, DecodeType.Code128)
   '고성능 모드 설정
   reader.QualitySettings = QualitySettings.HighPerformance
   '별도의 옵션 설정
   reader.QualitySettings.AllowMedianSmoothing = True
   reader.QualitySettings.MedianSmoothingWindowSize = 5
   For Each result As BarCodeResult In reader.ReadBarCodes()
       Console.WriteLine("BarCode Type: " + result.CodeTypeName)
   Next
End Using
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39Standard, DecodeType.Code128)
   '기본 모드는 NormalQuality입니다.
   '별도의 옵션 설정
   reader.QualitySettings.AllowMedianSmoothing = True
   reader.QualitySettings.MedianSmoothingWindowSize = 5
   For Each result As BarCodeResult In reader.ReadBarCodes()
       Console.WriteLine("BarCode Type: " + result.CodeTypeName)
   Next
End Using
```

### 또한보십시오

* 네임스페이스 [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* 집회 [Aspose.BarCode](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->
