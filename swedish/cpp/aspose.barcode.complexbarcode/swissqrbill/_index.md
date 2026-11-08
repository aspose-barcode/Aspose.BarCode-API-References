---
title: "Aspose::BarCode::ComplexBarcode::SwissQRBill class"
linktitle: "SwissQRBill"
second_title: "Aspose.BarCode for C++ API-referens"
description: "Aspose::BarCode::ComplexBarcode::SwissQRBill klass. SwissQR-fakturadata i C++."
type: docs
weight: 2700
url: /sv/cpp/aspose.barcode.complexbarcode/swissqrbill/
---
## SwissQRBill class


SwissQR-fakturadata

```cpp
class SwissQRBill : public System::IEquatable<System::SharedPtr<SwissQRBill>>
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [CreateAndSetCreditorReference](./createandsetcreditorreference/)(System::String) | Skapar och sätter en ISO11649‑kreditorreferens från en rå sträng genom att prefixa strängen med "RF" och modulo‑97‑kontrollen. |
| [Equals](./equals/)(System::SharedPtr\<System::Object\>) override | Bestämmer om det angivna objektet är lika med det aktuella objektet. |
| [Equals](./equals/)(System::SharedPtr\<SwissQRBill\>) override | Bestämmer om den angivna fakturan är lika med den aktuella fakturan. |
| [get_Account](./get_account/)() const | Hämtar kreditorns kontonummer. |
| [get_AlternativeSchemes](./get_alternativeschemes/)() const | Hämtar eller sätter de alternativa betalningsschemana. |
| [get_Amount](./get_amount/)() const | Hämtar betalningsbeloppet. |
| [get_BillInformation](./get_billinformation/)() const | Hämtar den ytterligare strukturerade fakturainformationen. |
| [get_Creditor](./get_creditor/)() const | Hämtar kreditorns adress. |
| [get_Currency](./get_currency/)() const | Hämtar betalningsvalutan. |
| [get_Debtor](./get_debtor/)() const | Hämtar gäldenärens adress. |
| [get_Reference](./get_reference/)() const | Hämtar kreditorns betalningsreferens. |
| [get_UnstructuredMessage](./get_unstructuredmessage/)() const | Hämtar det ytterligare ostrukturerade meddelandet. |
| [get_Version](./get_version/)() const | Hämtar versionen av SwissQR‑fakturastandarden. |
| [GetHashCode](./gethashcode/)() const override | Hämtar hashkoden för denna instans. |
| [set_Account](./set_account/)(System::String) | Sätter kreditorns kontonummer. |
| [set_AlternativeSchemes](./set_alternativeschemes/)(System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<AlternativeScheme\>>>) | Hämtar eller sätter de alternativa betalningsschemana. |
| [set_Amount](./set_amount/)(System::Decimal) | Sätter betalningsbeloppet. |
| [set_BillInformation](./set_billinformation/)(System::String) | Sätter den ytterligare strukturerade fakturainformationen. |
| [set_Creditor](./set_creditor/)(System::SharedPtr\<Address\>) | Sätter kreditorns adress. |
| [set_Currency](./set_currency/)(System::String) | Sätter betalningsvalutan. |
| [set_Debtor](./set_debtor/)(System::SharedPtr\<Address\>) | Sätter gäldenärens adress. |
| [set_Reference](./set_reference/)(System::String) | Sätter kreditorns betalningsreferens. |
| [set_UnstructuredMessage](./set_unstructuredmessage/)(System::String) | Ställer in det ytterligare ostrukturerade meddelandet. |
| [set_Version](./set_version/)(SwissQRBill::QrBillStandardVersion) | Ställer in versionen av SwissQR-fakturastandarden. |
## Typedefs

| Typedef | Beskrivning |
| --- | --- |
| [QrBillStandardVersion](./qrbillstandardversion/) | SwissQR-fakturastandard version |
## Se även

* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
