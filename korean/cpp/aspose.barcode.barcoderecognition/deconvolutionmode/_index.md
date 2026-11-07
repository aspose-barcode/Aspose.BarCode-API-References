---
title: "enum"
linktitle: "DeconvolutionMode"
second_title: "Aspose.BarCode for C++ API 레퍼런스"
description: "C++에서 enum을 사용하는 방법."
type: docs
weight: 3800
url: /ko/cpp/aspose.barcode.barcoderecognition/deconvolutionmode/
---
## DeconvolutionMode enum




```cpp
enum class DeconvolutionMode
```

### 값

| 이름 | 값 | 설명 |
| --- | --- | --- |
| 빠른 | 0 | 고품질 이미지에 대해 빠른 디컨볼루션 방법을 활성화합니다. |
| Normal | 1 | 일반 이미지에 대해 보통 디컨볼루션 방법을 활성화합니다. |
| 느린 | 2 | 저품질 이미지에 대해 느린 디컨볼루션 방법을 활성화합니다. |

## 비고


이미지 손상 정도를 정의하는 디컨볼루션(이미지 복원) 모드입니다. 원래 디컨볼루션은 카메라로 이미지를 촬영할 때 블러와 같은 자연 함수에 의해 손상(컨볼루션)된 이미지를 복원할 수 있는 기능입니다. 이미지 손상을 일으키는 함수를 감지할 수 없기 때문에, 샤프하거나 수학적 형태학과 같은 잘 알려진 함수를 확인해야 합니다.

이 샘플은 Deconvolution 모드를 사용하는 방법을 보여줍니다.
```cpp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings.Deconvolution = DeconvolutionMode.Slow;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```

## 또 보기

* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
