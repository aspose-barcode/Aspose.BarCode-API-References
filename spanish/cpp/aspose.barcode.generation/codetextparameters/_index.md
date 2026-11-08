---
title: "Aspose::BarCode::Generation::CodetextParameters class"
linktitle: "CodetextParameters"
second_title: "Aspose.BarCode for C++ Referencia de API"
description: "Clase Aspose::BarCode::Generation::CodetextParameters. Parámetros de texto de código en C++."
type: docs
weight: 1500
url: /es/cpp/aspose.barcode.generation/codetextparameters/
---
## CodetextParameters class


Parámetros de Codetext.

```cpp
class CodetextParameters : public System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| [get_Alignment](./get_alignment/)() const | Obtiene la alineación del texto de código. Valor predeterminado: [StringAlignment.Center](../textalignment/). |
| [get_Color](./get_color/)() const | Especifique el color del texto de código que se muestra. Valor predeterminado: Color.Black. |
| [get_Font](./get_font/)() const | Especifique la fuente del CodeText que se muestra. Valor predeterminado: Arial 5pt regular. Ignorado si FontMode está configurado a [FontMode.Auto](../aztecencodemode/). |
| [get_FontMode](./get_fontmode/)() const | Especifique FontMode. Si FontMode está configurado a Auto, el tamaño de fuente se calculará automáticamente en función del valor de xDimension. Se recomienda usar [FontMode.Auto](../aztecencodemode/) especialmente en [AutoSizeMode.Nearest](../autosizemode/) o [AutoSizeMode.Interpolation](../autosizemode/). Valor predeterminado: [FontMode.Auto](../aztecencodemode/). |
| [get_Location](./get_location/)() const | Especifique la ubicación del CodeText que se muestra, establezca [CodeLocation.None](../codelocation/) para ocultar CodeText. Valor predeterminado: [CodeLocation.Below](../codelocation/) para códigos de barras 1D y [CodeLocation.None](../codelocation/) para códigos de barras 2D. |
| [get_NoWrap](./get_nowrap/)() const | Especifique los saltos de línea dentro del texto. Valor predeterminado: false. |
| [get_Space](./get_space/)() const | Espacio entre el CodeText y el [BarCode](../../aspose.barcode/) en valor de [Unit ](../unit/). Valor predeterminado: 2pt. Ignorado para EAN8, EAN13, UPCE, UPCA, ISBN, ISMN, ISSN, UpcaGs1DatabarCoupon. |
| [get_TwoDDisplayText](./get_twoddisplaytext/)() const | Texto que se mostrará en lugar del codetext en códigos de barras 2D. Usado para: Aztec, Pdf417, DataMatrix, QR, MaxiCode, DotCode |
| [set_Alignment](./set_alignment/)(TextAlignment) | Establece la alineación del texto del código. Valor predeterminado: [StringAlignment.Center](../textalignment/). |
| [set_Color](./set_color/)(System::Drawing::Color) | Especifique el color del texto de código que se muestra. Valor predeterminado: Color.Black. |
| [set_FontMode](./set_fontmode/)(Aspose::BarCode::Generation::FontMode) | Especifique FontMode. Si FontMode está configurado a Auto, el tamaño de fuente se calculará automáticamente en función del valor de xDimension. Se recomienda usar [FontMode.Auto](../aztecencodemode/) especialmente en [AutoSizeMode.Nearest](../autosizemode/) o [AutoSizeMode.Interpolation](../autosizemode/). Valor predeterminado: [FontMode.Auto](../aztecencodemode/). |
| [set_Location](./set_location/)(CodeLocation) | Especifique la ubicación del CodeText que se muestra, establezca [CodeLocation.None](../codelocation/) para ocultar CodeText. Valor predeterminado: [CodeLocation.Below](../codelocation/) para códigos de barras 1D y [CodeLocation.None](../codelocation/) para códigos de barras 2D. |
| [set_NoWrap](./set_nowrap/)(bool) | Especifique los saltos de línea dentro del texto. Valor predeterminado: false. |
| [set_Space](./set_space/)(System::SharedPtr\<Unit\>) | Espacio entre el CodeText y el [BarCode](../../aspose.barcode/) en valor de [Unit ](../unit/). Valor predeterminado: 2pt. Ignorado para EAN8, EAN13, UPCE, UPCA, ISBN, ISMN, ISSN, UpcaGs1DatabarCoupon. |
| [set_TwoDDisplayText](./set_twoddisplaytext/)(System::String) | Texto que se mostrará en lugar del codetext en códigos de barras 2D. Usado para: Aztec, Pdf417, DataMatrix, QR, MaxiCode, DotCode |
| [ToString](./tostring/)() const override | Devuelve una representación de cadena legible por humanos de este [CodetextParameters](./). |
## Ver también

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
