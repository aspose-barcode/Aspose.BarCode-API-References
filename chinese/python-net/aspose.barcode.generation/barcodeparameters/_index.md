---
title: "BarcodeParameters"
second_title: "Aspose.BarCode for Python via .NET API Reference"
description: 
type: docs
url: /zh/python-net/aspose.barcode.generation/barcodeparameters/
---

## BarcodeParameters class

条码生成参数。

BarcodeParameters 类型公开以下成员：
## 属性
| 名称 | 描述 |
| :- | :- |
| x_dimension | x-dimension 是条形码条或空格单元的最小宽度。<br/>            增大此值将增加整个条码图像的宽度。<br/>            如果将 [auto_size_mode](/barcode/python-net/aspose.barcode.generation/basegenerationparameters/) 属性设置为 AutoSizeMode.Nearest 或 AutoSizeMode.Interpolation，则此设置被忽略。 |
| bar_height | 1D 条码条的高度，以 [Unit](/barcode/python-net/aspose.barcode.generation/unit/) 为单位。<br/>            如果将 [auto_size_mode](/barcode/python-net/aspose.barcode.generation/basegenerationparameters/) 属性设置为 AutoSizeMode.Nearest 或 AutoSizeMode.Interpolation，则此设置被忽略。 |
| bar_color | 条的颜色。<br/>            默认值：Color.Black。 |
| padding | 条码填充。<br/>            默认值：5pt 5pt 5pt 5pt。 |
| checksum_always_show | 始终在 Code128 和 GS1Code128 条码的人类可读文本中显示校验位数字。 |
| is_checksum_enabled |  |
| throw_exception_when_code_text_incorrect | 仅适用于 1D 条码。<br/>            如果 codetext 不正确且值设为 true，则会抛出异常。否则 codetext 将被纠正以符合条码规范。<br/>            以下情况始终会抛出异常：Databar 符号如果 codetext 不正确。<br/>            以下情况始终不会抛出异常：AustraliaPost、SingapurePost、Code39FullASCII、Code93、Code16K、Code128 符号如果 codetext 不正确。 |
| wide_narrow_ratio | 宽条与窄条的比例。<br/>            默认值：3，即宽条的宽度是窄条的 3 倍。<br/>            用于 ITF、PZN、PharmaCode、Standard2of5、Interleaved2of5、Matrix2of5、ItalianPost25、IATA2of5、VIN、DeutschePost、OPC、Code32、DataLogic2of5、PatchCode、Code39、Code39FullASCII。 |
| code_text_parameters | Codetext 参数。 |
| filled_bars | 获取或设置一个值，指示条是否已填充。<br/>            仅适用于 1D 条码。<br/>            默认值：true。 |
| bar_width_reduction | 获取或设置用于在打印时补偿墨水扩散的条宽度减小值。<br/>            默认值：0 |
| postal | 邮政参数。用于 Postnet、Planet。 |
| patch_code | PatchCode 参数。 |
| australian_post | AustralianPost 条码参数。 |
| data_bar | Databar 参数。 |
| gs1_composite_bar | GS1 Composite Bar 参数。 |
| codablock | Codablock 参数。 |
| data_matrix | DataMatrix 参数。 |
| code_16k | Code16K 参数。 |
| dot_code | DotCode 参数。 |
| itf | ITF 参数。 |
| pdf417 | PDF417 参数。 |
| qr | QR、MicroQR 和 RectMicroQR 参数。 |
| supplement | 补充参数。用于 Interleaved2of5、Standard2of5、EAN13、EAN8、UPCA、UPCE、ISBN、ISSN、ISMN。 |
| maxi_code | MaxiCode 参数。 |
| aztec | Aztec 参数。 |
| code128 | Code128 参数。 |
| codabar | Codabar 参数。 |
| coupon | 优惠券参数。用于 UpcaGs1DatabarCoupon、UpcaGs1Code128Coupon。 |
| han_xin | HanXin 参数。 |
| gs1 | GS1 参数。 |

### 另见

* namespace [aspose.barcode.generation](/barcode/python-net/aspose.barcode.generation/)
* assembly [Aspose.BarCode](/barcode/python-net/)

