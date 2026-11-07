---
title: "enum"
linktitle: "XDimensionMode"
second_title: "Aspose.BarCode для C++ справочник API"
description: "Как использовать enum в C++."
type: docs
weight: 4000
url: /ru/cpp/aspose.barcode.barcoderecognition/xdimensionmode/
---
## XDimensionMode enum




```cpp
enum class XDimensionMode
```

### Значения

| Имя | Значение | Описание |
| --- | --- | --- |
| Авто | 0 | Значение XDimension определяется ИИ (SVM). В данный момент оно такое же, как Normal |
| Small | 1 | Обнаруживает штрихкоды с небольшим XDimension от 1 пикселя и более, качество берётся из BarcodeQuality |
| Normal | 2 | Обнаруживает штрихкоды с классическим XDimension от 2 пикселей и более, качество берётся из BarcodeQuality или высококачественных штрихкодов. |
| Large | 3 | Обнаруживает штрихкоды с большим XDimension, качество берётся из BarcodeQuality, полученное с помощью камер высокого разрешения. |
| UseMinimalXDimension | 4 | Обнаруживает штрихкоды размера, установленного в MinimalXDimension, с качеством из BarcodeQuality |

## Примечания


[Recognition](../../aspose.barcode.barcoderecognition.recognition/) mode which sets size (from 1 to infinity) of barcode minimal element: matrix cell or bar. 

Этот пример показывает, как использовать режим XDimension
```cpp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings.XDimension = XDimensionMode.Small;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```

## См. также

* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
