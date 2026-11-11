---
title: "Enum InverseImageMode"
second_title: "Aspose.BarCode voor .NET API‑referentie"
description: "Aspose.BarCode.BarCodeRecognition.InverseImageMode enum. Modus die extra herkenning van barcodes op afbeeldingen met omgekeerde kleurluminantie in- of uitschakelt."
type: docs
weight: 270
url: /nl/net/aspose.barcode.barcoderecognition/inverseimagemode/
---
## InverseImageMode enumeration

Modus die extra herkenning van barcodes op afbeeldingen met omgekeerde kleuren (luminantie) in- of uitschakelt.

```csharp
public enum InverseImageMode
```

### Waarden

| Naam | Waarde | Beschrijving |
| --- | --- | --- |
| Auto | `0` | Schakelt extra herkenning van barcodes op inverse afbeeldingen uit voor alle barcode‑typen behalve QR‑Code. |
| Disabled | `1` | Schakelt extra herkenning van barcodes op inverse afbeeldingen uit. |
| Enabled | `2` | Schakelt extra herkenning van barcodes op inverse afbeeldingen in |

## Voorbeelden

Deze voorbeeld toont hoe de InverseImage-modus te gebruiken

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings.InverseImage = InverseImageMode.Enabled;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```

### Zie ook

* namespace [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../)


