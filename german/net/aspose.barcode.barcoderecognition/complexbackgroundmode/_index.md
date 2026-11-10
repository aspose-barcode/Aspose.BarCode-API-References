---
title: "Enum ComplexBackgroundMode"
second_title: "Aspose.BarCode für .NET API-Referenz"
description: "Aspose.BarCode.BarCodeRecognition.ComplexBackgroundMode Enum. Modus, der die zusätzliche Erkennung von Farbbarkeodes in Farbbildern aktiviert oder deaktiviert."
type: docs
weight: 200
url: /de/net/aspose.barcode.barcoderecognition/complexbackgroundmode/
---
## ComplexBackgroundMode enumeration

Modus, der die zusätzliche Erkennung von Farbbarcodes in Farbbildern ein- oder ausschaltet.

```csharp
public enum ComplexBackgroundMode
```

### Werte

| Name | Wert | Beschreibung |
| --- | --- | --- |
| Auto | `0` | Zurzeit dasselbe wie Disabled. Deaktiviert die zusätzliche Erkennung von Farbcodes in Farbbildern. |
| Disabled | `1` | Deaktiviert die zusätzliche Erkennung von Farbcodes in Farbbildern. |
| Enabled | `2` | Aktiviert die zusätzliche Erkennung von Farbcodes in Farbbildern. |

## Beispiele

Dieses Beispiel zeigt, wie der Modus ComplexBackground verwendet wird

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings.ComplexBackground = ComplexBackgroundMode.Enabled;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```

### Siehe auch

* namespace [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../)


