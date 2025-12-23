---
title: BarCodeReader.FoundCount
second_title: Aspose.BarCode for .NET API Reference
description: BarCodeReader property. Gets recognized barcodes count
type: docs
weight: 50
url: /net/aspose.barcode.barcoderecognition/barcodereader/foundcount/
---
## BarCodeReader.FoundCount property

Gets recognized barcodes count

```csharp
public int FoundCount { get; }
```

### Property Value

The recognized barcodes count

## Examples

This sample shows how to read barcodes with BarCodeReader

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

### See Also

* class [BarCodeReader](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)


