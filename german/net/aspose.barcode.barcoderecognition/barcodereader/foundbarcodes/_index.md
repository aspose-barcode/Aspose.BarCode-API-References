---
title: "BarCodeReader.FoundBarCodes"
second_title: "Aspose.BarCode für .NET API-Referenz"
description: "BarCodeReader-Eigenschaft. Gibt das erkannte BarCodeResults-Array zurück"
type: docs
weight: 50
url: /de/net/aspose.barcode.barcoderecognition/barcodereader/foundbarcodes/
---
## BarCodeReader.FoundBarCodes property

Gibt das erkannte [`BarCodeResult`](../../barcoderesult/)s-Array zurück

```csharp
public BarCodeResult[] FoundBarCodes { get; }
```

### Property Value

Das erkannte [`BarCodeResult`](../../barcoderesult/)s-Array

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

* class [BarCodeResult](../../barcoderesult/)
* class [BarCodeReader](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)


