---
title: "método"
linktitle: "IsValidQrReference"
second_title: "Aspose.BarCode for C++ Referencia de API"
description: " método. Valida si la cadena es una referencia QR válida en C++."
type: docs
weight: 600
url: /es/cpp/aspose.barcode.complexbarcode/payments/isvalidqrreference/
---
## Payments::IsValidQrReference method


Valida si la cadena es una referencia QR válida.

```cpp
static bool Aspose::BarCode::ComplexBarcode::Payments::IsValidQrReference(System::String reference)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| reference | System::String | El número de referencia QR a validar. |

### ReturnValue

**true** if the reference number is valid, **false** otherwise.
## Observaciones


Una referencia QR válida es una referencia ISR válida.

La cadena se verifica para caracteres válidos, longitud válida y un dígito de control válido. Los espacios en blanco se ignoran.

## Ver también

* Class [Payments](../)
* Namespace [Aspose::BarCode::ComplexBarcode](../../)
* Library [Aspose.BarCode for C++](../../../)
