---
title: "Enumeración DeconvolutionMode"
second_title: "Referencia de API de Aspose.BarCode para .NET"
description: "Aspose.BarCode.BarCodeRecognition.DeconvolutionMode enum. Modo de restauración de imágenes por deconvolución que define el nivel de degradación de la imagen. Originalmente, la deconvolución es una función que puede restaurar una imagen degradada y convolucionada por cualquier función natural como el desenfoque al obtener la imagen con una cámara. Debido a que no podemos detectar la función de la imagen que la corrompe, debemos comprobar las funciones más conocidas como sharp o morfología matemática."
type: docs
weight: 240
url: /es/net/aspose.barcode.barcoderecognition/deconvolutionmode/
---
## DeconvolutionMode enumeration

Modo de deconvolución (restauración de imágenes) que define el nivel de degradación de la imagen. Originalmente, la deconvolución es una función que puede restaurar una imagen degradada (convolucionada) por cualquier función natural como el desenfoque, al obtener la imagen con una cámara. Como no podemos detectar la función que corrompe la imagen, debemos comprobar las funciones más conocidas, como sharpen o la morfología matemática.

```csharp
public enum DeconvolutionMode
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| Fast | `0` | Habilita métodos rápidos de deconvolución para imágenes de alta calidad. |
| Normal | `1` | Habilita los métodos de deconvolución normales para imágenes comunes. |
| Slow | `2` | Habilita los métodos de deconvolución lentos para imágenes de baja calidad. |

## Ejemplos

Este ejemplo muestra cómo usar el modo Deconvolution

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings.Deconvolution = DeconvolutionMode.Slow;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```

### Ver también

* namespace [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../)


