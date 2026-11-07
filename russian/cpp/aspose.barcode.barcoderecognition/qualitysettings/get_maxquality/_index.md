---
title: "method"
linktitle: "get_MaxQuality"
second_title: "Aspose.BarCode для C++ справочник API"
description: " метод. Предустановка качества распознавания MaxQuality. Эта предустановка разработана для распознавания всех возможных штрихкодов, даже некорректных, в C++."
type: docs
weight: 400
url: /ru/cpp/aspose.barcode.barcoderecognition/qualitysettings/get_maxquality/
---
## QualitySettings::get_MaxQuality method


Предустановка качества распознавания MaxQuality. Эта предустановка разработана для распознавания всех возможных штрихкодов, даже некорректных штрихкодов.

```cpp
static System::SharedPtr<QualitySettings> Aspose::BarCode::BarCodeRecognition::QualitySettings::get_MaxQuality()
```

## Примечания


Этот пример показывает, как использовать режим MaxQuality
```cpp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings = QualitySettings.MaxQuality;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```


Предустановка качества распознавания MaxQuality.
## См. также

* Class [QualitySettings](../)
* Class [QualitySettings](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
