---
title: FoundCount
second_title: Aspose.BarCode für .NET-API-Referenz
description: Ruft die Anzahl der erkannten Barcodes ab
type: docs
weight: 50
url: /de/net/aspose.barcode.barcoderecognition/barcodereader/foundcount/
---
## BarCodeReader.FoundCount property

Ruft die Anzahl der erkannten Barcodes ab

```csharp
public int FoundCount { get; }
```

### Eigentumswert

Es zählen die erkannten Barcodes

### Beispiele

Dieses Beispiel zeigt, wie Barcodes mit BarCodeReader gelesen werden

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Standard, DecodeType.Code128))
{
    reader.ReadBarCodes();
    for(int i = 0; reader.FoundCount > i; ++i)
        Console.WriteLine("BarCode CodeText: " + reader.FoundBarCodes[i].CodeText);
}
[VB.NET]
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39Standard, DecodeType.Code128)
    reader.ReadBarCodes()
    For i As Integer = 0 To reader.FoundCount - 1 Step 1
        Console.WriteLine("BarCode CodeText: " + reader.FoundBarCodes(i).CodeText)
    Next
End Using
```

### Siehe auch

* class [BarCodeReader](../../barcodereader)
* namensraum [Aspose.BarCode.BarCodeRecognition](../../barcodereader)
* Montage [Aspose.BarCode](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->