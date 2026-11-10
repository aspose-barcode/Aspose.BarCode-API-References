---
title: "Enum InverseImageMode"
second_title: "Αναφορά API του Aspose.BarCode για .NET"
description: "Aspose.BarCode.BarCodeRecognition.InverseImageMode enum. Λειτουργία που ενεργοποιεί ή απενεργοποιεί την πρόσθετη αναγνώριση κωδικών γραμμής σε εικόνες με αντίστροφη φωτεινότητα χρωμάτων"
type: docs
weight: 270
url: /el/net/aspose.barcode.barcoderecognition/inverseimagemode/
---
## InverseImageMode enumeration

Λειτουργία που ενεργοποιεί ή απενεργοποιεί την πρόσθετη αναγνώριση barcodes σε εικόνες με ανεστραμμένα χρώματα (φωτεινότητα).

```csharp
public enum InverseImageMode
```

### Τιμές

| Όνομα | Τιμή | Περιγραφή |
| --- | --- | --- |
| Auto | `0` | Απενεργοποιεί την πρόσθετη αναγνώριση κωδικών γραμμής σε αντίστροφες εικόνες για όλους τους τύπους κωδικών εκτός του QR Code. |
| Disabled | `1` | Απενεργοποιεί την πρόσθετη αναγνώριση κωδικών γραμμής σε αντίστροφες εικόνες. |
| Enabled | `2` | Ενεργοποιεί την πρόσθετη αναγνώριση κωδικών γραμμής σε αντίστροφες εικόνες |

## Παραδείγματα

Αυτό το παράδειγμα δείχνει πώς να χρησιμοποιήσετε τη λειτουργία InverseImage

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings.InverseImage = InverseImageMode.Enabled;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```

### Δείτε επίσης

* namespace [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../)


