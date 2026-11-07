---
title: "enum"
linktitle: "EnableChecksum"
second_title: "Aspose.BarCode for C++ Riferimento API"
description: "Come utilizzare l'enumerazione in C++."
type: docs
weight: 6700
url: /it/cpp/aspose.barcode.generation/enablechecksum/
---
## EnableChecksum enum




```cpp
enum class EnableChecksum
```

### Valori

| Nome | Valore | Descrizione |
| --- | --- | --- |
| Predefinito | 0 | Se il checksum è richiesto dalla specifica, verrà allegato. |
| Sì | 1 | Usa sempre il checksum se possibile. |
| No | 2 | Non utilizzare il checksum. |

## Osservazioni


Abilita il checksum durante la generazione per i codici a barre 1D.

Il valore predefinito è considerato Sì per le simbologie che devono contenere il checksum, e No dove il checksum è solo opzionale.

Checksum mai usato: Codabar

Checksum possibile: Code39 Standard/Extended, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, DeutschePostIdentcode, DeutschePostLeitcode, VIN

Checksum sempre usato: Altre simbologie
## Vedi anche

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
