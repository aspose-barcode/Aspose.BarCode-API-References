---
title: "enum"
linktitle: "XDimensionMode"
second_title: "Aspose.BarCode for C++ Referencia de API"
description: "Cómo usar el enum en C++."
type: docs
weight: 4000
url: /es/cpp/aspose.barcode.barcoderecognition/xdimensionmode/
---
## XDimensionMode enum




```cpp
enum class XDimensionMode
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| Automático | 0 | El valor de XDimension es detectado por IA (SVM). En este momento es el mismo que Normal |
| Pequeño | 1 | Detecta códigos de barras con XDimension pequeña de 1 píxel o más con calidad de BarcodeQuality |
| Normal | 2 | Detecta códigos de barras con XDimension clásica de 2 píxeles o más con calidad de BarcodeQuality o códigos de barras de alta calidad. |
| Grande | 3 | Detecta códigos de barras con XDimension grande con calidad de BarcodeQuality capturada con cámaras de alta resolución. |
| UseMinimalXDimension | 4 | Detecta códigos de barras a partir del tamaño establecido en MinimalXDimension con calidad de BarcodeQuality |

## Observaciones


[Recognition](../../aspose.barcode.barcoderecognition.recognition/) mode which sets size (from 1 to infinity) of barcode minimal element: matrix cell or bar. 

Este ejemplo muestra cómo usar el modo XDimension
```cpp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings.XDimension = XDimensionMode.Small;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```

## Ver también

* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
