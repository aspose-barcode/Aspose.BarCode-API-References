---
title: "Enum BarcodeQualityMode"
second_title: "Aspose.BarCode für .NET API-Referenz"
description: "Aspose.BarCode.BarCodeRecognition.BarcodeQualityMode Enum. Modus, der Methoden ermöglicht, Barcode-Elemente mit der ausgewählten Qualität zu erkennen. Ein Barcode-Element mit niedrigerer Qualität erfordert aufwändigere Methoden, was die Erkennung verlangsamt."
type: docs
weight: 110
url: /de/net/aspose.barcode.barcoderecognition/barcodequalitymode/
---
## BarcodeQualityMode enumeration

Modus, der Methoden aktiviert, um Barcode‑Elemente mit der ausgewählten Qualität zu erkennen. Ein Barcode‑Element mit niedrigerer Qualität erfordert aufwändigere Methoden, was die Erkennung verlangsamt.

```csharp
public enum BarcodeQualityMode
```

### Werte

| Name | Wert | Beschreibung |
| --- | --- | --- |
| High | `0` | Aktiviert Erkennungsmethoden für Barcodes hoher Qualität. |
| Normal | `1` | Aktiviert Erkennungsmethoden für Barcodes üblicher (normaler) Qualität. |
| Low | `2` | Aktiviert Erkennungsmethoden für Barcodes niedriger Qualität. |

## Beispiele

Dieses Beispiel zeigt, wie man den BarcodeQuality-Modus verwendet.

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings.BarcodeQuality = BarcodeQualityMode.Low;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```

### Siehe auch

* namespace [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../)


