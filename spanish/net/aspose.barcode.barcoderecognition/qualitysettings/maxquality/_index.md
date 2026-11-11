---
title: "QualitySettings.MaxQuality"
second_title: "Referencia de API de Aspose.BarCode para .NET"
description: "Propiedad QualitySettings. Preajuste de calidad de reconocimiento MaxQuality. Este preajuste está desarrollado para reconocer todos los códigos de barras posibles, incluso códigos de barras incorrectos"
type: docs
weight: 30
url: /es/net/aspose.barcode.barcoderecognition/qualitysettings/maxquality/
---
## QualitySettings.MaxQuality property

Preajuste de calidad de reconocimiento MaxQuality. Este preajuste está desarrollado para reconocer todos los códigos de barras posibles, incluso códigos de barras incorrectos.

```csharp
public static QualitySettings MaxQuality { get; }
```

### Property Value

Preajuste de calidad de reconocimiento MaxQuality.

## Ejemplos

Este ejemplo muestra cómo usar el modo MaxQuality

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings = QualitySettings.MaxQuality;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```

### Ver también

* class [QualitySettings](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)


