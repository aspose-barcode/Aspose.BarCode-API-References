---
title: "enum"
linktitle: "Code128EncodeMode"
second_title: "Aspose.BarCode for C++ Riferimento API"
description: " enum. Modalità di codifica per i codici a barre Code128. Specifica Code 128 in C++."
type: docs
weight: 5900
url: /it/cpp/aspose.barcode.generation/code128encodemode/
---
## Code128EncodeMode enum


Modalità di codifica per i codici a barre Code128. Code 128

specifica.

```cpp
enum class Code128EncodeMode
```

### Valori

| Nome | Valore | Descrizione |
| --- | --- | --- |
| Auto | 0 | Codifica il testo del codice in modalità classica ISO 15417. La modalità dovrebbe essere usata in tutti i casi ordinari. |
| CodeA | 1 | Codifica il testo del codice solo nel set di codici 128A. |
| CodeB | 2 | Codifica il testo del codice solo nel set di codici 128B. |
| CodeC | 4 | Codifica il testo del codice solo nel set di codici 128C. |
| CodeAB | 3 | Codifica il testo del codice solo nei set di codici 128A e 128B. |
| CodeAC | 5 | Codifica il testo del codice solo nei set di codici 128A e 128C. |
| CodeBC | 6 | Codifica il testo del codice solo nei set di codici 128B e 128C. |

## Osservazioni


Questo codice dimostra come generare il codice 128 con diverse codifiche
```cpp
[C#]
//Genera il codice 128 con codifica ISO 15417
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Code128, "ABCD1234567890");
generator.Parameters.Barcode.Code128.Code128EncodeMode = Code128EncodeMode.Auto;
generator.Save(@"d:\save\rec\code128Auto.png", BarCodeImageFormat.Png);

//Genera il codice 128 solo con la codifica Codeset A.
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Code128, "ABCD1234567890");
generator.Parameters.Barcode.Code128.Code128EncodeMode = Code128EncodeMode.CodeA;
generator.Save(@"d:\save\rec\code128CodeA.png", BarCodeImageFormat.Png);
```

## Vedi anche

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
