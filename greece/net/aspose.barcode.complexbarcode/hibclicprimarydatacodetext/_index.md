---
title: "Κλάση HIBCLICPrimaryDataCodetext"
second_title: "Αναφορά API του Aspose.BarCode για .NET"
description: "Κλάση Aspose.BarCode.ComplexBarcode.HIBCLICPrimaryDataCodetext. Κλάση για κωδικοποίηση και αποκωδικοποίηση του κειμένου που ενσωματώνεται στον κώδικα HIBC LIC ο οποίος αποθηκεύει τα πρωτεύοντα δεδομένα"
type: docs
weight: 580
url: /el/net/aspose.barcode.complexbarcode/hibclicprimarydatacodetext/
---
## HIBCLICPrimaryDataCodetext class

Κλάση για κωδικοποίηση και αποκωδικοποίηση του κειμένου που ενσωματώνεται στον κώδικα HIBC LIC ο οποίος αποθηκεύει πρωτεύοντα δεδομένα.

```csharp
public class HIBCLICPrimaryDataCodetext : HIBCLICComplexCodetext
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [HIBCLICPrimaryDataCodetext](hibclicprimarydatacodetext/)() | Ο προεπιλεγμένος κατασκευαστής. |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [BarcodeType](../../aspose.barcode.complexbarcode/hibcliccomplexcodetext/barcodetype/) { get; set; } | Λαμβάνει ή ορίζει τον τύπο του barcode. Το codetext HIBC LIC μπορεί να κωδικοποιηθεί χρησιμοποιώντας τους τύπους κωδικοποίησης HIBCCode39LIC, HIBCCode128LIC, HIBCAztecLIC, HIBCDataMatrixLIC και HIBCQRLIC. Προεπιλεγμένη τιμή: HIBCCode39LIC. |
| [Data](../../aspose.barcode.complexbarcode/hibclicprimarydatacodetext/data/) { get; set; } | Αναγνωρίζει τα πρωτεύοντα δεδομένα. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| override [Equals](../../aspose.barcode.complexbarcode/hibclicprimarydatacodetext/equals/)(object) | Επιστρέφει μια τιμή που υποδεικνύει εάν αυτή η παρουσία είναι ίση με μια καθορισμένη τιμή `HIBCLICPrimaryDataCodetext`. |
| [GetBarcodeType](../../aspose.barcode.complexbarcode/hibcliccomplexcodetext/getbarcodetype/)() | Λαμβάνει τον τύπο του barcode. |
| override [GetConstructedCodetext](../../aspose.barcode.complexbarcode/hibclicprimarydatacodetext/getconstructedcodetext/)() | Δημιουργεί το codetext |
| override [GetHashCode](../../aspose.barcode.complexbarcode/hibclicprimarydatacodetext/gethashcode/)() | Επιστρέφει τον κωδικό κατακερματισμού για αυτήν την παρουσία. |
| override [InitFromString](../../aspose.barcode.complexbarcode/hibclicprimarydatacodetext/initfromstring/)(string) | Αρχικοποιεί την παρουσία από το κατασκευασμένο codetext. |

## Παραδείγματα

Αυτό το παράδειγμα δείχνει πώς να κωδικοποιήσετε και να αποκωδικοποιήσετε το HIBC LIC χρησιμοποιώντας το HIBCLICPrimaryDataCodetext.

```csharp
[C#]
HIBCLICPrimaryDataCodetext complexCodetext  = new HIBCLICPrimaryDataCodetext();
complexCodetext.BarcodeType = EncodeTypes.HIBCQRLIC;
complexCodetext.Data = new PrimaryData();
complexCodetext.Data.ProductOrCatalogNumber = "12345";
complexCodetext.Data.LabelerIdentificationCode = "A999";
complexCodetext.Data.UnitOfMeasureID = 1;
using (ComplexBarcodeGenerator generator = new ComplexBarcodeGenerator(complexCodetext))
{
    Bitmap image = generator.GenerateBarCodeImage();
    using (BarCodeReader reader = new BarCodeReader(image, DecodeType.HIBCQRLIC))
    {
        reader.ReadBarCodes();
        string codetext = reader.FoundBarCodes[0].CodeText;
        HIBCLICPrimaryDataCodetext result = (HIBCLICPrimaryDataCodetext)ComplexCodetextReader.TryDecodeHIBCLIC(codetext);
        Console.WriteLine("Product or catalog number: " + result.Data.ProductOrCatalogNumber);
        Console.WriteLine("Labeler identification code: " + result.Data.LabelerIdentificationCode);
        Console.WriteLine("Unit of measure ID: " + result.Data.UnitOfMeasureID);
    }
}
```

### Δείτε επίσης

* class [HIBCLICComplexCodetext](../hibcliccomplexcodetext/)
* namespace [Aspose.BarCode.ComplexBarcode](../../aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](../../)


