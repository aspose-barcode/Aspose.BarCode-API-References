---
title: "method"
linktitle: "set_AddressLine1"
second_title: "Aspose.BarCode for C++ Riferimento API"
description: " metodo. Imposta la prima riga dell'indirizzo in C++."
type: docs
weight: 500
url: /it/cpp/aspose.barcode.complexbarcode/address/set_addressline1/
---
## Address::set_AddressLine1 method


Imposta la prima riga dell'indirizzo.

```cpp
void Aspose::BarCode::ComplexBarcode::Address::set_AddressLine1(System::String value)
```

## Osservazioni


[Address](../) line 1 contains street name, house number or P.O. box. 

Impostando questo campo si imposta il tipo di indirizzo su [AddressType::CombinedElements](../../addresstype/) a meno che non sia già [AddressType::Structured](../../addresstype/), nel qual caso diventa [AddressType::Conflicting](../../addresstype/).

Questo campo è utilizzato solo per gli indirizzi a elementi combinati ed è opzionale.

La prima riga dell'indirizzo.
## Vedi anche

* Class [Address](../)
* Namespace [Aspose::BarCode::ComplexBarcode](../../)
* Library [Aspose.BarCode for C++](../../../)
