---
title: "enum"
linktitle: "InverseImageMode"
second_title: "Aspose.BarCode for C++ Referencia de API"
description: "Cómo usar el enum en C++."
type: docs
weight: 3900
url: /es/cpp/aspose.barcode.barcoderecognition/inverseimagemode/
---
## InverseImageMode enum




```cpp
enum class InverseImageMode
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| Auto | 0 | Desactiva el reconocimiento adicional de códigos de barras en imágenes inversas para todos los tipos de códigos de barras excepto el código [QR](../../aspose.barcode.barcoderecognition.qr/). |
| Desactivado | 1 | Desactiva el reconocimiento adicional de códigos de barras en imágenes inversas. |
| Activado | 2 | Activa el reconocimiento adicional de códigos de barras en imágenes inversas |

## Observaciones


Modo que habilita o deshabilita el reconocimiento adicional de códigos de barras en imágenes con colores invertidos (luminancia).

Este ejemplo muestra cómo usar el modo InverseImage
```cpp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings.InverseImage = InverseImageMode.Enabled;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```

## Ver también

* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
