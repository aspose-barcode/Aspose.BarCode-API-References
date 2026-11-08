---
title: "Clase Aspose::BarCode::ComplexBarcode::Payments"
linktitle: "Payments"
second_title: "Aspose.BarCode for C++ Referencia de API"
description: "Clase Aspose::BarCode::ComplexBarcode::Payments. Validaciones de campos relacionadas con los estándares de pago suizos en C++."
type: docs
weight: 2400
url: /es/cpp/aspose.barcode.complexbarcode/payments/
---
## Payments class


Validaciones de campos relacionadas con los estándares de pago suizos.

```cpp
class Payments
```

## Métodos

| Método | Descripción |
| --- | --- |
| static [CleanValue](./cleanvalue/)(System::String, Payments::CleaningResult\&) | Limpia un valor de cadena para que sea viable para los estándares de pago suizos 2018. |
| static [CreateIso11649Reference](./createiso11649reference/)(System::String) | Crea una referencia de acreedor ISO11649 a partir de una cadena cruda añadiendo el prefijo "RF" y el checksum módulo 97 |
| static [FormatIban](./formatiban/)(System::String) | Formatea un IBAN o una referencia de acreedor insertando espacios |
| static [FormatQrReferenceNumber](./formatqrreferencenumber/)(System::String) | Formatea un número de referencia QR insertando espacios. |
| static [IsAlphaNumeric](./isalphanumeric/)(System::String) |  |
| static [IsValidIban](./isvalidiban/)(System::String) | Valida si la cadena es un número IBAN válido |
| static [IsValidIso11649Reference](./isvalidiso11649reference/)(System::String) | Valida si la cadena es un número de referencia ISO 11649 válido |
| static [IsValidQrReference](./isvalidqrreference/)(System::String) | Valida si la cadena es una referencia QR válida. |
| [Payments](./payments/)() |  |
## Ver también

* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
