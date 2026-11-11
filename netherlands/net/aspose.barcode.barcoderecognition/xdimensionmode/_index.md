---
title: "Enum XDimensionMode"
second_title: "Aspose.BarCode voor .NET API‑referentie"
description: "Aspose.BarCode.BarCodeRecognition.XDimensionMode enum. Herkenningsmodus die de grootte instelt van 1 tot oneindig van de minimale elementmatrixcel of balk van de barcode"
type: docs
weight: 400
url: /nl/net/aspose.barcode.barcoderecognition/xdimensionmode/
---
## XDimensionMode enumeration

Herkenningsmodus die de grootte (van 1 tot oneindig) van het minimale barcode‑element instelt: matrixcel of balk.

```csharp
public enum XDimensionMode
```

### Waarden

| Naam | Waarde | Beschrijving |
| --- | --- | --- |
| Auto | `0` | Waarde van XDimension wordt gedetecteerd door AI (SVM). Op dit moment hetzelfde als Normaal |
| Small | `1` | Detecteert barcodes met een kleine XDimension van 1 pixel of meer met kwaliteit van BarcodeQuality |
| Normal | `2` | Detecteert barcodes met een klassieke XDimension van 2 pixels of meer met kwaliteit van BarcodeQuality of barcodes van hoge kwaliteit. |
| Large | `3` | Detecteert barcodes met een grote XDimension met kwaliteit van BarcodeQuality, vastgelegd met hoge-resolutiecamera's. |
| UseMinimalXDimension | `4` | Detecteert barcodes met een grootte ingesteld in MinimalXDimension met kwaliteit van BarcodeQuality |

## Voorbeelden

Dit voorbeeld toont hoe u de XDimension-modus gebruikt

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings.XDimension = XDimensionMode.Small;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```

### Zie ook

* namespace [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../)


