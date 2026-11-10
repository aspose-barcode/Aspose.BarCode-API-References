---
title: "QualitySettings.MaxQuality"
second_title: "Aspose.BarCode 适用于 .NET API 参考"
description: "QualitySettings 属性。MaxQuality 识别质量预设。此预设旨在识别所有可能的条形码，即使是错误的条形码"
type: docs
weight: 30
url: /zh/net/aspose.barcode.barcoderecognition/qualitysettings/maxquality/
---
## QualitySettings.MaxQuality property

MaxQuality 识别质量预设。此预设旨在识别所有可能的条码，即使是错误的条码。

```csharp
public static QualitySettings MaxQuality { get; }
```

### Property Value

MaxQuality 识别质量预设。

## 示例

此示例展示如何使用 MaxQuality 模式

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings = QualitySettings.MaxQuality;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```

### 另见

* class [QualitySettings](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)


