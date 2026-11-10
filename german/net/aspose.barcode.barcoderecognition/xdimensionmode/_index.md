---
title: "Enum XDimensionMode"
second_title: "Aspose.BarCode für .NET API-Referenz"
description: "Aspose.BarCode.BarCodeRecognition.XDimensionMode‑Enum. Erkennungsmodus, der die Größe von 1 bis unendlich des minimalen Element‑Matrix‑Zell‑ oder Balkenelements des Barcodes festlegt."
type: docs
weight: 400
url: /de/net/aspose.barcode.barcoderecognition/xdimensionmode/
---
## XDimensionMode enumeration

Erkennungsmodus, der die Größe (von 1 bis unendlich) des minimalen Barcode‑Elements festlegt: Matrixzelle oder Strich.

```csharp
public enum XDimensionMode
```

### Werte

| Name | Wert | Beschreibung |
| --- | --- | --- |
| Auto | `0` | Der Wert von XDimension wird durch KI (SVM) ermittelt. Derzeit ist er derselbe wie Normal. |
| Small | `1` | Erkennt Barcodes mit kleiner XDimension von 1 Pixel oder mehr mit Qualität von BarcodeQuality. |
| Normal | `2` | Erkennt Barcodes mit klassischer XDimension von 2 Pixeln oder mehr mit Qualität von BarcodeQuality oder hochwertigen Barcodes. |
| Large | `3` | Erkennt Barcodes mit großer XDimension mit Qualität von BarcodeQuality, aufgenommen mit hochauflösenden Kameras. |
| UseMinimalXDimension | `4` | Erkennt Barcodes anhand der in MinimalXDimension festgelegten Größe mit Qualität von BarcodeQuality. |

## Beispiele

Dieses Beispiel zeigt, wie man den XDimension‑Modus verwendet

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings.XDimension = XDimensionMode.Small;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```

### Siehe auch

* namespace [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../)


