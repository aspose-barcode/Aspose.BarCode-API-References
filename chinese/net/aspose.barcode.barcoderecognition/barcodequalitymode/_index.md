---
title: "枚举 BarcodeQualityMode"
second_title: "Aspose.BarCode 适用于 .NET API 参考"
description: "Aspose.BarCode.BarCodeRecognition.BarcodeQualityMode 枚举。此模式启用方法以所选质量识别条形码元素。质量较低的条形码元素需要更复杂的方法，从而减慢识别速度。"
type: docs
weight: 110
url: /zh/net/aspose.barcode.barcoderecognition/barcodequalitymode/
---
## BarcodeQualityMode enumeration

模式，使能够使用所选质量识别条形码元素。质量较低的条形码元素需要更复杂的方法，从而减慢识别速度。

```csharp
public enum BarcodeQualityMode
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| High | `0` | 启用对高质量条形码的识别方法。 |
| Normal | `1` | 启用对普通（正常）质量条形码的识别方法。 |
| Low | `2` | 启用对低质量条形码的识别方法。 |

## 示例

此示例展示了如何使用 BarcodeQuality 模式。

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings.BarcodeQuality = BarcodeQualityMode.Low;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```

### 另见

* namespace [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../)


