---
title: "Aspose::BarCode::ComplexBarcode::SwissQRBill class"
linktitle: "SwissQRBill"
second_title: "Aspose.BarCode for C++ API Referansı"
description: "Aspose::BarCode::ComplexBarcode::SwissQRBill sınıfı. C++'de SwissQR fatura verileri."
type: docs
weight: 2700
url: /tr/cpp/aspose.barcode.complexbarcode/swissqrbill/
---
## SwissQRBill class


SwissQR fatura verileri

```cpp
class SwissQRBill : public System::IEquatable<System::SharedPtr<SwissQRBill>>
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [CreateAndSetCreditorReference](./createandsetcreditorreference/)(System::String) | Ham bir dizeden ISO11649 alacaklı referansını, dizeyi "RF" ile ön ekleyerek ve 97 modülü kontrol toplamını ekleyerek oluşturur ve ayarlar. |
| [Equals](./equals/)(System::SharedPtr\<System::Object\>) override | Belirtilen nesnenin mevcut nesneye eşit olup olmadığını belirler. |
| [Equals](./equals/)(System::SharedPtr\<SwissQRBill\>) override | Belirtilen faturanın mevcut fatura ile eşit olup olmadığını belirler. |
| [get_Account](./get_account/)() const | Alacaklının hesap numarasını alır. |
| [get_AlternativeSchemes](./get_alternativeschemes/)() const | Alır veya alternatif ödeme şemalarını ayarlar. |
| [get_Amount](./get_amount/)() const | Ödeme tutarını alır. |
| [get_BillInformation](./get_billinformation/)() const | Ek yapılandırılmış fatura bilgilerini alır. |
| [get_Creditor](./get_creditor/)() const | Alacaklı adresini alır. |
| [get_Currency](./get_currency/)() const | Ödeme para birimini alır. |
| [get_Debtor](./get_debtor/)() const | Borçlu adresini alır. |
| [get_Reference](./get_reference/)() const | Alacaklı ödeme referansını alır. |
| [get_UnstructuredMessage](./get_unstructuredmessage/)() const | Ek yapılandırılmamış mesajı alır. |
| [get_Version](./get_version/)() const | SwissQR fatura standardının sürümünü alır. |
| [GetHashCode](./gethashcode/)() const override | Bu örnek için karma kodunu alır. |
| [set_Account](./set_account/)(System::String) | Alacaklının hesap numarasını ayarlar. |
| [set_AlternativeSchemes](./set_alternativeschemes/)(System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<AlternativeScheme\>>>) | Alır veya alternatif ödeme şemalarını ayarlar. |
| [set_Amount](./set_amount/)(System::Decimal) | Ödeme tutarını ayarlar. |
| [set_BillInformation](./set_billinformation/)(System::String) | Ek yapılandırılmış fatura bilgilerini ayarlar. |
| [set_Creditor](./set_creditor/)(System::SharedPtr\<Address\>) | Alacaklı adresini ayarlar. |
| [set_Currency](./set_currency/)(System::String) | Ödeme para birimini ayarlar. |
| [set_Debtor](./set_debtor/)(System::SharedPtr\<Address\>) | Borçlu adresini ayarlar. |
| [set_Reference](./set_reference/)(System::String) | Alacaklı ödeme referansını ayarlar. |
| [set_UnstructuredMessage](./set_unstructuredmessage/)(System::String) | Ek yapılandırılmamış mesajı ayarlar. |
| [set_Version](./set_version/)(SwissQRBill::QrBillStandardVersion) | SwissQR fatura standardının sürümünü ayarlar. |
## Typedefs

| Typedef | Açıklama |
| --- | --- |
| [QrBillStandardVersion](./qrbillstandardversion/) | SwissQR fatura standardı sürümü |
## Ayrıca Bakınız

* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
