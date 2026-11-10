---
title: "Κλάση HIBCLICSecondaryAndAdditionalDataCodetext"
second_title: "Αναφορά API του Aspose.BarCode για .NET"
description: "Κλάση Aspose.BarCode.ComplexBarcode.HIBCLICSecondaryAndAdditionalDataCodetext. Κλάση για κωδικοποίηση και αποκωδικοποίηση του κειμένου που ενσωματώνεται στον κώδικα HIBC LIC ο οποίος αποθηκεύει δευτερεύοντα δεδομένα."
type: docs
weight: 590
url: /el/net/aspose.barcode.complexbarcode/hibclicsecondaryandadditionaldatacodetext/
---
## HIBCLICSecondaryAndAdditionalDataCodetext class

Κλάση για κωδικοποίηση και αποκωδικοποίηση του κειμένου που ενσωματώνεται στον κώδικα HIBC LIC ο οποίος αποθηκεύει δευτερεύοντα δεδομένα.

```csharp
public class HIBCLICSecondaryAndAdditionalDataCodetext : HIBCLICComplexCodetext
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [HIBCLICSecondaryAndAdditionalDataCodetext](hibclicsecondaryandadditionaldatacodetext/)() | Ο προεπιλεγμένος κατασκευαστής. |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [BarcodeType](../../aspose.barcode.complexbarcode/hibcliccomplexcodetext/barcodetype/) { get; set; } | Λαμβάνει ή ορίζει τον τύπο του barcode. Το codetext HIBC LIC μπορεί να κωδικοποιηθεί χρησιμοποιώντας τους τύπους κωδικοποίησης HIBCCode39LIC, HIBCCode128LIC, HIBCAztecLIC, HIBCDataMatrixLIC και HIBCQRLIC. Προεπιλεγμένη τιμή: HIBCCode39LIC. |
| [Data](../../aspose.barcode.complexbarcode/hibclicsecondaryandadditionaldatacodetext/data/) { get; set; } | Αναγνωρίζει δευτερεύοντα και πρόσθετα συμπληρωματικά δεδομένα. |
| [LinkCharacter](../../aspose.barcode.complexbarcode/hibclicsecondaryandadditionaldatacodetext/linkcharacter/) { get; set; } | Αναγνωρίζει χαρακτήρα σύνδεσης. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| override [Equals](../../aspose.barcode.complexbarcode/hibclicsecondaryandadditionaldatacodetext/equals/)(object) | Επιστρέφει μια τιμή που υποδεικνύει εάν αυτή η παρουσία είναι ίση με μια καθορισμένη τιμή `HIBCLICSecondaryAndAdditionalDataCodetext`. |
| [GetBarcodeType](../../aspose.barcode.complexbarcode/hibcliccomplexcodetext/getbarcodetype/)() | Λαμβάνει τον τύπο του barcode. |
| override [GetConstructedCodetext](../../aspose.barcode.complexbarcode/hibclicsecondaryandadditionaldatacodetext/getconstructedcodetext/)() | Δημιουργεί το codetext |
| override [GetHashCode](../../aspose.barcode.complexbarcode/hibclicsecondaryandadditionaldatacodetext/gethashcode/)() | Επιστρέφει τον κωδικό κατακερματισμού για αυτήν την παρουσία. |
| override [InitFromString](../../aspose.barcode.complexbarcode/hibclicsecondaryandadditionaldatacodetext/initfromstring/)(string) | Αρχικοποιεί την παρουσία από το κατασκευασμένο codetext. |

## Παραδείγματα

Αυτό το παράδειγμα δείχνει πώς να κωδικοποιήσετε και να αποκωδικοποιήσετε το HIBC LIC χρησιμοποιώντας το HIBCLICSecondaryAndAdditionalDataCodetext.

```csharp
[C#]
HIBCLICSecondaryAndAdditionalDataCodetext complexCodetext = new HIBCLICSecondaryAndAdditionalDataCodetext();
complexCodetext.BarcodeType = EncodeTypes.HIBCQRLIC;
complexCodetext.LinkCharacter = 'L';
complexCodetext.Data = new SecondaryAndAdditionalData();
complexCodetext.Data.ExpiryDate = DateTime.Now;
complexCodetext.Data.ExpiryDateFormat = HIBCLICDateFormat.MMDDYY;
complexCodetext.Data.Quantity = 30;
complexCodetext.Data.LotNumber = "LOT123";
complexCodetext.Data.SerialNumber = "SERIAL123";
complexCodetext.Data.DateOfManufacture = DateTime.Now;
using (ComplexBarcodeGenerator generator = new ComplexBarcodeGenerator(complexCodetext))
{
    Bitmap image = generator.GenerateBarCodeImage();
    using (BarCodeReader reader = new BarCodeReader(image, DecodeType.HIBCQRLIC))
    {
        reader.ReadBarCodes();
        string codetext = reader.FoundBarCodes[0].CodeText;
        HIBCLICSecondaryAndAdditionalDataCodetext result = (HIBCLICSecondaryAndAdditionalDataCodetext)ComplexCodetextReader.TryDecodeHIBCLIC(codetext);
        Console.WriteLine("Expiry date: " + result.Data.ExpiryDate);
        Console.WriteLine("Quantity: " + result.Data.Quantity);
        Console.WriteLine("Lot number: " + result.Data.LotNumber);
        Console.WriteLine("Serial number: " + result.Data.SerialNumber);
        Console.WriteLine("Date of manufacture: " + result.Data.DateOfManufacture);
    }
}
```

### Δείτε επίσης

* class [HIBCLICComplexCodetext](../hibcliccomplexcodetext/)
* namespace [Aspose.BarCode.ComplexBarcode](../../aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](../../)


