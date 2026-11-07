---
title: "Aspose::BarCode::ComplexBarcode::SwissQRBill class"
linktitle: "SwissQRBill"
second_title: "Aspose.BarCode for C++ API-referentie"
description: "Aspose::BarCode::ComplexBarcode::SwissQRBill class. SwissQR-factuurgegevens in C++."
type: docs
weight: 2700
url: /nl/cpp/aspose.barcode.complexbarcode/swissqrbill/
---
## SwissQRBill class


SwissQR-factuurgegevens

```cpp
class SwissQRBill : public System::IEquatable<System::SharedPtr<SwissQRBill>>
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| [CreateAndSetCreditorReference](./createandsetcreditorreference/)(System::String) | Maakt en stelt een ISO11649‑crediteurreferentie in vanuit een ruwe tekenreeks door de tekenreeks te prefixen met "RF" en de modulo‑97‑controlesom. |
| [Equals](./equals/)(System::SharedPtr\<System::Object\>) override | Bepaalt of het opgegeven object gelijk is aan het huidige object. |
| [Equals](./equals/)(System::SharedPtr\<SwissQRBill\>) override | Bepaalt of de opgegeven factuur gelijk is aan de huidige factuur. |
| [get_Account](./get_account/)() const | Haalt het rekeningnummer van de crediteur op. |
| [get_AlternativeSchemes](./get_alternativeschemes/)() const | Haalt de alternatieve betaalregelingen op of stelt ze in. |
| [get_Amount](./get_amount/)() const | Haalt het betalingsbedrag op. |
| [get_BillInformation](./get_billinformation/)() const | Haalt de aanvullende gestructureerde factuurinformatie op. |
| [get_Creditor](./get_creditor/)() const | Haalt het adres van de crediteur op. |
| [get_Currency](./get_currency/)() const | Haalt de betaalvaluta op. |
| [get_Debtor](./get_debtor/)() const | Haalt het adres van de schuldenaar op. |
| [get_Reference](./get_reference/)() const | Haalt de betalingsreferentie van de crediteur op. |
| [get_UnstructuredMessage](./get_unstructuredmessage/)() const | Haalt het aanvullende ongestructureerde bericht op. |
| [get_Version](./get_version/)() const | Haalt de versie van de SwissQR‑factuurstandaard op. |
| [GetHashCode](./gethashcode/)() const override | Haalt de hashcode op voor deze instantie. |
| [set_Account](./set_account/)(System::String) | Stelt het rekeningnummer van de crediteur in. |
| [set_AlternativeSchemes](./set_alternativeschemes/)(System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<AlternativeScheme\>>>) | Haalt de alternatieve betaalregelingen op of stelt ze in. |
| [set_Amount](./set_amount/)(System::Decimal) | Stelt het betalingsbedrag in. |
| [set_BillInformation](./set_billinformation/)(System::String) | Stelt de aanvullende gestructureerde factuurinformatie in. |
| [set_Creditor](./set_creditor/)(System::SharedPtr\<Address\>) | Stelt het adres van de crediteur in. |
| [set_Currency](./set_currency/)(System::String) | Stelt de betaalvaluta in. |
| [set_Debtor](./set_debtor/)(System::SharedPtr\<Address\>) | Stelt het adres van de schuldenaar in. |
| [set_Reference](./set_reference/)(System::String) | Stelt de betalingsreferentie van de crediteur in. |
| [set_UnstructuredMessage](./set_unstructuredmessage/)(System::String) | Stelt het extra ongestructureerde bericht in. |
| [set_Version](./set_version/)(SwissQRBill::QrBillStandardVersion) | Stelt de versie van de SwissQR-factuurstandaard in. |
## Typedefs

| Typedef | Beschrijving |
| --- | --- |
| [QrBillStandardVersion](./qrbillstandardversion/) | SwissQR-factuurstandaard versie |
## Zie ook

* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
