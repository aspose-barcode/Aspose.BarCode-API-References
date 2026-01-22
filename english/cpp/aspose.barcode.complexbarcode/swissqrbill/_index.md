---
title: Aspose::BarCode::ComplexBarcode::SwissQRBill class
linktitle: SwissQRBill
second_title: Aspose.BarCode for C++ API Reference
description: 'Aspose::BarCode::ComplexBarcode::SwissQRBill class. SwissQR bill data in C++.'
type: docs
weight: 2500
url: /cpp/aspose.barcode.complexbarcode/swissqrbill/
---
## SwissQRBill class


SwissQR bill data

```cpp
class SwissQRBill : public System::IEquatable<System::SharedPtr<Aspose::BarCode::ComplexBarcode::SwissQRBill>>
```

## Methods

| Method | Description |
| --- | --- |
| [CreateAndSetCreditorReference](./createandsetcreditorreference/)(System::String) | Creates and sets a ISO11649 creditor reference from a raw string by prefixing the String with "RF" and the modulo 97 checksum. |
| [Equals](./equals/)(System::SharedPtr\<System::Object\>) override | Determines whether the specified object is equal to the current object. |
| [Equals](./equals/)(System::SharedPtr\<SwissQRBill\>) override | Determines whether the specified bill is equal to the current bill. |
| [get_Account](./get_account/)() const | Gets the creditor's account number. |
| [get_AlternativeSchemes](./get_alternativeschemes/)() const | Gets ors sets the alternative payment schemes. |
| [get_Amount](./get_amount/)() const | Gets the payment amount. |
| [get_BillInformation](./get_billinformation/)() const | Gets the additional structured bill information. |
| [get_Creditor](./get_creditor/)() const | Gets the creditor address. |
| [get_Currency](./get_currency/)() const | Gets the payment currency. |
| [get_Debtor](./get_debtor/)() const | Gets the debtor address. |
| [get_Reference](./get_reference/)() const | Gets the creditor payment reference. |
| [get_UnstructuredMessage](./get_unstructuredmessage/)() const | Gets the additional unstructured message. |
| [get_Version](./get_version/)() const | Gets the version of the SwissQR bill standard. |
| [GetHashCode](./gethashcode/)() const override | Gets the hash code for this instance. |
| [set_Account](./set_account/)(System::String) | Sets the creditor's account number. |
| [set_AlternativeSchemes](./set_alternativeschemes/)(System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<AlternativeScheme\>>>) | Gets ors sets the alternative payment schemes. |
| [set_Amount](./set_amount/)(System::Decimal) | Sets the payment amount. |
| [set_BillInformation](./set_billinformation/)(System::String) | Sets the additional structured bill information. |
| [set_Creditor](./set_creditor/)(System::SharedPtr\<Address\>) | Sets the creditor address. |
| [set_Currency](./set_currency/)(System::String) | Sets the payment currency. |
| [set_Debtor](./set_debtor/)(System::SharedPtr\<Address\>) | Sets the debtor address. |
| [set_Reference](./set_reference/)(System::String) | Sets the creditor payment reference. |
| [set_UnstructuredMessage](./set_unstructuredmessage/)(System::String) | Sets the additional unstructured message. |
| [set_Version](./set_version/)(SwissQRBill::QrBillStandardVersion) | Sets the version of the SwissQR bill standard. |
## Typedefs

| Typedef | Description |
| --- | --- |
| [QrBillStandardVersion](./qrbillstandardversion/) | SwissQR bill standard version |
## See Also

* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
