---
title: "method"
linktitle: "set_Reference"
second_title: "Aspose.BarCode for C++ Riferimento API"
description: " metodo. Imposta il riferimento di pagamento del creditore in C++."
type: docs
weight: 1200
url: /it/cpp/aspose.barcode.complexbarcode/swissqrbill/set_reference/
---
## SwissQRBill::set_Reference method


Imposta il riferimento di pagamento del creditore.

```cpp
void Aspose::BarCode::ComplexBarcode::SwissQRBill::set_Reference(System::String value)
```

## Osservazioni


Il riferimento è obbligatorio per gli IBAN SwissQR, cioè gli IBAN nell'intervallo CHxx30000xxxxxx fino a CHxx31999xxxxx.

Se specificato, il riferimento deve essere o un riferimento SwissQR valido (corrispondente al modulo di riferimento ISR) o un riferimento del creditore valido secondo ISO 11649 (\"RFxxxx\"). Entrambi possono contenere spazi per la formattazione.

Il riferimento di pagamento del creditore.
## Vedi anche

* Class [SwissQRBill](../)
* Namespace [Aspose::BarCode::ComplexBarcode](../../)
* Library [Aspose.BarCode for C++](../../../)
