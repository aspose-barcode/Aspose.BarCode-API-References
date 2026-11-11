---
title: "Перечисление XDimensionMode"
second_title: "Справочник API Aspose.BarCode для .NET"
description: "Перечисление Aspose.BarCode.BarCodeRecognition.XDimensionMode. Режим распознавания, который задает размер от 1 до бесконечности минимального элемента штрихкода: ячейки матрицы или полосы"
type: docs
weight: 400
url: /ru/net/aspose.barcode.barcoderecognition/xdimensionmode/
---
## XDimensionMode enumeration

Режим распознавания, который задает размер (от 1 до бесконечности) минимального элемента штрихкода: ячейка матрицы или полоса.

```csharp
public enum XDimensionMode
```

### Значения

| Имя | Значение | Описание |
| --- | --- | --- |
| Auto | `0` | Значение XDimension определяется ИИ (SVM). В настоящее время оно совпадает с Normal |
| Small | `1` | Обнаруживает штрихкоды с небольшим XDimension в 1 пиксель и более, с качеством из BarcodeQuality |
| Normal | `2` | Обнаруживает штрихкоды с классическим XDimension в 2 пикселя и более, с качеством из BarcodeQuality или штрихкоды высокого качества. |
| Large | `3` | Обнаруживает штрихкоды с большим XDimension, с качеством из BarcodeQuality, снятые камерами высокого разрешения. |
| UseMinimalXDimension | `4` | Обнаруживает штрихкоды с размером, установленным в MinimalXDimension, с качеством из BarcodeQuality |

## Примеры

Этот пример показывает, как использовать режим XDimension

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings.XDimension = XDimensionMode.Small;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```

### См. также

* namespace [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../)


