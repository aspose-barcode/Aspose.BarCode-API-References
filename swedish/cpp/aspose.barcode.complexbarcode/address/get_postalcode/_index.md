---
title: "metod"
linktitle: "get_PostalCode"
second_title: "Aspose.BarCode for C++ API-referens"
description: " metod. Hämtar postnumret i C++."
type: docs
weight: 1200
url: /sv/cpp/aspose.barcode.complexbarcode/address/get_postalcode/
---
## Address::get_PostalCode method


Hämtar postnumret.

```cpp
System::String Aspose::BarCode::ComplexBarcode::Address::get_PostalCode() const
```

## Anmärkningar


Genom att sätta detta fält sätts adresstypen till [AddressType::Structured](../../addresstype/) om den inte redan är [AddressType::CombinedElements](../../addresstype/), i så fall blir den [AddressType::Conflicting](../../addresstype/).

Detta fält används endast för strukturerade adresser. För denna typ är det obligatoriskt.

Postnumret.
## Se även

* Class [Address](../)
* Namespace [Aspose::BarCode::ComplexBarcode](../../)
* Library [Aspose.BarCode for C++](../../../)
