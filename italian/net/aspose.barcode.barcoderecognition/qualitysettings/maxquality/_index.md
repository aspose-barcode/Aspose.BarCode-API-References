---
title: "QualitySettings.MaxQuality"
second_title: "Riferimento API Aspose.BarCode per .NET"
description: "Proprietà QualitySettings. Preset di qualità di riconoscimento MaxQuality. Questo preset è sviluppato per riconoscere tutti i possibili codici a barre, anche quelli errati"
type: docs
weight: 30
url: /it/net/aspose.barcode.barcoderecognition/qualitysettings/maxquality/
---
## QualitySettings.MaxQuality property

Preset di qualità di riconoscimento MaxQuality. Questo preset è sviluppato per riconoscere tutti i possibili codici a barre, anche quelli errati.

```csharp
public static QualitySettings MaxQuality { get; }
```

### Property Value

Preset di qualità di riconoscimento MaxQuality.

## Esempi

Questo esempio mostra come utilizzare la modalità MaxQuality

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings = QualitySettings.MaxQuality;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```

### Vedi anche

* class [QualitySettings](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)


