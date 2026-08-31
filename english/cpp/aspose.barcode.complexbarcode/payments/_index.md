---
title: Aspose::BarCode::ComplexBarcode::Payments class
linktitle: Payments
second_title: Aspose.BarCode for C++ API Reference
description: 'Aspose::BarCode::ComplexBarcode::Payments class. Field validations related to Swiss Payment standards in C++.'
type: docs
weight: 2200
url: /cpp/aspose.barcode.complexbarcode/payments/
---
## Payments class


Field validations related to Swiss Payment standards.

```cpp
class Payments
```

## Methods

| Method | Description |
| --- | --- |
| static [CleanValue](./cleanvalue/)(System::String, Payments::CleaningResult\&) | Cleans a string value to make it viable for the Swiss Payment Standards 2018. |
| static [CreateIso11649Reference](./createiso11649reference/)(System::String) | Creates a ISO11649 creditor reference from a raw string by prefixing the string with "RF" and the modulo 97 checksum |
| static [FormatIban](./formatiban/)(System::String) | Formats an IBAN or creditor reference by inserting spaces |
| static [FormatQrReferenceNumber](./formatqrreferencenumber/)(System::String) | Formats a QR reference number by inserting spaces. |
| static [IsAlphaNumeric](./isalphanumeric/)(System::String) |  |
| static [IsValidIban](./isvalidiban/)(System::String) | Validates if the string is a valid IBAN number |
| static [IsValidIso11649Reference](./isvalidiso11649reference/)(System::String) | Validates if the string is a valid ISO 11649 reference number |
| static [IsValidQrReference](./isvalidqrreference/)(System::String) | Validates if the string is a valid QR reference. |
| [Payments](./payments/)() |  |
## See Also

* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
