---
title: "Απαρίθμηση EnableChecksum"
second_title: "Αναφορά API του Aspose.BarCode για .NET"
description: "Aspose.BarCode.Generation.EnableChecksum enum. Ενεργοποίηση ελέγχου αθροίσματος κατά τη δημιουργία για 1D γραμμικούς κώδικες"
type: docs
weight: 1280
url: /el/net/aspose.barcode.generation/enablechecksum/
---
## EnableChecksum enumeration

Ενεργοποίηση ελέγχου αθροίσματος κατά τη δημιουργία για 1D γραμμωτούς κώδικες.

Η προεπιλογή θεωρείται Ναι για συμβολισμούς που πρέπει να περιέχουν άθροισμα ελέγχου, και Όχι όπου το άθροισμα ελέγχου είναι μόνο δυνατό.

Ο έλεγχος αθροίσματος δεν χρησιμοποιείται ποτέ: Codabar

Το άθροισμα ελέγχου είναι δυνατό: Code39 Standard/Extended, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, DeutschePostIdentcode, DeutschePostLeitcode, VIN

Το checksum χρησιμοποιείται πάντα: υπόλοιπες συμβολισμοί

```csharp
public enum EnableChecksum
```

### Τιμές

| Όνομα | Τιμή | Περιγραφή |
| --- | --- | --- |
| Default | `0` | Εάν το άθροισμα ελέγχου απαιτείται από την προδιαγραφή - θα προσαρτηθεί. |
| Yes | `1` | Χρησιμοποιήστε πάντα το άθροισμα ελέγχου εάν είναι δυνατό. |
| No | `2` | Μην χρησιμοποιείτε το άθροισμα ελέγχου. |

### Δείτε επίσης

* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


