---
title: "enum"
linktitle: "DeconvolutionMode"
second_title: "Aspose.BarCode for C++ Referencia de API"
description: "Cómo usar el enum en C++."
type: docs
weight: 3800
url: /es/cpp/aspose.barcode.barcoderecognition/deconvolutionmode/
---
## DeconvolutionMode enum




```cpp
enum class DeconvolutionMode
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| Rápido | 0 | Activa métodos de deconvolución rápidos para imágenes de alta calidad. |
| Normal | 1 | Activa métodos de deconvolución normales para imágenes comunes. |
| Lento | 2 | Activa métodos de deconvolución lentos para imágenes de baja calidad. |

## Observaciones


Modo de deconvolución (restauración de imágenes) que define el nivel de degradación de la imagen. Originalmente, la deconvolución es una función que puede restaurar una imagen degradada (convolucionada) por cualquier función natural como el desenfoque, al obtener la imagen con una cámara. Como no podemos detectar la función que corrompe la imagen, debemos comprobar las funciones más conocidas como sharp o la morfología matemática.

Este ejemplo muestra cómo usar el modo Deconvolution
```cpp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings.Deconvolution = DeconvolutionMode.Slow;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```

## Ver también

* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
