---
title: "enum"
linktitle: "Pdf417EncodeMode"
second_title: "Aspose.BarCode for C++ Riferimento API"
description: " enum. Modalità di codifica del codice a barre Pdf417 in C++."
type: docs
weight: 7900
url: /it/cpp/aspose.barcode.generation/pdf417encodemode/
---
## Pdf417EncodeMode enum


Modalità di codifica del codice a barre Pdf417

```cpp
enum class Pdf417EncodeMode
```

### Valori

| Nome | Valore | Descrizione |
| --- | --- | --- |
| Auto | 0 | In modalità Auto, il CodeText viene codificato con la massima compattezza dei dati. I caratteri Unicode vengono ricodificati nella codifica specificata da ECIEncoding con l'inserimento di un identificatore ECI. Se viene trovato un carattere non supportato dalla codifica ECI selezionata, viene generata un'eccezione. |
| Binario | 1 | In modalità Binario, il CodeText viene codificato con la massima compattezza dei dati. Se viene trovato un carattere Unicode, viene generata un'eccezione. |
| ECI | 2 | In modalità ECI, l'intero messaggio viene ricodificato nella codifica specificata da ECIEncoding con l'inserimento di un identificatore ECI. Se viene trovato un carattere non supportato dalla codifica ECI selezionata, viene generata un'eccezione. Si prega di notare che alcuni scanner vecchi (pre 2006) potrebbero non supportare questa modalità. |
| Esteso | 3 |  |

## Vedi anche

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
