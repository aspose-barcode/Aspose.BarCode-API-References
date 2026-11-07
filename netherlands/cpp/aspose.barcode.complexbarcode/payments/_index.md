---
title: "Aspose::BarCode::ComplexBarcode::Payments klasse"
linktitle: "Payments"
second_title: "Aspose.BarCode for C++ API-referentie"
description: "Aspose::BarCode::ComplexBarcode::Payments klasse. Veldvalidaties gerelateerd aan de Zwitserse betalingsnormen in C++."
type: docs
weight: 2400
url: /nl/cpp/aspose.barcode.complexbarcode/payments/
---
## Payments class


Veldvalidaties gerelateerd aan Zwitserse betalingsnormen.

```cpp
class Payments
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| static [CleanValue](./cleanvalue/)(System::String, Payments::CleaningResult\&) | Reinigt een tekenreekswaarde om deze bruikbaar te maken voor de Zwitserse betalingsnormen 2018. |
| static [CreateIso11649Reference](./createiso11649reference/)(System::String) | Maakt een ISO11649 crediteurreferentie aan vanuit een ruwe tekenreeks door de tekenreeks te prefixen met "RF" en de modulo 97 controlegetal. |
| static [FormatIban](./formatiban/)(System::String) | Formatteert een IBAN of crediteurreferentie door spaties in te voegen |
| static [FormatQrReferenceNumber](./formatqrreferencenumber/)(System::String) | Formatteert een QR-referentienummer door spaties in te voegen. |
| static [IsAlphaNumeric](./isalphanumeric/)(System::String) |  |
| static [IsValidIban](./isvalidiban/)(System::String) | Valideert of de tekenreeks een geldig IBAN-nummer is |
| static [IsValidIso11649Reference](./isvalidiso11649reference/)(System::String) | Valideert of de tekenreeks een geldig ISO 11649-referentienummer is |
| static [IsValidQrReference](./isvalidqrreference/)(System::String) | Valideert of de tekenreeks een geldige QR-referentie is. |
| [Payments](./payments/)() |  |
## Zie ook

* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
