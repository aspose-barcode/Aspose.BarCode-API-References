---
title: "Απαρίθμηση ComplexBackgroundMode"
second_title: "Αναφορά API του Aspose.BarCode για .NET"
description: "Απαρίθμηση Aspose.BarCode.BarCodeRecognition.ComplexBackgroundMode. Λειτουργία που ενεργοποιεί ή απενεργοποιεί την πρόσθετη αναγνώριση χρωματικών barcode σε χρωματικές εικόνες"
type: docs
weight: 200
url: /el/net/aspose.barcode.barcoderecognition/complexbackgroundmode/
---
## ComplexBackgroundMode enumeration

Λειτουργία που ενεργοποιεί ή απενεργοποιεί την πρόσθετη αναγνώριση χρωματικών barcodes σε χρωματικές εικόνες.

```csharp
public enum ComplexBackgroundMode
```

### Τιμές

| Όνομα | Τιμή | Περιγραφή |
| --- | --- | --- |
| Auto | `0` | Αυτή τη στιγμή το ίδιο με το Disabled. Απενεργοποιεί την πρόσθετη αναγνώριση χρωματικών barcode σε χρωματικές εικόνες. |
| Disabled | `1` | Απενεργοποιεί την πρόσθετη αναγνώριση χρωματικών barcode σε χρωματικές εικόνες. |
| Enabled | `2` | Ενεργοποιεί την πρόσθετη αναγνώριση χρωματικών barcode σε χρωματικές εικόνες. |

## Παραδείγματα

Αυτό το παράδειγμα δείχνει πώς να χρησιμοποιήσετε τη λειτουργία ComplexBackground

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings.ComplexBackground = ComplexBackgroundMode.Enabled;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```

### Δείτε επίσης

* namespace [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../)


