---
title: "enum"
linktitle: "DeconvolutionMode"
second_title: "Aspose.BarCode für C++ API-Referenz"
description: "Wie man das enum in C++ verwendet."
type: docs
weight: 3800
url: /de/cpp/aspose.barcode.barcoderecognition/deconvolutionmode/
---
## DeconvolutionMode enum




```cpp
enum class DeconvolutionMode
```

### Werte

| Name | Wert | Beschreibung |
| --- | --- | --- |
| Schnell | 0 | Aktiviert schnelle Deconvolution-Methoden für hochqualitative Bilder. |
| Normal | 1 | Aktiviert normale Deconvolution-Methoden für gängige Bilder. |
| Langsam | 2 | Aktiviert langsame Deconvolution-Methoden für minderwertige Bilder |

## Hinweise


Deconvolution (Bildrestaurierung) Modus, der das Niveau der Bilddegradation definiert. Ursprünglich ist Deconvolution eine Funktion, die ein durch eine natürliche Funktion wie Unschärfe degradierte (konvolutierte) Bild wiederherstellen kann, das bei der Aufnahme mit einer Kamera entsteht. Da wir die Bildfunktion, die das Bild beschädigt, nicht erkennen können, müssen wir die am besten bekannten Funktionen wie Schärfen oder mathematische Morphologie prüfen.

Dieses Beispiel zeigt, wie der Deconvolution-Modus verwendet wird
```cpp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings.Deconvolution = DeconvolutionMode.Slow;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```

## Siehe auch

* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
