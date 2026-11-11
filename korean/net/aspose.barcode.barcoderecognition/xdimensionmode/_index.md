---
title: "열거형 XDimensionMode"
second_title: "Aspose.BarCode for .NET API 참조"
description: "Aspose.BarCode.BarCodeRecognition.XDimensionMode 열거형. 바코드 최소 요소 매트릭스 셀 또는 바의 크기를 1부터 무한대까지 설정하는 인식 모드"
type: docs
weight: 400
url: /ko/net/aspose.barcode.barcoderecognition/xdimensionmode/
---
## XDimensionMode enumeration

바코드 최소 요소(매트릭스 셀 또는 바)의 크기(1부터 무한대까지)를 설정하는 인식 모드입니다.

```csharp
public enum XDimensionMode
```

### 값

| 이름 | 값 | 설명 |
| --- | --- | --- |
| Auto | `0` | XDimension 값은 AI(SVM)로 감지됩니다. 현재는 Normal과 동일합니다. |
| Small | `1` | BarcodeQuality에서 제공되는 품질로 1픽셀 이상 작은 XDimension을 가진 바코드를 감지합니다. |
| Normal | `2` | BarcodeQuality 또는 고품질 바코드에서 제공되는 품질로 2픽셀 이상 클래식 XDimension을 가진 바코드를 감지합니다. |
| Large | `3` | 고해상도 카메라로 캡처된 BarcodeQuality 품질을 사용하여 큰 XDimension을 가진 바코드를 감지합니다. |
| UseMinimalXDimension | `4` | MinimalXDimension에 설정된 크기와 BarcodeQuality 품질을 사용하여 바코드를 감지합니다. |

## 예제

이 샘플은 XDimension 모드를 사용하는 방법을 보여줍니다.

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings.XDimension = XDimensionMode.Small;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```

### 또 보기

* namespace [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../)


