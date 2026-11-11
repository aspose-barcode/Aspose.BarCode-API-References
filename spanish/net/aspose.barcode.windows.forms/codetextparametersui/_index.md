---
title: "Clase CodetextParametersUI"
second_title: "Referencia de API de Aspose.BarCode para .NET"
description: "Clase Aspose.BarCode.Windows.Forms.CodetextParametersUI. Parámetros de Codetext"
type: docs
weight: 1820
url: /es/net/aspose.barcode.windows.forms/codetextparametersui/
---
## CodetextParametersUI class

Parámetros de codetext.

```csharp
public class CodetextParametersUI
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Alignment](../../aspose.barcode.windows.forms/codetextparametersui/alignment/) { get; set; } | Obtiene o establece la alineación del texto del código. Valor predeterminado: StringAlignment.Center. |
| [Color](../../aspose.barcode.windows.forms/codetextparametersui/color/) { get; set; } | Especifique el color de visualización del CodeText. Valor predeterminado: Color.Black. |
| [Font](../../aspose.barcode.windows.forms/codetextparametersui/font/) { get; set; } | Especifique la fuente de visualización del CodeText. Valor predeterminado: Arial 5pt regular. Ignorado si FontMode está configurado a FontMode.Auto. |
| [FontMode](../../aspose.barcode.windows.forms/codetextparametersui/fontmode/) { get; set; } | Especifique FontMode. Si FontMode está configurado en Auto, el tamaño de fuente se calculará automáticamente en función del valor de xDimension. Se recomienda usar FontMode.Auto especialmente en AutoSizeMode.Nearest o AutoSizeMode.Interpolation. Valor predeterminado: FontMode.Auto. |
| [Location](../../aspose.barcode.windows.forms/codetextparametersui/location/) { get; set; } | Especifique la ubicación de visualización de CodeText, establezca CodeLocation.None para ocultar CodeText. Valor predeterminado: CodeLocation.Below para códigos de barras 1D y CodeLocation.None para códigos de barras 2D. |
| [Space](../../aspose.barcode.windows.forms/codetextparametersui/space/) { get; } | Espacio entre CodeText y BarCode en unidades [`Unit`](../../aspose.barcode.generation/unit/). Valor predeterminado: 2pt. Ignorado para EAN8, EAN13, UPCE, UPCA, ISBN, ISMN, ISSN, UpcaGs1DatabarCoupon. |
| [TwoDDisplayText](../../aspose.barcode.windows.forms/codetextparametersui/twoddisplaytext/) { get; set; } | Texto que se mostrará en lugar de codetext en códigos de barras 2D. Usado para: Aztec, Pdf417, DataMatrix, QR, MaxiCode, DotCode. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| override [ToString](../../aspose.barcode.windows.forms/codetextparametersui/tostring/)() | Devuelve una representación de cadena legible por humanos de este [`CodetextParameters`](../../aspose.barcode.generation/codetextparameters/). |

### Ver también

* namespace [Aspose.BarCode.Windows.Forms](../../aspose.barcode.windows.forms/)
* assembly [Aspose.BarCode](../../)


