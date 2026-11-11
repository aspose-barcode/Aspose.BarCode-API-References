---
title: "Enum DeconvolutionMode"
second_title: "Aspose.BarCode voor .NET API‑referentie"
description: "Aspose.BarCode.BarCodeRecognition.DeconvolutionMode enum. Deconvolutie‑beeldherstelmodus die het niveau van beelddegradatie definieert. Oorspronkelijk is deconvolutie een functie die een door een natuurlijke functie, zoals onscherpte bij het maken van een foto, vervormd beeld kan herstellen. Omdat we de beeldfunctie die het beeld corrumpeert niet kunnen detecteren, moeten we de meest bekende functies zoals verscherping of wiskundige morfologie controleren."
type: docs
weight: 240
url: /nl/net/aspose.barcode.barcoderecognition/deconvolutionmode/
---
## DeconvolutionMode enumeration

Deconvolutie‑modus (beeldherstel) die het niveau van beelddegradatie definieert. Oorspronkelijk is deconvolutie een functie die een door een natuurlijke functie, zoals vervaging, gedegradeerd (geconvolueerd) beeld kan herstellen bij het verkrijgen van een afbeelding met een camera. Omdat we de beeldfunctie die het beeld corrumpeert niet kunnen detecteren, moeten we de meest bekende functies zoals scherpte of wiskundige morfologie controleren.

```csharp
public enum DeconvolutionMode
```

### Waarden

| Naam | Waarde | Beschrijving |
| --- | --- | --- |
| Fast | `0` | Schakelt snelle deconvolutiemethoden in voor beelden van hoge kwaliteit. |
| Normal | `1` | Schakelt normale deconvolutiemethoden in voor gewone afbeeldingen. |
| Slow | `2` | Schakelt trage deconvolutiemethoden in voor afbeeldingen van lage kwaliteit. |

## Voorbeelden

Dit voorbeeld laat zien hoe de Deconvolution-modus te gebruiken is.

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings.Deconvolution = DeconvolutionMode.Slow;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```

### Zie ook

* namespace [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../)


