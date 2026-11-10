---
title: "枚举 InverseImageMode"
second_title: "Aspose.BarCode 适用于 .NET API 参考"
description: "Aspose.BarCode.BarCodeRecognition.InverseImageMode 枚举。该模式用于在颜色亮度反转的图像上启用或禁用条码的额外识别。"
type: docs
weight: 270
url: /zh/net/aspose.barcode.barcoderecognition/inverseimagemode/
---
## InverseImageMode enumeration

模式，启用或禁用对颜色反转（亮度）图像中条形码的额外识别。

```csharp
public enum InverseImageMode
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| Auto | `0` | 对除 QR Code 之外的所有条码类型，禁用在反转图像上的额外识别。 |
| Disabled | `1` | 禁用在反转图像上的条码额外识别。 |
| Enabled | `2` | 启用在反转图像上的条码额外识别。 |

## 示例

此示例展示了如何使用 InverseImage 模式

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings.InverseImage = InverseImageMode.Enabled;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```

### 另见

* namespace [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../)


