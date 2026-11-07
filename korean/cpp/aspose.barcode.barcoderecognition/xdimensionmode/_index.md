---
title: "enum"
linktitle: "XDimensionMode"
second_title: "Aspose.BarCode for C++ API 레퍼런스"
description: "C++에서 enum을 사용하는 방법."
type: docs
weight: 4000
url: /ko/cpp/aspose.barcode.barcoderecognition/xdimensionmode/
---
## XDimensionMode enum




```cpp
enum class XDimensionMode
```

### 값

| 이름 | 값 | 설명 |
| --- | --- | --- |
| 자동 | 0 | XDimension 값은 AI(SVM)로 감지됩니다. 현재는 Normal과 동일합니다. |
| Small | 1 | BarcodeQuality의 품질로 1픽셀 이상 작은 XDimension을 가진 바코드를 감지합니다 |
| Normal | 2 | BarcodeQuality 또는 고품질 바코드의 품질로 2픽셀 이상 고전적인 XDimension을 가진 바코드를 감지합니다 |
| Large | 3 | 고해상도 카메라로 촬영된 BarcodeQuality의 품질로 큰 XDimension을 가진 바코드를 감지합니다 |
| UseMinimalXDimension | 4 | MinimalXDimension에 설정된 크기로부터 바코드를 감지하고 BarcodeQuality의 품질을 사용합니다 |

## 비고


[Recognition](../../aspose.barcode.barcoderecognition.recognition/) mode which sets size (from 1 to infinity) of barcode minimal element: matrix cell or bar. 

이 샘플은 XDimension 모드를 사용하는 방법을 보여줍니다
```cpp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings.XDimension = XDimensionMode.Small;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```

## 또 보기

* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
