---
title: "enum"
linktitle: "BarcodeQualityMode"
second_title: "Aspose.BarCode für C++ API-Referenz"
description: "Wie man das enum in C++ verwendet."
type: docs
weight: 3600
url: /de/cpp/aspose.barcode.barcoderecognition/barcodequalitymode/
---
## BarcodeQualityMode enum




```cpp
enum class BarcodeQualityMode
```

### Werte

| Name | Wert | Beschreibung |
| --- | --- | --- |
| High | 0 | Aktiviert Erkennungsmethoden für Barcodes hoher Qualität. |
| Normal | 1 | Aktiviert Erkennungsmethoden für Barcodes mit üblicher (normaler) Qualität. |
| Low | 2 | Aktiviert Erkennungsmethoden für Barcodes von niedriger Qualität. |

## Hinweise


Modus, der Methoden aktiviert, um Strichcode-Elemente mit der ausgewählten Qualität zu erkennen. Ein Strichcode-Element mit niedrigerer Qualität erfordert aufwändigere Methoden, was die Erkennung verlangsamt.

Dieses Beispiel zeigt, wie der BarcodeQuality‑Modus verwendet wird.
```cpp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings.BarcodeQuality = BarcodeQualityMode.Low;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```

## Siehe auch

* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
