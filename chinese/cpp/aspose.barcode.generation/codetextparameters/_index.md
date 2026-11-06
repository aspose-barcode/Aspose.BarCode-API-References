---
title: "Aspose::BarCode::Generation::CodetextParameters 类"
linktitle: "CodetextParameters"
second_title: "Aspose.BarCode for C++ API 参考"
description: "Aspose::BarCode::Generation::CodetextParameters 类。C++ 中的码文本参数。"
type: docs
weight: 1500
url: /zh/cpp/aspose.barcode.generation/codetextparameters/
---
## CodetextParameters class


Codetext 参数。

```cpp
class CodetextParameters : public System::Object
```

## 方法

| 方法 | 描述 |
| --- | --- |
| [get_Alignment](./get_alignment/)() const | 获取码文本的对齐方式。默认值: [StringAlignment.Center](../textalignment/)。 |
| [get_Color](./get_color/)() const | 指定显示的 CodeText 颜色。默认值: Color.Black。 |
| [get_Font](./get_font/)() const | 指定显示的 CodeText 字体。默认值：Arial 5pt 常规。如果 FontMode 设置为 [FontMode.Auto](../aztecencodemode/)，则忽略。 |
| [get_FontMode](./get_fontmode/)() const | 指定 FontMode。如果 FontMode 设置为 Auto，字体大小将根据 xDimension 值自动计算。建议使用 [FontMode.Auto](../aztecencodemode/)，尤其在 [AutoSizeMode.Nearest](../autosizemode/) 或 [AutoSizeMode.Interpolation](../autosizemode/) 中。默认值： [FontMode.Auto](../aztecencodemode/)。 |
| [get_Location](./get_location/)() const | 指定显示的 CodeText 位置，设置为 [CodeLocation.None](../codelocation/) 可隐藏 CodeText。默认值：1D 条码为 [CodeLocation.Below](../codelocation/)，2D 条码为 [CodeLocation.None](../codelocation/)。 |
| [get_NoWrap](./get_nowrap/)() const | 指定文本中的自动换行（换行符）。默认值：false。 |
| [get_Space](./get_space/)() const | 在 [Unit ](../unit/) 值中，CodeText 与 [BarCode](../../aspose.barcode/) 之间的间距。默认值：2pt。对 EAN8、EAN13、UPCE、UPCA、ISBN、ISMN、ISSN、UpcaGs1DatabarCoupon 忽略。 |
| [get_TwoDDisplayText](./get_twoddisplaytext/)() const | 在 2D 条码中将显示的文本，代替 codetext。用于：Aztec、Pdf417、DataMatrix、QR、MaxiCode、DotCode。 |
| [set_Alignment](./set_alignment/)(TextAlignment) | 设置代码文本的对齐方式。默认值：[StringAlignment.Center](../textalignment/)。 |
| [set_Color](./set_color/)(System::Drawing::Color) | 指定显示的 CodeText 颜色。默认值: Color.Black。 |
| [set_FontMode](./set_fontmode/)(Aspose::BarCode::Generation::FontMode) | 指定 FontMode。如果 FontMode 设置为 Auto，字体大小将根据 xDimension 值自动计算。建议使用 [FontMode.Auto](../aztecencodemode/)，尤其在 [AutoSizeMode.Nearest](../autosizemode/) 或 [AutoSizeMode.Interpolation](../autosizemode/) 中。默认值： [FontMode.Auto](../aztecencodemode/)。 |
| [set_Location](./set_location/)(CodeLocation) | 指定显示的 CodeText 位置，设置为 [CodeLocation.None](../codelocation/) 可隐藏 CodeText。默认值：1D 条码为 [CodeLocation.Below](../codelocation/)，2D 条码为 [CodeLocation.None](../codelocation/)。 |
| [set_NoWrap](./set_nowrap/)(bool) | 指定文本中的自动换行（换行符）。默认值：false。 |
| [set_Space](./set_space/)(System::SharedPtr\<Unit\>) | 在 [Unit ](../unit/) 值中，CodeText 与 [BarCode](../../aspose.barcode/) 之间的间距。默认值：2pt。对 EAN8、EAN13、UPCE、UPCA、ISBN、ISMN、ISSN、UpcaGs1DatabarCoupon 忽略。 |
| [set_TwoDDisplayText](./set_twoddisplaytext/)(System::String) | 在 2D 条码中将显示的文本，代替 codetext。用于：Aztec、Pdf417、DataMatrix、QR、MaxiCode、DotCode。 |
| [ToString](./tostring/)() const override | 返回此 [CodetextParameters](./) 的可读字符串表示。 |
## 另见

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
