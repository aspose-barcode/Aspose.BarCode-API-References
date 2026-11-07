---
title: "enum"
linktitle: "AutoSizeMode"
second_title: "Aspose.BarCode for C++ Riferimento API"
description: " enum. Specifica i diversi tipi di modalità di dimensionamento automatico in C++."
type: docs
weight: 5200
url: /it/cpp/aspose.barcode.generation/autosizemode/
---
## AutoSizeMode enum


Specifica i diversi tipi di modalità di dimensionamento automatico.

```cpp
enum class AutoSizeMode
```

### Valori

| Nome | Valore | Descrizione |
| --- | --- | --- |
| Nessuno | 0 | Il ridimensionamento automatico è disabilitato. |
| Nearest | 1 | Ridimensiona il codice a barre alla dimensione più bassa possibile più vicina specificata dalle proprietà ImageWidth e ImageHeight. Preserva il rapporto d'aspetto predefinito. |
| Interpolazione | 2 | Ridimensiona il codice a barre alla dimensione specificata. La dimensione può essere specificata tramite le proprietà ImageWidth e ImageHeight. Il codice a barre generato potrebbe essere non valido (non leggibile) dopo il ridimensionamento. |

## Vedi anche

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
