---
title: "method"
linktitle: "set_Street"
second_title: "Aspose.BarCode for C++ Riferimento API"
description: " metodo. Imposta la via in C++."
type: docs
weight: 900
url: /it/cpp/aspose.barcode.complexbarcode/address/set_street/
---
## Address::set_Street method


Imposta la via.

```cpp
void Aspose::BarCode::ComplexBarcode::Address::set_Street(System::String value)
```

## Osservazioni


La via deve essere specificata senza numero civico.

Impostando questo campo si imposta il tipo di indirizzo su [AddressType::Structured](../../addresstype/) a meno che non sia già [AddressType::CombinedElements](../../addresstype/), nel qual caso diventa [AddressType::Conflicting](../../addresstype/).

Questo campo è utilizzato solo per gli indirizzi strutturati ed è opzionale.

La via.
## Vedi anche

* Class [Address](../)
* Namespace [Aspose::BarCode::ComplexBarcode](../../)
* Library [Aspose.BarCode for C++](../../../)
