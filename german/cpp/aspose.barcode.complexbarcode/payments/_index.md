---
title: "Aspose::BarCode::ComplexBarcode::Payments Klasse"
linktitle: "Payments"
second_title: "Aspose.BarCode für C++ API-Referenz"
description: "Aspose::BarCode::ComplexBarcode::Payments Klasse. Feldvalidierungen im Zusammenhang mit den Schweizer Zahlungsstandards in C++."
type: docs
weight: 2400
url: /de/cpp/aspose.barcode.complexbarcode/payments/
---
## Payments class


Feldvalidierungen im Zusammenhang mit den Schweizer Zahlungsstandards.

```cpp
class Payments
```

## Methods

| Method | Beschreibung |
| --- | --- |
| static [CleanValue](./cleanvalue/)(System::String, Payments::CleaningResult\&) | Bereinigt einen Zeichenkettenwert, um ihn für die Schweizer Zahlungsstandards 2018 nutzbar zu machen. |
| static [CreateIso11649Reference](./createiso11649reference/)(System::String) | Erstellt eine ISO11649-Gläubigerreferenz aus einer Rohzeichenkette, indem die Zeichenkette mit "RF" und der Modulo-97-Prüfsumme versehen wird. |
| static [FormatIban](./formatiban/)(System::String) | Formatiert eine IBAN oder Gläubigerreferenz, indem Leerzeichen eingefügt werden. |
| static [FormatQrReferenceNumber](./formatqrreferencenumber/)(System::String) | Formatiert eine QR-Referenznummer, indem Leerzeichen eingefügt werden. |
| static [IsAlphaNumeric](./isalphanumeric/)(System::String) |  |
| static [IsValidIban](./isvalidiban/)(System::String) | Validiert, ob die Zeichenkette eine gültige IBAN-Nummer ist. |
| static [IsValidIso11649Reference](./isvalidiso11649reference/)(System::String) | Validiert, ob die Zeichenkette eine gültige ISO-11649-Referenznummer ist. |
| static [IsValidQrReference](./isvalidqrreference/)(System::String) | Validiert, ob die Zeichenkette eine gültige QR-Referenz ist. |
| [Payments](./payments/)() |  |
## Siehe auch

* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
