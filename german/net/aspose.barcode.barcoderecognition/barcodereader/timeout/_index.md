---
title: Timeout
second_title: Aspose.BarCode für .NET-API-Referenz
description: Ruft das Timeout des Erkennungsprozesses in Millisekunden ab oder setzt es.
type: docs
weight: 70
url: /de/net/aspose.barcode.barcoderecognition/barcodereader/timeout/
---
## BarCodeReader.Timeout property

Ruft das Timeout des Erkennungsprozesses in Millisekunden ab oder setzt es.

```csharp
public int Timeout { get; set; }
```

### Eigentumswert

Die Zeitüberschreitung.

### Beispiele

Dieses Beispiel zeigt, wie Erkennungsprobleme mit Timeount bei großen Bildern vermieden werden

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

* class [BarCodeReader](../../barcodereader)
* namensraum [Aspose.BarCode.BarCodeRecognition](../../barcodereader)
* Montage [Aspose.BarCode](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->