---
title: "Aspose::BarCode::Generation::BaseGenerationParameters klasse"
linktitle: "BaseGenerationParameters"
second_title: "Aspose.BarCode for C++ API-referentie"
description: "Aspose::BarCode::Generation::BaseGenerationParameters klasse. Barcode-afbeeldingsgeneratieparameters in C++."
type: docs
weight: 700
url: /nl/cpp/aspose.barcode.generation/basegenerationparameters/
---
## BaseGenerationParameters class


Barcode‑afbeeldingsgeneratieparameters.

```cpp
class BaseGenerationParameters : public System::Object
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| [get_AutoSizeMode](./get_autosizemode/)() const | Specificeert de verschillende typen automatische formaatmodi. Standaardwaarde: [AutoSizeMode.None](../autosizemode/). |
| [get_BackColor](./get_backcolor/)() const | Achtergrondkleur van de barcode-afbeelding. Standaardwaarde: Color.White. Zie [Color](../). |
| [get_Barcode](./get_barcode/)() const | Haalt de [BarcodeParameters](../barcodeparameters/) op die alle barcode-eigenschappen bevat. |
| [get_Border](./get_border/)() const | Haalt de [BorderParameters](../borderparameters/) op die alle configuratie-eigenschappen voor de barcode-rand bevat. |
| [get_CaptionAbove](./get_captionabove/)() const | Bijschrift boven de [BarCode](../../aspose.barcode/) afbeelding. Zie [CaptionParameters](../captionparameters/). |
| [get_CaptionBelow](./get_captionbelow/)() const | Bijschrift onder de [BarCode](../../aspose.barcode/) afbeelding. Zie [CaptionParameters](../captionparameters/). |
| [get_Image](./get_image/)() const | Afbeeldingsparameters. Zie [ImageParameters](../imageparameters/). |
| [get_ImageHeight](./get_imageheight/)() const | Hoogte van de [BarCode](../../aspose.barcode/) afbeelding wanneer de eigenschap [AutoSizeMode](../autosizemode/) is ingesteld op [AutoSizeMode.Nearest](../autosizemode/) of [AutoSizeMode.Interpolation](../autosizemode/). |
| [get_ImageWidth](./get_imagewidth/)() const | Breedte van de [BarCode](../../aspose.barcode/) afbeelding wanneer de eigenschap [AutoSizeMode](../autosizemode/) is ingesteld op [AutoSizeMode.Nearest](../autosizemode/) of [AutoSizeMode.Interpolation](../autosizemode/). |
| [get_Resolution](./get_resolution/)() const | Haalt de resolutie van de [BarCode](../../aspose.barcode/) afbeelding op. Eén waarde voor beide dimensies. Standaardwaarde: 96 dpi. |
| [get_RotationAngle](./get_rotationangle/)() const | Rotatiehoek van de [BarCode](../../aspose.barcode/) afbeelding, gemeten in graden, bijv. RotationAngle = 0 of RotationAngle = 360 betekent geen rotatie. Als RotationAngle NIET gelijk is aan 90, 180, 270 of 0, kan dit de moeilijkheid voor de scanner om de afbeelding te lezen verhogen. Standaardwaarde: 0. |
| [get_UseAntiAlias](./get_useantialias/)() const | Haalt een waarde op die aangeeft of anti-aliasing modus wordt gebruikt om de afbeelding te renderen |
| [set_AutoSizeMode](./set_autosizemode/)(Aspose::BarCode::Generation::AutoSizeMode) | Specificeert de verschillende typen automatische formaatmodi. Standaardwaarde: [AutoSizeMode.None](../autosizemode/). |
| [set_BackColor](./set_backcolor/)(System::Drawing::Color) | Achtergrondkleur van de barcode-afbeelding. Standaardwaarde: Color.White. Zie [Color](../). |
| [set_ImageHeight](./set_imageheight/)(System::SharedPtr\<Unit\>) | Hoogte van de [BarCode](../../aspose.barcode/) afbeelding wanneer de eigenschap [AutoSizeMode](../autosizemode/) is ingesteld op [AutoSizeMode.Nearest](../autosizemode/) of [AutoSizeMode.Interpolation](../autosizemode/). |
| [set_ImageWidth](./set_imagewidth/)(System::SharedPtr\<Unit\>) | Breedte van de [BarCode](../../aspose.barcode/) afbeelding wanneer de eigenschap [AutoSizeMode](../autosizemode/) is ingesteld op [AutoSizeMode.Nearest](../autosizemode/) of [AutoSizeMode.Interpolation](../autosizemode/). |
| [set_Resolution](./set_resolution/)(float) | Stelt de resolutie van de [BarCode](../../aspose.barcode/) afbeelding in. Eén waarde voor beide dimensies. Standaardwaarde: 96 dpi. |
| [set_RotationAngle](./set_rotationangle/)(float) | Rotatiehoek van de [BarCode](../../aspose.barcode/) afbeelding, gemeten in graden, bijv. RotationAngle = 0 of RotationAngle = 360 betekent geen rotatie. Als RotationAngle NIET gelijk is aan 90, 180, 270 of 0, kan dit de moeilijkheid voor de scanner om de afbeelding te lezen verhogen. Standaardwaarde: 0. |
| [set_UseAntiAlias](./set_useantialias/)(bool) | Stelt een waarde in die aangeeft of anti-aliasing modus wordt gebruikt om de afbeelding te renderen |
## Zie ook

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
