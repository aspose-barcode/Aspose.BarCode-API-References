---
title: "metod"
linktitle: "get_Street"
second_title: "Aspose.BarCode for C++ API-referens"
description: " metod. Hämtar gatan i C++."
type: docs
weight: 800
url: /sv/cpp/aspose.barcode.complexbarcode/address/get_street/
---
## Address::get_Street method


Hämtar gatan.

```cpp
System::String Aspose::BarCode::ComplexBarcode::Address::get_Street() const
```

## Anmärkningar


Gatan måste anges utan husnummer.

Genom att sätta detta fält sätts adresstypen till [AddressType::Structured](../../addresstype/) om den inte redan är [AddressType::CombinedElements](../../addresstype/), i så fall blir den [AddressType::Conflicting](../../addresstype/).

Detta fält används endast för strukturerade adresser och är valfritt.

Gatan.
## Se även

* Class [Address](../)
* Namespace [Aspose::BarCode::ComplexBarcode](../../)
* Library [Aspose.BarCode for C++](../../../)
