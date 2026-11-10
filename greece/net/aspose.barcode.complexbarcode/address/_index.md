---
title: "Κλάση Address"
second_title: "Αναφορά API του Aspose.BarCode για .NET"
description: "Κλάση Aspose.BarCode.ComplexBarcode.Address. Διεύθυνση του πιστωτή ή του οφειλέτη"
type: docs
weight: 480
url: /el/net/aspose.barcode.complexbarcode/address/
---
## Address class

Διεύθυνση του πιστωτή ή του οφειλέτη.

Μπορείτε είτε να ορίσετε το δρόμο, τον αριθμό σπιτιού, τον ταχυδρομικό κώδικα και την πόλη (τύπος δομημένης διεύθυνσης) είτε τη γραμμή διεύθυνσης 1 και 2 (τύπος συνδυασμένων στοιχείων διεύθυνσης). Ο τύπος ορίζεται αυτόματα μόλις οριστεί οποιοδήποτε από αυτά τα πεδία. Πριν οριστούν τα πεδία, ο τύπος διεύθυνσης είναι ακαθόριστος. Εάν οριστούν πεδία και των δύο τύπων, ο τύπος διεύθυνσης γίνεται συγκρουσιακός. Το όνομα και ο κωδικός χώρας πρέπει πάντα να ορίζονται εκτός εάν όλα τα πεδία είναι κενά.

```csharp
public sealed class Address : IEquatable<Address>
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [Address](address/)() | Δημιουργεί μια παρουσία της Address |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [AddressLine1](../../aspose.barcode.complexbarcode/address/addressline1/) { get; set; } | Ανακτά ή ορίζει τη γραμμή διεύθυνσης 1. |
| [AddressLine2](../../aspose.barcode.complexbarcode/address/addressline2/) { get; set; } | Ανακτά ή ορίζει τη γραμμή διεύθυνσης 2. |
| [CountryCode](../../aspose.barcode.complexbarcode/address/countrycode/) { get; set; } | Ανακτά ή ορίζει τον διψήφιο κωδικό χώρας ISO. |
| [HouseNo](../../aspose.barcode.complexbarcode/address/houseno/) { get; set; } | Ανακτά ή ορίζει τον αριθμό σπιτιού. |
| [Name](../../aspose.barcode.complexbarcode/address/name/) { get; set; } | Ανακτά ή ορίζει το όνομα, είτε το όνομα και επώνυμο φυσικού προσώπου είτε το όνομα εταιρείας νομικού προσώπου. |
| [PostalCode](../../aspose.barcode.complexbarcode/address/postalcode/) { get; set; } | Ανακτά ή ορίζει τον ταχυδρομικό κώδικα. |
| [Street](../../aspose.barcode.complexbarcode/address/street/) { get; set; } | Ανακτά ή ορίζει το δρόμο. |
| [Town](../../aspose.barcode.complexbarcode/address/town/) { get; set; } | Ανακτά ή ορίζει την πόλη ή το κωμόπολη. |
| [Type](../../aspose.barcode.complexbarcode/address/type/) { get; } | Ανακτά τον τύπο διεύθυνσης. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [Clear](../../aspose.barcode.complexbarcode/address/clear/)() | Καθαρίζει όλα τα πεδία και ορίζει τον τύπο σε Απροσδιόριστο. |
| [Equals](../../aspose.barcode.complexbarcode/address/equals/#equals)(Address) | Καθορίζει εάν η καθορισμένη διεύθυνση είναι ίση με την τρέχουσα διεύθυνση. |
| override [Equals](../../aspose.barcode.complexbarcode/address/equals/#equals_1)(object) | Καθορίζει εάν το καθορισμένο αντικείμενο είναι ίσο με το τρέχον αντικείμενο. |
| override [GetHashCode](../../aspose.barcode.complexbarcode/address/gethashcode/)() | Λαμβάνει τον κωδικό κατακερματισμού για αυτήν την παρουσία. |

### Δείτε επίσης

* namespace [Aspose.BarCode.ComplexBarcode](../../aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](../../)


