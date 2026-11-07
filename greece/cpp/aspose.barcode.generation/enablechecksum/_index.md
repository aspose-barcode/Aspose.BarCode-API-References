---
title: "enum"
linktitle: "EnableChecksum"
second_title: "Aspose.BarCode για C++ Αναφορά API"
description: "Πώς να χρησιμοποιήσετε enum σε C++."
type: docs
weight: 6700
url: /el/cpp/aspose.barcode.generation/enablechecksum/
---
## EnableChecksum enum




```cpp
enum class EnableChecksum
```

### Τιμές

| Όνομα | Τιμή | Περιγραφή |
| --- | --- | --- |
| Προεπιλογή | 0 | Εάν το checksum απαιτείται από την προδιαγραφή - θα προσαρτηθεί. |
| Ναι | 1 | Χρησιμοποιήστε πάντα checksum εάν είναι δυνατόν. |
| Όχι | 2 | Μην χρησιμοποιείτε checksum. |

## Σχόλια


Ενεργοποιήστε το checksum κατά τη δημιουργία για 1D barcode.

Η προεπιλογή αντιμετωπίζεται ως Ναι για τις συμβολές που πρέπει να περιέχουν checksum, ως Όχι όπου το checksum είναι μόνο δυνατό.

Checksum δεν χρησιμοποιείται ποτέ: Codabar

Checksum είναι δυνατό: Code39 Standard/Extended, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, DeutschePostIdentcode, DeutschePostLeitcode, VIN

Checksum πάντα χρησιμοποιείται: Οι υπόλοιπες συμβολές
## Δείτε επίσης

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
