---
title: BarCodeReader.Timeout
second_title: Aspose.BarCode for .NET API Reference
description: BarCodeReader property. Gets or sets the timeout of recognition process in milliseconds
type: docs
weight: 70
url: /net/aspose.barcode.barcoderecognition/barcodereader/timeout/
---
## BarCodeReader.Timeout property

Gets or sets the timeout of recognition process in milliseconds.

```csharp
public int Timeout { get; set; }
```

### Property Value

The timeout.

## Examples

This sample shows how to avoid recogntion hungs with timeount on large images

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

### See Also

* class [BarCodeReader](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)


