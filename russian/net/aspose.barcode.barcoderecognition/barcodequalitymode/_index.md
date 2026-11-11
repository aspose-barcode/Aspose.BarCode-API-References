---
title: "Перечисление BarcodeQualityMode"
second_title: "Справочник API Aspose.BarCode для .NET"
description: "Перечисление Aspose.BarCode.BarCodeRecognition.BarcodeQualityMode. Режим, который позволяет методам распознавать элементы штрих‑кода с выбранным качеством. Элемент штрих‑кода с более низким качеством требует более сложных методов, что замедляет распознавание"
type: docs
weight: 110
url: /ru/net/aspose.barcode.barcoderecognition/barcodequalitymode/
---
## BarcodeQualityMode enumeration

Режим, который позволяет методам распознавать элементы штрих‑кода с выбранным качеством. Элемент штрих‑кода с более низким качеством требует более сложных методов, что замедляет распознавание.

```csharp
public enum BarcodeQualityMode
```

### Значения

| Имя | Значение | Описание |
| --- | --- | --- |
| High | `0` | Включает методы распознавания для штрих‑кодов высокого качества. |
| Normal | `1` | Включает методы распознавания для штрих‑кодов обычного (нормального) качества. |
| Low | `2` | Включает методы распознавания для штрих‑кодов низкого качества. |

## Примеры

Этот пример показывает, как использовать режим BarcodeQuality

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings.BarcodeQuality = BarcodeQualityMode.Low;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```

### См. также

* namespace [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../)


