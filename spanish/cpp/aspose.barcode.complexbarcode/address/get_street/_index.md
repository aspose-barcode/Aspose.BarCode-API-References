---
title: "método"
linktitle: "get_Street"
second_title: "Aspose.BarCode for C++ Referencia de API"
description: " método. Obtiene la calle en C++."
type: docs
weight: 800
url: /es/cpp/aspose.barcode.complexbarcode/address/get_street/
---
## Address::get_Street method


Obtiene la calle.

```cpp
System::String Aspose::BarCode::ComplexBarcode::Address::get_Street() const
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
