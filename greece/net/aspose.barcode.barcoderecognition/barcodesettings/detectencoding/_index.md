---
title: "BarcodeSettings.DetectEncoding"
second_title: "Αναφορά API του Aspose.BarCode για .NET"
description: "BarcodeSettings ιδιότητα. Η σημαία που αναγκάζει τη μηχανή να ανιχνεύει την κωδικοποίηση του κειμένου κώδικα για σύνολα χαρακτήρων Unicode. Η προεπιλεγμένη τιμή είναι true."
type: docs
weight: 40
url: /el/net/aspose.barcode.barcoderecognition/barcodesettings/detectencoding/
---
## BarcodeSettings.DetectEncoding property

Η σημαία που αναγκάζει τη μηχανή να εντοπίζει την κωδικοποίηση του κειμένου κώδικα για σύνολα Unicode. Η προεπιλεγμένη τιμή είναι true.

```csharp
public bool DetectEncoding { get; set; }
```

### Property Value

Η σημαία που αναγκάζει τη μηχανή να ανιχνεύει την κωδικοποίηση του κειμένου κώδικα για σύνολα χαρακτήρων Unicode.

## Παραδείγματα

Αυτό το παράδειγμα δείχνει πώς να ανιχνεύσετε την κωδικοποίηση κειμένου σε πραγματικό χρόνο εάν το DetectEncoding είναι ενεργοποιημένο.

```csharp
[C#]
using (MemoryStream ms = new MemoryStream())
{
    using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.QR))
    {
        generator.SetCodeText("Слово", Encoding.UTF8);
        generator.Save(ms, BarCodeImageFormat.Png);
    }
    //Η ανίχνευση κωδικοποίησης για σύνολα χαρακτήρων Unicode είναι ενεργοποιημένη.
    ms.Position = 0;
    using (BarCodeReader reader = new BarCodeReader(ms, DecodeType.QR))
    {
        reader.BarcodeSettings.DetectEncoding = true;
        foreach (BarCodeResult result in reader.ReadBarCodes())
            Console.WriteLine("BarCode CodeText: " + result.CodeText);
    }
    //Η ανίχνευση κωδικοποίησης είναι απενεργοποιημένη.
    ms.Position = 0;
    using (BarCodeReader reader = new BarCodeReader(ms, DecodeType.QR))
    {
        reader.BarcodeSettings.DetectEncoding = false;
        foreach (BarCodeResult result in reader.ReadBarCodes())
            Console.WriteLine("BarCode CodeText: " + result.CodeText);
    }
}
[VB.NET]
Using ms As New MemoryStream
    Using generator As New BarcodeGenerator(EncodeTypes.QR, "Слово")
        generator.SetCodeText("Слово", System.Text.Encoding.UTF8)
        generator.Save(ms, BarCodeImageFormat.Png)
    End Using
    'detects encoding for Unicode codesets is enabled
    ms.Position = 0
    Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39, DecodeType.Code128)
        reader.BarcodeSettings.DetectEncoding = True
        For Each result As BarCodeResult In reader.ReadBarCodes()
            Console.WriteLine("BarCode CodeText: " + result.CodeText)
        Next
    End Using
    'detect encoding is disabled
    ms.Position = 0
    Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39, DecodeType.Code128)
        reader.BarcodeSettings.DetectEncoding = False
        For Each result As BarCodeResult In reader.ReadBarCodes()
            Console.WriteLine("BarCode CodeText: " + result.CodeText)
        Next
    End Using
End Using
```

### Δείτε επίσης

* class [BarcodeSettings](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)


