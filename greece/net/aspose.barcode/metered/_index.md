---
title: "Κλάση Metered"
second_title: "Αναφορά API του Aspose.BarCode για .NET"
description: "Aspose.BarCode.Metered κλάση. Παρέχει μεθόδους για ορισμό του metered key"
type: docs
weight: 1770
url: /el/net/aspose.barcode/metered/
---
## Metered class

Παρέχει μεθόδους για τον ορισμό του μετρημένου κλειδιού.

```csharp
public class Metered
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [Metered](metered/)() | Ο προεπιλεγμένος κατασκευαστής. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [GetProductName](../../aspose.barcode/metered/getproductname/)() | Λαμβάνει το όνομα του αδειοδοτημένου προϊόντος |
| [SetMeteredKey](../../aspose.barcode/metered/setmeteredkey/)(string, string) | Ορίζει το δημόσιο και ιδιωτικό κλειδί metered. Εάν αγοράσετε άδεια metered, όταν ξεκινάτε την εφαρμογή, αυτό το API πρέπει να κληθεί, συνήθως αυτό είναι αρκετό. Ωστόσο, εάν αποτυγχάνει συνεχώς η μεταφόρτωση δεδομένων κατανάλωσης και υπερβεί τις 24 ώρες, η άδεια θα οριστεί σε κατάσταση αξιολόγησης· για να αποφύγετε αυτή την περίπτωση, πρέπει να ελέγχετε τακτικά την κατάσταση της άδειας· εάν είναι σε κατάσταση αξιολόγησης, καλέστε ξανά αυτό το API. |
| static [GetConsumptionCredit](../../aspose.barcode/metered/getconsumptioncredit/)() | Λαμβάνει το πιστωτικό κατανάλωσης |
| static [GetConsumptionQuantity](../../aspose.barcode/metered/getconsumptionquantity/)() | Λαμβάνει το μέγεθος του αρχείου κατανάλωσης |
| static [IsMeteredLicensed](../../aspose.barcode/metered/ismeteredlicensed/)() | Ελέγξτε εάν η χρέωση είναι αδειοδοτημένη |

## Παραδείγματα

Σε αυτό το παράδειγμα, θα γίνει προσπάθεια να οριστεί το δημόσιο και το ιδιωτικό κλειδί χρέωσης

```csharp
[C#]

Metered matered = new Metered();
matered.SetMeteredKey("PublicKey", "PrivateKey");


[Visual Basic]

Dim matered As Metered = New Metered
matered.SetMeteredKey("PublicKey", "PrivateKey")
```

### Δείτε επίσης

* namespace [Aspose.BarCode](../../aspose.barcode/)
* assembly [Aspose.BarCode](../../)


