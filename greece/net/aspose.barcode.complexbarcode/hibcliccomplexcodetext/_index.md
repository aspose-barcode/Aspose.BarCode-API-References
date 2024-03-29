---
title: HIBCLICComplexCodetext
second_title: Aspose.BarCode για Αναφορά API .NET
description: Βασική κλάση για κωδικοποίηση και αποκωδικοποίηση του κειμένου που είναι ενσωματωμένο στον κωδικό HIBC LIC.
type: docs
weight: 380
url: /el/net/aspose.barcode.complexbarcode/hibcliccomplexcodetext/
---
## HIBCLICComplexCodetext class

Βασική κλάση για κωδικοποίηση και αποκωδικοποίηση του κειμένου που είναι ενσωματωμένο στον κωδικό HIBC LIC.

```csharp
public abstract class HIBCLICComplexCodetext : IComplexCodetext
```

## Ιδιότητες

| Ονομα | Περιγραφή |
| --- | --- |
| [BarcodeType](../../aspose.barcode.complexbarcode/hibcliccomplexcodetext/barcodetype/) { get; set; } | Λαμβάνει ή ορίζει τον τύπο γραμμικού κώδικα. Το κωδικοποιημένο κείμενο HIBC LIC μπορεί να κωδικοποιηθεί χρησιμοποιώντας τύπους κωδικοποίησης HIBCCode39LIC, HIBCCode128LIC, HIBCAztecLIC, HIBCDataMatrixLIC και HIBCQRLIC. Προεπιλεγμένη τιμή: HIBCCode39LIC. |

## Μέθοδοι

| Ονομα | Περιγραφή |
| --- | --- |
| [GetBarcodeType](../../aspose.barcode.complexbarcode/hibcliccomplexcodetext/getbarcodetype/)() | Λαμβάνει τύπο γραμμικού κώδικα. |
| abstract [GetConstructedCodetext](../../aspose.barcode.complexbarcode/hibcliccomplexcodetext/getconstructedcodetext/)() | Κατασκευάζει codetext |
| abstract [InitFromString](../../aspose.barcode.complexbarcode/hibcliccomplexcodetext/initfromstring/)(string) | Αρχικοποιεί το στιγμιότυπο από το κατασκευασμένο κώδικα κειμένου. |

### Παραδείγματα

Αυτό το δείγμα δείχνει πώς να αποκωδικοποιήσετε το ακατέργαστο κωδικοποιημένο κείμενο HIBC LIC στην παρουσία HIBCLIComplexCodetext.

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.HIBCAztecLIC))
{
     foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        HIBCLICComplexCodetext resultHIBCLICComplexCodetext = ComplexCodetextReader.TryDecodeHIBCLIC(result.CodeText);
        Console.WriteLine("BarCode Type: " + resultMaxiCodeCodetext.GetBarcodeType());
        Console.WriteLine("BarCode CodeText: " + resultMaxiCodeCodetext.GetConstructedCodetext());
    }
}
```

### Δείτε επίσης

* interface [IComplexCodetext](../icomplexcodetext/)
* χώρος ονομάτων [Aspose.BarCode.ComplexBarcode](../../aspose.barcode.complexbarcode/)
* συνέλευση [Aspose.BarCode](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->
