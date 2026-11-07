---
title: "μέθοδος"
linktitle: "set_DetectEncoding"
second_title: "Aspose.BarCode για C++ Αναφορά API"
description: " μέθοδος. Η σημαία που αναγκάζει τη μηχανή να εντοπίζει την κωδικοποίηση του κειμένου κώδικα για σύνολα χαρακτήρων Unicode. Η προεπιλεγμένη τιμή είναι αληθής σε C++."
type: docs
weight: 800
url: /el/cpp/aspose.barcode.barcoderecognition/barcodesettings/set_detectencoding/
---
## BarcodeSettings::set_DetectEncoding method


Η σημαία που αναγκάζει τη μηχανή να εντοπίσει την κωδικοποίηση του κειμένου κώδικα για σύνολα Unicode. Η προεπιλεγμένη τιμή είναι true.

```cpp
void Aspose::BarCode::BarCodeRecognition::BarcodeSettings::set_DetectEncoding(bool value)
```

## Σχόλια


Αυτό το παράδειγμα δείχνει πώς να εντοπίζετε την κωδικοποίηση κειμένου σε πραγματικό χρόνο εάν το DetectEncoding είναι ενεργοποιημένο
```cpp
[C#]
using (MemoryStream ms = new MemoryStream())
{
    using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.QR))
    {
        generator.SetCodeText("Слово", Encoding.UTF8);
        generator.Save(ms, BarCodeImageFormat.Png);
    }
    //η ανίχνευση κωδικοποίησης για σύνολα χαρακτήρων Unicode είναι ενεργοποιημένη
    ms.Position = 0;
    using (BarCodeReader reader = new BarCodeReader(ms, DecodeType.QR))
    {
        reader.BarcodeSettings.DetectEncoding = true;
        foreach (BarCodeResult result in reader.ReadBarCodes())
            Console.WriteLine("BarCode CodeText: " + result.CodeText);
    }
    //η ανίχνευση κωδικοποίησης είναι απενεργοποιημένη
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


Η σημαία που αναγκάζει τη μηχανή να εντοπίζει την κωδικοποίηση του κειμένου κώδικα για σύνολα χαρακτήρων Unicode
## Δείτε επίσης

* Class [BarcodeSettings](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
