---
title: "类 QualitySettings"
second_title: "Aspose.BarCode 适用于 .NET API 参考"
description: "Aspose.BarCode.BarCodeRecognition.QualitySettings 类。QualitySettings 允许手动配置识别质量和速度。您可以使用内置预设 HighPerformance、NormalQuality、HighQuality、MaxQuality 快速设置 QualitySettings，或手动配置各个选项。QualitySettings 的默认值为 NormalQuality。"
type: docs
weight: 370
url: /zh/net/aspose.barcode.barcoderecognition/qualitysettings/
---
## QualitySettings class

QualitySettings 允许手动配置识别质量和速度。您可以使用内置预设快速设置 QualitySettings：HighPerformance、NormalQuality、HighQuality、MaxQuality，或者手动配置各个选项。QualitySettings 的默认值为 NormalQuality。

```csharp
public sealed class QualitySettings
```

## 属性

| 名称 | 描述 |
| --- | --- |
| static [HighPerformance](../../aspose.barcode.barcoderecognition/qualitysettings/highperformance/) { get; } | HighPerformance 识别质量预设。在此模式下，高质量条码能够被良好识别。 |
| static [HighQuality](../../aspose.barcode.barcoderecognition/qualitysettings/highquality/) { get; } | HighQuality 识别质量预设。此预设针对低质量条码而开发，能够检测高度损坏的条码。 |
| static [MaxQuality](../../aspose.barcode.barcoderecognition/qualitysettings/maxquality/) { get; } | MaxQuality 识别质量预设。此预设旨在识别所有可能的条码，即使是错误的条码。 |
| static [NormalQuality](../../aspose.barcode.barcoderecognition/qualitysettings/normalquality/) { get; } | NormalQuality 识别质量预设。适用于大多数条码 |
| [AllowIncorrectBarcodes](../../aspose.barcode.barcoderecognition/qualitysettings/allowincorrectbarcodes/) { get; set; } | 允许引擎识别具有错误校验和或错误数值的条码。此模式可用于识别文本错误的损坏条码。 |
| [BarcodeQuality](../../aspose.barcode.barcoderecognition/qualitysettings/barcodequality/) { get; set; } | 模式，使能够使用所选质量识别条形码元素。质量较低的条形码元素需要更复杂的方法，从而减慢识别速度。 |
| [ComplexBackground](../../aspose.barcode.barcoderecognition/qualitysettings/complexbackground/) { get; set; } | 模式，启用或禁用对彩色图像中彩色条形码的额外识别。 |
| [Deconvolution](../../aspose.barcode.barcoderecognition/qualitysettings/deconvolution/) { get; set; } | 去卷积（图像恢复）模式，用于定义图像退化的程度。去卷积最初是一种能够恢复因自然函数（如模糊）在相机拍摄时导致的退化（卷积）图像的功能。由于我们无法检测导致图像损坏的函数，只能检查最常见的函数，如锐化或数学形态学。 |
| [InverseImage](../../aspose.barcode.barcoderecognition/qualitysettings/inverseimage/) { get; set; } | 模式，启用或禁用对颜色反转（亮度）图像中条形码的额外识别。 |
| [MinimalXDimension](../../aspose.barcode.barcoderecognition/qualitysettings/minimalxdimension/) { get; set; } | 使用 UseMinimalXDimension 时的 XDimension 最小像素尺寸。 |
| [XDimension](../../aspose.barcode.barcoderecognition/qualitysettings/xdimension/) { get; set; } | 识别模式，用于设置条形码最小元素（矩阵单元或条）的大小（从 1 到无限大）。 |

## 示例

此示例展示了如何将 QualitySettings 与 BarCodeReader 一起使用

```csharp
[C#]
//设置 HighPerformance 识别模式
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings = QualitySettings.HighPerformance;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}

//设置 HighQuality 识别模式
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings = QualitySettings.HighQuality;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}

//为小尺寸条码设置 HighPerformance 识别模式
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings = QualitySettings.HighPerformance;
    reader.QualitySettings.XDimension = XDimensionMode.Small;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}

//为低质量条码设置 HighPerformance 识别模式
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings = QualitySettings.HighPerformance;
    reader.QualitySettings.BarcodeQuality = BarcodeQualityMode.Low;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}    
```

### 另见

* namespace [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../)


