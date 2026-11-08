---
title: "método"
linktitle: "set_PostalCode"
second_title: "Aspose.BarCode for C++ Referencia de API"
description: " método. Establece el código postal en C++."
type: docs
weight: 1300
url: /es/cpp/aspose.barcode.complexbarcode/address/set_postalcode/
---
## Address::set_PostalCode method


Establece el código postal.

```cpp
void Aspose::BarCode::ComplexBarcode::Address::set_PostalCode(System::String value)
```

## Observaciones


Al establecer este campo se asigna el tipo de dirección a [AddressType::Structured](../../addresstype/) a menos que ya sea [AddressType::CombinedElements](../../addresstype/), en cuyo caso se convierte en [AddressType::Conflicting](../../addresstype/).

Este campo solo se usa para direcciones estructuradas. Para este tipo, es obligatorio.

El código postal.
## Ver también

* Class [Address](../)
* Namespace [Aspose::BarCode::ComplexBarcode](../../)
* Library [Aspose.BarCode for C++](../../../)
