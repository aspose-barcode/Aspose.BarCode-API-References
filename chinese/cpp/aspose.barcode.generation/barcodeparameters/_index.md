---
title: "Aspose::BarCode::Generation::BarcodeParameters 类"
linktitle: "BarcodeParameters"
second_title: "Aspose.BarCode for C++ API 参考"
description: "Aspose::BarCode::Generation::BarcodeParameters 类。C++ 中的条形码生成参数。"
type: docs
weight: 500
url: /zh/cpp/aspose.barcode.generation/barcodeparameters/
---
## BarcodeParameters class


条形码生成参数。

```cpp
class BarcodeParameters : public System::Object
```

## 方法

| 方法 | 描述 |
| --- | --- |
| [get_AustralianPost](./get_australianpost/)() const | AustralianPost 条形码参数。 |
| [get_Aztec](./get_aztec/)() const | Aztec 参数。 |
| [get_BarColor](./get_barcolor/)() const | 条形颜色。默认值：Color.Black。 |
| [get_BarHeight](./get_barheight/)() const | 1D 条码条的高度，以 [Unit](../unit/) 为单位。 如果将 [BaseGenerationParameters::AutoSizeMode](../) 属性设置为 [AutoSizeMode.Nearest](../autosizemode/) 或 [AutoSizeMode.Interpolation](../autosizemode/)，则忽略。 |
| [get_BarWidthReduction](./get_barwidthreduction/)() const | 获取或设置用于在打印时补偿油墨扩散的条形减小值。默认值：0。 |
| [get_ChecksumAlwaysShow](./get_checksumalwaysshow/)() const | 始终在 Code128 和 GS1Code128 条码的人类可读文本中显示校验位。 |
| [get_Codabar](./get_codabar/)() const | Codabar 参数。 |
| [get_Codablock](./get_codablock/)() const | Codablock 参数。 |
| [get_Code128](./get_code128/)() const | Code128 参数。 |
| [get_Code16K](./get_code16k/)() const | Code16K 参数。 |
| [get_CodeTextParameters](./get_codetextparameters/)() const | Codetext 参数。 |
| [get_Coupon](./get_coupon/)() const | 优惠券参数。用于 UpcaGs1DatabarCoupon、UpcaGs1Code128Coupon。 |
| [get_DataBar](./get_databar/)() const | Databar 参数。 |
| [get_DataMatrix](./get_datamatrix/)() const | DataMatrix 参数。 |
| [get_DotCode](./get_dotcode/)() const | DotCode 参数。 |
| [get_FilledBars](./get_filledbars/)() const | 获取一个指示条是否填充的值。仅适用于 1D 条码。默认值：true。 |
| [get_GS1](./get_gs1/)() const | GS1 参数。 |
| [get_GS1CompositeBar](./get_gs1compositebar/)() const | GS1 复合条参数。 |
| [get_HanXin](./get_hanxin/)() const | HanXin 参数。 |
| [get_IsChecksumEnabled](./get_ischecksumenabled/)() const |  |
| [get_ITF](./get_itf/)() const | ITF 参数。 |
| [get_MaxiCode](./get_maxicode/)() const | MaxiCode 参数。 |
| [get_Padding](./get_padding/)() const | 条码填充。默认值：5pt 5pt 5pt 5pt。 |
| [get_PatchCode](./get_patchcode/)() const | PatchCode 参数。 |
| [get_Pdf417](./get_pdf417/)() const | PDF417 参数。 |
| [get_Postal](./get_postal/)() const | 邮政参数。用于 Postnet、Planet。 |
| [get_QR](./get_qr/)() const | QR、MicroQR 和 RectMicroQR 参数。 |
| [get_Supplement](./get_supplement/)() const | 补充参数。用于 Interleaved2of5、Standard2of5、EAN13、EAN8、UPCA、UPCE、ISBN、ISSN、ISMN。 |
| [get_ThrowExceptionWhenCodeTextIncorrect](./get_throwexceptionwhencodetextincorrect/)() const | 仅适用于 1D 条码。如果 codetext 不正确且值设为 true——将抛出异常。否则 codetext 将被纠正以符合条码规范。以下情况下始终会抛出异常：Databar 符号如果 codetext 不正确。以下情况下始终不会抛出异常：AustraliaPost、SingapurePost、Code39FullASCII、Code93、Code16K、Code128 符号如果 codetext 不正确。 |
| [get_WideNarrowRatio](./get_widenarrowratio/)() const | 宽条与窄条的比例。默认值：3，即宽条是窄条的 3 倍。用于 ITF、PZN、PharmaCode、Standard2of5、Interleaved2of5、Matrix2of5、ItalianPost25、IATA2of5、VIN、DeutschePost、OPC、Code32、DataLogic2of5、PatchCode、Code39、Code39FullASCII。 |
| [get_XDimension](./get_xdimension/)() const | x-dimension 是 [BarCode](../../aspose.barcode/) 条或空格单元的最小宽度。增大此值将增加整个条码图像的宽度。如果将 [BaseGenerationParameters::AutoSizeMode](../) 属性设置为 [AutoSizeMode.Nearest](../autosizemode/) 或 [AutoSizeMode.Interpolation](../autosizemode/)，则此设置将被忽略。 |
| [set_BarColor](./set_barcolor/)(System::Drawing::Color) | 条形颜色。默认值：Color.Black。 |
| [set_BarHeight](./set_barheight/)(System::SharedPtr\<Unit\>) | 1D 条码条的高度，以 [Unit](../unit/) 为单位。 如果将 [BaseGenerationParameters::AutoSizeMode](../) 属性设置为 [AutoSizeMode.Nearest](../autosizemode/) 或 [AutoSizeMode.Interpolation](../autosizemode/)，则忽略。 |
| [set_BarWidthReduction](./set_barwidthreduction/)(System::SharedPtr\<Unit\>) | 获取或设置用于在打印时补偿油墨扩散的条形减小值。默认值：0。 |
| [set_ChecksumAlwaysShow](./set_checksumalwaysshow/)(bool) | 始终在 Code128 和 GS1Code128 条码的人类可读文本中显示校验位。 |
| [set_FilledBars](./set_filledbars/)(bool) | 设置一个指示条是否填充的值。仅适用于 1D 条码。默认值：true。 |
| [set_GS1CompositeBar](./set_gs1compositebar/)(System::SharedPtr\<GS1CompositeBarParameters\>) | GS1 复合条参数。 |
| [set_IsChecksumEnabled](./set_ischecksumenabled/)(EnableChecksum) |  |
| [set_ThrowExceptionWhenCodeTextIncorrect](./set_throwexceptionwhencodetextincorrect/)(bool) | 仅适用于 1D 条码。如果 codetext 不正确且值设为 true——将抛出异常。否则 codetext 将被纠正以符合条码规范。以下情况下始终会抛出异常：Databar 符号如果 codetext 不正确。以下情况下始终不会抛出异常：AustraliaPost、SingapurePost、Code39FullASCII、Code93、Code16K、Code128 符号如果 codetext 不正确。 |
| [set_WideNarrowRatio](./set_widenarrowratio/)(float) | 宽条与窄条的比例。默认值：3，即宽条是窄条的 3 倍。用于 ITF、PZN、PharmaCode、Standard2of5、Interleaved2of5、Matrix2of5、ItalianPost25、IATA2of5、VIN、DeutschePost、OPC、Code32、DataLogic2of5、PatchCode、Code39、Code39FullASCII。 |
| [set_XDimension](./set_xdimension/)(System::SharedPtr\<Unit\>) | x-dimension 是 [BarCode](../../aspose.barcode/) 条或空格单元的最小宽度。增大此值将增加整个条码图像的宽度。如果将 [BaseGenerationParameters::AutoSizeMode](../) 属性设置为 [AutoSizeMode.Nearest](../autosizemode/) 或 [AutoSizeMode.Interpolation](../autosizemode/)，则此设置将被忽略。 |
## 另见

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
