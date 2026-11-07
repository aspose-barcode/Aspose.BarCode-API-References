---
title: "method"
linktitle: "get_HighQuality"
second_title: "Aspose.BarCode для C++ справочник API"
description: " метод. Предустановка качества распознавания HighQuality. Эта предустановка разработана для штрихкодов низкого качества. Позволяет обнаруживать сильно повреждённые штрихкоды в C++."
type: docs
weight: 300
url: /ru/cpp/aspose.barcode.barcoderecognition/qualitysettings/get_highquality/
---
## QualitySettings::get_HighQuality method


Предустановка качества распознавания HighQuality. Эта предустановка разработана для штрихкодов низкого качества. Позволяет обнаруживать сильно повреждённые штрихкоды.

```cpp
static System::SharedPtr<QualitySettings> Aspose::BarCode::BarCodeRecognition::QualitySettings::get_HighQuality()
```

## Примечания


Этот пример показывает, как использовать режим HighQuality
```cpp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings = QualitySettings.HighQuality;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```


Предустановка качества распознавания HighQuality.
## См. также

* Class [QualitySettings](../)
* Class [QualitySettings](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
