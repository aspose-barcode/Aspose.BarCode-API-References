---
title: "Enumeración InverseImageMode"
second_title: "Referencia de API de Aspose.BarCode para .NET"
description: "Aspose.BarCode.BarCodeRecognition.InverseImageMode enum. Modo que habilita o deshabilita el reconocimiento adicional de códigos de barras en imágenes con luminancia de colores invertidos"
type: docs
weight: 270
url: /es/net/aspose.barcode.barcoderecognition/inverseimagemode/
---
## InverseImageMode enumeration

Modo que habilita o deshabilita el reconocimiento adicional de códigos de barras en imágenes con colores invertidos (luminancia).

```csharp
public enum InverseImageMode
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| Auto | `0` | Deshabilita el reconocimiento adicional de códigos de barras en imágenes inversas para todos los tipos de códigos de barras, excepto QR Code. |
| Disabled | `1` | Deshabilita el reconocimiento adicional de códigos de barras en imágenes inversas. |
| Enabled | `2` | Habilita el reconocimiento adicional de códigos de barras en imágenes inversas |

## Ejemplos

Este ejemplo muestra cómo usar el modo InverseImage

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings.InverseImage = InverseImageMode.Enabled;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```

### Ver también

* namespace [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../)


