---
title: Aspose::BarCode::Generation::BaseGenerationParameters class
linktitle: BaseGenerationParameters
second_title: Aspose.BarCode for C++ API Reference
description: 'Aspose::BarCode::Generation::BaseGenerationParameters class. Barcode image generation parameters in C++.'
type: docs
weight: 700
url: /cpp/aspose.barcode.generation/basegenerationparameters/
---
## BaseGenerationParameters class


Barcode image generation parameters.

```cpp
class BaseGenerationParameters : public System::Object
```

## Methods

| Method | Description |
| --- | --- |
| [get_AutoSizeMode](./get_autosizemode/)() const | Specifies the different types of automatic sizing modes. Default value: [AutoSizeMode.None](../autosizemode/). |
| [get_BackColor](./get_backcolor/)() | Background color of the barcode image. Default value: Color.White. See [Color](../). |
| [get_Barcode](./get_barcode/)() const | Gets the [BarcodeParameters](../barcodeparameters/) that contains all barcode properties. |
| [get_Border](./get_border/)() const | Gets the [BorderParameters](../borderparameters/) that contains all configuration properties for barcode border. |
| [get_CaptionAbove](./get_captionabove/)() const | Caption Above the [BarCode](../../aspose.barcode/) image. See [CaptionParameters](../captionparameters/). |
| [get_CaptionBelow](./get_captionbelow/)() const | Caption Below the [BarCode](../../aspose.barcode/) image. See [CaptionParameters](../captionparameters/). |
| [get_Image](./get_image/)() const | Image parameters. See [ImageParameters](../imageparameters/). |
| [get_ImageHeight](./get_imageheight/)() const | [BarCode](../../aspose.barcode/) image height when [AutoSizeMode](../autosizemode/) property is set to [AutoSizeMode.Nearest](../autosizemode/) or [AutoSizeMode.Interpolation](../autosizemode/). |
| [get_ImageWidth](./get_imagewidth/)() const | [BarCode](../../aspose.barcode/) image width when [AutoSizeMode](../autosizemode/) property is set to [AutoSizeMode.Nearest](../autosizemode/) or [AutoSizeMode.Interpolation](../autosizemode/). |
| [get_Resolution](./get_resolution/)() | Gets the resolution of the [BarCode](../../aspose.barcode/) image. One value for both dimensions. Default value: 96 dpi. |
| [get_RotationAngle](./get_rotationangle/)() | [BarCode](../../aspose.barcode/) image rotation angle, measured in degree, e.g. RotationAngle = 0 or RotationAngle = 360 means no rotation. If RotationAngle NOT equal to 90, 180, 270 or 0, it may increase the difficulty for the scanner to read the image. Default value: 0. |
| [get_UseAntiAlias](./get_useantialias/)() | Gets a value indicating whether is used anti-aliasing mode to render image |
| [set_AutoSizeMode](./set_autosizemode/)(Aspose::BarCode::Generation::AutoSizeMode) | Specifies the different types of automatic sizing modes. Default value: [AutoSizeMode.None](../autosizemode/). |
| [set_BackColor](./set_backcolor/)(System::Drawing::Color) | Background color of the barcode image. Default value: Color.White. See [Color](../). |
| [set_ImageHeight](./set_imageheight/)(System::SharedPtr\<Unit\>) | [BarCode](../../aspose.barcode/) image height when [AutoSizeMode](../autosizemode/) property is set to [AutoSizeMode.Nearest](../autosizemode/) or [AutoSizeMode.Interpolation](../autosizemode/). |
| [set_ImageWidth](./set_imagewidth/)(System::SharedPtr\<Unit\>) | [BarCode](../../aspose.barcode/) image width when [AutoSizeMode](../autosizemode/) property is set to [AutoSizeMode.Nearest](../autosizemode/) or [AutoSizeMode.Interpolation](../autosizemode/). |
| [set_Resolution](./set_resolution/)(float) | Sets the resolution of the [BarCode](../../aspose.barcode/) image. One value for both dimensions. Default value: 96 dpi. |
| [set_RotationAngle](./set_rotationangle/)(float) | [BarCode](../../aspose.barcode/) image rotation angle, measured in degree, e.g. RotationAngle = 0 or RotationAngle = 360 means no rotation. If RotationAngle NOT equal to 90, 180, 270 or 0, it may increase the difficulty for the scanner to read the image. Default value: 0. |
| [set_UseAntiAlias](./set_useantialias/)(bool) | Sets a value indicating whether is used anti-aliasing mode to render image |
## See Also

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
