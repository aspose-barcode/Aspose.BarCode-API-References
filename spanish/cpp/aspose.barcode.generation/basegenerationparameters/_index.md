---
title: "Aspose::BarCode::Generation::BaseGenerationParameters clase"
linktitle: "BaseGenerationParameters"
second_title: "Aspose.BarCode for C++ Referencia de API"
description: "Aspose::BarCode::Generation::BaseGenerationParameters clase. Parámetros de generación de imágenes de código de barras en C++."
type: docs
weight: 700
url: /es/cpp/aspose.barcode.generation/basegenerationparameters/
---
## BaseGenerationParameters class


Parámetros de generación de imágenes de códigos de barras.

```cpp
class BaseGenerationParameters : public System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| [get_AutoSizeMode](./get_autosizemode/)() const | Especifica los diferentes tipos de modos de dimensionado automático. Valor predeterminado: [AutoSizeMode.None](../autosizemode/). |
| [get_BackColor](./get_backcolor/)() const | Color de fondo de la imagen del código de barras. Valor predeterminado: Color.White. Ver [Color](../). |
| [get_Barcode](./get_barcode/)() const | Obtiene los [BarcodeParameters](../barcodeparameters/) que contienen todas las propiedades del código de barras. |
| [get_Border](./get_border/)() const | Obtiene los [BorderParameters](../borderparameters/) que contienen todas las propiedades de configuración del borde del código de barras. |
| [get_CaptionAbove](./get_captionabove/)() const | Leyenda encima de la imagen [BarCode](../../aspose.barcode/). Ver [CaptionParameters](../captionparameters/). |
| [get_CaptionBelow](./get_captionbelow/)() const | Leyenda debajo de la imagen [BarCode](../../aspose.barcode/). Ver [CaptionParameters](../captionparameters/). |
| [get_Image](./get_image/)() const | Parámetros de imagen. Ver [ImageParameters](../imageparameters/). |
| [get_ImageHeight](./get_imageheight/)() const | Altura de la imagen [BarCode](../../aspose.barcode/) cuando la propiedad [AutoSizeMode](../autosizemode/) está configurada a [AutoSizeMode.Nearest](../autosizemode/) o [AutoSizeMode.Interpolation](../autosizemode/). |
| [get_ImageWidth](./get_imagewidth/)() const | Anchura de la imagen [BarCode](../../aspose.barcode/) cuando la propiedad [AutoSizeMode](../autosizemode/) está configurada a [AutoSizeMode.Nearest](../autosizemode/) o [AutoSizeMode.Interpolation](../autosizemode/). |
| [get_Resolution](./get_resolution/)() const | Obtiene la resolución de la imagen [BarCode](../../aspose.barcode/). Un valor para ambas dimensiones. Valor predeterminado: 96 dpi. |
| [get_RotationAngle](./get_rotationangle/)() const | Ángulo de rotación de la imagen [BarCode](../../aspose.barcode/), medido en grados, p.ej. RotationAngle = 0 o RotationAngle = 360 significa sin rotación. Si RotationAngle NO es igual a 90, 180, 270 o 0, puede aumentar la dificultad para que el escáner lea la imagen. Valor predeterminado: 0. |
| [get_UseAntiAlias](./get_useantialias/)() const | Obtiene un valor que indica si se utiliza el modo anti-aliasing para renderizar la imagen |
| [set_AutoSizeMode](./set_autosizemode/)(Aspose::BarCode::Generation::AutoSizeMode) | Especifica los diferentes tipos de modos de dimensionado automático. Valor predeterminado: [AutoSizeMode.None](../autosizemode/). |
| [set_BackColor](./set_backcolor/)(System::Drawing::Color) | Color de fondo de la imagen del código de barras. Valor predeterminado: Color.White. Ver [Color](../). |
| [set_ImageHeight](./set_imageheight/)(System::SharedPtr\<Unit\>) | Altura de la imagen [BarCode](../../aspose.barcode/) cuando la propiedad [AutoSizeMode](../autosizemode/) está configurada a [AutoSizeMode.Nearest](../autosizemode/) o [AutoSizeMode.Interpolation](../autosizemode/). |
| [set_ImageWidth](./set_imagewidth/)(System::SharedPtr\<Unit\>) | Anchura de la imagen [BarCode](../../aspose.barcode/) cuando la propiedad [AutoSizeMode](../autosizemode/) está configurada a [AutoSizeMode.Nearest](../autosizemode/) o [AutoSizeMode.Interpolation](../autosizemode/). |
| [set_Resolution](./set_resolution/)(float) | Establece la resolución de la imagen [BarCode](../../aspose.barcode/). Un valor para ambas dimensiones. Valor predeterminado: 96 dpi. |
| [set_RotationAngle](./set_rotationangle/)(float) | Ángulo de rotación de la imagen [BarCode](../../aspose.barcode/), medido en grados, p.ej. RotationAngle = 0 o RotationAngle = 360 significa sin rotación. Si RotationAngle NO es igual a 90, 180, 270 o 0, puede aumentar la dificultad para que el escáner lea la imagen. Valor predeterminado: 0. |
| [set_UseAntiAlias](./set_useantialias/)(bool) | Establece un valor que indica si se utiliza el modo anti-aliasing para renderizar la imagen |
## Ver también

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
