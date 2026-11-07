---
title: "메서드"
linktitle: "get_NormalQuality"
second_title: "Aspose.BarCode for C++ API 레퍼런스"
description: " 메서드. NormalQuality 인식 품질 사전 설정. C++에서 대부분의 바코드에 적합합니다."
type: docs
weight: 200
url: /ko/cpp/aspose.barcode.barcoderecognition/qualitysettings/get_normalquality/
---
## QualitySettings::get_NormalQuality method


NormalQuality 인식 품질 프리셋. 대부분의 바코드에 적합합니다.

```cpp
static System::SharedPtr<QualitySettings> Aspose::BarCode::BarCodeRecognition::QualitySettings::get_NormalQuality()
```

## 비고


이 샘플은 NormalQuality 모드를 사용하는 방법을 보여줍니다.
```cpp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings = QualitySettings.NormalQuality;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```


NormalQuality 인식 품질 사전 설정.
## 또 보기

* Class [QualitySettings](../)
* Class [QualitySettings](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
