---
title: "method"
linktitle: "SetMeteredKey"
second_title: "Aspose.BarCode for C++ Riferimento API"
description: " metodo. Imposta la chiave pubblica e privata a consumo. Se acquisti una licenza a consumo, all'avvio dell'applicazione, questa API dovrebbe essere chiamata; normalmente è sufficiente. Tuttavia, se fallisce sempre il caricamento dei dati di consumo e supera le 24 ore, la licenza verrà impostata in stato di valutazione; per evitare tale caso, dovresti controllare regolarmente lo stato della licenza; se è in stato di valutazione, chiama nuovamente questa API in C++."
type: docs
weight: 200
url: /it/cpp/aspose.barcode/metered/setmeteredkey/
---
## Metered::SetMeteredKey method


Imposta la chiave pubblica e privata metered. Se acquisti una licenza metered, all'avvio dell'applicazione, questa API dovrebbe essere chiamata; normalmente è sufficiente. Tuttavia, se il caricamento dei dati di consumo fallisce continuamente e supera le 24 ore, la licenza verrà impostata su stato di valutazione; per evitare tale caso, dovresti controllare regolarmente lo stato della licenza e, se è in stato di valutazione, chiamare nuovamente questa API.

```cpp
void Aspose::BarCode::Metered::SetMeteredKey(System::String publicKey, System::String privateKey)
```


| Parameter | Type | Descrizione |
| --- | --- | --- |
| publicKey | System::String | chiave pubblica |
| privateKey | System::String | chiave privata |

## Vedi anche

* Class [Metered](../)
* Namespace [Aspose::BarCode](../../)
* Library [Aspose.BarCode for C++](../../../)
