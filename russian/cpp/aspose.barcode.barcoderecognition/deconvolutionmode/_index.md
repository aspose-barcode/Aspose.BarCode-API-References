---
title: "enum"
linktitle: "DeconvolutionMode"
second_title: "Aspose.BarCode для C++ справочник API"
description: "Как использовать enum в C++."
type: docs
weight: 3800
url: /ru/cpp/aspose.barcode.barcoderecognition/deconvolutionmode/
---
## DeconvolutionMode enum




```cpp
enum class DeconvolutionMode
```

### Значения

| Имя | Значение | Описание |
| --- | --- | --- |
| Быстро | 0 | Включает быстрые методы деконволюции для изображений высокого качества. |
| Normal | 1 | Включает обычные методы деконволюции для обычных изображений. |
| Медленно | 2 | Включает медленные методы деконволюции для изображений низкого качества. |

## Примечания


Режим деконволюции (восстановления изображений), определяющий уровень деградации изображения. Изначально деконволюция — это функция, способная восстановить изображение, искажённое (свёрнутое) любой естественной функцией, такой как размытие, при получении изображения камерой. Поскольку мы не можем определить функцию, испортившую изображение, нам приходится проверять наиболее известные функции, такие как резкость или математическая морфология.

Этот пример показывает, как использовать режим Deconvolution
```cpp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings.Deconvolution = DeconvolutionMode.Slow;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```

## См. также

* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
