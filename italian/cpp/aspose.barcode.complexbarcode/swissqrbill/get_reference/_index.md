---
title: "method"
linktitle: "get_Reference"
second_title: "Aspose.BarCode for C++ Riferimento API"
description: " metodo. Ottiene il riferimento di pagamento del creditore in C++."
type: docs
weight: 1100
url: /it/cpp/aspose.barcode.complexbarcode/swissqrbill/get_reference/
---
## SwissQRBill::get_Reference method


Ottiene il riferimento di pagamento del creditore.

```cpp
System::String Aspose::BarCode::ComplexBarcode::SwissQRBill::get_Reference() const
```

## Osservazioni


Il riferimento è obbligatorio per gli IBAN SwissQR, cioè gli IBAN nell'intervallo CHxx30000xxxxxx fino a CHxx31999xxxxx.

Se specificato, il riferimento deve essere o un riferimento SwissQR valido (corrispondente al modulo di riferimento ISR) o un riferimento del creditore valido secondo ISO 11649 (\"RFxxxx\"). Entrambi possono contenere spazi per la formattazione.

Il riferimento di pagamento del creditore.
## Vedi anche

* Class [SwissQRBill](../)
* Namespace [Aspose::BarCode::ComplexBarcode](../../)
* Library [Aspose.BarCode for C++](../../../)
