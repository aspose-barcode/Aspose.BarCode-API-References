---
title: "enum"
linktitle: "Code128EncodeMode"
second_title: "Aspose.BarCode για C++ Αναφορά API"
description: " enum. Λειτουργία κωδικοποίησης για γραμμωτούς κώδικες Code128. Προδιαγραφή Code 128 σε C++."
type: docs
weight: 5900
url: /el/cpp/aspose.barcode.generation/code128encodemode/
---
## Code128EncodeMode enum


Λειτουργία κωδικοποίησης για γραμμωτούς κώδικες Code128. Code 128

προδιαγραφή.

```cpp
enum class Code128EncodeMode
```

### Τιμές

| Όνομα | Τιμή | Περιγραφή |
| --- | --- | --- |
| Αυτόματο | 0 | Κωδικοποιήστε το κείμενο κώδικα σε κλασική λειτουργία ISO 15417. Η λειτουργία πρέπει να χρησιμοποιείται σε όλες τις συνηθισμένες περιπτώσεις. |
| CodeA | 1 | Κωδικοποιήστε το κείμενο κώδικα μόνο στο σύνολο κωδικών 128A. |
| CodeB | 2 | Κωδικοποιήστε το κείμενο κώδικα μόνο στο σύνολο κωδικών 128B. |
| CodeC | 4 | Κωδικοποιήστε το κείμενο κώδικα μόνο στο σύνολο κωδικών 128C. |
| CodeAB | 3 | Κωδικοποιήστε το κείμενο κώδικα μόνο στα σύνολα κωδικών 128A και 128B. |
| CodeAC | 5 | Κωδικοποιήστε το κείμενο κώδικα μόνο στα σύνολα κωδικών 128A και 128C. |
| CodeBC | 6 | Κωδικοποιήστε το κείμενο κώδικα μόνο στα σύνολα κωδικών 128B και 128C. |

## Σχόλια


Αυτός ο κώδικας δείχνει πώς να δημιουργήσετε κώδικα 128 με διαφορετικές κωδικοποιήσεις.
```cpp
[C#]
//Δημιουργήστε κώδικα 128 με κωδικοποίηση ISO 15417.
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Code128, "ABCD1234567890");
generator.Parameters.Barcode.Code128.Code128EncodeMode = Code128EncodeMode.Auto;
generator.Save(@"d:\save\rec\code128Auto.png", BarCodeImageFormat.Png);

//Δημιουργήστε κώδικα 128 μόνο με κωδικοποίηση Codeset A.
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Code128, "ABCD1234567890");
generator.Parameters.Barcode.Code128.Code128EncodeMode = Code128EncodeMode.CodeA;
generator.Save(@"d:\save\rec\code128CodeA.png", BarCodeImageFormat.Png);
```

## Δείτε επίσης

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
