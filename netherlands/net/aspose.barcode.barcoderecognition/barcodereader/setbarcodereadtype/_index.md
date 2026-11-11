---
title: "BarCodeReader.SetBarCodeReadType"
second_title: "Aspose.BarCode voor .NET API‑referentie"
description: "BarCodeReader methode. Stelt SingleDecodeType type-array in voor herkenning. Moet worden aangeroepen vóór de ReadBarCodes-methode"
type: docs
weight: 130
url: /nl/net/aspose.barcode.barcoderecognition/barcodereader/setbarcodereadtype/
---
## BarCodeReader.SetBarCodeReadType method

Stelt [`SingleDecodeType`](../../singledecodetype/) type-array in voor herkenning. Moet worden aangeroepen vóór de ReadBarCodes() methode.

```csharp
public void SetBarCodeReadType(params SingleDecodeType[] barcodeTypes)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| barcodeTypes | SingleDecodeType[] | De [`SingleDecodeType`](../../singledecodetype/) type-array om te lezen. |

## Voorbeelden

Dit voorbeeld toont hoe Code39- en Code128-barcodes te detecteren.

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader())
{
    reader.SetBarCodeReadType(DecodeType.Code39, DecodeType.Code128);
    reader.SetBarCodeImage(@"c:\test.png");
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
    }
}
[VB.NET]
Using reader As New BarCodeReader()
    reader.SetBarCodeReadType(DecodeType.Code39, DecodeType.Code128)
    reader.SetBarCodeImage("c:\test.png")
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
    Next
End Using
```

### Zie ook

* class [SingleDecodeType](../../singledecodetype/)
* class [BarCodeReader](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)


