---
title: "BarCodeReader.Timeout"
second_title: "Aspose.BarCode voor .NET API‑referentie"
description: "BarCodeReader eigenschap. Haalt op of stelt de timeout van het herkenningsproces in milliseconden in"
type: docs
weight: 80
url: /nl/net/aspose.barcode.barcoderecognition/barcodereader/timeout/
---
## BarCodeReader.Timeout property

Haalt op of stelt de time‑out van het herkenningsproces in milliseconden in.

```csharp
public int Timeout { get; set; }
```

### Property Value

De time-out.

## Voorbeelden

Dit voorbeeld laat zien hoe je herkenningshangen kunt vermijden met time-out op grote afbeeldingen

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png"))
{
    reader.Timeout = 5000;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
}
[VB.NET]
Using reader As New BarCodeReader("c:\test.png")
    reader.Timeout = 5000
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
    Next
End Using
```

### Zie ook

* class [BarCodeReader](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)


