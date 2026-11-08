---
title: "método"
linktitle: "get_AddressLine1"
second_title: "Aspose.BarCode for C++ Referencia de API"
description: " método. Obtiene la línea de dirección 1 en C++."
type: docs
weight: 400
url: /es/cpp/aspose.barcode.complexbarcode/address/get_addressline1/
---
## Address::get_AddressLine1 method


Obtiene la línea 1 de la dirección.

```cpp
System::String Aspose::BarCode::ComplexBarcode::Address::get_AddressLine1() const
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
