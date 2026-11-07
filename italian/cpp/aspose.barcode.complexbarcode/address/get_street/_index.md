---
title: "method"
linktitle: "get_Street"
second_title: "Aspose.BarCode for C++ Riferimento API"
description: " metodo. Ottiene la via in C++."
type: docs
weight: 800
url: /it/cpp/aspose.barcode.complexbarcode/address/get_street/
---
## Address::get_Street method


Ottiene la via.

```cpp
System::String Aspose::BarCode::ComplexBarcode::Address::get_Street() const
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
