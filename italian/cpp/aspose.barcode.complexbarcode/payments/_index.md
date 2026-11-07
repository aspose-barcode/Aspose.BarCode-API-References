---
title: "classe Aspose::BarCode::ComplexBarcode::Payments"
linktitle: "Payments"
second_title: "Aspose.BarCode for C++ Riferimento API"
description: "classe Aspose::BarCode::ComplexBarcode::Payments. Convalide dei campi relative agli standard di pagamento svizzeri in C++."
type: docs
weight: 2400
url: /it/cpp/aspose.barcode.complexbarcode/payments/
---
## Payments class


Validazioni dei campi relative agli standard di pagamento svizzeri.

```cpp
class Payments
```

## Metodi

| Metodo | Descrizione |
| --- | --- |
| static [CleanValue](./cleanvalue/)(System::String, Payments::CleaningResult\&) | Pulisce un valore stringa per renderlo idoneo agli Standard di Pagamento Svizzeri 2018. |
| static [CreateIso11649Reference](./createiso11649reference/)(System::String) | Crea un riferimento creditore ISO11649 da una stringa grezza aggiungendo il prefisso "RF" e il checksum modulo 97 |
| static [FormatIban](./formatiban/)(System::String) | Formatta un IBAN o un riferimento creditore inserendo spazi |
| static [FormatQrReferenceNumber](./formatqrreferencenumber/)(System::String) | Formatta un numero di riferimento QR inserendo spazi. |
| static [IsAlphaNumeric](./isalphanumeric/)(System::String) |  |
| static [IsValidIban](./isvalidiban/)(System::String) | Convalida se la stringa è un numero IBAN valido |
| static [IsValidIso11649Reference](./isvalidiso11649reference/)(System::String) | Convalida se la stringa è un numero di riferimento ISO 11649 valido |
| static [IsValidQrReference](./isvalidqrreference/)(System::String) | Convalida se la stringa è un riferimento QR valido. |
| [Payments](./payments/)() |  |
## Vedi anche

* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
