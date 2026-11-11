---
title: "QualitySettings.HighQuality"
second_title: "Referencia de API de Aspose.BarCode para .NET"
description: "Propiedad QualitySettings. Preajuste de calidad de reconocimiento HighQuality. Este preajuste está desarrollado para códigos de barras de baja calidad. Permite detectar códigos de barras altamente dañados"
type: docs
weight: 20
url: /es/net/aspose.barcode.barcoderecognition/qualitysettings/highquality/
---
## QualitySettings.HighQuality property

Preajuste de calidad de reconocimiento HighQuality. Este preajuste está desarrollado para códigos de barras de baja calidad. Permite detectar códigos de barras altamente dañados.

```csharp
public static QualitySettings HighQuality { get; }
```

### Property Value

Preajuste de calidad de reconocimiento HighQuality.

## Ejemplos

Este ejemplo muestra cómo usar el modo HighQuality

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings = QualitySettings.HighQuality;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```

### Ver también

* class [QualitySettings](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)


