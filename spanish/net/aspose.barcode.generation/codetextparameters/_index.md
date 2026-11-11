---
title: "Clase CodetextParameters"
second_title: "Referencia de API de Aspose.BarCode para .NET"
description: "Clase Aspose.BarCode.Generation.CodetextParameters. Parámetros de codetexto"
type: docs
weight: 1160
url: /es/net/aspose.barcode.generation/codetextparameters/
---
## CodetextParameters class

Parámetros de codetext.

```csharp
public class CodetextParameters
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Alignment](../../aspose.barcode.generation/codetextparameters/alignment/) { get; set; } | Obtiene o establece la alineación del texto del código. Valor predeterminado: StringAlignment.Center. |
| [Color](../../aspose.barcode.generation/codetextparameters/color/) { get; set; } | Especifique el color de visualización del CodeText. Valor predeterminado: Color.Black. |
| [Font](../../aspose.barcode.generation/codetextparameters/font/) { get; } | Especifique la fuente de visualización del CodeText. Valor predeterminado: Arial 5pt regular. Ignorado si FontMode está configurado a FontMode.Auto. |
| [FontMode](../../aspose.barcode.generation/codetextparameters/fontmode/) { get; set; } | Especifique FontMode. Si FontMode está configurado en Auto, el tamaño de fuente se calculará automáticamente en función del valor de xDimension. Se recomienda usar FontMode.Auto especialmente en AutoSizeMode.Nearest o AutoSizeMode.Interpolation. Valor predeterminado: FontMode.Auto. |
| [Location](../../aspose.barcode.generation/codetextparameters/location/) { get; set; } | Especifique la ubicación de visualización de CodeText, establezca CodeLocation.None para ocultar CodeText. Valor predeterminado: CodeLocation.Below para códigos de barras 1D y CodeLocation.None para códigos de barras 2D. |
| [NoWrap](../../aspose.barcode.generation/codetextparameters/nowrap/) { get; set; } | Especifique los ajustes de línea (saltos de línea) dentro del texto. Valor predeterminado: false. |
| [Space](../../aspose.barcode.generation/codetextparameters/space/) { get; set; } | Espacio entre el CodeText y el BarCode en la unidad [`Unit`](../unit/). Valor predeterminado: 2pt. Ignorado para EAN8, EAN13, UPCE, UPCA, ISBN, ISMN, ISSN, UpcaGs1DatabarCoupon. |
| [TwoDDisplayText](../../aspose.barcode.generation/codetextparameters/twoddisplaytext/) { get; set; } | Texto que se mostrará en lugar de codetext en códigos de barras 2D. Usado para: Aztec, Pdf417, DataMatrix, QR, MaxiCode, DotCode. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| override [ToString](../../aspose.barcode.generation/codetextparameters/tostring/)() | Devuelve una representación de cadena legible por humanos de este `CodetextParameters`. |

### Ver también

* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


