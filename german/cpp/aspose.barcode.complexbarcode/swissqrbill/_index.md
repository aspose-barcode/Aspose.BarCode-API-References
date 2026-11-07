---
title: "Aspose::BarCode::ComplexBarcode::SwissQRBill Klasse"
linktitle: "SwissQRBill"
second_title: "Aspose.BarCode für C++ API-Referenz"
description: "Aspose::BarCode::ComplexBarcode::SwissQRBill Klasse. SwissQR-Rechnungsdaten in C++."
type: docs
weight: 2700
url: /de/cpp/aspose.barcode.complexbarcode/swissqrbill/
---
## SwissQRBill class


SwissQR‑Rechnungsdaten

```cpp
class SwissQRBill : public System::IEquatable<System::SharedPtr<SwissQRBill>>
```

## Methods

| Method | Beschreibung |
| --- | --- |
| [CreateAndSetCreditorReference](./createandsetcreditorreference/)(System::String) | Erstellt und setzt eine ISO11649-Gläubigerreferenz aus einem Rohstring, indem dem String das Präfix "RF" und die Modulo‑97-Prüfsumme vorangestellt werden. |
| [Equals](./equals/)(System::SharedPtr\<System::Object\>) override | Bestimmt, ob das angegebene Objekt dem aktuellen Objekt gleich ist. |
| [Equals](./equals/)(System::SharedPtr\<SwissQRBill\>) override | Bestimmt, ob die angegebene Rechnung der aktuellen Rechnung entspricht. |
| [get_Account](./get_account/)() const | Liefert die Kontonummer des Gläubigers. |
| [get_AlternativeSchemes](./get_alternativeschemes/)() const | Liefert oder setzt die alternativen Zahlungsschemata. |
| [get_Amount](./get_amount/)() const | Liefert den Zahlungsbetrag. |
| [get_BillInformation](./get_billinformation/)() const | Liefert die zusätzlichen strukturierten Rechnungsinformationen. |
| [get_Creditor](./get_creditor/)() const | Liefert die Gläubigeradresse. |
| [get_Currency](./get_currency/)() const | Liefert die Zahlungswährung. |
| [get_Debtor](./get_debtor/)() const | Liefert die Schuldneradresse. |
| [get_Reference](./get_reference/)() const | Liefert die Zahlungsreferenz des Gläubigers. |
| [get_UnstructuredMessage](./get_unstructuredmessage/)() const | Liefert die zusätzliche unstrukturierte Nachricht. |
| [get_Version](./get_version/)() const | Liefert die Version des SwissQR-Rechnungsstandards. |
| [GetHashCode](./gethashcode/)() const override | Liefert den Hashcode für diese Instanz. |
| [set_Account](./set_account/)(System::String) | Setzt die Kontonummer des Gläubigers. |
| [set_AlternativeSchemes](./set_alternativeschemes/)(System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<AlternativeScheme\>>>) | Liefert oder setzt die alternativen Zahlungsschemata. |
| [set_Amount](./set_amount/)(System::Decimal) | Setzt den Zahlungsbetrag. |
| [set_BillInformation](./set_billinformation/)(System::String) | Setzt die zusätzlichen strukturierten Rechnungsinformationen. |
| [set_Creditor](./set_creditor/)(System::SharedPtr\<Address\>) | Setzt die Gläubigeradresse. |
| [set_Currency](./set_currency/)(System::String) | Setzt die Zahlungswährung. |
| [set_Debtor](./set_debtor/)(System::SharedPtr\<Address\>) | Setzt die Schuldneradresse. |
| [set_Reference](./set_reference/)(System::String) | Setzt die Zahlungsreferenz des Gläubigers. |
| [set_UnstructuredMessage](./set_unstructuredmessage/)(System::String) | Legt die zusätzliche unstrukturierte Nachricht fest. |
| [set_Version](./set_version/)(SwissQRBill::QrBillStandardVersion) | Legt die Version des SwissQR-Rechnungsstandards fest. |
## Typedefs

| Typedef | Beschreibung |
| --- | --- |
| [QrBillStandardVersion](./qrbillstandardversion/) | Version des SwissQR-Rechnungsstandards |
## Siehe auch

* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
