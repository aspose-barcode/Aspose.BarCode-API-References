---
title: "QualitySettings.HighPerformance"
second_title: "Αναφορά API του Aspose.BarCode για .NET"
description: "Ιδιότητα QualitySettings. Προεπιλογή ποιότητας αναγνώρισης HighPerformance. Τα barcode υψηλής ποιότητας αναγνωρίζονται καλά σε αυτή τη λειτουργία."
type: docs
weight: 10
url: /el/net/aspose.barcode.barcoderecognition/qualitysettings/highperformance/
---
## QualitySettings.HighPerformance property

Προεπιλογή ποιότητας αναγνώρισης HighPerformance. Τα barcode υψηλής ποιότητας αναγνωρίζονται καλά σε αυτή τη λειτουργία.

```csharp
public static QualitySettings HighPerformance { get; }
```

### Property Value

Προεπιλογή ποιότητας αναγνώρισης HighPerformance.

## Παραδείγματα

Αυτό το παράδειγμα δείχνει πώς να χρησιμοποιήσετε τη λειτουργία HighPerformance.

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings = QualitySettings.HighPerformance;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```

### Δείτε επίσης

* class [QualitySettings](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)


