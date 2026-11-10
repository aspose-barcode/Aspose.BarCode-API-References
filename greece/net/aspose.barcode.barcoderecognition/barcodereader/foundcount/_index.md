---
title: "BarCodeReader.FoundCount"
second_title: "Αναφορά API του Aspose.BarCode για .NET"
description: "Ιδιότητα BarCodeReader. Επιστρέφει τον αριθμό των αναγνωρισμένων barcode."
type: docs
weight: 60
url: /el/net/aspose.barcode.barcoderecognition/barcodereader/foundcount/
---
## BarCodeReader.FoundCount property

Ανακτά τον αριθμό των αναγνωρισμένων barcode

```csharp
public int FoundCount { get; }
```

### Property Value

Ο αριθμός των αναγνωρισμένων barcode.

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

* class [BarCodeReader](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)


