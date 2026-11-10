---
title: "BarCodeReader.SetBarCodeReadType"
second_title: "Αναφορά API του Aspose.BarCode για .NET"
description: "Μέθοδος BarCodeReader. Ορίζει τον πίνακα τύπων SingleDecodeType για την αναγνώριση. Πρέπει να κληθεί πριν από τη μέθοδο ReadBarCodes"
type: docs
weight: 130
url: /el/net/aspose.barcode.barcoderecognition/barcodereader/setbarcodereadtype/
---
## BarCodeReader.SetBarCodeReadType method

Ορίζει τον πίνακα τύπων [`SingleDecodeType`](../../singledecodetype/) για την αναγνώριση. Πρέπει να κληθεί πριν από τη μέθοδο ReadBarCodes().

```csharp
public void SetBarCodeReadType(params SingleDecodeType[] barcodeTypes)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| barcodeTypes | SingleDecodeType[] | Ο πίνακας τύπων [`SingleDecodeType`](../../singledecodetype/) για ανάγνωση. |

## Παραδείγματα

Αυτό το παράδειγμα δείχνει πώς να εντοπίσετε γραμμωτούς κώδικες Code39 και Code128.

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

### Δείτε επίσης

* class [SingleDecodeType](../../singledecodetype/)
* class [BarCodeReader](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)


