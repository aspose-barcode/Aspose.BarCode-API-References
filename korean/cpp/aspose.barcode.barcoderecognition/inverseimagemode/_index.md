---
title: "enum"
linktitle: "InverseImageMode"
second_title: "Aspose.BarCode for C++ API 레퍼런스"
description: "C++에서 enum을 사용하는 방법."
type: docs
weight: 3900
url: /ko/cpp/aspose.barcode.barcoderecognition/inverseimagemode/
---
## InverseImageMode enum




```cpp
enum class InverseImageMode
```

### 값

| 이름 | 값 | 설명 |
| --- | --- | --- |
| Auto | 0 | 역 이미지에서 모든 바코드 유형에 대해 [QR](../../aspose.barcode.barcoderecognition.qr/) 코드를 제외하고 바코드 추가 인식을 비활성화합니다. |
| 비활성화 | 1 | 역 이미지에서 바코드 추가 인식을 비활성화합니다. |
| 활성화 | 2 | 역 이미지에서 바코드 추가 인식을 활성화합니다. |

## 비고


색상(휘도)이 반전된 이미지에서 바코드의 추가 인식을 활성화하거나 비활성화하는 모드입니다.

이 샘플은 InverseImage 모드를 사용하는 방법을 보여줍니다.
```cpp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings.InverseImage = InverseImageMode.Enabled;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```

## 또 보기

* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
