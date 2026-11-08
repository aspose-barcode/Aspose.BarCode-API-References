---
title: "metod"
linktitle: "set_AddressLine1"
second_title: "Aspose.BarCode for C++ API-referens"
description: " metod. Sätter adressrad 1 i C++."
type: docs
weight: 500
url: /sv/cpp/aspose.barcode.complexbarcode/address/set_addressline1/
---
## Address::set_AddressLine1 method


Sätter adressrad 1.

```cpp
void Aspose::BarCode::ComplexBarcode::Address::set_AddressLine1(System::String value)
```

## Anmärkningar


[Address](../) line 1 contains street name, house number or P.O. box. 

Genom att sätta detta fält sätts adresstypen till [AddressType::CombinedElements](../../addresstype/) om den inte redan är [AddressType::Structured](../../addresstype/), i så fall blir den [AddressType::Conflicting](../../addresstype/).

Detta fält används endast för adresser med kombinerade element och är valfritt.

Adressrad 1.
## Se även

* Class [Address](../)
* Namespace [Aspose::BarCode::ComplexBarcode](../../)
* Library [Aspose.BarCode for C++](../../../)
