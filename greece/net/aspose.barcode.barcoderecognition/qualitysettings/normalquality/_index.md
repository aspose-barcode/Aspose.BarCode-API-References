---
title: "QualitySettings.NormalQuality"
second_title: "Αναφορά API του Aspose.BarCode για .NET"
description: "Ιδιότητα QualitySettings. Προεπιλογή ποιότητας αναγνώρισης NormalQuality. Κατάλληλη για τα περισσότερα barcode"
type: docs
weight: 40
url: /el/net/aspose.barcode.barcoderecognition/qualitysettings/normalquality/
---
## QualitySettings.NormalQuality property

Προεπιλογή ποιότητας αναγνώρισης NormalQuality. Κατάλληλη για τα περισσότερα barcode

```csharp
public static QualitySettings NormalQuality { get; }
```

### Property Value

Προεπιλογή ποιότητας αναγνώρισης NormalQuality.

## Παραδείγματα

Αυτό το παράδειγμα δείχνει πώς να χρησιμοποιήσετε τη λειτουργία NormalQuality

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings = QualitySettings.NormalQuality;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```

### Δείτε επίσης

* class [QualitySettings](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)


