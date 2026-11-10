---
title: "BarCodeReader.FoundCount"
second_title: "Aspose.BarCode für .NET API-Referenz"
description: "BarCodeReader-Eigenschaft. Gibt die Anzahl erkannter Barcodes zurück."
type: docs
weight: 60
url: /de/net/aspose.barcode.barcoderecognition/barcodereader/foundcount/
---
## BarCodeReader.FoundCount property

Liefert die Anzahl erkannter Barcodes

```csharp
public int FoundCount { get; }
```

### Property Value

Die Anzahl erkannter Barcodes

## Beispiele

Dieses Beispiel zeigt, wie man Barcodes mit BarCodeReader liest.

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

### Siehe auch

* class [BarCodeReader](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)


