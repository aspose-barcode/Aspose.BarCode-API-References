---
title: "Enum XDimensionMode"
second_title: "Aspose.BarCode för .NET API-referens"
description: "Aspose.BarCode.BarCodeRecognition.XDimensionMode-enum. Identifieringsläge som anger storlek från 1 till oändlighet för streckkodens minsta element, matriscell eller stapel"
type: docs
weight: 400
url: /sv/net/aspose.barcode.barcoderecognition/xdimensionmode/
---
## XDimensionMode enumeration

Identifieringsläge som anger storlek (från 1 till oändlighet) för streckkodens minsta element: matriscell eller stapel.

```csharp
public enum XDimensionMode
```

### Värden

| Namn | Värde | Beskrivning |
| --- | --- | --- |
| Auto | `0` | Värdet för XDimension upptäcks av AI (SVM). För närvarande samma som Normal. |
| Small | `1` | Detekterar streckkoder med liten XDimension på 1 pixel eller mer med kvalitet från BarcodeQuality |
| Normal | `2` | Detekterar streckkoder med klassisk XDimension på 2 pixlar eller mer med kvalitet från BarcodeQuality eller högkvalitativa streckkoder. |
| Large | `3` | Detekterar streckkoder med stor XDimension med kvalitet från BarcodeQuality som fångas med högupplösta kameror. |
| UseMinimalXDimension | `4` | Detekterar streckkoder med storlek inställd i MinimalXDimension med kvalitet från BarcodeQuality |

## Exempel

Detta exempel visar hur man använder XDimension-läget

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings.XDimension = XDimensionMode.Small;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```

### Se även

* namespace [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../)


