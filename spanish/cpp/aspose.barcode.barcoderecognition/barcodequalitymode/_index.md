---
title: "enum"
linktitle: "BarcodeQualityMode"
second_title: "Aspose.BarCode for C++ Referencia de API"
description: "Cómo usar el enum en C++."
type: docs
weight: 3600
url: /es/cpp/aspose.barcode.barcoderecognition/barcodequalitymode/
---
## BarcodeQualityMode enum




```cpp
enum class BarcodeQualityMode
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| High | 0 | Habilita los métodos de reconocimiento para códigos de barras de alta calidad. |
| Normal | 1 | Habilita los métodos de reconocimiento para códigos de barras de calidad común (Normal). |
| Low | 2 | Habilita los métodos de reconocimiento para códigos de barras de baja calidad. |

## Observaciones


Modo que habilita métodos para reconocer elementos de códigos de barras con la calidad seleccionada. Un elemento de código de barras con calidad inferior requiere métodos más complejos, lo que ralentiza el reconocimiento.

Este ejemplo muestra cómo usar el modo BarcodeQuality
```cpp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings.BarcodeQuality = BarcodeQualityMode.Low;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```

## Ver también

* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
