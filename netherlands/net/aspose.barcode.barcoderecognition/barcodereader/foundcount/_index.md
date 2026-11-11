---
title: "BarCodeReader.FoundCount"
second_title: "Aspose.BarCode voor .NET API‑referentie"
description: "BarCodeReader eigenschap. Haalt het aantal herkende barcodes op."
type: docs
weight: 60
url: /nl/net/aspose.barcode.barcoderecognition/barcodereader/foundcount/
---
## BarCodeReader.FoundCount property

Haalt het aantal herkende barcodes op

```csharp
public int FoundCount { get; }
```

### Property Value

Het aantal herkende barcodes

## Voorbeelden

Dit voorbeeld toont hoe barcodes te lezen met BarCodeReader.

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39, DecodeType.Code128))
{
    reader.ReadBarCodes();
    for(int i = 0; reader.FoundCount > i; ++i)
        Console.WriteLine("BarCode CodeText: " + reader.FoundBarCodes[i].CodeText);
}
[VB.NET]
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39, DecodeType.Code128)
    reader.ReadBarCodes()
    For i As Integer = 0 To reader.FoundCount - 1 Step 1
        Console.WriteLine("BarCode CodeText: " + reader.FoundBarCodes(i).CodeText)
    Next
End Using
```

### Zie ook

* class [BarCodeReader](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)


