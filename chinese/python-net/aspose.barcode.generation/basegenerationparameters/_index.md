---
title: "BaseGenerationParameters"
second_title: "Aspose.BarCode for Python via .NET API Reference"
description: 
type: docs
url: /zh/python-net/aspose.barcode.generation/basegenerationparameters/
---

## BaseGenerationParameters class

条码图像生成参数。

BaseGenerationParameters 类型公开以下成员：
## 属性
| 名称 | 描述 |
| :- | :- |
| use_anti_alias | 获取或设置一个值，指示是否在渲染图像时使用抗锯齿模式 |
| back_color | 条形码图像的背景颜色。<br/>            默认值：Color.White。<br/>            参见 [Color](/barcode/python-net/aspose.drawing/color/)。 |
| 分辨率 | 获取或设置条形码图像的分辨率。<br/>            两个维度使用相同的值。<br/>            默认值：96 dpi。 |
| rotation_angle | 条形码图像的旋转角度，以度为单位，例如 RotationAngle = 0 或 RotationAngle = 360 表示不旋转。<br/>            如果 RotationAngle 不等于 90、180、270 或 0，可能会增加扫描仪读取图像的难度。<br/>            默认值：0。 |
| caption_above | 条形码图像上方的标题。参见 [CaptionParameters](/barcode/python-net/aspose.barcode.generation/captionparameters/)。 |
| caption_below | 条形码图像下方的标题。参见 [CaptionParameters](/barcode/python-net/aspose.barcode.generation/captionparameters/)。 |
| image | 图像参数。参见 [ImageParameters](/barcode/python-net/aspose.barcode.generation/imageparameters/)。 |
| auto_size_mode | 指定不同类型的自动尺寸模式。<br/>            默认值：AutoSizeMode.None。 |
| image_height | 当 [auto_size_mode](/barcode/python-net/aspose.barcode.generation/basegenerationparameters/) 属性设置为 AutoSizeMode.Nearest 或 AutoSizeMode.Interpolation 时，BarCode 图像高度。 |
| image_width | 当 [auto_size_mode](/barcode/python-net/aspose.barcode.generation/basegenerationparameters/) 属性设置为 AutoSizeMode.Nearest 或 AutoSizeMode.Interpolation 时，BarCode 图像宽度。 |
| barcode | 获取包含所有条码属性的 [BarcodeParameters](/barcode/python-net/aspose.barcode.generation/barcodeparameters/)。 |
| border | 获取包含条码边框所有配置属性的 [BorderParameters](/barcode/python-net/aspose.barcode.generation/borderparameters/)。 |

### 另见

* namespace [aspose.barcode.generation](/barcode/python-net/aspose.barcode.generation/)
* assembly [Aspose.BarCode](/barcode/python-net/)

