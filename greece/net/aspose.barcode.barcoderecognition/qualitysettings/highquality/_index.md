---
title: "QualitySettings.HighQuality"
second_title: "Αναφορά API του Aspose.BarCode για .NET"
description: "Ιδιότητα QualitySettings. Προεπιλογή αναγνώρισης υψηλής ποιότητας HighQuality. Αυτή η προεπιλογή έχει αναπτυχθεί για barcode χαμηλής ποιότητας. Επιτρέπει την ανίχνευση εξαιρετικά κατεστραμμένων barcode."
type: docs
weight: 20
url: /el/net/aspose.barcode.barcoderecognition/qualitysettings/highquality/
---
## QualitySettings.HighQuality property

Προεπιλογή ποιότητας αναγνώρισης HighQuality. Αυτή η προεπιλογή έχει αναπτυχθεί για barcode χαμηλής ποιότητας. Επιτρέπει τον εντοπισμό πολύ κατεστραμμένων barcode.

```csharp
public static QualitySettings HighQuality { get; }
```

### Property Value

Προεπιλογή ποιότητας αναγνώρισης HighQuality.

## Παραδείγματα

Αυτό το παράδειγμα δείχνει πώς να χρησιμοποιήσετε τη λειτουργία HighQuality

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings = QualitySettings.HighQuality;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```

### Δείτε επίσης

* class [QualitySettings](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)


