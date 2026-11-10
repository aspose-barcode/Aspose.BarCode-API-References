---
title: "Απαρίθμηση MaxiCodeMode"
second_title: "Αναφορά API του Aspose.BarCode για .NET"
description: "Aspose.BarCode.Generation.MaxiCodeMode enum. Λειτουργία κωδικοποίησης για γραμμωτούς κώδικες MaxiCode"
type: docs
weight: 1480
url: /el/net/aspose.barcode.generation/maxicodemode/
---
## MaxiCodeMode enumeration

Λειτουργία κωδικοποίησης για γραμμωτούς κώδικες MaxiCode.

```csharp
public enum MaxiCodeMode
```

### Τιμές

| Όνομα | Τιμή | Περιγραφή |
| --- | --- | --- |
| Mode2 | `2` | Η λειτουργία 2 κωδικοποιεί τα ταχυδρομικά στοιχεία στο πρώτο μήνυμα και τα δεδομένα στο δεύτερο μήνυμα. Έχει ταχυδρομικό κώδικα 9 ψηφίων (χρησιμοποιείται μόνο στις ΗΠΑ). |
| Mode3 | `3` | Η λειτουργία 3 κωδικοποιεί τα ταχυδρομικά στοιχεία στο πρώτο μήνυμα και τα δεδομένα στο δεύτερο μήνυμα. Έχει αλφαριθμητικό ταχυδρομικό κώδικα 6 χαρακτήρων, που χρησιμοποιείται παγκοσμίως. |
| Mode4 | `4` | Η λειτουργία 4 κωδικοποιεί δεδομένα στο πρώτο και στο δεύτερο μήνυμα, με σύντομη διόρθωση ECC. |
| Mode5 | `5` | Η λειτουργία 5 κωδικοποιεί δεδομένα στο πρώτο και στο δεύτερο μήνυμα, με μακρά διόρθωση ECC. |
| Mode6 | `6` | Η λειτουργία 6 κωδικοποιεί δεδομένα στο πρώτο και στο δεύτερο μήνυμα, με σύντομη διόρθωση ECC. Χρησιμοποιείται για κωδικοποίηση συσκευής. |

## Παραδείγματα

Αυτό το παράδειγμα δείχνει πώς να δημιουργήσετε γραμμωτούς κώδικες MaxiCode χρησιμοποιώντας το ComplexBarcodeGenerator

```csharp
[C#]
//Λειτουργία 2 με τυπικό δεύτερο μήνυμα
MaxiCodeCodetextMode2 maxiCodeCodetext = new MaxiCodeCodetextMode2();
maxiCodeCodetext.PostalCode = "524032140";
maxiCodeCodetext.CountryCode = 056;
maxiCodeCodetext.ServiceCategory = 999;
MaxiCodeStandardSecondMessage maxiCodeStandardSecondMessage = new MaxiCodeStandardSecondMessage();
maxiCodeStandardSecondMessage.Message = "Test message";
maxiCodeCodetext.SecondMessage = maxiCodeStandardSecondMessage;
using (ComplexBarcodeGenerator complexGenerator = new ComplexBarcodeGenerator(maxiCodeCodetext))
{
    complexGenerator.GenerateBarCodeImage();
}
//Λειτουργία 2 με δομημένο δεύτερο μήνυμα
MaxiCodeCodetextMode2 maxiCodeCodetext = new MaxiCodeCodetextMode2();
maxiCodeCodetext.PostalCode = "524032140";
maxiCodeCodetext.CountryCode = 056;
maxiCodeCodetext.ServiceCategory = 999;
MaxiCodeStructuredSecondMessage maxiCodeStructuredSecondMessage = new MaxiCodeStructuredSecondMessage();
maxiCodeStructuredSecondMessage.Add("634 ALPHA DRIVE");
maxiCodeStructuredSecondMessage.Add("PITTSBURGH");
maxiCodeStructuredSecondMessage.Add("PA");
maxiCodeStructuredSecondMessage.Year = 99;
maxiCodeCodetext.SecondMessage = maxiCodeStructuredSecondMessage;
using (ComplexBarcodeGenerator complexGenerator = new ComplexBarcodeGenerator(maxiCodeCodetext))
{
    complexGenerator.GenerateBarCodeImage();
}
//Λειτουργία 3 με τυπικό δεύτερο μήνυμα
MaxiCodeCodetextMode3 maxiCodeCodetext = new MaxiCodeCodetextMode3();
maxiCodeCodetext.PostalCode = "B1050";
maxiCodeCodetext.CountryCode = 056;
maxiCodeCodetext.ServiceCategory = 999;
MaxiCodeStandardSecondMessage maxiCodeStandardSecondMessage = new MaxiCodeStandardSecondMessage();
maxiCodeStandardSecondMessage.Message = "Test message";
maxiCodeCodetext.SecondMessage = maxiCodeStandardSecondMessage;
using (ComplexBarcodeGenerator complexGenerator = new ComplexBarcodeGenerator(maxiCodeCodetext))
{
    complexGenerator.GenerateBarCodeImage();
}
//Λειτουργία 3 με δομημένο δεύτερο μήνυμα
MaxiCodeCodetextMode3 maxiCodeCodetext = new MaxiCodeCodetextMode3();
maxiCodeCodetext.PostalCode = "B1050";
maxiCodeCodetext.CountryCode = 056;
maxiCodeCodetext.ServiceCategory = 999;
MaxiCodeStructuredSecondMessage maxiCodeStructuredSecondMessage = new MaxiCodeStructuredSecondMessage();
maxiCodeStructuredSecondMessage.Add("634 ALPHA DRIVE");
maxiCodeStructuredSecondMessage.Add("PITTSBURGH");
maxiCodeStructuredSecondMessage.Add("PA");
maxiCodeStructuredSecondMessage.Year = 99;
maxiCodeCodetext.SecondMessage = maxiCodeStructuredSecondMessage;
using (ComplexBarcodeGenerator complexGenerator = new ComplexBarcodeGenerator(maxiCodeCodetext.GetConstructedCodetext())
{
    complexGenerator.GenerateBarCodeImage();
}
//Λειτουργία 4
MaxiCodeStandardCodetext maxiCodeCodetext = new MaxiCodeStandardCodetext();
maxiCodeCodetext.Mode = MaxiCodeMode.Mode4;
maxiCodeCodetext.Message = "Test message";
using (ComplexBarcodeGenerator complexGenerator = new ComplexBarcodeGenerator(maxiCodeCodetext.GetConstructedCodetext())
{
    complexGenerator.GenerateBarCodeImage();
}
//Λειτουργία 5
MaxiCodeStandardCodetext maxiCodeCodetext = new MaxiCodeStandardCodetext();
maxiCodeCodetext.Mode = MaxiCodeMode.Mode5;
maxiCodeCodetext.Message = "Test message";
using (ComplexBarcodeGenerator complexGenerator = new ComplexBarcodeGenerator(maxiCodeCodetext.GetConstructedCodetext())
{
    complexGenerator.GenerateBarCodeImage();
} 
//Λειτουργία 6
MaxiCodeStandardCodetext maxiCodeCodetext = new MaxiCodeStandardCodetext();
maxiCodeCodetext.Mode = MaxiCodeMode.Mode6;
maxiCodeCodetext.Message = "Test message";
using (ComplexBarcodeGenerator complexGenerator = new ComplexBarcodeGenerator(maxiCodeCodetext.GetConstructedCodetext())
{
    complexGenerator.GenerateBarCodeImage();
} 
```

### Δείτε επίσης

* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


