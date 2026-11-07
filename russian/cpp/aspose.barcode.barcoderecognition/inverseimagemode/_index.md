---
title: "enum"
linktitle: "InverseImageMode"
second_title: "Aspose.BarCode для C++ справочник API"
description: "Как использовать enum в C++."
type: docs
weight: 3900
url: /ru/cpp/aspose.barcode.barcoderecognition/inverseimagemode/
---
## InverseImageMode enum




```cpp
enum class InverseImageMode
```

### Значения

| Имя | Значение | Описание |
| --- | --- | --- |
| Auto | 0 | Отключает дополнительное распознавание штрихкодов на инвертированных изображениях для всех типов штрихкодов, кроме [QR](../../aspose.barcode.barcoderecognition.qr/) кода. |
| Отключено | 1 | Отключает дополнительное распознавание штрихкодов на инвертированных изображениях. |
| Включено | 2 | Включает дополнительное распознавание штрихкодов на инвертированных изображениях |

## Примечания


Режим, который включает или отключает дополнительное распознавание штрихкодов на изображениях с инвертированными цветами (яркостью).

Этот пример показывает, как использовать режим InverseImage
```cpp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings.InverseImage = InverseImageMode.Enabled;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```

## См. также

* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
