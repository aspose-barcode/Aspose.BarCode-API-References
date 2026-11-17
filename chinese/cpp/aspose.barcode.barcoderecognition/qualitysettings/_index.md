---
title: "Aspose::BarCode::BarCodeRecognition::QualitySettings 类"
linktitle: "QualitySettings"
second_title: "Aspose.BarCode for C++ API 参考"
description: "Aspose::BarCode::BarCodeRecognition::QualitySettings 类。QualitySettings 允许手动配置识别质量和速度。您可以使用内置预设快速设置 QualitySettings：HighPerformance、NormalQuality、HighQuality、MaxQuality，或手动配置各个选项。QualitySettings 的默认值在 C++ 中为 NormalQuality。"
type: docs
weight: 3100
url: /zh/cpp/aspose.barcode.barcoderecognition/qualitysettings/
---
## QualitySettings class


[QualitySettings](./) allows to configure recognition quality and speed manually. You can quickly set up [QualitySettings](./) with embedded presets: HighPerformance, NormalQuality, HighQuality, MaxQuality or you can manually configure separate options. Default value of [QualitySettings](./) is NormalQuality.

```cpp
class QualitySettings : public System::Object
```

## 方法

| 方法 | 描述 |
| --- | --- |
| [get_AllowIncorrectBarcodes](./get_allowincorrectbarcodes/)() const | 允许引擎识别校验和错误或数值错误的条码。此模式可用于识别文本错误的损坏条码。 |
| [get_BarcodeQuality](./get_barcodequality/)() const | 此模式启用使用所选质量识别条码元素的方法。质量较低的条码元素需要更复杂的方法，从而减慢识别速度。 |
| [get_ComplexBackground](./get_complexbackground/)() const | 此模式启用或禁用对彩色图像中彩色条码的额外识别。 |
| [get_Deconvolution](./get_deconvolution/)() const | 去卷积（图像恢复）模式，用于定义图像退化程度。去卷积本质上是一种能够恢复因自然函数（如模糊）在相机拍摄时导致的退化（卷积）图像的功能。由于我们无法检测导致图像损坏的函数，只能检查最常见的函数，如锐化或数学形态学。 |
| static [get_HighPerformance](./get_highperformance/)() | HighPerformance 识别质量预设。在此模式下，高质量条码能够得到良好识别。 |
| static [get_HighQuality](./get_highquality/)() | HighQuality 识别质量预设。此预设针对低质量条码而开发。允许检测高度损坏的条码。 |
| [get_InverseImage](./get_inverseimage/)() const | 此模式启用或禁用对颜色反转（亮度）图像中条码的额外识别。 |
| static [get_MaxQuality](./get_maxquality/)() | MaxQuality 识别质量预设。此预设旨在识别所有可能的条形码，即使是错误的条形码。 |
| [get_MinimalXDimension](./get_minimalxdimension/)() const | 使用 UseMinimalXDimension 时 XDimension 的最小像素尺寸。 |
| static [get_NormalQuality](./get_normalquality/)() | NormalQuality 识别质量预设。适用于大多数条形码。 |
| [get_XDimension](./get_xdimension/)() const | [Recognition](../../aspose.barcode.barcoderecognition.recognition/) 模式，用于设置条形码最小元素（矩阵单元或条）的大小（从 1 到无限）。 |
| [set_AllowIncorrectBarcodes](./set_allowincorrectbarcodes/)(bool) | 允许引擎识别校验和错误或数值错误的条码。此模式可用于识别文本错误的损坏条码。 |
| [set_BarcodeQuality](./set_barcodequality/)(BarcodeQualityMode) | 此模式启用使用所选质量识别条码元素的方法。质量较低的条码元素需要更复杂的方法，从而减慢识别速度。 |
| [set_ComplexBackground](./set_complexbackground/)(ComplexBackgroundMode) | 此模式启用或禁用对彩色图像中彩色条码的额外识别。 |
| [set_Deconvolution](./set_deconvolution/)(DeconvolutionMode) | 去卷积（图像恢复）模式，用于定义图像退化程度。去卷积本质上是一种能够恢复因自然函数（如模糊）在相机拍摄时导致的退化（卷积）图像的功能。由于我们无法检测导致图像损坏的函数，只能检查最常见的函数，如锐化或数学形态学。 |
| [set_InverseImage](./set_inverseimage/)(InverseImageMode) | 此模式启用或禁用对颜色反转（亮度）图像中条码的额外识别。 |
| [set_MinimalXDimension](./set_minimalxdimension/)(float) | 使用 UseMinimalXDimension 时 XDimension 的最小像素尺寸。 |
| [set_XDimension](./set_xdimension/)(XDimensionMode) | [Recognition](../../aspose.barcode.barcoderecognition.recognition/) 模式，用于设置条形码最小元素（矩阵单元或条）的大小（从 1 到无限）。 |
## 备注


此示例展示了如何将 [QualitySettings](./) 与 [BarCodeReader](../barcodereader/) 一起使用。
```cpp
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

//为尺寸较小的条形码设置 HighPerformance 识别模式
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings = QualitySettings.HighPerformance;
    reader.QualitySettings.XDimension = XDimensionMode.Small;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}

//为质量较低的条形码设置 HighPerformance 识别模式
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings = QualitySettings.HighPerformance;
    reader.QualitySettings.BarcodeQuality = BarcodeQualityMode.Low;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```

## 另见

* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
