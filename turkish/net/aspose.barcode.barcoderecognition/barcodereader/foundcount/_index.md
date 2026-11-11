---
title: "BarCodeReader.FoundCount"
second_title: "Aspose.BarCode for .NET API Referansı"
description: "BarCodeReader özelliği. Tanınan barkod sayısını alır."
type: docs
weight: 60
url: /tr/net/aspose.barcode.barcoderecognition/barcodereader/foundcount/
---
## BarCodeReader.FoundCount property

Tanımlanan barkodların sayısını alır

```csharp
public int FoundCount { get; }
```

### Property Value

Tanınan barkod sayısı

## Örnekler

Bu örnek, BarCodeReader ile barkodların nasıl okunacağını gösterir.

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

### Ayrıca Bakınız

* class [BarCodeReader](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)


