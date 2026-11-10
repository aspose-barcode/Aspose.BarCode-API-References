---
title: "BarCodeReader.ReadBarCodes"
second_title: "Αναφορά API του Aspose.BarCode για .NET"
description: "Μέθοδος BarCodeReader. Διαβάζει τα BarCodeResults από την εικόνα"
type: docs
weight: 110
url: /el/net/aspose.barcode.barcoderecognition/barcodereader/readbarcodes/
---
## BarCodeReader.ReadBarCodes method

Διαβάζει τα [`BarCodeResult`](../../barcoderesult/)s από την εικόνα.

```csharp
public BarCodeResult[] ReadBarCodes()
```

### Τιμή Επιστροφής

Επιστρέφει πίνακα των αναγνωρισμένων [`BarCodeResult`](../../barcoderesult/)s στην εικόνα. Εάν δεν αναγνωριστεί τίποτα, επιστρέφεται κενός πίνακας.

## Παραδείγματα

Αυτό το παράδειγμα δείχνει πώς να διαβάσετε barcode με το BarCodeReader.

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

### Δείτε επίσης

* class [BarCodeResult](../../barcoderesult/)
* class [BarCodeReader](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)


