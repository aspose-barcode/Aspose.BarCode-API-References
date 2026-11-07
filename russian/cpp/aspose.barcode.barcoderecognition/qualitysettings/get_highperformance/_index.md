---
title: "method"
linktitle: "get_HighPerformance"
second_title: "Aspose.BarCode для C++ справочник API"
description: " метод. Предустановка качества распознавания HighPerformance. Штрих‑коды высокого качества хорошо распознаются в этом режиме в C++."
type: docs
weight: 100
url: /ru/cpp/aspose.barcode.barcoderecognition/qualitysettings/get_highperformance/
---
## QualitySettings::get_HighPerformance method


Предустановка качества распознавания HighPerformance. Штрихкоды высокого качества хорошо распознаются в этом режиме.

```cpp
static System::SharedPtr<QualitySettings> Aspose::BarCode::BarCodeRecognition::QualitySettings::get_HighPerformance()
```

## Примечания


Этот пример показывает, как использовать режим HighPerformance
```cpp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings = QualitySettings.HighPerformance;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```


Предустановка качества распознавания HighPerformance.
## См. также

* Class [QualitySettings](../)
* Class [QualitySettings](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
