---
title: "枚举 ComplexBackgroundMode"
second_title: "Aspose.BarCode 适用于 .NET API 参考"
description: "Aspose.BarCode.BarCodeRecognition.ComplexBackgroundMode 枚举。启用或禁用对彩色图像上彩色条形码的额外识别的模式"
type: docs
weight: 200
url: /zh/net/aspose.barcode.barcoderecognition/complexbackgroundmode/
---
## ComplexBackgroundMode enumeration

模式，启用或禁用对彩色图像中彩色条形码的额外识别。

```csharp
public enum ComplexBackgroundMode
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| Auto | `0` | 此时与 Disabled 相同。禁用对彩色图像上彩色条形码的额外识别。 |
| Disabled | `1` | 禁用对彩色图像上彩色条形码的额外识别。 |
| Enabled | `2` | 启用对彩色图像上彩色条形码的额外识别。 |

## 示例

此示例展示了如何使用 ComplexBackground 模式

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings.ComplexBackground = ComplexBackgroundMode.Enabled;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```

### 另见

* namespace [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../)


