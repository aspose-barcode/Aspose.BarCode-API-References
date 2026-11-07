---
title: "method"
linktitle: "get_NormalQuality"
second_title: "Aspose.BarCode для C++ справочник API"
description: " метод. Предустановленный уровень качества распознавания NormalQuality. Подходит для большинства штрих‑кодов в C++."
type: docs
weight: 200
url: /ru/cpp/aspose.barcode.barcoderecognition/qualitysettings/get_normalquality/
---
## QualitySettings::get_NormalQuality method


Предустановка качества распознавания NormalQuality. Подходит для большинства штрихкодов.

```cpp
static System::SharedPtr<QualitySettings> Aspose::BarCode::BarCodeRecognition::QualitySettings::get_NormalQuality()
```

## Примечания


Этот пример показывает, как использовать режим NormalQuality
```cpp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings = QualitySettings.NormalQuality;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```


Набор предустановок качества распознавания NormalQuality.
## См. также

* Class [QualitySettings](../)
* Class [QualitySettings](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
