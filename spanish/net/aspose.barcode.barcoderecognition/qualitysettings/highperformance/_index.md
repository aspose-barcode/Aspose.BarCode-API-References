---
title: "QualitySettings.HighPerformance"
second_title: "Referencia de API de Aspose.BarCode para .NET"
description: "Propiedad QualitySettings. Preajuste de calidad de reconocimiento HighPerformance. Los códigos de barras de alta calidad se reconocen bien en este modo."
type: docs
weight: 10
url: /es/net/aspose.barcode.barcoderecognition/qualitysettings/highperformance/
---
## QualitySettings.HighPerformance property

Preajuste de calidad de reconocimiento HighPerformance. Los códigos de barras de alta calidad se reconocen bien en este modo.

```csharp
public static QualitySettings HighPerformance { get; }
```

### Property Value

Preajuste de calidad de reconocimiento HighPerformance.

## Ejemplos

Este ejemplo muestra cómo usar el modo HighPerformance.

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings = QualitySettings.HighPerformance;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```

### Ver también

* class [QualitySettings](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)


