---
title: "Enumeración XDimensionMode"
second_title: "Referencia de API de Aspose.BarCode para .NET"
description: "Enumeración Aspose.BarCode.BarCodeRecognition.XDimensionMode. Modo de reconocimiento que establece el tamaño desde 1 hasta infinito del elemento mínimo de la matriz del código de barras o barra"
type: docs
weight: 400
url: /es/net/aspose.barcode.barcoderecognition/xdimensionmode/
---
## XDimensionMode enumeration

Modo de reconocimiento que establece el tamaño (de 1 a infinito) del elemento mínimo del código de barras: celda de matriz o barra.

```csharp
public enum XDimensionMode
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| Auto | `0` | El valor de XDimension es detectado por IA (SVM). En este momento es igual a Normal |
| Small | `1` | Detecta códigos de barras con XDimension pequeña en 1 píxel o más con calidad de BarcodeQuality |
| Normal | `2` | Detecta códigos de barras con XDimension clásica en 2 píxeles o más con calidad de BarcodeQuality o códigos de barras de alta calidad. |
| Large | `3` | Detecta códigos de barras con XDimension grande con calidad de BarcodeQuality capturada con cámaras de alta resolución. |
| UseMinimalXDimension | `4` | Detecta códigos de barras con el tamaño establecido en MinimalXDimension con calidad de BarcodeQuality |

## Ejemplos

Este ejemplo muestra cómo usar el modo XDimension

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings.XDimension = XDimensionMode.Small;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```

### Ver también

* namespace [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../)


