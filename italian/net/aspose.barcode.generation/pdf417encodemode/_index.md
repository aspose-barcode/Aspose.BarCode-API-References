---
title: "Enum Pdf417EncodeMode"
second_title: "Riferimento API Aspose.BarCode per .NET"
description: "Aspose.BarCode.Generation.Pdf417EncodeMode enum. Modalità di codifica del codice a barre Pdf417"
type: docs
weight: 1540
url: /it/net/aspose.barcode.generation/pdf417encodemode/
---
## Pdf417EncodeMode enumeration

Modalità di codifica del codice a barre Pdf417

```csharp
public enum Pdf417EncodeMode
```

### Valori

| Nome | Valore | Descrizione |
| --- | --- | --- |
| Auto | `0` | In modalità Auto, il CodeText viene codificato con la massima compattezza dei dati. I caratteri Unicode vengono ricodificati nella codifica specificata da ECIEncoding con l'inserimento di un identificatore ECI. Se viene trovato un carattere non supportato dalla codifica ECI selezionata, viene sollevata un'eccezione. |
| Binary | `1` | In modalità Binaria, il CodeText viene codificato con la massima compattezza dei dati. Se viene trovato un carattere Unicode, viene sollevata un'eccezione. |
| ECI | `2` | In modalità ECI, l'intero messaggio viene ricodificato nella codifica specificata da ECIEncoding con l'inserimento di un identificatore ECI. Se viene trovato un carattere non supportato dalla codifica ECI selezionata, viene sollevata un'eccezione. Si prega di notare che alcuni scanner vecchi (precedenti al 2006) potrebbero non supportare questa modalità. |
| Extended | `3` | Modalità estesa che supporta più modalità ECI. |

### Vedi anche

* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


