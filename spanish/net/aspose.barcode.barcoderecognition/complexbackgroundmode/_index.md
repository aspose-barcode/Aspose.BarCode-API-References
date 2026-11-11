---
title: "Enum ComplexBackgroundMode"
second_title: "Referencia de API de Aspose.BarCode para .NET"
description: "Aspose.BarCode.BarCodeRecognition.ComplexBackgroundMode enum. Modo que habilita o deshabilita el reconocimiento adicional de códigos de barras de color en imágenes a color."
type: docs
weight: 200
url: /es/net/aspose.barcode.barcoderecognition/complexbackgroundmode/
---
## ComplexBackgroundMode enumeration

Modo que habilita o deshabilita el reconocimiento adicional de códigos de barras de color en imágenes a color.

```csharp
public enum ComplexBackgroundMode
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| Auto | `0` | En este momento es lo mismo que Disabled. Deshabilita el reconocimiento adicional de códigos de barras de color en imágenes a color. |
| Disabled | `1` | Deshabilita el reconocimiento adicional de códigos de barras de color en imágenes a color. |
| Enabled | `2` | Habilita el reconocimiento adicional de códigos de barras de color en imágenes a color. |

## Ejemplos

Este ejemplo muestra cómo usar el modo ComplexBackground

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings.ComplexBackground = ComplexBackgroundMode.Enabled;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```

### Ver también

* namespace [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../)


