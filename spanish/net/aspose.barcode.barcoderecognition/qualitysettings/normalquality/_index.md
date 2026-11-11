---
title: "QualitySettings.NormalQuality"
second_title: "Referencia de API de Aspose.BarCode para .NET"
description: "Propiedad QualitySettings. Preajuste de calidad de reconocimiento NormalQuality. Adecuado para la mayoría de los códigos de barras"
type: docs
weight: 40
url: /es/net/aspose.barcode.barcoderecognition/qualitysettings/normalquality/
---
## QualitySettings.NormalQuality property

Preajuste de calidad de reconocimiento NormalQuality. Adecuado para la mayoría de los códigos de barras

```csharp
public static QualitySettings NormalQuality { get; }
```

### Property Value

Preajuste de calidad de reconocimiento NormalQuality.

## Ejemplos

Este ejemplo muestra cómo usar el modo NormalQuality

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings = QualitySettings.NormalQuality;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```

### Ver también

* class [QualitySettings](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)


