---
title: BarcodeParameters
second_title: Referencia de API de Aspose.BarCode para .NET
description: Parámetros de generación de código de barras.
type: docs
weight: 500
url: /es/net/aspose.barcode.generation/barcodeparameters/
---
## BarcodeParameters class

Parámetros de generación de código de barras.

```csharp
public class BarcodeParameters
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AustralianPost](../../aspose.barcode.generation/barcodeparameters/australianpost) { get; } | Parámetros de código de barras de AustralianPost. |
| [Aztec](../../aspose.barcode.generation/barcodeparameters/aztec) { get; } | Parámetros aztecas. |
| [BarColor](../../aspose.barcode.generation/barcodeparameters/barcolor) { get; set; } | Color de barras. Valor por defecto: Color.Black. |
| [BarHeight](../../aspose.barcode.generation/barcodeparameters/barheight) { get; set; } | Altura de las barras de los códigos de barras 1D en[`Unit`](../unit) value. Ignorado siAutoSizeMode la propiedad se establece en AutoSizeMode.Nearest o AutoSizeMode.Interpolation. |
| [BarWidthReduction](../../aspose.barcode.generation/barcodeparameters/barwidthreduction) { get; set; } | Obtiene o establece el valor de reducción de barras que se utiliza para compensar la dispersión de tinta durante la impresión. Valor predeterminado: 0 |
| [ChecksumAlwaysShow](../../aspose.barcode.generation/barcodeparameters/checksumalwaysshow) { get; set; } | Mostrar siempre el dígito de la suma de verificación en el texto legible por humanos para los códigos de barras Code128 y GS1Code128. |
| [Codabar](../../aspose.barcode.generation/barcodeparameters/codabar) { get; } | Parámetros Codabar. |
| [Codablock](../../aspose.barcode.generation/barcodeparameters/codablock) { get; } | Parámetros Codablock. |
| [Code16K](../../aspose.barcode.generation/barcodeparameters/code16k) { get; } | Codigo16K parametros. |
| [CodeTextParameters](../../aspose.barcode.generation/barcodeparameters/codetextparameters) { get; } | Parámetros de texto en código. |
| [Coupon](../../aspose.barcode.generation/barcodeparameters/coupon) { get; } | Parámetros del cupón. Usado para UpcaGs1DatabarCoupon, UpcaGs1Code128Coupon. |
| [DataBar](../../aspose.barcode.generation/barcodeparameters/databar) { get; } | Parámetros de la barra de datos. |
| [DataMatrix](../../aspose.barcode.generation/barcodeparameters/datamatrix) { get; } | Parámetros DataMatrix. |
| [DotCode](../../aspose.barcode.generation/barcodeparameters/dotcode) { get; } | Parámetros DotCode. |
| [EnableEscape](../../aspose.barcode.generation/barcodeparameters/enableescape) { get; set; } | Indica si se explica el carácter "\" como carácter de escape en la propiedad CodeText. Usado para Pdf417, DataMatrix, Code128 only Si EnableEscape es verdadero, "\" se explicará como un carácter de escape especial. De lo contrario, "\" actúa como caracteres normales. Aspose.BarCode admite la entrada de código ascii decimal y mnemónicos para caracteres de código de control ASCII. Por ejemplo, \013 y \\CR significan CR. |
| [FilledBars](../../aspose.barcode.generation/barcodeparameters/filledbars) { get; set; } | Obtiene o establece un valor que indica si las barras se llenaron. Solo para códigos de barras 1D. Valor predeterminado: verdadero. |
| [GS1CompositeBar](../../aspose.barcode.generation/barcodeparameters/gs1compositebar) { get; set; } | Parámetros de barra compuesta GS1. |
| [IsChecksumEnabled](../../aspose.barcode.generation/barcodeparameters/ischecksumenabled) { get; set; } | Habilite la suma de comprobación durante la generación de códigos de barras 1D. |
| [ITF](../../aspose.barcode.generation/barcodeparameters/itf) { get; } | Parámetros ITF. |
| [MaxiCode](../../aspose.barcode.generation/barcodeparameters/maxicode) { get; } | Parámetros MaxiCode. |
| [Padding](../../aspose.barcode.generation/barcodeparameters/padding) { get; } | Rellenos de código de barras. Valor predeterminado: 5pt 5pt 5pt 5pt. |
| [PatchCode](../../aspose.barcode.generation/barcodeparameters/patchcode) { get; } | Parámetros de código de parche. |
| [Pdf417](../../aspose.barcode.generation/barcodeparameters/pdf417) { get; } | Parámetros PDF417. |
| [Postal](../../aspose.barcode.generation/barcodeparameters/postal) { get; } | Parámetros postales. Usado para Postnet, Planet. |
| [QR](../../aspose.barcode.generation/barcodeparameters/qr) { get; } | Parámetros QR. |
| [Supplement](../../aspose.barcode.generation/barcodeparameters/supplement) { get; } | Parámetros de suplemento. Usado para Interleaved2of5, Standard2of5, EAN13, EAN8, UPCA, UPCE, ISBN, ISSN, ISMN. |
| [ThrowExceptionWhenCodeTextIncorrect](../../aspose.barcode.generation/barcodeparameters/throwexceptionwhencodetextincorrect) { get; set; } | Solo para códigos de barras 1D. Si el texto del código es incorrecto y el valor se establece en verdadero, se generará una excepción. De lo contrario, el texto del código se corregirá para que coincida con la especificación del código de barras. Siempre se lanzará una excepción para: Simbología de la barra de datos si el texto del código es incorrecto. . |
| [WideNarrowRatio](../../aspose.barcode.generation/barcodeparameters/widenarrowratio) { get; set; } | Relación entre barras anchas y barras estrechas. Valor predeterminado: 3, es decir, las barras anchas son 3 veces más anchas que las estrechas. Se utiliza para ITF, PZN, PharmaCode, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, IATA2of5, VIN, DeutschePost , OPC, Code32, DataLogic2of5, PatchCode, Code39Extended, Code39Standard |
| [XDimension](../../aspose.barcode.generation/barcodeparameters/xdimension) { get; set; } | la dimensión x es el ancho más pequeño de la unidad de barras o espacios del código de barras. Aumentar esto aumentará el ancho completo de la imagen del código de barras.AutoSizeMode la propiedad se establece en AutoSizeMode.Nearest o AutoSizeMode.Interpolation. |

### Ver también

* espacio de nombres [Aspose.BarCode.Generation](../../aspose.barcode.generation)
* asamblea [Aspose.BarCode](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->
