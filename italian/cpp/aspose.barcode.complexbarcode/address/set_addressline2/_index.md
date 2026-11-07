---
title: "method"
linktitle: "set_AddressLine2"
second_title: "Aspose.BarCode for C++ Riferimento API"
description: " method. Imposta la seconda riga dell'indirizzo in C++."
type: docs
weight: 700
url: /it/cpp/aspose.barcode.complexbarcode/address/set_addressline2/
---
## Address::set_AddressLine2 method


Imposta la seconda riga dell'indirizzo.

```cpp
void Aspose::BarCode::ComplexBarcode::Address::set_AddressLine2(System::String value)
```

## Osservazioni


[Address](../) line 2 contains postal code and town. 

Impostando questo campo si imposta il tipo di indirizzo su [AddressType::CombinedElements](../../addresstype/) a meno che non sia già [AddressType::Structured](../../addresstype/), nel qual caso diventa [AddressType::Conflicting](../../addresstype/).

Questo campo è utilizzato solo per gli indirizzi a elementi combinati. Per questo tipo, è obbligatorio.

La seconda riga dell'indirizzo.
## Vedi anche

* Class [Address](../)
* Namespace [Aspose::BarCode::ComplexBarcode](../../)
* Library [Aspose.BarCode for C++](../../../)
