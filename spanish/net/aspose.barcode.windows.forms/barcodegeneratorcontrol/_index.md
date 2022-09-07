---
title: BarCodeGeneratorControl
second_title: Referencia de API de Aspose.BarCode para .NET
description: BarCode Windows Control vaya al panel de su caja de herramientas y agregue Aspose.BarCode.dll y verá que aparece BarcodeGeneratorControl. Simplemente arrástrelo y suéltelo en su formulario de Windows. ver ver
type: docs
weight: 1050
url: /es/net/aspose.barcode.windows.forms/barcodegeneratorcontrol/
---
## BarCodeGeneratorControl class

BarCode Windows Control, vaya al panel de su caja de herramientas y agregue Aspose.BarCode.dll, y verá que aparece BarcodeGeneratorControl. Simplemente arrástrelo y suéltelo en su formulario de Windows. ver ver

```csharp
public sealed class BarCodeGeneratorControl : Control, IBarCodeGeneratorControl
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [BarCodeGeneratorControl](barcodegeneratorcontrol)() | Constructor predeterminado |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AutoSizeMode](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/autosizemode) { get; set; } | Obtiene o establece el modo en que el código de barras cambia de tamaño automáticamente. El valor predeterminado es AutoSizeMode.None. |
| [BackgroundColor](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/backgroundcolor) { get; set; } | Color de fondo de la imagen del código de barras. |
| [BarCodeHeight](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/barcodeheight) { get; } | Altura de la imagen del código de barras cuando[`AutoSizeMode`](../../aspose.barcode.generation/autosizemode) la propiedad se establece en AutoSizeMode.Nearest o AutoSizeMode.Interpolation. |
| [BarcodePaddings](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/barcodepaddings) { get; } | Obtiene o establece parámetros de relleno de código de barras[`Padding`](../../aspose.barcode.generation/padding) . |
| [BarcodeType](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/barcodetype) { get; set; } | Tipo de codificación de BarCode (simbología). Uso[`EncodeTypes`](../../aspose.barcode.generation/encodetypes) para obtener la simbología actual. |
| [BarCodeWidth](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/barcodewidth) { get; } | Ancho de imagen de código de barras cuando[`AutoSizeMode`](../../aspose.barcode.generation/autosizemode) la propiedad se establece en AutoSizeMode.Nearest o AutoSizeMode.Interpolation. |
| [BarColor](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/barcolor) { get; set; } | Color de barras. |
| [BarHeight](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/barheight) { get; } | Altura de las barras de los códigos de barras 1D. Ignorado si[`AutoSizeMode`](../../aspose.barcode.generation/autosizemode) la propiedad se establece en AutoSizeMode.Nearest o AutoSizeMode.Interpolation. |
| [Border](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/border) { get; } | Obtiene o establece parámetros de borde[`BorderParameters`](../../aspose.barcode.generation/borderparameters) . |
| [CaptionAbove](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/captionabove) { get; } | Leyenda encima de la imagen del código de barras. Ver[`CaptionParameters`](../../aspose.barcode.generation/captionparameters) . |
| [CaptionBelow](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/captionbelow) { get; } | Leyenda debajo de la imagen del código de barras. Ver[`CaptionParameters`](../../aspose.barcode.generation/captionparameters) . |
| [ChecksumAlwaysShow](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/checksumalwaysshow) { get; set; } | Mostrar siempre el dígito de la suma de verificación en el texto legible por humanos para los códigos de barras Code128 y GS1Code128. |
| [CodeText](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/codetext) { get; set; } | Datos a codificar, diferentes tipos de código de barras pueden tener diferentes restricciones de longitud de CodeText. |
| [CodeTextParameters](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/codetextparameters) { get; } | Obtiene o establece parámetros CodeText[`CodetextParameters`](../../aspose.barcode.generation/codetextparameters) . |
| [EnableEscape](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/enableescape) { get; set; } | Indica si se explica el carácter "\" como carácter de escape en la propiedad CodeText. Usado para Pdf417, DataMatrix, Code128 only Si EnableEscape es verdadero, "\" se explicará como un carácter de escape especial. De lo contrario, "\" actúa como caracteres normales. Aspose.BarCode admite la entrada de código ascii decimal y mnemónicos para caracteres de código de control ASCII. Por ejemplo, \013 y \\CR significan CR. |
| [EncodeType](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/encodetype) { get; set; } | Tipo de codificación de BarCode (simbología). Uso[`EncodeTypes`](../../aspose.barcode.generation/encodetypes) para obtener la simbología actual. |
| [FilledBars](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/filledbars) { get; set; } | Obtiene o establece un valor que indica si las barras se llenaron. Solo para códigos de barras 1D. |
| [IsChecksumEnabled](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/ischecksumenabled) { get; set; } | Habilite la suma de comprobación durante la generación de códigos de barras 1D. |
| [Resolution](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/resolution) { get; set; } | Obtiene o establece la resolución de la imagen del código de barras. Un valor para ambas dimensiones. Valor predeterminado: 96 ppp. |
| [RotationAngle](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/rotationangle) { get; set; } | Ángulo de rotación de la imagen del código de barras, medido en grados, por ejemplo, RotationAngle = 0 o RotationAngle = 360 significa que no hay rotación. Si RotationAngle NO es igual a 90, 180, 270 o 0, puede aumentar la dificultad para que el escáner lea la imagen. |
| [Specific](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/specific) { get; } | Parámetros específicos |
| [ThrowExceptionWhenCodeTextIncorrect](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/throwexceptionwhencodetextincorrect) { get; set; } | Solo para códigos de barras 1D. Si el texto del código es incorrecto y el valor se establece en verdadero, se generará una excepción. De lo contrario, el texto del código se corregirá para que coincida con la especificación del código de barras. Siempre se lanzará una excepción para: Simbología de la barra de datos si el texto del código es incorrecto. . |
| [WideNarrowRatio](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/widenarrowratio) { get; set; } | Relación entre barras anchas y barras estrechas. Valor predeterminado: 3, es decir, las barras anchas son 3 veces más anchas que las estrechas. Se utiliza para ITF, PZN, PharmaCode, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, IATA2of5, VIN, DeutschePost , OPC, Code32, DataLogic2of5, PatchCode, Code39Extended, Code39Standard |
| [XDimension](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/xdimension) { get; } | La dimensión X es el ancho más pequeño de la unidad de barras o espacios del código de barras. Aumentar esto aumentará el ancho completo de la imagen del código de barras. Se ignora si[`AutoSizeMode`](../../aspose.barcode.generation/autosizemode) la propiedad se establece en AutoSizeMode.Nearest o AutoSizeMode.Interpolation. |

### Ver también

* interface [IBarCodeGeneratorControl](../ibarcodegeneratorcontrol)
* espacio de nombres [Aspose.BarCode.Windows.Forms](../../aspose.barcode.windows.forms)
* asamblea [Aspose.BarCode](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->
