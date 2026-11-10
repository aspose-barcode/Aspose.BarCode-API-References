---
title: "BarCodeReader.FoundBarCodes"
second_title: "Référence de l'API Aspose.BarCode pour .NET"
description: "Propriété BarCodeReader. Obtient le tableau de BarCodeResults reconnus"
type: docs
weight: 50
url: /fr/net/aspose.barcode.barcoderecognition/barcodereader/foundbarcodes/
---
## BarCodeReader.FoundBarCodes property

Obtient le tableau de [`BarCodeResult`](../../barcoderesult/)s reconnus

```csharp
public BarCodeResult[] FoundBarCodes { get; }
```

### Property Value

Le tableau de [`BarCodeResult`](../../barcoderesult/)s reconnus

## Exemples

Cet exemple montre comment lire les codes‑barres avec BarCodeReader.

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

### Voir aussi

* class [BarCodeResult](../../barcoderesult/)
* class [BarCodeReader](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)


