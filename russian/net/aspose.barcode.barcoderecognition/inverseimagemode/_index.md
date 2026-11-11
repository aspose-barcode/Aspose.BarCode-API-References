---
title: "Перечисление InverseImageMode"
second_title: "Справочник API Aspose.BarCode для .NET"
description: "Перечисление Aspose.BarCode.BarCodeRecognition.InverseImageMode. Режим, который включает или отключает дополнительное распознавание штрих‑кодов на изображениях с инвертированной яркостью цветов"
type: docs
weight: 270
url: /ru/net/aspose.barcode.barcoderecognition/inverseimagemode/
---
## InverseImageMode enumeration

Режим, который включает или отключает дополнительное распознавание штрих‑кодов на изображениях с инвертированными цветами (яркость).

```csharp
public enum InverseImageMode
```

### Значения

| Имя | Значение | Описание |
| --- | --- | --- |
| Auto | `0` | Отключает дополнительное распознавание штрих‑кодов на инвертированных изображениях для всех типов штрих‑кодов, кроме QR Code. |
| Disabled | `1` | Отключает дополнительное распознавание штрих‑кодов на инвертированных изображениях. |
| Enabled | `2` | Включает дополнительное распознавание штрих‑кодов на инвертированных изображениях |

## Примеры

Этот пример показывает, как использовать режим InverseImage

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings.InverseImage = InverseImageMode.Enabled;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```

### См. также

* namespace [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../)


