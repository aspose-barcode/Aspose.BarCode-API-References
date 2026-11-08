---
title: "método"
linktitle: "set_Town"
second_title: "Aspose.BarCode for C++ Referencia de API"
description: " método. Establece la ciudad o pueblo en C++."
type: docs
weight: 1500
url: /es/cpp/aspose.barcode.complexbarcode/address/set_town/
---
## Address::set_Town method


Establece la localidad o la ciudad.

```cpp
void Aspose::BarCode::ComplexBarcode::Address::set_Town(System::String value)
```

## Observaciones


Al establecer este campo se asigna el tipo de dirección a [AddressType::Structured](../../addresstype/) a menos que ya sea [AddressType::CombinedElements](../../addresstype/), en cuyo caso se convierte en [AddressType::Conflicting](../../addresstype/).

Este campo solo se usa para direcciones estructuradas. Para este tipo, es obligatorio.

La ciudad o pueblo.
## Ver también

* Class [Address](../)
* Namespace [Aspose::BarCode::ComplexBarcode](../../)
* Library [Aspose.BarCode for C++](../../../)
