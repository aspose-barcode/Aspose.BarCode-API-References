---
title: "Перечисление ComplexBackgroundMode"
second_title: "Справочник API Aspose.BarCode для .NET"
description: "Перечисление Aspose.BarCode.BarCodeRecognition.ComplexBackgroundMode. Режим, который включает или отключает дополнительное распознавание цветных штрихкодов на цветных изображениях"
type: docs
weight: 200
url: /ru/net/aspose.barcode.barcoderecognition/complexbackgroundmode/
---
## ComplexBackgroundMode enumeration

Режим, который включает или отключает дополнительное распознавание цветных штрихкодов на цветных изображениях.

```csharp
public enum ComplexBackgroundMode
```

### Значения

| Имя | Значение | Описание |
| --- | --- | --- |
| Auto | `0` | В настоящее время то же, что и Disabled. Отключает дополнительное распознавание цветных штрихкодов на цветных изображениях. |
| Disabled | `1` | Отключает дополнительное распознавание цветных штрихкодов на цветных изображениях. |
| Enabled | `2` | Включает дополнительное распознавание цветных штрихкодов на цветных изображениях. |

## Примеры

Этот пример показывает, как использовать режим ComplexBackground

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings.ComplexBackground = ComplexBackgroundMode.Enabled;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```

### См. также

* namespace [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../)


