---
title: "enum"
linktitle: "ComplexBackgroundMode"
second_title: "Aspose.BarCode for C++ API 레퍼런스"
description: "C++에서 enum을 사용하는 방법."
type: docs
weight: 3700
url: /ko/cpp/aspose.barcode.barcoderecognition/complexbackgroundmode/
---
## ComplexBackgroundMode enum




```cpp
enum class ComplexBackgroundMode
```

### 값

| 이름 | 값 | 설명 |
| --- | --- | --- |
| 자동 | 0 | 현재는 Disabled와 동일합니다. 컬러 이미지에서 컬러 바코드의 추가 인식을 비활성화합니다. |
| 비활성화 | 1 | 컬러 이미지에서 컬러 바코드의 추가 인식을 비활성화합니다. |
| 활성화 | 2 | 컬러 이미지에서 컬러 바코드의 추가 인식을 활성화합니다. |

## 비고


컬러 이미지에서 컬러 바코드의 추가 인식을 활성화하거나 비활성화하는 모드입니다.

이 샘플은 ComplexBackground 모드를 사용하는 방법을 보여줍니다.
```cpp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings.ComplexBackground = ComplexBackgroundMode.Enabled;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```

## 또 보기

* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
