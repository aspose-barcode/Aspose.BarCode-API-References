---
title: "método"
linktitle: "get_AddressLine2"
second_title: "Aspose.BarCode for C++ Referencia de API"
description: " método. Obtiene la línea de dirección 2 en C++."
type: docs
weight: 600
url: /es/cpp/aspose.barcode.complexbarcode/address/get_addressline2/
---
## Address::get_AddressLine2 method


Obtiene la línea 2 de la dirección.

```cpp
System::String Aspose::BarCode::ComplexBarcode::Address::get_AddressLine2() const
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
