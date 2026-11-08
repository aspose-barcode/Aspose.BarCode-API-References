---
title: "método"
linktitle: "set_AddressLine2"
second_title: "Aspose.BarCode for C++ Referencia de API"
description: " método. Establece la línea de dirección 2 en C++."
type: docs
weight: 700
url: /es/cpp/aspose.barcode.complexbarcode/address/set_addressline2/
---
## Address::set_AddressLine2 method


Establece la línea 2 de la dirección.

```cpp
void Aspose::BarCode::ComplexBarcode::Address::set_AddressLine2(System::String value)
```

## Observaciones


[Address](../) line 2 contains postal code and town. 

Al establecer este campo se asigna el tipo de dirección a [AddressType::CombinedElements](../../addresstype/) a menos que ya sea [AddressType::Structured](../../addresstype/), en cuyo caso se convierte en [AddressType::Conflicting](../../addresstype/).

Este campo solo se usa para direcciones de elementos combinados. Para este tipo, es obligatorio.

La línea de dirección 2.
## Ver también

* Class [Address](../)
* Namespace [Aspose::BarCode::ComplexBarcode](../../)
* Library [Aspose.BarCode for C++](../../../)
