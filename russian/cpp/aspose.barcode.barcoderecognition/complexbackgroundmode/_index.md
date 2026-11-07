---
title: "enum"
linktitle: "ComplexBackgroundMode"
second_title: "Aspose.BarCode для C++ справочник API"
description: "Как использовать enum в C++."
type: docs
weight: 3700
url: /ru/cpp/aspose.barcode.barcoderecognition/complexbackgroundmode/
---
## ComplexBackgroundMode enum




```cpp
enum class ComplexBackgroundMode
```

### Значения

| Имя | Значение | Описание |
| --- | --- | --- |
| Авто | 0 | В настоящее время то же, что и Disabled. Отключает дополнительное распознавание цветных штрихкодов на цветных изображениях. |
| Отключено | 1 | Отключает дополнительное распознавание цветных штрихкодов на цветных изображениях. |
| Включено | 2 | Включает дополнительное распознавание цветных штрихкодов на цветных изображениях. |

## Примечания


Режим, который включает или отключает дополнительное распознавание цветных штрихкодов на цветных изображениях.

Этот пример показывает, как использовать режим ComplexBackground
```cpp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings.ComplexBackground = ComplexBackgroundMode.Enabled;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```

## См. также

* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
