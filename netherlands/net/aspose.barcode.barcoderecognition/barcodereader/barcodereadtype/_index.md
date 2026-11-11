---
title: "BarCodeReader.BarCodeReadType"
second_title: "Aspose.BarCode voor .NET API‑referentie"
description: "BarCodeReader-eigenschap. Haalt het barcode-decodeertype op of stelt het in dat wordt gebruikt voor herkenning. Moet worden ingesteld voordat ReadBarCodes wordt aangeroepen."
type: docs
weight: 30
url: /nl/net/aspose.barcode.barcoderecognition/barcodereader/barcodereadtype/
---
## BarCodeReader.BarCodeReadType property

Haalt het barcode-decodeertype op of stelt het in dat wordt gebruikt voor herkenning. Moet worden ingesteld voordat [`ReadBarCodes`](../readbarcodes/) wordt aangeroepen.

```csharp
public BaseDecodeType BarCodeReadType { get; set; }
```

## Voorbeelden

Dit voorbeeld toont hoe Code39- en Code128-barcodes te detecteren.

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader())
{
    reader.BarCodeReadType = new MultiDecodeType(DecodeType.Code39, DecodeType.Code128);
    reader.SetBarCodeImage(@"c:\test.png");
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
    }
    Console.WriteLine("BarCodeReadType: " + reader.BarCodeReadType.ToString());
}
[VB.NET]
Using reader As New BarCodeReader()
    reader.BarCodeReadType = New MultiDecodeType(DecodeType.Code39, DecodeType.Code128)
    reader.SetBarCodeImage("c:\test.png")
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
    Next
    Console.WriteLine("BarCodeReadType: " + reader.BarCodeReadType.ToString())
End Using
```

### Zie ook

* class [BaseDecodeType](../../basedecodetype/)
* class [BarCodeReader](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)


