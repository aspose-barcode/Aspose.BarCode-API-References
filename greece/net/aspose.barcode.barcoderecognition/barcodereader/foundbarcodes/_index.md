---
title: "BarCodeReader.FoundBarCodes"
second_title: "Αναφορά API του Aspose.BarCode για .NET"
description: "Ιδιότητα BarCodeReader. Λαμβάνει τον αναγνωρισμένο πίνακα BarCodeResults"
type: docs
weight: 50
url: /el/net/aspose.barcode.barcoderecognition/barcodereader/foundbarcodes/
---
## BarCodeReader.FoundBarCodes property

Λαμβάνει τον αναγνωρισμένο πίνακα [`BarCodeResult`](../../barcoderesult/)s

```csharp
public BarCodeResult[] FoundBarCodes { get; }
```

### Property Value

Ο αναγνωρισμένος πίνακας [`BarCodeResult`](../../barcoderesult/)s

## Παραδείγματα

Αυτό το παράδειγμα δείχνει πώς να διαβάσετε barcode με το BarCodeReader.

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

### Δείτε επίσης

* class [BarCodeResult](../../barcoderesult/)
* class [BarCodeReader](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)


