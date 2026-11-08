---
title: "método"
linktitle: "get_Town"
second_title: "Aspose.BarCode for C++ Referencia de API"
description: " método. Obtiene la ciudad o pueblo en C++."
type: docs
weight: 1400
url: /es/cpp/aspose.barcode.complexbarcode/address/get_town/
---
## Address::get_Town method


Obtiene la localidad o ciudad.

```cpp
System::String Aspose::BarCode::ComplexBarcode::Address::get_Town() const
```

## Observaciones


Al establecer este campo se asigna el tipo de dirección a [AddressType::Structured](../../addresstype/) a menos que ya sea [AddressType::CombinedElements](../../addresstype/), en cuyo caso se convierte en [AddressType::Conflicting](../../addresstype/).

Este campo solo se usa para direcciones estructuradas. Para este tipo, es obligatorio.

La ciudad o pueblo.
## Ver también

* Class [Address](../)
* Namespace [Aspose::BarCode::ComplexBarcode](../../)
* Library [Aspose.BarCode for C++](../../../)
