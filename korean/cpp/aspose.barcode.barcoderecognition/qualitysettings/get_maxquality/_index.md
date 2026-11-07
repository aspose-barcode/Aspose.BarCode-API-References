---
title: "메서드"
linktitle: "get_MaxQuality"
second_title: "Aspose.BarCode for C++ API 레퍼런스"
description: " method. MaxQuality 인식 품질 사전 설정. 이 사전 설정은 C++에서 가능한 모든 바코드, 심지어 잘못된 바코드까지 인식하도록 개발되었습니다."
type: docs
weight: 400
url: /ko/cpp/aspose.barcode.barcoderecognition/qualitysettings/get_maxquality/
---
## QualitySettings::get_MaxQuality method


MaxQuality 인식 품질 프리셋. 이 프리셋은 가능한 모든 바코드를, 심지어 잘못된 바코드까지 인식하도록 개발되었습니다.

```cpp
static System::SharedPtr<QualitySettings> Aspose::BarCode::BarCodeRecognition::QualitySettings::get_MaxQuality()
```

## 비고


이 샘플은 MaxQuality 모드를 사용하는 방법을 보여줍니다.
```cpp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings = QualitySettings.MaxQuality;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```


MaxQuality 인식 품질 사전 설정.
## 또 보기

* Class [QualitySettings](../)
* Class [QualitySettings](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
