---
title: "metod"
linktitle: "get_AddressLine1"
second_title: "Aspose.BarCode for C++ API-referens"
description: " metod. Hämtar adressrad 1 i C++."
type: docs
weight: 400
url: /sv/cpp/aspose.barcode.complexbarcode/address/get_addressline1/
---
## Address::get_AddressLine1 method


Hämtar adressrad 1.

```cpp
System::String Aspose::BarCode::ComplexBarcode::Address::get_AddressLine1() const
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
