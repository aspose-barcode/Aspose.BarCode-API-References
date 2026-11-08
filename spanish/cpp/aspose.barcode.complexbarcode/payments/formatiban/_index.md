---
title: "método"
linktitle: "FormatIban"
second_title: "Aspose.BarCode for C++ Referencia de API"
description: " método. Formatea un IBAN o referencia del acreedor insertando espacios en C++."
type: docs
weight: 300
url: /es/cpp/aspose.barcode.complexbarcode/payments/formatiban/
---
## Payments::FormatIban method


Formatea un IBAN o una referencia de acreedor insertando espacios

```cpp
static System::String Aspose::BarCode::ComplexBarcode::Payments::FormatIban(System::String iban)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| iban | System::String | El IBAN o referencia del acreedor sin espacios. |

### ReturnValue

El IBAN o referencia del acreedor formateado.
## Observaciones


Se insertan espacios para formar grupos de 4 letras/dígitos. Si se necesita un grupo de menos de 4 letras/dígitos, aparece al final.

## Ver también

* Class [Payments](../)
* Namespace [Aspose::BarCode::ComplexBarcode](../../)
* Library [Aspose.BarCode for C++](../../../)
