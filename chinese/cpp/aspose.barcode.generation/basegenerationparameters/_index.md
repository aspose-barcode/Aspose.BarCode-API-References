---
title: "Aspose::BarCode::Generation::BaseGenerationParameters 类"
linktitle: "BaseGenerationParameters"
second_title: "Aspose.BarCode for C++ API 参考"
description: "Aspose::BarCode::Generation::BaseGenerationParameters 类。用于在 C++ 中生成条形码图像的参数。"
type: docs
weight: 700
url: /zh/cpp/aspose.barcode.generation/basegenerationparameters/
---
## BaseGenerationParameters class


条形码图像生成参数。

```cpp
class BaseGenerationParameters : public System::Object
```

## 方法

| 方法 | 描述 |
| --- | --- |
| [get_AutoSizeMode](./get_autosizemode/)() const | 指定自动尺寸模式的不同类型。默认值： [AutoSizeMode.None](../autosizemode/)。 |
| [get_BackColor](./get_backcolor/)() const | 条形码图像的背景颜色。默认值： Color.White。参见 [Color](../)。 |
| [get_Barcode](./get_barcode/)() const | 获取包含所有条形码属性的 [BarcodeParameters](../barcodeparameters/)。 |
| [get_Border](./get_border/)() const | 获取包含条形码边框所有配置属性的 [BorderParameters](../borderparameters/)。 |
| [get_CaptionAbove](./get_captionabove/)() const | 在 [BarCode](../../aspose.barcode/) 图像上方的标题。参见 [CaptionParameters](../captionparameters/)。 |
| [get_CaptionBelow](./get_captionbelow/)() const | 在 [BarCode](../../aspose.barcode/) 图像下方的标题。参见 [CaptionParameters](../captionparameters/)。 |
| [get_Image](./get_image/)() const | 图像参数。参见 [ImageParameters](../imageparameters/)。 |
| [get_ImageHeight](./get_imageheight/)() const | [BarCode](../../aspose.barcode/) 图像高度，当 [AutoSizeMode](../autosizemode/) 属性设置为 [AutoSizeMode.Nearest](../autosizemode/) 或 [AutoSizeMode.Interpolation](../autosizemode/) 时。 |
| [get_ImageWidth](./get_imagewidth/)() const | [BarCode](../../aspose.barcode/) 图像宽度，当 [AutoSizeMode](../autosizemode/) 属性设置为 [AutoSizeMode.Nearest](../autosizemode/) 或 [AutoSizeMode.Interpolation](../autosizemode/) 时。 |
| [get_Resolution](./get_resolution/)() const | 获取 [BarCode](../../aspose.barcode/) 图像的分辨率。两个维度使用相同的值。默认值：96 dpi。 |
| [get_RotationAngle](./get_rotationangle/)() const | [BarCode](../../aspose.barcode/) 图像旋转角度，以度为单位，例如 RotationAngle = 0 或 RotationAngle = 360 表示不旋转。如果 RotationAngle 不等于 90、180、270 或 0，可能会增加扫描仪读取图像的难度。默认值：0。 |
| [get_UseAntiAlias](./get_useantialias/)() const | 获取一个值，指示是否在渲染图像时使用抗锯齿模式 |
| [set_AutoSizeMode](./set_autosizemode/)(Aspose::BarCode::Generation::AutoSizeMode) | 指定自动尺寸模式的不同类型。默认值： [AutoSizeMode.None](../autosizemode/)。 |
| [set_BackColor](./set_backcolor/)(System::Drawing::Color) | 条形码图像的背景颜色。默认值： Color.White。参见 [Color](../)。 |
| [set_ImageHeight](./set_imageheight/)(System::SharedPtr\<Unit\>) | [BarCode](../../aspose.barcode/) 图像高度，当 [AutoSizeMode](../autosizemode/) 属性设置为 [AutoSizeMode.Nearest](../autosizemode/) 或 [AutoSizeMode.Interpolation](../autosizemode/) 时。 |
| [set_ImageWidth](./set_imagewidth/)(System::SharedPtr\<Unit\>) | [BarCode](../../aspose.barcode/) 图像宽度，当 [AutoSizeMode](../autosizemode/) 属性设置为 [AutoSizeMode.Nearest](../autosizemode/) 或 [AutoSizeMode.Interpolation](../autosizemode/) 时。 |
| [set_Resolution](./set_resolution/)(float) | 设置 [BarCode](../../aspose.barcode/) 图像的分辨率。两个维度使用相同的值。默认值：96 dpi。 |
| [set_RotationAngle](./set_rotationangle/)(float) | [BarCode](../../aspose.barcode/) 图像旋转角度，以度为单位，例如 RotationAngle = 0 或 RotationAngle = 360 表示不旋转。如果 RotationAngle 不等于 90、180、270 或 0，可能会增加扫描仪读取图像的难度。默认值：0。 |
| [set_UseAntiAlias](./set_useantialias/)(bool) | 设置一个值，指示是否在渲染图像时使用抗锯齿模式 |
## 另见

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
