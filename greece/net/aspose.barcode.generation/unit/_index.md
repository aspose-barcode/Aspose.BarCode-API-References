---
title: "Κλάση Unit"
second_title: "Αναφορά API του Aspose.BarCode για .NET"
description: "Aspose.BarCode.Generation.Unit κλάση. Καθορίζει την τιμή μεγέθους σε διαφορετικές μονάδες Pixel, Inches κλπ."
type: docs
weight: 1740
url: /el/net/aspose.barcode.generation/unit/
---
## Unit class

Καθορίζει την τιμή μεγέθους σε διαφορετικές μονάδες (Pixel, ίντσες, κ.λπ.).

```csharp
public sealed class Unit
```

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [Document](../../aspose.barcode.generation/unit/document/) { get; set; } | Λαμβάνει ή ορίζει την τιμή μεγέθους σε μονάδες εγγράφου. |
| [Inches](../../aspose.barcode.generation/unit/inches/) { get; set; } | Λαμβάνει ή ορίζει την τιμή μεγέθους σε ίντσες. |
| [Millimeters](../../aspose.barcode.generation/unit/millimeters/) { get; set; } | Λαμβάνει ή ορίζει την τιμή μεγέθους σε χιλιοστά. |
| [Pixels](../../aspose.barcode.generation/unit/pixels/) { get; set; } | Λαμβάνει ή ορίζει την τιμή μεγέθους σε pixel. |
| [Point](../../aspose.barcode.generation/unit/point/) { get; set; } | Λαμβάνει ή ορίζει την τιμή μεγέθους σε σημείο. |
| [Resolution](../../aspose.barcode.generation/unit/resolution/) { get; } | Ανάλυση |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| override [Equals](../../aspose.barcode.generation/unit/equals/)(object) | Καθορίζει εάν αυτή η παρουσία και ένα καθορισμένο αντικείμενο, το οποίο πρέπει επίσης να είναι αντικείμενο `Unit`, έχουν την ίδια τιμή. |
| override [GetHashCode](../../aspose.barcode.generation/unit/gethashcode/)() | Επιστρέφει τον κωδικό κατακερματισμού για αυτό το αντικείμενο. |
| override [ToString](../../aspose.barcode.generation/unit/tostring/)() | Επιστρέφει μια ανθρώπινα αναγνώσιμη αναπαράσταση συμβολοσειράς του `Unit`. |

## Παραδείγματα

Αυτό το παράδειγμα δείχνει πώς να δημιουργήσετε και να αποθηκεύσετε μια εικόνα BarCode.

```csharp
[C#]
  using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Code128))
  {
      generator.Parameters.Barcode.BarHeight.Millimeters = 10;
      generator.Save("test.png");
  }
```

### Δείτε επίσης

* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


