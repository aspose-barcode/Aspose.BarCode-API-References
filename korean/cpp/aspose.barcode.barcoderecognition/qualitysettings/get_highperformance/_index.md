---
title: "메서드"
linktitle: "get_HighPerformance"
second_title: "Aspose.BarCode for C++ API 레퍼런스"
description: " method. HighPerformance 인식 품질 프리셋입니다. 이 모드에서는 고품질 바코드가 잘 인식됩니다 C++."
type: docs
weight: 100
url: /ko/cpp/aspose.barcode.barcoderecognition/qualitysettings/get_highperformance/
---
## QualitySettings::get_HighPerformance method


HighPerformance 인식 품질 프리셋. 이 모드에서는 고품질 바코드를 잘 인식합니다.

```cpp
static System::SharedPtr<QualitySettings> Aspose::BarCode::BarCodeRecognition::QualitySettings::get_HighPerformance()
```

## 비고


이 샘플은 HighPerformance 모드를 사용하는 방법을 보여줍니다.
```cpp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings = QualitySettings.HighPerformance;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```


HighPerformance 인식 품질 프리셋.
## 또 보기

* Class [QualitySettings](../)
* Class [QualitySettings](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
