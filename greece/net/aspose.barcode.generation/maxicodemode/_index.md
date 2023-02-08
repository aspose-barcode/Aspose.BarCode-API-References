---
title: MaxiCodeMode
second_title: Aspose.BarCode για Αναφορά API .NET
description: Λειτουργία κωδικοποίησης για γραμμωτούς κώδικες MaxiCode.
type: docs
weight: 1050
url: /el/net/aspose.barcode.generation/maxicodemode/
---
## MaxiCodeMode enumeration

Λειτουργία κωδικοποίησης για γραμμωτούς κώδικες MaxiCode.

```csharp
public enum MaxiCodeMode
```

### Αξίες

| Ονομα | αξία | Περιγραφή |
| --- | --- | --- |
| Mode2 | `2` | Η λειτουργία 2 κωδικοποιεί ταχυδρομικές πληροφορίες στο πρώτο μήνυμα και δεδομένα στο δεύτερο μήνυμα. Έχει 9ψήφιο ταχυδρομικό κώδικα (χρησιμοποιείται μόνο στις ΗΠΑ). |
| Mode3 | `3` | Η λειτουργία 3 κωδικοποιεί ταχυδρομικές πληροφορίες στο πρώτο μήνυμα και δεδομένα στο δεύτερο μήνυμα. Διαθέτει 6 αλφαριθμητικούς ταχυδρομικούς κωδικούς, που χρησιμοποιούνται στον κόσμο. |
| Mode4 | `4` | Η λειτουργία 4 κωδικοποιεί δεδομένα στο πρώτο και στο δεύτερο μήνυμα, με σύντομη διόρθωση ECC. |
| Mode5 | `5` | Η λειτουργία 5 κωδικοποιεί δεδομένα στο πρώτο και στο δεύτερο μήνυμα, με μεγάλη διόρθωση ECC. |
| Mode6 | `6` | Η λειτουργία 6 κωδικοποιεί δεδομένα στο πρώτο και στο δεύτερο μήνυμα, με σύντομη διόρθωση ECC. Χρησιμοποιείται για την κωδικοποίηση της συσκευής. |

### Παραδείγματα

Αυτό το δείγμα δείχνει πώς να δημιουργήσετε γραμμωτούς κώδικες MaxiCode χρησιμοποιώντας ComplexBacodeGenerator

```csharp
[C#]
//Λειτουργία 2 με βασικό δεύτερο μήνυμα
MaxiCodeCodetextMode2 maxiCodeCodetext = new MaxiCodeCodetextMode2();
maxiCodeCodetext.PostalCode = "524032140";
maxiCodeCodetext.CountryCode = 056;
maxiCodeCodetext.ServiceCategory = 999;
MaxiCodeStandartSecondMessage maxiCodeStandartSecondMessage = new MaxiCodeStandartSecondMessage();
maxiCodeStandartSecondMessage.Message = "Test message";
maxiCodeCodetext.SecondMessage = maxiCodeStandartSecondMessage;
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
//Λειτουργία 3 με βασικό δεύτερο μήνυμα
MaxiCodeCodetextMode3 maxiCodeCodetext = new MaxiCodeCodetextMode3();
maxiCodeCodetext.PostalCode = "B1050";
maxiCodeCodetext.CountryCode = 056;
maxiCodeCodetext.ServiceCategory = 999;
MaxiCodeStandartSecondMessage maxiCodeStandartSecondMessage = new MaxiCodeStandartSecondMessage();
maxiCodeStandartSecondMessage.Message = "Test message";
maxiCodeCodetext.SecondMessage = maxiCodeStandartSecondMessage;
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

* χώρος ονομάτων [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* συνέλευση [Aspose.BarCode](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->
