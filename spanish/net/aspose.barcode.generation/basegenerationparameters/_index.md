---
title: "Clase BaseGenerationParameters"
second_title: "Referencia de API de Aspose.BarCode para .NET"
description: "Clase Aspose.BarCode.Generation.BaseGenerationParameters. Parámetros de generación de imagen de código de barras"
type: docs
weight: 1030
url: /es/net/aspose.barcode.generation/basegenerationparameters/
---
## BaseGenerationParameters class

Parámetros de generación de imágenes de códigos de barras.

```csharp
public class BaseGenerationParameters
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AutoSizeMode](../../aspose.barcode.generation/basegenerationparameters/autosizemode/) { get; set; } | Especifica los diferentes tipos de modos de dimensionado automático. Valor predeterminado: AutoSizeMode.None. |
| [BackColor](../../aspose.barcode.generation/basegenerationparameters/backcolor/) { get; set; } | Color de fondo de la imagen del código de barras. Valor predeterminado: Color.White. Ver Color. |
| [Barcode](../../aspose.barcode.generation/basegenerationparameters/barcode/) { get; } | Obtiene los [`BarcodeParameters`](../barcodeparameters/) que contienen todas las propiedades del código de barras. |
| [Border](../../aspose.barcode.generation/basegenerationparameters/border/) { get; } | Obtiene los [`BorderParameters`](../borderparameters/) que contienen todas las propiedades de configuración del borde del código de barras. |
| [CaptionAbove](../../aspose.barcode.generation/basegenerationparameters/captionabove/) { get; } | Leyenda superior de la imagen del código de barras. Ver [`CaptionParameters`](../captionparameters/). |
| [CaptionBelow](../../aspose.barcode.generation/basegenerationparameters/captionbelow/) { get; } | Leyenda inferior de la imagen del código de barras. Ver [`CaptionParameters`](../captionparameters/). |
| [Image](../../aspose.barcode.generation/basegenerationparameters/image/) { get; } | Parámetros de imagen. Ver [`ImageParameters`](../imageparameters/). |
| [ImageHeight](../../aspose.barcode.generation/basegenerationparameters/imageheight/) { get; set; } | Altura de la imagen del código de barras cuando la propiedad [`AutoSizeMode`](./autosizemode/) está configurada a AutoSizeMode.Nearest o AutoSizeMode.Interpolation. |
| [ImageWidth](../../aspose.barcode.generation/basegenerationparameters/imagewidth/) { get; set; } | Ancho de la imagen del código de barras cuando la propiedad [`AutoSizeMode`](./autosizemode/) está configurada a AutoSizeMode.Nearest o AutoSizeMode.Interpolation. |
| [Resolution](../../aspose.barcode.generation/basegenerationparameters/resolution/) { get; set; } | Obtiene o establece la resolución de la imagen BarCode. Un valor para ambas dimensiones. Valor predeterminado: 96 dpi. |
| [RotationAngle](../../aspose.barcode.generation/basegenerationparameters/rotationangle/) { get; set; } | Ángulo de rotación de la imagen del código de barras, medido en grados, p. ej. RotationAngle = 0 o RotationAngle = 360 significa sin rotación. Si RotationAngle NO es igual a 90, 180, 270 o 0, puede aumentar la dificultad para que el escáner lea la imagen. Valor predeterminado: 0. |
| [UseAntiAlias](../../aspose.barcode.generation/basegenerationparameters/useantialias/) { get; set; } | Obtiene o establece un valor que indica si se utiliza el modo antialiasing para renderizar la imagen |

### Ver también

* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


