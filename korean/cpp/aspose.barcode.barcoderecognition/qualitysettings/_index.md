---
title: "Aspose::BarCode::BarCodeRecognition::QualitySettings 클래스"
linktitle: "QualitySettings"
second_title: "Aspose.BarCode for C++ API 레퍼런스"
description: "Aspose::BarCode::BarCodeRecognition::QualitySettings 클래스. QualitySettings는 인식 품질과 속도를 수동으로 구성할 수 있게 합니다. 내장 프리셋인 HighPerformance, NormalQuality, HighQuality, MaxQuality를 사용하여 빠르게 설정하거나 개별 옵션을 수동으로 구성할 수 있습니다. C++에서 QualitySettings의 기본값은 NormalQuality입니다."
type: docs
weight: 3100
url: /ko/cpp/aspose.barcode.barcoderecognition/qualitysettings/
---
## QualitySettings class


[QualitySettings](./) allows to configure recognition quality and speed manually. You can quickly set up [QualitySettings](./) with embedded presets: HighPerformance, NormalQuality, HighQuality, MaxQuality or you can manually configure separate options. Default value of [QualitySettings](./) is NormalQuality.

```cpp
class QualitySettings : public System::Object
```

## 메서드

| 메서드 | 설명 |
| --- | --- |
| [get_AllowIncorrectBarcodes](./get_allowincorrectbarcodes/)() const | 엔진이 체크섬이 잘못되었거나 값이 올바르지 않은 바코드를 인식하도록 허용합니다. 이 모드는 텍스트가 올바르지 않은 손상된 바코드를 인식하는 데 사용할 수 있습니다. |
| [get_BarcodeQuality](./get_barcodequality/)() const | 선택된 품질로 바코드 요소를 인식하는 방법을 활성화하는 모드입니다. 품질이 낮은 바코드 요소는 더 많은 복잡한 방법이 필요하여 인식 속도가 느려집니다. |
| [get_ComplexBackground](./get_complexbackground/)() const | 컬러 이미지에서 컬러 바코드의 추가 인식을 활성화하거나 비활성화하는 모드입니다. |
| [get_Deconvolution](./get_deconvolution/)() const | 이미지 손상 정도를 정의하는 디컨볼루션(이미지 복원) 모드입니다. 원래 디컨볼루션은 카메라로 이미지를 촬영할 때 블러와 같은 자연 함수에 의해 손상(컨볼루션)된 이미지를 복원할 수 있는 기능입니다. 이미지 손상을 일으키는 함수를 감지할 수 없기 때문에, 샤프하거나 수학적 형태학과 같은 잘 알려진 함수를 확인해야 합니다. |
| static [get_HighPerformance](./get_highperformance/)() | HighPerformance 인식 품질 프리셋. 이 모드에서는 고품질 바코드를 잘 인식합니다. |
| static [get_HighQuality](./get_highquality/)() | HighQuality 인식 품질 프리셋. 이 프리셋은 저품질 바코드를 위해 개발되었습니다. 심하게 손상된 바코드를 감지할 수 있습니다. |
| [get_InverseImage](./get_inverseimage/)() const | 색상(휘도)이 반전된 이미지에서 바코드의 추가 인식을 활성화하거나 비활성화하는 모드입니다. |
| static [get_MaxQuality](./get_maxquality/)() | MaxQuality 인식 품질 프리셋. 이 프리셋은 가능한 모든 바코드를, 심지어 잘못된 바코드까지 인식하도록 개발되었습니다. |
| [get_MinimalXDimension](./get_minimalxdimension/)() const | UseMinimalXDimension과 함께 사용되는 XDimension의 최소 크기(픽셀)입니다. |
| static [get_NormalQuality](./get_normalquality/)() | NormalQuality 인식 품질 프리셋. 대부분의 바코드에 적합합니다. |
| [get_XDimension](./get_xdimension/)() const | [Recognition](../../aspose.barcode.barcoderecognition.recognition/) 모드는 바코드 최소 요소(매트릭스 셀 또는 바)의 크기(1부터 무한대까지)를 설정합니다. |
| [set_AllowIncorrectBarcodes](./set_allowincorrectbarcodes/)(bool) | 엔진이 체크섬이 잘못되었거나 값이 올바르지 않은 바코드를 인식하도록 허용합니다. 이 모드는 텍스트가 올바르지 않은 손상된 바코드를 인식하는 데 사용할 수 있습니다. |
| [set_BarcodeQuality](./set_barcodequality/)(BarcodeQualityMode) | 선택된 품질로 바코드 요소를 인식하는 방법을 활성화하는 모드입니다. 품질이 낮은 바코드 요소는 더 많은 복잡한 방법이 필요하여 인식 속도가 느려집니다. |
| [set_ComplexBackground](./set_complexbackground/)(ComplexBackgroundMode) | 컬러 이미지에서 컬러 바코드의 추가 인식을 활성화하거나 비활성화하는 모드입니다. |
| [set_Deconvolution](./set_deconvolution/)(DeconvolutionMode) | 이미지 손상 정도를 정의하는 디컨볼루션(이미지 복원) 모드입니다. 원래 디컨볼루션은 카메라로 이미지를 촬영할 때 블러와 같은 자연 함수에 의해 손상(컨볼루션)된 이미지를 복원할 수 있는 기능입니다. 이미지 손상을 일으키는 함수를 감지할 수 없기 때문에, 샤프하거나 수학적 형태학과 같은 잘 알려진 함수를 확인해야 합니다. |
| [set_InverseImage](./set_inverseimage/)(InverseImageMode) | 색상(휘도)이 반전된 이미지에서 바코드의 추가 인식을 활성화하거나 비활성화하는 모드입니다. |
| [set_MinimalXDimension](./set_minimalxdimension/)(float) | UseMinimalXDimension과 함께 사용되는 XDimension의 최소 크기(픽셀)입니다. |
| [set_XDimension](./set_xdimension/)(XDimensionMode) | [Recognition](../../aspose.barcode.barcoderecognition.recognition/) 모드는 바코드 최소 요소(매트릭스 셀 또는 바)의 크기(1부터 무한대까지)를 설정합니다. |
## 비고


이 샘플은 [QualitySettings](./)을 [BarCodeReader](../barcodereader/)와 함께 사용하는 방법을 보여줍니다.
```cpp
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

//소형 바코드에 대한 HighPerformance 인식 모드 설정
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

## 또 보기

* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
