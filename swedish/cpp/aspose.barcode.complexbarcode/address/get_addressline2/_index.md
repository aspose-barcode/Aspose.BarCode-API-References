---
title: "metod"
linktitle: "get_AddressLine2"
second_title: "Aspose.BarCode for C++ API-referens"
description: " metod. Hämtar adressrad 2 i C++."
type: docs
weight: 600
url: /sv/cpp/aspose.barcode.complexbarcode/address/get_addressline2/
---
## Address::get_AddressLine2 method


Hämtar adressrad 2.

```cpp
System::String Aspose::BarCode::ComplexBarcode::Address::get_AddressLine2() const
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
