---
title: "método"
linktitle: "set_Street"
second_title: "Aspose.BarCode for C++ Referencia de API"
description: " método. Establece la calle en C++."
type: docs
weight: 900
url: /es/cpp/aspose.barcode.complexbarcode/address/set_street/
---
## Address::set_Street method


Establece la calle.

```cpp
void Aspose::BarCode::ComplexBarcode::Address::set_Street(System::String value)
```

## Observaciones


La calle debe especificarse sin número de casa.

Al establecer este campo se asigna el tipo de dirección a [AddressType::Structured](../../addresstype/) a menos que ya sea [AddressType::CombinedElements](../../addresstype/), en cuyo caso se convierte en [AddressType::Conflicting](../../addresstype/).

Este campo solo se usa para direcciones estructuradas y es opcional.

La calle.
## Ver también

* Class [Address](../)
* Namespace [Aspose::BarCode::ComplexBarcode](../../)
* Library [Aspose.BarCode for C++](../../../)
