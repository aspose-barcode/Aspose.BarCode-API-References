---
title: "Enum BarcodeQualityMode"
second_title: "Aspose.BarCode voor .NET API‑referentie"
description: "Aspose.BarCode.BarCodeRecognition.BarcodeQualityMode enum. Modus die methoden mogelijk maakt om barcode-elementen te herkennen met de geselecteerde kwaliteit. Barcode-elementen met lagere kwaliteit vereisen meer intensieve methoden, waardoor de herkenning trager wordt."
type: docs
weight: 110
url: /nl/net/aspose.barcode.barcoderecognition/barcodequalitymode/
---
## BarcodeQualityMode enumeration

Modus die methoden inschakelt om barcode‑elementen te herkennen met de geselecteerde kwaliteit. Een barcode‑element met lagere kwaliteit vereist meer intensieve methoden, wat de herkenning vertraagt.

```csharp
public enum BarcodeQualityMode
```

### Waarden

| Naam | Waarde | Beschrijving |
| --- | --- | --- |
| High | `0` | Schakelt herkenningsmethoden in voor barcodes van hoge kwaliteit. |
| Normal | `1` | Schakelt herkenningsmethoden in voor barcodes van gewone (normale) kwaliteit. |
| Low | `2` | Schakelt herkenningsmethoden in voor barcodes van lage kwaliteit. |

## Voorbeelden

Dit voorbeeld toont hoe de BarcodeQuality-modus te gebruiken

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings.BarcodeQuality = BarcodeQualityMode.Low;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```

### Zie ook

* namespace [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../)


