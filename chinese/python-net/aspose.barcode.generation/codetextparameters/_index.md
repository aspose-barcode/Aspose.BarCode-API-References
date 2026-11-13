---
title: "CodetextParameters"
second_title: "Aspose.BarCode for Python via .NET API Reference"
description: 
type: docs
url: /zh/python-net/aspose.barcode.generation/codetextparameters/
---

## CodetextParameters class

Codetext 参数。

CodetextParameters 类型公开以下成员：
## 属性
| 名称 | 描述 |
| :- | :- |
| two_d_display_text | 将在二维条码中显示的文本，代替编码文本。<br/>            用于：Aztec、Pdf417、DataMatrix、QR、MaxiCode、DotCode |
| font_mode | 指定 FontMode。如果 FontMode 设置为 Auto，字体大小将根据 xDimension 值自动计算。<br/>            建议在 AutoSizeMode.Nearest 或 AutoSizeMode.Interpolation 中使用 FontMode.Auto。<br/>            默认值：FontMode.Auto。 |
| font | 指定显示的 CodeText 字体。<br/>            默认值：Arial 5pt 常规。<br/>            如果 FontMode 设置为 FontMode.Auto，则此设置被忽略。 |
| space | CodeText 与条形码之间的间距，以 [Unit](/barcode/python-net/aspose.barcode.generation/unit/) 为单位。<br/>            默认值：2pt。<br/>            对 EAN8、EAN13、UPCE、UPCA、ISBN、ISMN、ISSN、UpcaGs1DatabarCoupon 忽略此设置。 |
| 对齐 | 获取或设置代码文本的对齐方式。<br/>            默认值: StringAlignment.Center. |
| 颜色 | 指定显示的 CodeText 的颜色。<br/>            默认值: Color.Black. |
| 位置 | 指定显示的 CodeText 位置，设置为 CodeLocation.None 可隐藏 CodeText。<br/>            默认值: 对于一维条码为 CodeLocation.Below，二维条码为 CodeLocation.None。 |
| 不换行 | 指定文本中的自动换行（换行符）。<br/>            默认值: false. |

### 另见

* namespace [aspose.barcode.generation](/barcode/python-net/aspose.barcode.generation/)
* assembly [Aspose.BarCode](/barcode/python-net/)

