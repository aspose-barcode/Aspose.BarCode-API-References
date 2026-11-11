---
title: "Clase BarCodeGeneratorControl"
second_title: "Referencia de API de Aspose.BarCode para .NET"
description: "Clase Aspose.BarCode.Windows.Forms.BarCodeGeneratorControl. Control de Windows BarCode ve a tu panel de caja de herramientas y agrega Aspose.BarCode.dll y verás que aparece BarcodeGeneratorControl. Simplemente arrástralo y suéltalo en tu formulario de Windows. ver  ver"
type: docs
weight: 1800
url: /es/net/aspose.barcode.windows.forms/barcodegeneratorcontrol/
---
## BarCodeGeneratorControl class

BarCode Windows Control, vaya a su panel de herramientas y agregue Aspose.BarCode.dll, y verá que aparece BarcodeGeneratorControl. Simplemente arrástrelo y suéltelo en su formulario Windows. ver  ver

```csharp
public sealed class BarCodeGeneratorControl : Control, IBarCodeGeneratorControl
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [BarCodeGeneratorControl](barcodegeneratorcontrol/)() | El constructor predeterminado. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AutoSizeMode](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/autosizemode/) { get; set; } | Obtiene o establece el modo por el cual el código de barras cambia de tamaño automáticamente. El valor predeterminado es AutoSizeMode.None. |
| [BackgroundColor](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/backgroundcolor/) { get; set; } | Color de fondo de la imagen del código de barras. |
| [BarCodeHeight](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/barcodeheight/) { get; } | Altura de la imagen BarCode cuando la propiedad [`AutoSizeMode`](../../aspose.barcode.generation/autosizemode/) está configurada a AutoSizeMode.Nearest o AutoSizeMode.Interpolation. |
| [BarcodePaddings](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/barcodepaddings/) { get; } | Obtiene o establece los parámetros de relleno del código de barras [`Padding`](../../aspose.barcode.generation/padding/). |
| [BarcodeType](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/barcodetype/) { get; set; } | Tipo de codificación del BarCode (simbología). Usa [`EncodeTypes`](../../aspose.barcode.generation/encodetypes/) para obtener la simbología actual. |
| [BarCodeWidth](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/barcodewidth/) { get; } | Ancho de la imagen BarCode cuando la propiedad [`AutoSizeMode`](../../aspose.barcode.generation/autosizemode/) está configurada a AutoSizeMode.Nearest o AutoSizeMode.Interpolation. |
| [BarColor](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/barcolor/) { get; set; } | Color de barras. |
| [BarHeight](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/barheight/) { get; } | Altura de las barras de códigos de barras 1D. Ignorada si la propiedad [`AutoSizeMode`](../../aspose.barcode.generation/autosizemode/) está configurada a AutoSizeMode.Nearest o AutoSizeMode.Interpolation. |
| [Border](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/border/) { get; } | Obtiene o establece los parámetros de borde [`BorderParameters`](../../aspose.barcode.generation/borderparameters/). |
| [CaptionAbove](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/captionabove/) { get; } | Título encima de la imagen BarCode. Ver [`CaptionUI`](../captionui/). |
| [CaptionBelow](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/captionbelow/) { get; } | Título debajo de la imagen BarCode. Ver [`CaptionUI`](../captionui/). |
| [ChecksumAlwaysShow](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/checksumalwaysshow/) { get; set; } | Mostrar siempre el dígito de suma de verificación en el texto legible para humanos de los códigos de barras Code128 y GS1Code128. |
| [CodeText](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/codetext/) { get; set; } | Datos a codificar, diferentes tipos de BarCode pueden tener distintas restricciones de longitud de CodeText. |
| [CodeTextParameters](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/codetextparameters/) { get; } | Obtiene o establece los parámetros de CodeText [`CodetextParametersUI`](../codetextparametersui/). |
| [EncodeType](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/encodetype/) { get; set; } | Tipo de codificación del BarCode (simbología). Usa [`EncodeTypes`](../../aspose.barcode.generation/encodetypes/) para obtener la simbología actual. |
| [FilledBars](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/filledbars/) { get; set; } | Obtiene o establece un valor que indica si las barras están rellenas. Solo para códigos de barras 1D. |
| [IsChecksumEnabled](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/ischecksumenabled/) { get; set; } | Habilitar suma de verificación durante la generación de códigos de barras 1D. |
| [Resolution](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/resolution/) { get; set; } | Obtiene o establece la resolución de la imagen BarCode. Un valor para ambas dimensiones. Valor predeterminado: 96 dpi. |
| [RotationAngle](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/rotationangle/) { get; set; } | Ángulo de rotación de la imagen del código de barras, medido en grados, p. ej. RotationAngle = 0 o RotationAngle = 360 significa sin rotación. Si RotationAngle NO es igual a 90, 180, 270 o 0, puede aumentar la dificultad para que el escáner lea la imagen. |
| [Specific](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/specific/) { get; } | Parámetros específicos |
| [ThrowExceptionWhenCodeTextIncorrect](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/throwexceptionwhencodetextincorrect/) { get; set; } | Solo para códigos de barras 1D. Si el texto del código es incorrecto y el valor se establece en true, se lanzará una excepción. De lo contrario, el texto del código se corregirá para que coincida con la especificación del código de barras. La excepción siempre se lanzará para: simbología Databar si el texto del código es incorrecto. La excepción nunca se lanzará para: AustraliaPost, SingapurePost, Code39Extended, Code93Extended, Code16K, simbología Code128 si el texto del código es incorrecto. |
| [UseAntiAlias](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/useantialias/) { get; set; } | Obtiene o establece un valor que indica si se utiliza el modo antialiasing para renderizar la imagen. |
| [WideNarrowRatio](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/widenarrowratio/) { get; set; } | Relación de barras anchas a barras estrechas. Valor predeterminado: 3, es decir, las barras anchas son 3 veces más anchas que las estrechas. Se utiliza para ITF, PZN, PharmaCode, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, IATA2of5, VIN, DeutschePost, OPC, Code32, DataLogic2of5, PatchCode, Code39, Code39FullASCII |
| [XDimension](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/xdimension/) { get; } | La X-dimensión es el ancho más pequeño de la unidad de barras o espacios del código de barras. Incrementar esto aumentará el ancho total de la imagen del código de barras. Se ignora si la propiedad [`AutoSizeMode`](../../aspose.barcode.generation/autosizemode/) está configurada en AutoSizeMode.Nearest o AutoSizeMode.Interpolation. |

### Ver también

* interface [IBarCodeGeneratorControl](../ibarcodegeneratorcontrol/)
* namespace [Aspose.BarCode.Windows.Forms](../../aspose.barcode.windows.forms/)
* assembly [Aspose.BarCode](../../)


