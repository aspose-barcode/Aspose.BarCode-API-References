---
title: "메서드"
linktitle: "get_HighQuality"
second_title: "Aspose.BarCode for C++ API 레퍼런스"
description: " method. HighQuality 인식 품질 사전 설정. 이 사전 설정은 저품질 바코드를 위해 개발되었습니다. C++에서 심하게 손상된 바코드를 감지할 수 있습니다."
type: docs
weight: 300
url: /ko/cpp/aspose.barcode.barcoderecognition/qualitysettings/get_highquality/
---
## QualitySettings::get_HighQuality method


HighQuality 인식 품질 프리셋. 이 프리셋은 저품질 바코드를 위해 개발되었습니다. 심하게 손상된 바코드를 감지할 수 있습니다.

```cpp
static System::SharedPtr<QualitySettings> Aspose::BarCode::BarCodeRecognition::QualitySettings::get_HighQuality()
```

## 비고


이 샘플은 HighQuality 모드를 사용하는 방법을 보여줍니다.
```cpp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings = QualitySettings.HighQuality;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```


HighQuality 인식 품질 사전 설정.
## 또 보기

* Class [QualitySettings](../)
* Class [QualitySettings](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
