---
title: "Enumeración BarcodeQualityMode"
second_title: "Referencia de API de Aspose.BarCode para .NET"
description: "Aspose.BarCode.BarCodeRecognition.BarcodeQualityMode enum. Modo que permite que los métodos reconozcan elementos de código de barras con la calidad seleccionada. Un elemento de código de barras con menor calidad requiere métodos más complejos, lo que ralentiza el reconocimiento."
type: docs
weight: 110
url: /es/net/aspose.barcode.barcoderecognition/barcodequalitymode/
---
## BarcodeQualityMode enumeration

Modo que permite a los métodos reconocer elementos de código de barras con la calidad seleccionada. Un elemento de código de barras con calidad inferior requiere métodos más complejos, lo que ralentiza el reconocimiento.

```csharp
public enum BarcodeQualityMode
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| High | `0` | Habilita los métodos de reconocimiento para códigos de barras de alta calidad. |
| Normal | `1` | Habilita los métodos de reconocimiento para códigos de barras de calidad común (normal). |
| Low | `2` | Habilita los métodos de reconocimiento para códigos de barras de baja calidad. |

## Ejemplos

Este ejemplo muestra cómo usar el modo BarcodeQuality.

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings.BarcodeQuality = BarcodeQualityMode.Low;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```

### Ver también

* namespace [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../)


