---
title: "QualitySettings.NormalQuality"
second_title: "Aspose.BarCode 适用于 .NET API 参考"
description: "QualitySettings 属性。NormalQuality 识别质量预设。适用于大多数条形码"
type: docs
weight: 40
url: /zh/net/aspose.barcode.barcoderecognition/qualitysettings/normalquality/
---
## QualitySettings.NormalQuality property

NormalQuality 识别质量预设。适用于大多数条码

```csharp
public static QualitySettings NormalQuality { get; }
```

### Property Value

NormalQuality 识别质量预设。

## 示例

此示例展示如何使用 NormalQuality 模式

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings = QualitySettings.NormalQuality;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```

### 另见

* class [QualitySettings](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)


