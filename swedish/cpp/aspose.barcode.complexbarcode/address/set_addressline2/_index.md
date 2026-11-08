---
title: "metod"
linktitle: "set_AddressLine2"
second_title: "Aspose.BarCode for C++ API-referens"
description: " metod. Sätter adressrad 2 i C++."
type: docs
weight: 700
url: /sv/cpp/aspose.barcode.complexbarcode/address/set_addressline2/
---
## Address::set_AddressLine2 method


Sätter adressrad 2.

```cpp
void Aspose::BarCode::ComplexBarcode::Address::set_AddressLine2(System::String value)
```

## Anmärkningar


[Address](../) line 2 contains postal code and town. 

Genom att sätta detta fält sätts adresstypen till [AddressType::CombinedElements](../../addresstype/) om den inte redan är [AddressType::Structured](../../addresstype/), i så fall blir den [AddressType::Conflicting](../../addresstype/).

Detta fält används endast för adresser med kombinerade element. För denna typ är det obligatoriskt.

Adressrad 2.
## Se även

* Class [Address](../)
* Namespace [Aspose::BarCode::ComplexBarcode](../../)
* Library [Aspose.BarCode for C++](../../../)
