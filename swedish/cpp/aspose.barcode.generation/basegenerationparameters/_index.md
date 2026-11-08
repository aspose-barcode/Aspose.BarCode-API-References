---
title: "Aspose::BarCode::Generation::BaseGenerationParameters klass"
linktitle: "BaseGenerationParameters"
second_title: "Aspose.BarCode for C++ API-referens"
description: "Aspose::BarCode::Generation::BaseGenerationParameters klass. Parametrar för generering av streckkodsbilder i C++."
type: docs
weight: 700
url: /sv/cpp/aspose.barcode.generation/basegenerationparameters/
---
## BaseGenerationParameters class


Parametrar för generering av streckkodsbilder.

```cpp
class BaseGenerationParameters : public System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [get_AutoSizeMode](./get_autosizemode/)() const | Anger de olika typerna av automatiska storleksinställningslägen. Standardvärde: [AutoSizeMode.None](../autosizemode/). |
| [get_BackColor](./get_backcolor/)() const | Bakgrundsfärg för streckkodbilden. Standardvärde: Color.White. Se [Color](../). |
| [get_Barcode](./get_barcode/)() const | Hämtar [BarcodeParameters](../barcodeparameters/) som innehåller alla streckkodsegenskaper. |
| [get_Border](./get_border/)() const | Hämtar [BorderParameters](../borderparameters/) som innehåller alla konfigurationsegenskaper för streckkodens kant. |
| [get_CaptionAbove](./get_captionabove/)() const | Rubrik ovanför [BarCode](../../aspose.barcode/) bilden. Se [CaptionParameters](../captionparameters/). |
| [get_CaptionBelow](./get_captionbelow/)() const | Rubrik under [BarCode](../../aspose.barcode/) bilden. Se [CaptionParameters](../captionparameters/). |
| [get_Image](./get_image/)() const | Bildparametrar. Se [ImageParameters](../imageparameters/). |
| [get_ImageHeight](./get_imageheight/)() const | [BarCode](../../aspose.barcode/) bildhöjd när egenskapen [AutoSizeMode](../autosizemode/) är inställd på [AutoSizeMode.Nearest](../autosizemode/) eller [AutoSizeMode.Interpolation](../autosizemode/). |
| [get_ImageWidth](./get_imagewidth/)() const | [BarCode](../../aspose.barcode/) bildbredd när egenskapen [AutoSizeMode](../autosizemode/) är inställd på [AutoSizeMode.Nearest](../autosizemode/) eller [AutoSizeMode.Interpolation](../autosizemode/). |
| [get_Resolution](./get_resolution/)() const | Hämtar upplösningen för [BarCode](../../aspose.barcode/) bilden. Ett värde för båda dimensionerna. Standardvärde: 96 dpi. |
| [get_RotationAngle](./get_rotationangle/)() const | [BarCode](../../aspose.barcode/) bildrotationsvinkel, mätt i grader, t.ex. RotationAngle = 0 eller RotationAngle = 360 betyder ingen rotation. Om RotationAngle INTE är lika med 90, 180, 270 eller 0 kan det göra det svårare för skannern att läsa bilden. Standardvärde: 0. |
| [get_UseAntiAlias](./get_useantialias/)() const | Hämtar ett värde som indikerar om anti-aliasing‑läge används för att rendera bilden |
| [set_AutoSizeMode](./set_autosizemode/)(Aspose::BarCode::Generation::AutoSizeMode) | Anger de olika typerna av automatiska storleksinställningslägen. Standardvärde: [AutoSizeMode.None](../autosizemode/). |
| [set_BackColor](./set_backcolor/)(System::Drawing::Color) | Bakgrundsfärg för streckkodbilden. Standardvärde: Color.White. Se [Color](../). |
| [set_ImageHeight](./set_imageheight/)(System::SharedPtr\<Unit\>) | [BarCode](../../aspose.barcode/) bildhöjd när egenskapen [AutoSizeMode](../autosizemode/) är inställd på [AutoSizeMode.Nearest](../autosizemode/) eller [AutoSizeMode.Interpolation](../autosizemode/). |
| [set_ImageWidth](./set_imagewidth/)(System::SharedPtr\<Unit\>) | [BarCode](../../aspose.barcode/) bildbredd när egenskapen [AutoSizeMode](../autosizemode/) är inställd på [AutoSizeMode.Nearest](../autosizemode/) eller [AutoSizeMode.Interpolation](../autosizemode/). |
| [set_Resolution](./set_resolution/)(float) | Ställer in upplösningen för [BarCode](../../aspose.barcode/) bilden. Ett värde för båda dimensionerna. Standardvärde: 96 dpi. |
| [set_RotationAngle](./set_rotationangle/)(float) | [BarCode](../../aspose.barcode/) bildrotationsvinkel, mätt i grader, t.ex. RotationAngle = 0 eller RotationAngle = 360 betyder ingen rotation. Om RotationAngle INTE är lika med 90, 180, 270 eller 0 kan det göra det svårare för skannern att läsa bilden. Standardvärde: 0. |
| [set_UseAntiAlias](./set_useantialias/)(bool) | Ställer in ett värde som indikerar om anti-aliasing‑läge används för att rendera bilden |
## Se även

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
