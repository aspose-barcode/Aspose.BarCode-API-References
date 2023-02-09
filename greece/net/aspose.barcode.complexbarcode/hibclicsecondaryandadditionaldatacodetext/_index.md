---
title: HIBCLICSecondaryAndAdditionalDataCodetext
second_title: Aspose.BarCode για Αναφορά API .NET
description: Κλάση για κωδικοποίηση και αποκωδικοποίηση του κειμένου που είναι ενσωματωμένο στον κωδικό HIBC LIC που αποθηκεύει δευτερεύοντα δεδομένα.
type: docs
weight: 410
url: /el/net/aspose.barcode.complexbarcode/hibclicsecondaryandadditionaldatacodetext/
---
## HIBCLICSecondaryAndAdditionalDataCodetext class

Κλάση για κωδικοποίηση και αποκωδικοποίηση του κειμένου που είναι ενσωματωμένο στον κωδικό HIBC LIC που αποθηκεύει δευτερεύοντα δεδομένα.

```csharp
public class HIBCLICSecondaryAndAdditionalDataCodetext : HIBCLICComplexCodetext
```

## Κατασκευαστές

| Ονομα | Περιγραφή |
| --- | --- |
| [HIBCLICSecondaryAndAdditionalDataCodetext](hibclicsecondaryandadditionaldatacodetext/)() | Ο προεπιλεγμένος κατασκευαστής. |

## Ιδιότητες

| Ονομα | Περιγραφή |
| --- | --- |
| [BarcodeType](../../aspose.barcode.complexbarcode/hibcliccomplexcodetext/barcodetype/) { get; set; } | Λαμβάνει ή ορίζει τον τύπο γραμμικού κώδικα. Το κωδικοποιημένο κείμενο HIBC LIC μπορεί να κωδικοποιηθεί χρησιμοποιώντας τύπους κωδικοποίησης HIBCCode39LIC, HIBCCode128LIC, HIBCAztecLIC, HIBCDataMatrixLIC και HIBCQRLIC. Προεπιλεγμένη τιμή: HIBCCode39LIC. |
| [Data](../../aspose.barcode.complexbarcode/hibclicsecondaryandadditionaldatacodetext/data/) { get; set; } | Προσδιορίζει δευτερογενή και πρόσθετα συμπληρωματικά δεδομένα. |
| [LinkCharacter](../../aspose.barcode.complexbarcode/hibclicsecondaryandadditionaldatacodetext/linkcharacter/) { get; set; } | Προσδιορίζει τον χαρακτήρα συνδέσμου. |

## Μέθοδοι

| Ονομα | Περιγραφή |
| --- | --- |
| override [Equals](../../aspose.barcode.complexbarcode/hibclicsecondaryandadditionaldatacodetext/equals/)(object) | Επιστρέφει μια τιμή που υποδεικνύει εάν αυτή η παρουσία είναι ίση με μια καθορισμένη`HIBCLICSecondaryAndAdditionalDataCodetext` τιμή. |
| [GetBarcodeType](../../aspose.barcode.complexbarcode/hibcliccomplexcodetext/getbarcodetype/)() | Λαμβάνει τύπο γραμμικού κώδικα. |
| override [GetConstructedCodetext](../../aspose.barcode.complexbarcode/hibclicsecondaryandadditionaldatacodetext/getconstructedcodetext/)() | Κατασκευάζει codetext |
| override [GetHashCode](../../aspose.barcode.complexbarcode/hibclicsecondaryandadditionaldatacodetext/gethashcode/)() | Επιστρέφει τον κωδικό κατακερματισμού για αυτήν την εμφάνιση. |
| override [InitFromString](../../aspose.barcode.complexbarcode/hibclicsecondaryandadditionaldatacodetext/initfromstring/)(string) | Αρχικοποιεί το στιγμιότυπο από το κατασκευασμένο κώδικα κειμένου. |

### Παραδείγματα

Αυτό το δείγμα δείχνει πώς να κωδικοποιήσετε και να αποκωδικοποιήσετε το HIBC LIC χρησιμοποιώντας το HIBCLICSsecondaryAndAdditionalDataCodetext.

```csharp
[C#]
HIBCLICSecondaryAndAdditionalDataCodetext complexCodetext = new HIBCLICSecondaryAndAdditionalDataCodetext();
complexCodetext.BarcodeType = EncodeTypes.HIBCQRLIC;
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
* χώρος ονομάτων [Aspose.BarCode.ComplexBarcode](../../aspose.barcode.complexbarcode/)
* συνέλευση [Aspose.BarCode](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->