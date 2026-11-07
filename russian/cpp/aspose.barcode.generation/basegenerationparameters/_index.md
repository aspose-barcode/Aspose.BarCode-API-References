---
title: "Aspose::BarCode::Generation::BaseGenerationParameters class"
linktitle: "BaseGenerationParameters"
second_title: "Aspose.BarCode для C++ справочник API"
description: "Aspose::BarCode::Generation::BaseGenerationParameters class. Параметры генерации изображения штрих‑кода в C++."
type: docs
weight: 700
url: /ru/cpp/aspose.barcode.generation/basegenerationparameters/
---
## BaseGenerationParameters class


Параметры генерации изображения штрихкода.

```cpp
class BaseGenerationParameters : public System::Object
```

## Methods

| Method | Описание |
| --- | --- |
| [get_AutoSizeMode](./get_autosizemode/)() const | Указывает различные типы режимов автоматического масштабирования. Значение по умолчанию: [AutoSizeMode.None](../autosizemode/). |
| [get_BackColor](./get_backcolor/)() const | Фоновый цвет изображения штрих‑кода. Значение по умолчанию: Color.White. См. [Color](../). |
| [get_Barcode](./get_barcode/)() const | Получает [BarcodeParameters](../barcodeparameters/), содержащий все свойства штрих‑кода. |
| [get_Border](./get_border/)() const | Получает [BorderParameters](../borderparameters/), содержащий все свойства конфигурации границы штрих‑кода. |
| [get_CaptionAbove](./get_captionabove/)() const | Подпись над изображением [BarCode](../../aspose.barcode/). См. [CaptionParameters](../captionparameters/). |
| [get_CaptionBelow](./get_captionbelow/)() const | Подпись под изображением [BarCode](../../aspose.barcode/). См. [CaptionParameters](../captionparameters/). |
| [get_Image](./get_image/)() const | Параметры изображения. См. [ImageParameters](../imageparameters/). |
| [get_ImageHeight](./get_imageheight/)() const | Высота изображения [BarCode](../../aspose.barcode/) при установленном свойстве [AutoSizeMode](../autosizemode/) в значение [AutoSizeMode.Nearest](../autosizemode/) или [AutoSizeMode.Interpolation](../autosizemode/). |
| [get_ImageWidth](./get_imagewidth/)() const | Ширина изображения [BarCode](../../aspose.barcode/) при установленном свойстве [AutoSizeMode](../autosizemode/) в значение [AutoSizeMode.Nearest](../autosizemode/) или [AutoSizeMode.Interpolation](../autosizemode/). |
| [get_Resolution](./get_resolution/)() const | Получает разрешение изображения [BarCode](../../aspose.barcode/). Одна величина для обеих измерений. Значение по умолчанию: 96 dpi. |
| [get_RotationAngle](./get_rotationangle/)() const | Угол вращения изображения [BarCode](../../aspose.barcode/), измеряется в градусах, например RotationAngle = 0 или RotationAngle = 360 означает отсутствие вращения. Если RotationAngle НЕ равен 90, 180, 270 или 0, это может усложнить сканеру чтение изображения. Значение по умолчанию: 0. |
| [get_UseAntiAlias](./get_useantialias/)() const | Получает значение, указывающее, используется ли режим сглаживания при рендеринге изображения |
| [set_AutoSizeMode](./set_autosizemode/)(Aspose::BarCode::Generation::AutoSizeMode) | Указывает различные типы режимов автоматического масштабирования. Значение по умолчанию: [AutoSizeMode.None](../autosizemode/). |
| [set_BackColor](./set_backcolor/)(System::Drawing::Color) | Фоновый цвет изображения штрих‑кода. Значение по умолчанию: Color.White. См. [Color](../). |
| [set_ImageHeight](./set_imageheight/)(System::SharedPtr\<Unit\>) | Высота изображения [BarCode](../../aspose.barcode/) при установленном свойстве [AutoSizeMode](../autosizemode/) в значение [AutoSizeMode.Nearest](../autosizemode/) или [AutoSizeMode.Interpolation](../autosizemode/). |
| [set_ImageWidth](./set_imagewidth/)(System::SharedPtr\<Unit\>) | Ширина изображения [BarCode](../../aspose.barcode/) при установленном свойстве [AutoSizeMode](../autosizemode/) в значение [AutoSizeMode.Nearest](../autosizemode/) или [AutoSizeMode.Interpolation](../autosizemode/). |
| [set_Resolution](./set_resolution/)(float) | Устанавливает разрешение изображения [BarCode](../../aspose.barcode/). Одна величина для обеих измерений. Значение по умолчанию: 96 dpi. |
| [set_RotationAngle](./set_rotationangle/)(float) | Угол вращения изображения [BarCode](../../aspose.barcode/), измеряется в градусах, например RotationAngle = 0 или RotationAngle = 360 означает отсутствие вращения. Если RotationAngle НЕ равен 90, 180, 270 или 0, это может усложнить сканеру чтение изображения. Значение по умолчанию: 0. |
| [set_UseAntiAlias](./set_useantialias/)(bool) | Устанавливает значение, указывающее, используется ли режим сглаживания при рендеринге изображения |
## См. также

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
