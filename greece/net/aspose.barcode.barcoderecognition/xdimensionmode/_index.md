---
title: "Απαρίθμηση XDimensionMode"
second_title: "Αναφορά API του Aspose.BarCode για .NET"
description: "Aspose.BarCode.BarCodeRecognition.XDimensionMode απαρίθμηση. Λειτουργία αναγνώρισης που ορίζει το μέγεθος από 1 έως το άπειρο του ελάχιστου στοιχείου του πλέγματος ή γραμμής του barcode"
type: docs
weight: 400
url: /el/net/aspose.barcode.barcoderecognition/xdimensionmode/
---
## XDimensionMode enumeration

Λειτουργία αναγνώρισης που ορίζει το μέγεθος (από 1 έως άπειρο) του ελάχιστου στοιχείου barcode: κελί πλέγματος ή μπάρα.

```csharp
public enum XDimensionMode
```

### Τιμές

| Όνομα | Τιμή | Περιγραφή |
| --- | --- | --- |
| Auto | `0` | Η τιμή του XDimension ανιχνεύεται από AI (SVM). Αυτή τη στιγμή είναι η ίδια με το Normal |
| Small | `1` | Ανιχνεύει barcodes με μικρό XDimension σε 1 pixel ή περισσότερο με ποιότητα από το BarcodeQuality |
| Normal | `2` | Ανιχνεύει barcodes με κλασικό XDimension σε 2 pixels ή περισσότερο με ποιότητα από το BarcodeQuality ή barcodes υψηλής ποιότητας. |
| Large | `3` | Ανιχνεύει barcodes με μεγάλο XDimension με ποιότητα από το BarcodeQuality που καταγράφεται με κάμερες υψηλής ανάλυσης. |
| UseMinimalXDimension | `4` | Ανιχνεύει barcodes από το μέγεθος που ορίζεται στο MinimalXDimension με ποιότητα από το BarcodeQuality |

## Παραδείγματα

Αυτό το παράδειγμα δείχνει πώς να χρησιμοποιήσετε τη λειτουργία XDimension

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings.XDimension = XDimensionMode.Small;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```

### Δείτε επίσης

* namespace [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../)


