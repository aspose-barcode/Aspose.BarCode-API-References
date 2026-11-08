---
title: "metod"
linktitle: "set_PostalCode"
second_title: "Aspose.BarCode for C++ API-referens"
description: " metod. Sätter postnumret i C++."
type: docs
weight: 1300
url: /sv/cpp/aspose.barcode.complexbarcode/address/set_postalcode/
---
## Address::set_PostalCode method


Sätter postnumret.

```cpp
void Aspose::BarCode::ComplexBarcode::Address::set_PostalCode(System::String value)
```

## Anmärkningar


Genom att sätta detta fält sätts adresstypen till [AddressType::Structured](../../addresstype/) om den inte redan är [AddressType::CombinedElements](../../addresstype/), i så fall blir den [AddressType::Conflicting](../../addresstype/).

Detta fält används endast för strukturerade adresser. För denna typ är det obligatoriskt.

Postnumret.
## Se även

* Class [Address](../)
* Namespace [Aspose::BarCode::ComplexBarcode](../../)
* Library [Aspose.BarCode for C++](../../../)
