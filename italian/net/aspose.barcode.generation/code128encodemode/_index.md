---
title: "Enum Code128EncodeMode"
second_title: "Riferimento API Aspose.BarCode per .NET"
description: "Enum Aspose.BarCode.Generation.Code128EncodeMode. Modalità di codifica per i codici a barre Code128. Specifica Code 128"
type: docs
weight: 1120
url: /it/net/aspose.barcode.generation/code128encodemode/
---
## Code128EncodeMode enumeration

Modalità di codifica per i codici a barre Code128. Specifica [Code 128](https://en.wikipedia.org/wiki/Code_128).

```csharp
public enum Code128EncodeMode
```

### Valori

| Nome | Valore | Descrizione |
| --- | --- | --- |
| Auto | `0` | Codifica il testo del codice nella modalità classica ISO 15417. La modalità dovrebbe essere usata in tutti i casi ordinari. |
| CodeA | `1` | Codifica il testo del codice solo nel set di codici 128A. |
| CodeB | `2` | Codifica il testo del codice solo nel set di codici 128B. |
| CodeC | `4` | Codifica il testo del codice solo nel set di codici 128C. |
| CodeAB | `3` | Codifica il testo del codice solo nei set di codici 128A e 128B. |
| CodeAC | `5` | Codifica il testo del codice solo nei set di codici 128A e 128C. |
| CodeBC | `6` | Codifica il testo del codice solo nei set di codici 128B e 128C. |

## Esempi

Questo codice dimostra come generare il codice 128 con diverse codifiche

```csharp
[C#]
//Genera il codice 128 con codifica ISO 15417
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Code128, "ABCD1234567890");
generator.Parameters.Barcode.Code128.Code128EncodeMode = Code128EncodeMode.Auto;
generator.Save(@"d:\save\rec\code128Auto.png", BarCodeImageFormat.Png);

//Genera code 128 solo con codifica Codeset A
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Code128, "ABCD1234567890");
generator.Parameters.Barcode.Code128.Code128EncodeMode = Code128EncodeMode.CodeA;
generator.Save(@"d:\save\rec\code128CodeA.png", BarCodeImageFormat.Png);
```

### Vedi anche

* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


