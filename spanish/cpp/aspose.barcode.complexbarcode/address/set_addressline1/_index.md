---
title: "método"
linktitle: "set_AddressLine1"
second_title: "Aspose.BarCode for C++ Referencia de API"
description: " método. Establece la línea de dirección 1 en C++."
type: docs
weight: 500
url: /es/cpp/aspose.barcode.complexbarcode/address/set_addressline1/
---
## Address::set_AddressLine1 method


Establece la línea 1 de la dirección.

```cpp
void Aspose::BarCode::ComplexBarcode::Address::set_AddressLine1(System::String value)
```

## Observaciones


[Address](../) line 1 contains street name, house number or P.O. box. 

Al establecer este campo se asigna el tipo de dirección a [AddressType::CombinedElements](../../addresstype/) a menos que ya sea [AddressType::Structured](../../addresstype/), en cuyo caso se convierte en [AddressType::Conflicting](../../addresstype/).

Este campo solo se usa para direcciones de elementos combinados y es opcional.

La línea de dirección 1.
## Ver también

* Class [Address](../)
* Namespace [Aspose::BarCode::ComplexBarcode](../../)
* Library [Aspose.BarCode for C++](../../../)
