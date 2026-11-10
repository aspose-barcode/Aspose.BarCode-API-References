---
title: "BarCodeReader.QualitySettings"
second_title: "Αναφορά API του Aspose.BarCode για .NET"
description: "Ιδιότητα BarCodeReader. Το QualitySettings επιτρέπει τη χειροκίνητη ρύθμιση της ποιότητας και της ταχύτητας αναγνώρισης. Μπορείτε γρήγορα να ρυθμίσετε το QualitySettings με ενσωματωμένες προεπιλογές HighPerformance, NormalQuality, HighQuality, MaxBarCodes ή να ρυθμίσετε χειροκίνητα ξεχωριστές επιλογές. Η προεπιλεγμένη τιμή του QualitySettings είναι NormalQuality."
type: docs
weight: 70
url: /el/net/aspose.barcode.barcoderecognition/barcodereader/qualitysettings/
---
## BarCodeReader.QualitySettings property

Το QualitySettings επιτρέπει τη χειροκίνητη διαμόρφωση της ποιότητας και της ταχύτητας αναγνώρισης. Μπορείτε γρήγορα να ρυθμίσετε το QualitySettings χρησιμοποιώντας ενσωματωμένες προεπιλογές: HighPerformance, NormalQuality, HighQuality, MaxBarCodes ή να διαμορφώσετε χειροκίνητα ξεχωριστές επιλογές. Η προεπιλεγμένη τιμή του QualitySettings είναι NormalQuality.

```csharp
public QualitySettings QualitySettings { get; set; }
```

### Property Value

QualitySettings για τη ρύθμιση της ποιότητας και της ταχύτητας αναγνώρισης.

## Παραδείγματα

Αυτό το παράδειγμα δείχνει πώς να χρησιμοποιήσετε το QualitySettings με το BarCodeReader

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39, DecodeType.Code128))
{
   //ορίστε τη λειτουργία υψηλής απόδοσης
   reader.QualitySettings = QualitySettings.HighPerformance;
   foreach (BarCodeResult result in reader.ReadBarCodes())
      Console.WriteLine("BarCode CodeText: " + result.CodeText);
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39, DecodeType.Code128))
{
   //η λειτουργία normal quality ορίζεται εξ ορισμού
   foreach (BarCodeResult result in reader.ReadBarCodes())
      Console.WriteLine("BarCode CodeText: " + result.CodeText);
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39, DecodeType.Code128))
{
   //ορίστε τη λειτουργία υψηλής απόδοσης
   reader.QualitySettings = QualitySettings.HighPerformance;
   //ορίστε ξεχωριστές επιλογές
   reader.QualitySettings.AllowMedianSmoothing = true;
   reader.QualitySettings.MedianSmoothingWindowSize = 5;
   foreach (BarCodeResult result in reader.ReadBarCodes())
      Console.WriteLine("BarCode CodeText: " + result.CodeText);
}
[VB.NET]
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39, DecodeType.Code128)
    'set high performance mode
    reader.QualitySettings = QualitySettings.HighPerformance
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
    Next
End Using
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39, DecodeType.Code128)
    'normal quality mode is set by default
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
    Next
End Using
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39, DecodeType.Code128)
   'set high performance mode
   reader.QualitySettings = QualitySettings.HighPerformance
   'set separate options
   reader.QualitySettings.AllowMedianSmoothing = True
   reader.QualitySettings.MedianSmoothingWindowSize = 5
   For Each result As BarCodeResult In reader.ReadBarCodes()
       Console.WriteLine("BarCode Type: " + result.CodeTypeName)
   Next
End Using
```

### Δείτε επίσης

* class [QualitySettings](../../qualitysettings/)
* class [BarCodeReader](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)


