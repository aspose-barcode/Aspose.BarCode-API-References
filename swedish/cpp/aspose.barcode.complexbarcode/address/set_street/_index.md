---
title: "metod"
linktitle: "set_Street"
second_title: "Aspose.BarCode for C++ API-referens"
description: " metod. Sätter gatan i C++."
type: docs
weight: 900
url: /sv/cpp/aspose.barcode.complexbarcode/address/set_street/
---
## Address::set_Street method


Anger gatan.

```cpp
void Aspose::BarCode::ComplexBarcode::Address::set_Street(System::String value)
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
