---
title: "Enum ComplexBackgroundMode"
second_title: "Aspose.BarCode voor .NET API‑referentie"
description: "Aspose.BarCode.BarCodeRecognition.ComplexBackgroundMode-enum. Modus die extra herkenning van gekleurde barcodes op gekleurde afbeeldingen in- of uitschakelt"
type: docs
weight: 200
url: /nl/net/aspose.barcode.barcoderecognition/complexbackgroundmode/
---
## ComplexBackgroundMode enumeration

Modus die extra herkenning van gekleurde barcodes op kleurafbeeldingen in- of uitschakelt.

```csharp
public enum ComplexBackgroundMode
```

### Waarden

| Naam | Waarde | Beschrijving |
| --- | --- | --- |
| Auto | `0` | Op dit moment hetzelfde als Disabled. Schakelt extra herkenning van gekleurde barcodes op gekleurde afbeeldingen uit. |
| Disabled | `1` | Schakelt extra herkenning van gekleurde barcodes op gekleurde afbeeldingen uit. |
| Enabled | `2` | Schakelt extra herkenning van gekleurde barcodes op gekleurde afbeeldingen in. |

## Voorbeelden

Dit voorbeeld toont hoe u de ComplexBackground-modus gebruikt

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings.ComplexBackground = ComplexBackgroundMode.Enabled;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```

### Zie ook

* namespace [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../)


