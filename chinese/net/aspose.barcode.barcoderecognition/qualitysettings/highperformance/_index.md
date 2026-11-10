---
title: "QualitySettings.HighPerformance"
second_title: "Aspose.BarCode 适用于 .NET API 参考"
description: "QualitySettings 属性。HighPerformance 识别质量预设。在此模式下，高质量条码能够被很好地识别。"
type: docs
weight: 10
url: /zh/net/aspose.barcode.barcoderecognition/qualitysettings/highperformance/
---
## QualitySettings.HighPerformance property

HighPerformance 识别质量预设。在此模式下，高质量条码能够被良好识别。

```csharp
public static QualitySettings HighPerformance { get; }
```

### Property Value

HighPerformance 识别质量预设。

## 示例

此示例展示了如何使用 HighPerformance 模式

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings = QualitySettings.HighPerformance;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```

### 另见

* class [QualitySettings](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)


