---
title: "enum"
linktitle: "ComplexBackgroundMode"
second_title: "Aspose.BarCode for C++ Referencia de API"
description: "Cómo usar el enum en C++."
type: docs
weight: 3700
url: /es/cpp/aspose.barcode.barcoderecognition/complexbackgroundmode/
---
## ComplexBackgroundMode enum




```cpp
enum class ComplexBackgroundMode
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| Automático | 0 | En este momento es lo mismo que Disabled. Desactiva el reconocimiento adicional de códigos de barras de color en imágenes a color. |
| Desactivado | 1 | Desactiva el reconocimiento adicional de códigos de barras de color en imágenes a color. |
| Activado | 2 | Activa el reconocimiento adicional de códigos de barras de color en imágenes a color. |

## Observaciones


Modo que habilita o deshabilita el reconocimiento adicional de códigos de barras de color en imágenes en color.

Este ejemplo muestra cómo usar el modo ComplexBackground
```cpp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings.ComplexBackground = ComplexBackgroundMode.Enabled;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```

## Ver también

* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
