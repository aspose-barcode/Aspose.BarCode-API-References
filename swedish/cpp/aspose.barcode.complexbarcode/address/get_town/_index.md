---
title: "metod"
linktitle: "get_Town"
second_title: "Aspose.BarCode for C++ API-referens"
description: " metod. Hämtar staden eller orten i C++."
type: docs
weight: 1400
url: /sv/cpp/aspose.barcode.complexbarcode/address/get_town/
---
## Address::get_Town method


Hämtar stad eller ort.

```cpp
System::String Aspose::BarCode::ComplexBarcode::Address::get_Town() const
```

## Anmärkningar


Genom att sätta detta fält sätts adresstypen till [AddressType::Structured](../../addresstype/) om den inte redan är [AddressType::CombinedElements](../../addresstype/), i så fall blir den [AddressType::Conflicting](../../addresstype/).

Detta fält används endast för strukturerade adresser. För denna typ är det obligatoriskt.

Staden eller orten.
## Se även

* Class [Address](../)
* Namespace [Aspose::BarCode::ComplexBarcode](../../)
* Library [Aspose.BarCode for C++](../../../)
