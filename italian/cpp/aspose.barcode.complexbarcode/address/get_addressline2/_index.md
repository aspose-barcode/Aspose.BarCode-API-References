---
title: "method"
linktitle: "get_AddressLine2"
second_title: "Aspose.BarCode for C++ Riferimento API"
description: " metodo. Ottiene la seconda riga dell'indirizzo in C++."
type: docs
weight: 600
url: /it/cpp/aspose.barcode.complexbarcode/address/get_addressline2/
---
## Address::get_AddressLine2 method


Ottiene la seconda riga dell'indirizzo.

```cpp
System::String Aspose::BarCode::ComplexBarcode::Address::get_AddressLine2() const
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
