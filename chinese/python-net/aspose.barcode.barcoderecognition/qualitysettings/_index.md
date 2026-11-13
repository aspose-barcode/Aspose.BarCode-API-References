---
title: "QualitySettings"
second_title: "Aspose.BarCode for Python via .NET API Reference"
description: 
type: docs
url: /zh/python-net/aspose.barcode.barcoderecognition/qualitysettings/
---

## QualitySettings class

QualitySettings 允许手动配置识别质量和速度。<br/> 您可以使用内置预设快速设置 QualitySettings：HighPerformance、NormalQuality、HighQuality、MaxQuality，或者手动配置各个选项。<br/> QualitySettings 的默认值为 NormalQuality。

QualitySettings 类型公开以下成员：
## 属性
| 名称 | 描述 |
| :- | :- |
| high_performance | HighPerformance 识别质量预设。在此模式下，高质量条码能够被很好地识别。 |
| normal_quality | NormalQuality 识别质量预设。适用于大多数条形码 |
| high_quality | HighQuality 识别质量预设。此预设针对低质量条形码而开发。能够检测高度损坏的条形码。 |
| max_quality | MaxQuality 识别质量预设。此预设旨在识别所有可能的条形码，甚至错误的条形码。 |
| x_dimension | 识别模式，用于设置条形码最小元素（矩阵单元或条）的大小（从 1 到无穷大）。 |
| minimal_x_dimension | 在使用 UseMinimalXDimension 时，XDimension 的最小像素尺寸。 |
| barcode_quality | 模式，启用使用所选质量识别条形码元素的方法。质量较低的条形码元素需要更复杂的算法，导致识别速度变慢。 |
| deconvolution | 去卷积（图像恢复）模式，用于定义图像退化程度。去卷积最初是一种能够恢复因相机拍摄时产生的模糊等自然函数导致的退化（卷积）图像的功能。由于我们无法检测导致图像损坏的函数，<br/>            必须检查最常见的函数，如锐化或数学形态学。 |
| inverse_image | 模式，启用或禁用对颜色（亮度）反转图像中条形码的额外识别。 |
| complex_background | 模式，启用或禁用对彩色图像中彩色条形码的额外识别。 |
| allow_incorrect_barcodes | 允许引擎识别校验和或数值错误的条形码。该模式可用于识别文本错误的受损条形码。 |

### 另见

* namespace [aspose.barcode.barcoderecognition](/barcode/python-net/aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](/barcode/python-net/)

