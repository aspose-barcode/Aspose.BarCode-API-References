---
title: "CodetextParameters"
second_title: "Referencia de API de Aspose.BarCode para Python a través de .NET"
description: 
type: docs
url: /es/python-net/aspose.barcode.generation/codetextparameters/
---

## CodetextParameters class

Parámetros de Codetext.

El tipo CodetextParameters expone los siguientes miembros:
## Propiedades
| Nombre | Descripción |
| :- | :- |
| two_d_display_text | Texto que se mostrará en lugar del codetext en códigos de barras 2D.<br/>            Usado para: Aztec, Pdf417, DataMatrix, QR, MaxiCode, DotCode |
| font_mode | Especifique FontMode. Si FontMode está configurado en Auto, el tamaño de fuente se calculará automáticamente en función del valor de xDimension.<br/>            Se recomienda usar FontMode.Auto especialmente en AutoSizeMode.Nearest o AutoSizeMode.Interpolation.<br/>            Valor predeterminado: FontMode.Auto. |
| font | Especifique la fuente del CodeText que se muestra.<br/>            Valor predeterminado: Arial 5pt regular.<br/>            Se ignora si FontMode está configurado en FontMode.Auto. |
| space | Espacio entre el CodeText y el BarCode en unidades [Unit](/barcode/python-net/aspose.barcode.generation/unit/).<br/>            Valor predeterminado: 2pt.<br/>            Se ignora para EAN8, EAN13, UPCE, UPCA, ISBN, ISMN, ISSN, UpcaGs1DatabarCoupon. |
| alineación | Obtiene o establece la alineación del texto del código.<br/>            Valor predeterminado: StringAlignment.Center. |
| color | Especifique el color que se muestra del CodeText.<br/>            Valor predeterminado: Color.Black. |
| ubicación | Especifique la ubicación del CodeText que se muestra, establezca CodeLocation.None para ocultar CodeText.<br/>            Valor predeterminado: CodeLocation.Below para códigos de barras 1D y CodeLocation.None para códigos de barras 2D. |
| no_wrap | Especifique los ajustes de línea (saltos de línea) dentro del texto.<br/>            Valor predeterminado: false. |

### Ver también

* namespace [aspose.barcode.generation](/barcode/python-net/aspose.barcode.generation/)
* assembly [Aspose.BarCode](/barcode/python-net/)

