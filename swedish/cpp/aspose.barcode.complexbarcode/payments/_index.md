---
title: "Aspose::BarCode::ComplexBarcode::Payments klass"
linktitle: "Payments"
second_title: "Aspose.BarCode for C++ API-referens"
description: "Aspose::BarCode::ComplexBarcode::Payments klass. Fältvalideringar relaterade till schweiziska betalningsstandarder i C++."
type: docs
weight: 2400
url: /sv/cpp/aspose.barcode.complexbarcode/payments/
---
## Payments class


Fältvalideringar relaterade till schweiziska betalningsstandarder.

```cpp
class Payments
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| static [CleanValue](./cleanvalue/)(System::String, Payments::CleaningResult\&) | Rensar ett strängvärde för att göra det giltigt för de schweiziska betalningsstandarderna 2018. |
| static [CreateIso11649Reference](./createiso11649reference/)(System::String) | Skapar en ISO11649-kreditorreferens från en rå sträng genom att prefixa strängen med "RF" och modulo 97-kontrollsumman. |
| static [FormatIban](./formatiban/)(System::String) | Formaterar ett IBAN eller en kreditorreferens genom att infoga mellanslag |
| static [FormatQrReferenceNumber](./formatqrreferencenumber/)(System::String) | Formaterar ett QR-referensnummer genom att infoga mellanslag. |
| static [IsAlphaNumeric](./isalphanumeric/)(System::String) |  |
| static [IsValidIban](./isvalidiban/)(System::String) | Validerar om strängen är ett giltigt IBAN-nummer |
| static [IsValidIso11649Reference](./isvalidiso11649reference/)(System::String) | Validerar om strängen är ett giltigt ISO 11649-referensnummer |
| static [IsValidQrReference](./isvalidqrreference/)(System::String) | Validerar om strängen är en giltig QR-referens. |
| [Payments](./payments/)() |  |
## Se även

* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
