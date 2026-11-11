---
title: "QualitySettings.MaxQuality"
second_title: "Справочник API Aspose.BarCode для .NET"
description: "Свойство QualitySettings. Предустановка качества распознавания MaxQuality. Эта предустановка разработана для распознавания всех возможных штрих‑кодов, даже некорректных."
type: docs
weight: 30
url: /ru/net/aspose.barcode.barcoderecognition/qualitysettings/maxquality/
---
## QualitySettings.MaxQuality property

Предустановка качества распознавания MaxQuality. Эта предустановка разработана для распознавания всех возможных штрих‑кодов, даже некорректных.

```csharp
public static QualitySettings MaxQuality { get; }
```

### Property Value

Предустановка качества распознавания MaxQuality.

## Примеры

Этот пример показывает, как использовать режим MaxQuality.

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings = QualitySettings.MaxQuality;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```

### См. также

* class [QualitySettings](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)


