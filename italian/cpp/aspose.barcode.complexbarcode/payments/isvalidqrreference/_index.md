---
title: "method"
linktitle: "IsValidQrReference"
second_title: "Aspose.BarCode for C++ Riferimento API"
description: " metodo. Convalida se la stringa è un riferimento QR valido in C++."
type: docs
weight: 600
url: /it/cpp/aspose.barcode.complexbarcode/payments/isvalidqrreference/
---
## Payments::IsValidQrReference method


Convalida se la stringa è un riferimento QR valido.

```cpp
static bool Aspose::BarCode::ComplexBarcode::Payments::IsValidQrReference(System::String reference)
```


| Parameter | Type | Descrizione |
| --- | --- | --- |
| reference | System::String | Il numero di riferimento QR da convalidare. |

### ReturnValue

**true** if the reference number is valid, **false** otherwise.
## Osservazioni


Un riferimento QR valido è un riferimento ISR valido.

La stringa viene controllata per caratteri validi, lunghezza valida e un cifrario di controllo valido. Gli spazi bianchi sono ignorati.

## Vedi anche

* Class [Payments](../)
* Namespace [Aspose::BarCode::ComplexBarcode](../../)
* Library [Aspose.BarCode for C++](../../../)
