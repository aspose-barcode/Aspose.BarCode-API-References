---
title: "metod"
linktitle: "set_Town"
second_title: "Aspose.BarCode for C++ API-referens"
description: " metod. Sätter staden eller orten i C++."
type: docs
weight: 1500
url: /sv/cpp/aspose.barcode.complexbarcode/address/set_town/
---
## Address::set_Town method


Anger orten eller staden.

```cpp
void Aspose::BarCode::ComplexBarcode::Address::set_Town(System::String value)
```

## Anmärkningar


Genom att sätta detta fält sätts adresstypen till [AddressType::Structured](../../addresstype/) om den inte redan är [AddressType::CombinedElements](../../addresstype/), i så fall blir den [AddressType::Conflicting](../../addresstype/).

Detta fält används endast för strukturerade adresser. För denna typ är det obligatoriskt.

Staden eller orten.
## Se även

* Class [Address](../)
* Namespace [Aspose::BarCode::ComplexBarcode](../../)
* Library [Aspose.BarCode for C++](../../../)
