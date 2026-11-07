---
title: "Aspose::BarCode::Generation::BaseGenerationParameters Klasse"
linktitle: "BaseGenerationParameters"
second_title: "Aspose.BarCode für C++ API-Referenz"
description: "Aspose::BarCode::Generation::BaseGenerationParameters Klasse. Barcode-Bildgenerierungsparameter in C++."
type: docs
weight: 700
url: /de/cpp/aspose.barcode.generation/basegenerationparameters/
---
## BaseGenerationParameters class


Parameter für die Barcode-Bilderzeugung.

```cpp
class BaseGenerationParameters : public System::Object
```

## Methods

| Method | Beschreibung |
| --- | --- |
| [get_AutoSizeMode](./get_autosizemode/)() const | Gibt die verschiedenen Typen der automatischen Größenmodi an. Standardwert: [AutoSizeMode.None](../autosizemode/). |
| [get_BackColor](./get_backcolor/)() const | Hintergrundfarbe des Barcode-Bildes. Standardwert: Color.White. Siehe [Color](../). |
| [get_Barcode](./get_barcode/)() const | Ruft die [BarcodeParameters](../barcodeparameters/) ab, die alle Barcode-Eigenschaften enthält. |
| [get_Border](./get_border/)() const | Ruft die [BorderParameters](../borderparameters/) ab, die alle Konfigurationseigenschaften für den Barcode-Rahmen enthält. |
| [get_CaptionAbove](./get_captionabove/)() const | Beschriftung über dem [BarCode](../../aspose.barcode/) Bild. Siehe [CaptionParameters](../captionparameters/). |
| [get_CaptionBelow](./get_captionbelow/)() const | Beschriftung unter dem [BarCode](../../aspose.barcode/) Bild. Siehe [CaptionParameters](../captionparameters/). |
| [get_Image](./get_image/)() const | Bildparameter. Siehe [ImageParameters](../imageparameters/). |
| [get_ImageHeight](./get_imageheight/)() const | Höhe des [BarCode](../../aspose.barcode/) Bildes, wenn die Eigenschaft [AutoSizeMode](../autosizemode/) auf [AutoSizeMode.Nearest](../autosizemode/) oder [AutoSizeMode.Interpolation](../autosizemode/) gesetzt ist. |
| [get_ImageWidth](./get_imagewidth/)() const | Breite des [BarCode](../../aspose.barcode/) Bildes, wenn die Eigenschaft [AutoSizeMode](../autosizemode/) auf [AutoSizeMode.Nearest](../autosizemode/) oder [AutoSizeMode.Interpolation](../autosizemode/) gesetzt ist. |
| [get_Resolution](./get_resolution/)() const | Ruft die Auflösung des [BarCode](../../aspose.barcode/) Bildes ab. Ein Wert für beide Dimensionen. Standardwert: 96 dpi. |
| [get_RotationAngle](./get_rotationangle/)() const | Drehwinkel des [BarCode](../../aspose.barcode/) Bildes, gemessen in Grad, z. B. RotationAngle = 0 oder RotationAngle = 360 bedeutet keine Drehung. Wenn RotationAngle NICHT gleich 90, 180, 270 oder 0 ist, kann dies die Schwierigkeit für den Scanner erhöhen, das Bild zu lesen. Standardwert: 0. |
| [get_UseAntiAlias](./get_useantialias/)() const | Ruft einen Wert ab, der angibt, ob ein Anti-Aliasing-Modus zum Rendern des Bildes verwendet wird |
| [set_AutoSizeMode](./set_autosizemode/)(Aspose::BarCode::Generation::AutoSizeMode) | Gibt die verschiedenen Typen der automatischen Größenmodi an. Standardwert: [AutoSizeMode.None](../autosizemode/). |
| [set_BackColor](./set_backcolor/)(System::Drawing::Color) | Hintergrundfarbe des Barcode-Bildes. Standardwert: Color.White. Siehe [Color](../). |
| [set_ImageHeight](./set_imageheight/)(System::SharedPtr\<Unit\>) | Höhe des [BarCode](../../aspose.barcode/) Bildes, wenn die Eigenschaft [AutoSizeMode](../autosizemode/) auf [AutoSizeMode.Nearest](../autosizemode/) oder [AutoSizeMode.Interpolation](../autosizemode/) gesetzt ist. |
| [set_ImageWidth](./set_imagewidth/)(System::SharedPtr\<Unit\>) | Breite des [BarCode](../../aspose.barcode/) Bildes, wenn die Eigenschaft [AutoSizeMode](../autosizemode/) auf [AutoSizeMode.Nearest](../autosizemode/) oder [AutoSizeMode.Interpolation](../autosizemode/) gesetzt ist. |
| [set_Resolution](./set_resolution/)(float) | Setzt die Auflösung des [BarCode](../../aspose.barcode/) Bildes. Ein Wert für beide Dimensionen. Standardwert: 96 dpi. |
| [set_RotationAngle](./set_rotationangle/)(float) | Drehwinkel des [BarCode](../../aspose.barcode/) Bildes, gemessen in Grad, z. B. RotationAngle = 0 oder RotationAngle = 360 bedeutet keine Drehung. Wenn RotationAngle NICHT gleich 90, 180, 270 oder 0 ist, kann dies die Schwierigkeit für den Scanner erhöhen, das Bild zu lesen. Standardwert: 0. |
| [set_UseAntiAlias](./set_useantialias/)(bool) | Setzt einen Wert, der angibt, ob ein Anti-Aliasing-Modus zum Rendern des Bildes verwendet wird |
## Siehe auch

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
