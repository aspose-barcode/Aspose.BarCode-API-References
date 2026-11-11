---
title: "Clase BarcodeParameters"
second_title: "Referencia de API de Aspose.BarCode para .NET"
description: "Clase Aspose.BarCode.Generation.BarcodeParameters. Parámetros de generación de códigos de barras"
type: docs
weight: 1010
url: /es/net/aspose.barcode.generation/barcodeparameters/
---
## BarcodeParameters class

Parámetros de generación de códigos de barras.

```csharp
public class BarcodeParameters
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AustralianPost](../../aspose.barcode.generation/barcodeparameters/australianpost/) { get; } | Parámetros del código de barras AustralianPost. |
| [Aztec](../../aspose.barcode.generation/barcodeparameters/aztec/) { get; } | Parámetros de Aztec. |
| [BarColor](../../aspose.barcode.generation/barcodeparameters/barcolor/) { get; set; } | Color de barras. Valor predeterminado: Color.Black. |
| [BarHeight](../../aspose.barcode.generation/barcodeparameters/barheight/) { get; set; } | Altura de las barras de códigos de barras 1D en valor de [`Unit`](../unit/). Se ignora si la propiedad [`AutoSizeMode`](../basegenerationparameters/autosizemode/) está establecida en AutoSizeMode.Nearest o AutoSizeMode.Interpolation. |
| [BarWidthReduction](../../aspose.barcode.generation/barcodeparameters/barwidthreduction/) { get; set; } | Obtiene o establece el valor de reducción de barras que se usa para compensar la difusión de tinta al imprimir. Valor predeterminado: 0 |
| [ChecksumAlwaysShow](../../aspose.barcode.generation/barcodeparameters/checksumalwaysshow/) { get; set; } | Mostrar siempre el dígito de suma de verificación en el texto legible para humanos de los códigos de barras Code128 y GS1Code128. |
| [Codabar](../../aspose.barcode.generation/barcodeparameters/codabar/) { get; } | Parámetros de Codabar. |
| [Codablock](../../aspose.barcode.generation/barcodeparameters/codablock/) { get; } | Parámetros de Codablock. |
| [Code128](../../aspose.barcode.generation/barcodeparameters/code128/) { get; } | Parámetros de Code128. |
| [Code16K](../../aspose.barcode.generation/barcodeparameters/code16k/) { get; } | Parámetros de Code16K. |
| [CodeTextParameters](../../aspose.barcode.generation/barcodeparameters/codetextparameters/) { get; } | Parámetros de codetext. |
| [Coupon](../../aspose.barcode.generation/barcodeparameters/coupon/) { get; } | Parámetros de cupón. Usado para UpcaGs1DatabarCoupon, UpcaGs1Code128Coupon. |
| [DataBar](../../aspose.barcode.generation/barcodeparameters/databar/) { get; } | Parámetros de Databar. |
| [DataMatrix](../../aspose.barcode.generation/barcodeparameters/datamatrix/) { get; } | Parámetros de DataMatrix. |
| [DotCode](../../aspose.barcode.generation/barcodeparameters/dotcode/) { get; } | Parámetros de DotCode. |
| [FilledBars](../../aspose.barcode.generation/barcodeparameters/filledbars/) { get; set; } | Obtiene o establece un valor que indica si las barras están rellenas. Solo para códigos de barras 1D. Valor predeterminado: true. |
| [GS1](../../aspose.barcode.generation/barcodeparameters/gs1/) { get; } | Parámetros de GS1. |
| [GS1CompositeBar](../../aspose.barcode.generation/barcodeparameters/gs1compositebar/) { get; set; } | Parámetros de barra compuesta GS1. |
| [HanXin](../../aspose.barcode.generation/barcodeparameters/hanxin/) { get; } | Parámetros HanXin. |
| [IsChecksumEnabled](../../aspose.barcode.generation/barcodeparameters/ischecksumenabled/) { get; set; } | Habilitar suma de verificación durante la generación de códigos de barras 1D. |
| [ITF](../../aspose.barcode.generation/barcodeparameters/itf/) { get; } | Parámetros de ITF. |
| [MaxiCode](../../aspose.barcode.generation/barcodeparameters/maxicode/) { get; } | Parámetros de MaxiCode. |
| [Padding](../../aspose.barcode.generation/barcodeparameters/padding/) { get; } | Rellenos del código de barras. Valor predeterminado: 5pt 5pt 5pt 5pt. |
| [PatchCode](../../aspose.barcode.generation/barcodeparameters/patchcode/) { get; } | Parámetros de PatchCode. |
| [Pdf417](../../aspose.barcode.generation/barcodeparameters/pdf417/) { get; } | Parámetros PDF417. |
| [Postal](../../aspose.barcode.generation/barcodeparameters/postal/) { get; } | Parámetros postales. Usado para Postnet, Planet. |
| [QR](../../aspose.barcode.generation/barcodeparameters/qr/) { get; } | Parámetros QR, MicroQR y RectMicroQR. |
| [Supplement](../../aspose.barcode.generation/barcodeparameters/supplement/) { get; } | Parámetros suplementarios. Usado para Interleaved2of5, Standard2of5, EAN13, EAN8, UPCA, UPCE, ISBN, ISSN, ISMN. |
| [ThrowExceptionWhenCodeTextIncorrect](../../aspose.barcode.generation/barcodeparameters/throwexceptionwhencodetextincorrect/) { get; set; } | Solo para códigos de barras 1D. Si el texto del código es incorrecto y el valor se establece en true, se lanzará una excepción. De lo contrario, el texto del código se corregirá para cumplir con la especificación del código de barras. La excepción siempre se lanzará para: la simbología Databar si el texto del código es incorrecto. La excepción nunca se lanzará para: AustraliaPost, SingapurePost, Code39FullASCII, Code93, Code16K, simbología Code128 si el texto del código es incorrecto. |
| [WideNarrowRatio](../../aspose.barcode.generation/barcodeparameters/widenarrowratio/) { get; set; } | Relación de barras anchas a barras estrechas. Valor predeterminado: 3, es decir, las barras anchas son 3 veces más anchas que las estrechas. Se utiliza para ITF, PZN, PharmaCode, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, IATA2of5, VIN, DeutschePost, OPC, Code32, DataLogic2of5, PatchCode, Code39, Code39FullASCII |
| [XDimension](../../aspose.barcode.generation/barcodeparameters/xdimension/) { get; set; } | La x-dimensión es el ancho más pequeño de la unidad de barras o espacios del código de barras. Incrementar esto aumentará el ancho total de la imagen del código de barras. Se ignora si la propiedad [`AutoSizeMode`](../basegenerationparameters/autosizemode/) está establecida en AutoSizeMode.Nearest o AutoSizeMode.Interpolation. |

### Ver también

* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


