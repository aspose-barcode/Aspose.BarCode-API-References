---
title: "Απαρίθμηση Code128EncodeMode"
second_title: "Αναφορά API του Aspose.BarCode για .NET"
description: "Απαρίθμηση Aspose.BarCode.Generation.Code128EncodeMode. Λειτουργία κωδικοποίησης για γραμμωτούς κώδικες Code128. Προδιαγραφή Code 128"
type: docs
weight: 1120
url: /el/net/aspose.barcode.generation/code128encodemode/
---
## Code128EncodeMode enumeration

Λειτουργία κωδικοποίησης για γραμμωτούς κώδικες Code128. Προδιαγραφή [Code 128](https://en.wikipedia.org/wiki/Code_128).

```csharp
public enum Code128EncodeMode
```

### Τιμές

| Όνομα | Τιμή | Περιγραφή |
| --- | --- | --- |
| Auto | `0` | Κωδικοποίηση του κειμένου κώδικα σε κλασική λειτουργία ISO 15417. Η λειτουργία πρέπει να χρησιμοποιείται σε όλες τις συνηθισμένες περιπτώσεις. |
| CodeA | `1` | Κωδικοποίηση του κειμένου κώδικα μόνο στο σύνολο κωδικών 128A. |
| CodeB | `2` | Κωδικοποίηση του κειμένου κώδικα μόνο στο σύνολο κωδικών 128B. |
| CodeC | `4` | Κωδικοποίηση του κειμένου κώδικα μόνο στο σύνολο κωδικών 128C. |
| CodeAB | `3` | Κωδικοποίηση του κειμένου κώδικα μόνο στα σύνολα κωδικών 128A και 128B. |
| CodeAC | `5` | Κωδικοποίηση του κειμένου κώδικα μόνο στα σύνολα κωδικών 128A και 128C. |
| CodeBC | `6` | Κωδικοποίηση του κειμένου κώδικα μόνο στα σύνολα κωδικών 128B και 128C. |

## Παραδείγματα

Αυτός ο κώδικας δείχνει πώς να δημιουργήσετε code 128 με διαφορετικές κωδικοποιήσεις

```csharp
[C#]
//Δημιουργήστε code 128 με κωδικοποίηση ISO 15417
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Code128, "ABCD1234567890");
generator.Parameters.Barcode.Code128.Code128EncodeMode = Code128EncodeMode.Auto;
generator.Save(@"d:\save\rec\code128Auto.png", BarCodeImageFormat.Png);

//Δημιουργήστε code 128 μόνο με κωδικοποίηση Codeset A
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Code128, "ABCD1234567890");
generator.Parameters.Barcode.Code128.Code128EncodeMode = Code128EncodeMode.CodeA;
generator.Save(@"d:\save\rec\code128CodeA.png", BarCodeImageFormat.Png);
```

### Δείτε επίσης

* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


