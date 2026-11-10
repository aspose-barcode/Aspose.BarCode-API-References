---
title: "BarCodeReader.Timeout"
second_title: "Aspose.BarCode für .NET API-Referenz"
description: "BarCodeReader-Eigenschaft. Ruft den Timeout des Erkennungsprozesses in Millisekunden ab oder legt ihn fest"
type: docs
weight: 80
url: /de/net/aspose.barcode.barcoderecognition/barcodereader/timeout/
---
## BarCodeReader.Timeout property

Liest oder setzt den Timeout des Erkennungsprozesses in Millisekunden.

```csharp
public int Timeout { get; set; }
```

### Property Value

Der Timeout.

## Beispiele

Dieses Beispiel zeigt, wie man Erkennungs‑Hänger bei großen Bildern mit einem Timeout vermeidet

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

### Siehe auch

* class [BarCodeReader](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)


