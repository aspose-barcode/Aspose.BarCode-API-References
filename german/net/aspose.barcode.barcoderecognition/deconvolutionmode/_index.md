---
title: "Enum DeconvolutionMode"
second_title: "Aspose.BarCode für .NET API-Referenz"
description: "Aspose.BarCode.BarCodeRecognition.DeconvolutionMode enum. Deconvolution Bildwiederherstellungsmodus, der das Niveau der Bilddegradation definiert. Ursprünglich ist Deconvolution eine Funktion, die ein durch eine beliebige natürliche Funktion wie Unschärfe beim Aufnehmen des Bildes mit der Kamera verwischtes Bild wiederherstellen kann. Da wir die Bildfunktion, die das Bild beschädigt, nicht erkennen können, müssen wir die am besten bekannten Funktionen wie Schärfen oder mathematische Morphologie prüfen."
type: docs
weight: 240
url: /de/net/aspose.barcode.barcoderecognition/deconvolutionmode/
---
## DeconvolutionMode enumeration

Deconvolution‑Modus (Bildrestaurierung), der das Niveau der Bilddegradation definiert. Ursprünglich ist Deconvolution eine Funktion, die ein durch eine natürliche Funktion wie Unschärfe (Blur) degradierte (konvolutierte) Bild wiederherstellen kann, das bei der Aufnahme mit einer Kamera entsteht. Da wir die Bildfunktion, die das Bild beschädigt, nicht erkennen können, müssen wir die am besten bekannten Funktionen wie Schärfen oder mathematische Morphologie prüfen.

```csharp
public enum DeconvolutionMode
```

### Werte

| Name | Wert | Beschreibung |
| --- | --- | --- |
| Fast | `0` | Aktiviert schnelle Deconvolution-Methoden für hochqualitative Bilder. |
| Normal | `1` | Aktiviert normale Deconvolution-Methoden für gängige Bilder. |
| Slow | `2` | Aktiviert langsame Deconvolution-Methoden für Bilder niedriger Qualität. |

## Beispiele

Dieses Beispiel zeigt, wie man den Deconvolution-Modus verwendet

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings.Deconvolution = DeconvolutionMode.Slow;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```

### Siehe auch

* namespace [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../)


