---
title: "enum"
linktitle: "BarcodeQualityMode"
second_title: "Aspose.BarCode для C++ справочник API"
description: "Как использовать enum в C++."
type: docs
weight: 3600
url: /ru/cpp/aspose.barcode.barcoderecognition/barcodequalitymode/
---
## BarcodeQualityMode enum




```cpp
enum class BarcodeQualityMode
```

### Значения

| Имя | Значение | Описание |
| --- | --- | --- |
| High | 0 | Включает методы распознавания для штрихкодов высокого качества. |
| Normal | 1 | Включает методы распознавания для штрихкодов обычного (Normal) качества. |
| Low | 2 | Включает методы распознавания для штрихкодов низкого качества. |

## Примечания


Режим, который включает методы распознавания элементов штрихкода с выбранным качеством. Элемент штрихкода более низкого качества требует более сложных методов, что замедляет распознавание.

Этот пример показывает, как использовать режим BarcodeQuality
```cpp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings.BarcodeQuality = BarcodeQualityMode.Low;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```

## См. также

* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
