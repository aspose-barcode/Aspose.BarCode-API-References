---
title: "método"
linktitle: "FormatQrReferenceNumber"
second_title: "Aspose.BarCode for C++ Referencia de API"
description: " método. Formatea un número de referencia QR insertando espacios en C++."
type: docs
weight: 700
url: /es/cpp/aspose.barcode.complexbarcode/payments/formatqrreferencenumber/
---
## Payments::FormatQrReferenceNumber method


Formatea un número de referencia QR insertando espacios.

```cpp
static System::String Aspose::BarCode::ComplexBarcode::Payments::FormatQrReferenceNumber(System::String refNo)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| refNo | System::String | El número de referencia sin espacios en blanco. |

### ReturnValue

el número de referencia formateado.
## Observaciones


Se insertan espacios para crear grupos de 5 dígitos. Si se necesita un grupo de menos de 5 dígitos, aparece al inicio del número de referencia formateado.

## Ver también

* Class [Payments](../)
* Namespace [Aspose::BarCode::ComplexBarcode](../../)
* Library [Aspose.BarCode for C++](../../../)
