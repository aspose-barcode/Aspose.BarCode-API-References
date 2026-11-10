---
title: "BarCodeReader.Timeout"
second_title: "Αναφορά API του Aspose.BarCode για .NET"
description: "Ιδιότητα BarCodeReader. Λαμβάνει ή ορίζει το χρονικό όριο της διαδικασίας αναγνώρισης σε χιλιοστά του δευτερολέπτου"
type: docs
weight: 80
url: /el/net/aspose.barcode.barcoderecognition/barcodereader/timeout/
---
## BarCodeReader.Timeout property

Ανακτά ή ορίζει το χρονικό όριο της διαδικασίας αναγνώρισης σε χιλιοστά του δευτερολέπτου.

```csharp
public int Timeout { get; set; }
```

### Property Value

Το χρονικό όριο.

## Παραδείγματα

Αυτό το παράδειγμα δείχνει πώς να αποφύγετε τα κρεμάσματα αναγνώρισης με χρονικό όριο σε μεγάλες εικόνες.

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

### Δείτε επίσης

* class [BarCodeReader](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)


