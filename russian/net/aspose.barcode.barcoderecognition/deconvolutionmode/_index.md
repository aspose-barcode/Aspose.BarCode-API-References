---
title: "Перечисление DeconvolutionMode"
second_title: "Справочник API Aspose.BarCode для .NET"
description: "Перечисление Aspose.BarCode.BarCodeRecognition.DeconvolutionMode. Режим деконволюции восстановления изображения, определяющий степень деградации изображения. Изначально деконволюция — это функция, способная восстановить изображение, ухудшенное (свёрнутое) любой естественной функцией, такой как размытие, при получении изображения камерой. Поскольку мы не можем определить функцию, испортившую изображение, нам приходится проверять наиболее известные функции, такие как резкость или математическая морфология."
type: docs
weight: 240
url: /ru/net/aspose.barcode.barcoderecognition/deconvolutionmode/
---
## DeconvolutionMode enumeration

Режим деконволюции (восстановление изображения), определяющий степень деградации изображения. Изначально деконволюция — это функция, способная восстановить изображение, ухудшенное (свёрнутое) любой естественной функцией, такой как размытие, при получении изображения камерой. Поскольку мы не можем определить функцию, испортившую изображение, нам приходится проверять наиболее известные функции, такие как резкость или математическая морфология.

```csharp
public enum DeconvolutionMode
```

### Значения

| Имя | Значение | Описание |
| --- | --- | --- |
| Fast | `0` | Включает быстрые методы деконволюции для изображений высокого качества. |
| Normal | `1` | Включает обычные методы деконволюции для обычных изображений. |
| Slow | `2` | Включает медленные методы деконволюции для изображений низкого качества. |

## Примеры

Этот пример показывает, как использовать режим Deconvolution

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings.Deconvolution = DeconvolutionMode.Slow;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```

### См. также

* namespace [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../)


