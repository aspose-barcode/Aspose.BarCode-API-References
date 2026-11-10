---
title: "Κλάση ComplexBarcodeGenerator"
second_title: "Αναφορά API του Aspose.BarCode για .NET"
description: "Aspose.BarCode.ComplexBarcode.ComplexBarcodeGenerator κλάση. ComplexBarcodeGenerator για δημιουργία σύνθετων barcode στο backend, π.χ. δημιουργία εικόνων SwissQR"
type: docs
weight: 510
url: /el/net/aspose.barcode.complexbarcode/complexbarcodegenerator/
---
## ComplexBarcodeGenerator class

ComplexBarcodeGenerator για δημιουργία εικόνων σύνθετων γραμμωτών κωδίκων (π.χ. SwissQR) στο backend.

```csharp
public sealed class ComplexBarcodeGenerator : Component
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [ComplexBarcodeGenerator](complexbarcodegenerator/)(IComplexCodetext) | Δημιουργεί μια παρουσία του ComplexBarcodeGenerator. |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [Parameters](../../aspose.barcode.complexbarcode/complexbarcodegenerator/parameters/) { get; } | Παράμετροι δημιουργίας. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [GenerateBarCodeImage](../../aspose.barcode.complexbarcode/complexbarcodegenerator/generatebarcodeimage/)() | Δημιουργεί εικόνα σύνθετου barcode με τις τρέχουσες ρυθμίσεις. |
| [Save](../../aspose.barcode.complexbarcode/complexbarcodegenerator/save/#save_1)(string) | Δημιουργεί και αποθηκεύει εικόνα σύνθετου barcode με τις τρέχουσες ρυθμίσεις. |
| [Save](../../aspose.barcode.complexbarcode/complexbarcodegenerator/save/#save)(Stream, BarCodeImageFormat) | Δημιουργεί και αποθηκεύει εικόνα σύνθετου barcode με τις τρέχουσες ρυθμίσεις. |
| [Save](../../aspose.barcode.complexbarcode/complexbarcodegenerator/save/#save_2)(string, BarCodeImageFormat) | Δημιουργεί και αποθηκεύει εικόνα σύνθετου barcode με τις τρέχουσες ρυθμίσεις. |

## Παραδείγματα

Αυτό το παράδειγμα δείχνει πώς να δημιουργήσετε και να αποθηκεύσετε μια εικόνα SwissQR.

```csharp
[C#]
  var swissQRCodetext = new SwissQRCodetext();
  swissQRCodetext.Bill.Account = "Account";
  swissQRCodetext.Bill.BillInformation = "BillInformation";
  // Αρχικοποιεί τα υπόλοιπα πεδία
  using (var cg = new ComplexBarcodeGenerator(swissQRCodetext))
  {
    var res = cg.GenerateBarCodeImage();
  }
```

### Δείτε επίσης

* namespace [Aspose.BarCode.ComplexBarcode](../../aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](../../)


