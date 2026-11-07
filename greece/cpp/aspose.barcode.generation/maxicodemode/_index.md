---
title: "enum"
linktitle: "MaxiCodeMode"
second_title: "Aspose.BarCode για C++ Αναφορά API"
description: " enum. Λειτουργία κωδικοποίησης για τα barcode MaxiCode σε C++."
type: docs
weight: 7600
url: /el/cpp/aspose.barcode.generation/maxicodemode/
---
## MaxiCodeMode enum


Λειτουργία κωδικοποίησης για τα barcode MaxiCode.

```cpp
enum class MaxiCodeMode
```

### Τιμές

| Όνομα | Τιμή | Περιγραφή |
| --- | --- | --- |
| Mode2 | 2 | Το Mode 2 κωδικοποιεί τις ταχυδρομικές πληροφορίες στο πρώτο μήνυμα και τα δεδομένα στο δεύτερο μήνυμα. Διαθέτει ταχυδρομικό κώδικα 9 ψηφίων (χρησιμοποιείται μόνο στις ΗΠΑ). |
| Mode3 | 3 | Το Mode 3 κωδικοποιεί τις ταχυδρομικές πληροφορίες στο πρώτο μήνυμα και τα δεδομένα στο δεύτερο μήνυμα. Διαθέτει αλφαριθμητικό ταχυδρομικό κώδικα 6 χαρακτήρων, που χρησιμοποιείται παγκοσμίως. |
| Mode4 | 4 | Το Mode 4 κωδικοποιεί τα δεδομένα στο πρώτο και δεύτερο μήνυμα, με σύντομη διόρθωση ECC. |
| Mode5 | 5 | Το Mode 5 κωδικοποιεί τα δεδομένα στο πρώτο και δεύτερο μήνυμα, με μακρά διόρθωση ECC. |
| Mode6 | 6 | Το Mode 6 κωδικοποιεί τα δεδομένα στο πρώτο και δεύτερο μήνυμα, με σύντομη διόρθωση ECC. Χρησιμοποιείται για κωδικοποίηση συσκευής. |

## Σχόλια


Αυτό το παράδειγμα δείχνει πώς να δημιουργήσετε κωδικούς MaxiCode χρησιμοποιώντας το ComplexBarcodeGenerator
```cpp
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
//Mode 4
MaxiCodeStandardCodetext maxiCodeCodetext = new MaxiCodeStandardCodetext();
maxiCodeCodetext.Mode = MaxiCodeMode.Mode4;
maxiCodeCodetext.Message = "Test message";
using (ComplexBarcodeGenerator complexGenerator = new ComplexBarcodeGenerator(maxiCodeCodetext.GetConstructedCodetext())
{
    complexGenerator.GenerateBarCodeImage();
}
//Mode 5
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

## Δείτε επίσης

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
