---
title: "BarCodeReader.ReadBarCodes"
second_title: "Aspose.BarCode voor .NET API‑referentie"
description: "BarCodeReader methode. Leest BarCodeResults uit de afbeelding"
type: docs
weight: 110
url: /nl/net/aspose.barcode.barcoderecognition/barcodereader/readbarcodes/
---
## BarCodeReader.ReadBarCodes method

Leest [`BarCodeResult`](../../barcoderesult/)s uit de afbeelding.

```csharp
public BarCodeResult[] ReadBarCodes()
```

### Retourwaarde

Retourneert een array met herkende [`BarCodeResult`](../../barcoderesult/)s op de afbeelding. Als er niets wordt herkend, wordt een lege array geretourneerd.

## Voorbeelden

Dit voorbeeld toont hoe barcodes te lezen met BarCodeReader.

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39, DecodeType.Code128))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
}
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

Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39, DecodeType.Code128)
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
    Next
End Using
```

### Zie ook

* class [BarCodeResult](../../barcoderesult/)
* class [BarCodeReader](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)


