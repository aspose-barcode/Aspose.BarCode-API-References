---
title: "BarcodeParameters"
second_title: "Referencia de API de Aspose.BarCode para Python a través de .NET"
description: 
type: docs
url: /es/python-net/aspose.barcode.generation/barcodeparameters/
---

## BarcodeParameters class

Parámetros de generación de códigos de barras.

El tipo BarcodeParameters expone los siguientes miembros:
## Propiedades
| Nombre | Descripción |
| :- | :- |
| x_dimension | x-dimension es el ancho más pequeño de la unidad de barras o espacios del código de barras.<br/>            Aumentar esto incrementará el ancho total de la imagen del código de barras.<br/>            Se ignora si la propiedad [auto_size_mode](/barcode/python-net/aspose.barcode.generation/basegenerationparameters/) está configurada como AutoSizeMode.Nearest o AutoSizeMode.Interpolation. |
| bar_height | Altura de las barras de códigos de barras 1D en unidades [Unit](/barcode/python-net/aspose.barcode.generation/unit/).<br/>            Se ignora si la propiedad [auto_size_mode](/barcode/python-net/aspose.barcode.generation/basegenerationparameters/) está configurada como AutoSizeMode.Nearest o AutoSizeMode.Interpolation. |
| bar_color | Color de las barras.<br/>            Valor predeterminado: Color.Black. |
| padding | Rellenos del código de barras.<br/>            Valor predeterminado: 5pt 5pt 5pt 5pt. |
| checksum_always_show | Mostrar siempre el dígito de suma de verificación en el texto legible para humanos de los códigos de barras Code128 y GS1Code128. |
| is_checksum_enabled |  |
| throw_exception_when_code_text_incorrect | Solo para códigos de barras 1D.<br/>            Si el texto del código es incorrecto y el valor está configurado como true, se lanzará una excepción. De lo contrario, el texto del código se corregirá para cumplir con la especificación del código de barras.<br/>            La excepción siempre se lanzará para: la simbología Databar si el texto del código es incorrecto.<br/>            La excepción nunca se lanzará para: AustraliaPost, SingapurePost, Code39FullASCII, Code93, Code16K, la simbología Code128 si el texto del código es incorrecto. |
| wide_narrow_ratio | Relación entre barras anchas y barras estrechas.<br/>            Valor predeterminado: 3, es decir, las barras anchas son 3 veces más anchas que las barras estrechas.<br/>            Se utiliza para ITF, PZN, PharmaCode, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, IATA2of5, VIN, DeutschePost, OPC, Code32, DataLogic2of5, PatchCode, Code39, Code39FullASCII. |
| code_text_parameters | Parámetros de Codetext. |
| filled_bars | Obtiene o establece un valor que indica si las barras están rellenas.<br/>            Solo para códigos de barras 1D.<br/>            Valor predeterminado: true. |
| bar_width_reduction | Obtiene o establece el valor de reducción de ancho de barra que se usa para compensar la difusión de tinta al imprimir.<br/>            Valor predeterminado: 0. |
| postal | Parámetros postales. Usado para Postnet, Planet. |
| patch_code | Parámetros de PatchCode. |
| australian_post | Parámetros del código de barras AustralianPost. |
| data_bar | Parámetros de Databar. |
| gs1_composite_bar | Parámetros de GS1 Composite Bar. |
| codablock | Parámetros de Codablock. |
| data_matrix | Parámetros de DataMatrix. |
| code_16k | Parámetros de Code16K. |
| dot_code | Parámetros de DotCode. |
| itf | Parámetros de ITF. |
| pdf417 | Parámetros de PDF417. |
| qr | Parámetros de QR, MicroQR y RectMicroQR. |
| supplement | Parámetros suplementarios. Usado para Interleaved2of5, Standard2of5, EAN13, EAN8, UPCA, UPCE, ISBN, ISSN, ISMN. |
| maxi_code | Parámetros de MaxiCode. |
| aztec | Parámetros de Aztec. |
| code128 | Parámetros de Code128. |
| codabar | Parámetros de Codabar. |
| coupon | Parámetros de cupón. Usado para UpcaGs1DatabarCoupon, UpcaGs1Code128Coupon. |
| han_xin | Parámetros de HanXin. |
| gs1 | Parámetros de GS1. |

### Ver también

* namespace [aspose.barcode.generation](/barcode/python-net/aspose.barcode.generation/)
* assembly [Aspose.BarCode](/barcode/python-net/)

