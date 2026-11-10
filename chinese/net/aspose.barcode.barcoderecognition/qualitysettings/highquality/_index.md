---
title: "QualitySettings.HighQuality"
second_title: "Aspose.BarCode 适用于 .NET API 参考"
description: "QualitySettings 属性。HighQuality 识别质量预设。此预设针对低质量条码开发。可检测高度损坏的条码。"
type: docs
weight: 20
url: /zh/net/aspose.barcode.barcoderecognition/qualitysettings/highquality/
---
## QualitySettings.HighQuality property

HighQuality 识别质量预设。此预设针对低质量条码而开发，能够检测高度损坏的条码。

```csharp
public static QualitySettings HighQuality { get; }
```

### Property Value

HighQuality 识别质量预设。

## 示例

此示例展示如何使用 HighQuality 模式

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings = QualitySettings.HighQuality;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```

### 另见

* class [QualitySettings](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)


