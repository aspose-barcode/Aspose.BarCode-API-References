---
title: "Aspose::BarCode::ComplexBarcode::SwissQRBill classe"
linktitle: "SwissQRBill"
second_title: "Aspose.BarCode for C++ Riferimento API"
description: "Aspose::BarCode::ComplexBarcode::SwissQRBill classe. Dati della fattura SwissQR in C++."
type: docs
weight: 2700
url: /it/cpp/aspose.barcode.complexbarcode/swissqrbill/
---
## SwissQRBill class


Dati della fattura SwissQR

```cpp
class SwissQRBill : public System::IEquatable<System::SharedPtr<SwissQRBill>>
```

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [CreateAndSetCreditorReference](./createandsetcreditorreference/)(System::String) | Crea e imposta un riferimento creditore ISO11649 da una stringa grezza prefissando la String con "RF" e il checksum modulo 97. |
| [Equals](./equals/)(System::SharedPtr\<System::Object\>) override | Determina se l'oggetto specificato è uguale all'oggetto corrente. |
| [Equals](./equals/)(System::SharedPtr\<SwissQRBill\>) override | Determina se la fattura specificata è uguale alla fattura corrente. |
| [get_Account](./get_account/)() const | Ottiene il numero di conto del creditore. |
| [get_AlternativeSchemes](./get_alternativeschemes/)() const | Ottiene o imposta gli schemi di pagamento alternativi. |
| [get_Amount](./get_amount/)() const | Ottiene l'importo del pagamento. |
| [get_BillInformation](./get_billinformation/)() const | Ottiene le informazioni aggiuntive strutturate della fattura. |
| [get_Creditor](./get_creditor/)() const | Ottiene l'indirizzo del creditore. |
| [get_Currency](./get_currency/)() const | Ottiene la valuta del pagamento. |
| [get_Debtor](./get_debtor/)() const | Ottiene l'indirizzo del debitore. |
| [get_Reference](./get_reference/)() const | Ottiene il riferimento di pagamento del creditore. |
| [get_UnstructuredMessage](./get_unstructuredmessage/)() const | Ottiene il messaggio aggiuntivo non strutturato. |
| [get_Version](./get_version/)() const | Ottiene la versione dello standard della fattura SwissQR. |
| [GetHashCode](./gethashcode/)() const override | Ottiene il codice hash per questa istanza. |
| [set_Account](./set_account/)(System::String) | Imposta il numero di conto del creditore. |
| [set_AlternativeSchemes](./set_alternativeschemes/)(System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<AlternativeScheme\>>>) | Ottiene o imposta gli schemi di pagamento alternativi. |
| [set_Amount](./set_amount/)(System::Decimal) | Imposta l'importo del pagamento. |
| [set_BillInformation](./set_billinformation/)(System::String) | Imposta le informazioni aggiuntive strutturate della fattura. |
| [set_Creditor](./set_creditor/)(System::SharedPtr\<Address\>) | Imposta l'indirizzo del creditore. |
| [set_Currency](./set_currency/)(System::String) | Imposta la valuta del pagamento. |
| [set_Debtor](./set_debtor/)(System::SharedPtr\<Address\>) | Imposta l'indirizzo del debitore. |
| [set_Reference](./set_reference/)(System::String) | Imposta il riferimento di pagamento del creditore. |
| [set_UnstructuredMessage](./set_unstructuredmessage/)(System::String) | Imposta il messaggio non strutturato aggiuntivo. |
| [set_Version](./set_version/)(SwissQRBill::QrBillStandardVersion) | Imposta la versione dello standard di fatturazione SwissQR. |
## Typedefs

| Typedef | Descrizione |
| --- | --- |
| [QrBillStandardVersion](./qrbillstandardversion/) | Versione dello standard di fatturazione SwissQR |
## Vedi anche

* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
