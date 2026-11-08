---
title: "método"
linktitle: "get_Reference"
second_title: "Aspose.BarCode for C++ Referencia de API"
description: " método. Obtiene la referencia de pago del acreedor en C++."
type: docs
weight: 1100
url: /es/cpp/aspose.barcode.complexbarcode/swissqrbill/get_reference/
---
## SwissQRBill::get_Reference method


Obtiene la referencia de pago del acreedor.

```cpp
System::String Aspose::BarCode::ComplexBarcode::SwissQRBill::get_Reference() const
```

## Observaciones


La referencia es obligatoria para los IBAN SwissQR, es decir, los IBAN en el rango CHxx30000xxxxxx hasta CHxx31999xxxxx.

Si se especifica, la referencia debe ser una referencia SwissQR válida (correspondiente al formulario de referencia ISR) o una referencia de acreedor válida según la ISO 11649 (\"RFxxxx\"). Ambas pueden contener espacios para el formato.

La referencia de pago del acreedor.
## Ver también

* Class [SwissQRBill](../)
* Namespace [Aspose::BarCode::ComplexBarcode](../../)
* Library [Aspose.BarCode for C++](../../../)
