---
title: "enum"
linktitle: "BarcodeQualityMode"
second_title: "Aspose.BarCode for C++ API 레퍼런스"
description: "C++에서 enum을 사용하는 방법."
type: docs
weight: 3600
url: /ko/cpp/aspose.barcode.barcoderecognition/barcodequalitymode/
---
## BarcodeQualityMode enum




```cpp
enum class BarcodeQualityMode
```

### 값

| 이름 | 값 | 설명 |
| --- | --- | --- |
| High | 0 | 고품질 바코드에 대한 인식 방법을 활성화합니다. |
| Normal | 1 | 일반(보통) 품질 바코드에 대한 인식 방법을 활성화합니다. |
| Low | 2 | 저품질 바코드에 대한 인식 방법을 활성화합니다. |

## 비고


선택된 품질로 바코드 요소를 인식하는 방법을 활성화하는 모드입니다. 품질이 낮은 바코드 요소는 더 많은 복잡한 방법이 필요하여 인식 속도가 느려집니다.

이 샘플은 BarcodeQuality 모드를 사용하는 방법을 보여줍니다
```cpp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings.BarcodeQuality = BarcodeQualityMode.Low;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```

## 또 보기

* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
