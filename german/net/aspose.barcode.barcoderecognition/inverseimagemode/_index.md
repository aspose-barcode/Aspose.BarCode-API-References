---
title: "Enum InverseImageMode"
second_title: "Aspose.BarCode für .NET API-Referenz"
description: "Aspose.BarCode.BarCodeRecognition.InverseImageMode-Enum. Modus, der die zusätzliche Erkennung von Barcodes auf Bildern mit invertierter Farbluminanz aktiviert oder deaktiviert."
type: docs
weight: 270
url: /de/net/aspose.barcode.barcoderecognition/inverseimagemode/
---
## InverseImageMode enumeration

Modus, der die zusätzliche Erkennung von Barcodes in Bildern mit invertierten Farben (Luminanz) ein- oder ausschaltet.

```csharp
public enum InverseImageMode
```

### Werte

| Name | Wert | Beschreibung |
| --- | --- | --- |
| Auto | `0` | Deaktiviert die zusätzliche Erkennung von Barcodes auf inversen Bildern für alle Barcode-Typen außer QR Code. |
| Disabled | `1` | Deaktiviert die zusätzliche Erkennung von Barcodes auf inversen Bildern. |
| Enabled | `2` | Aktiviert die zusätzliche Erkennung von Barcodes auf inversen Bildern |

## Beispiele

Dieses Beispiel zeigt, wie der InverseImage-Modus verwendet wird

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings.InverseImage = InverseImageMode.Enabled;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```

### Siehe auch

* namespace [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../)


