---
title: "Aspose::BarCode::ComplexBarcode::SwissQRBill kelas"
linktitle: "SwissQRBill"
second_title: "Aspose.BarCode for C++ Referensi API"
description: "Aspose::BarCode::ComplexBarcode::SwissQRBill kelas. Data tagihan SwissQR dalam C++."
type: docs
weight: 2700
url: /id/cpp/aspose.barcode.complexbarcode/swissqrbill/
---
## SwissQRBill class


Data tagihan SwissQR

```cpp
class SwissQRBill : public System::IEquatable<System::SharedPtr<SwissQRBill>>
```

## Metode

| Metode | Deskripsi |
| --- | --- |
| [CreateAndSetCreditorReference](./createandsetcreditorreference/)(System::String) | Membuat dan mengatur referensi kreditur ISO11649 dari string mentah dengan menambahkan awalan "RF" pada String dan checksum modulo 97. |
| [Equals](./equals/)(System::SharedPtr\<System::Object\>) override | Menentukan apakah objek yang ditentukan sama dengan objek saat ini. |
| [Equals](./equals/)(System::SharedPtr\<SwissQRBill\>) override | Menentukan apakah tagihan yang ditentukan sama dengan tagihan saat ini. |
| [get_Account](./get_account/)() const | Mendapatkan nomor akun kreditur. |
| [get_AlternativeSchemes](./get_alternativeschemes/)() const | Mendapatkan atau mengatur skema pembayaran alternatif. |
| [get_Amount](./get_amount/)() const | Mendapatkan jumlah pembayaran. |
| [get_BillInformation](./get_billinformation/)() const | Mendapatkan informasi tagihan terstruktur tambahan. |
| [get_Creditor](./get_creditor/)() const | Mendapatkan alamat kreditur. |
| [get_Currency](./get_currency/)() const | Mendapatkan mata uang pembayaran. |
| [get_Debtor](./get_debtor/)() const | Mendapatkan alamat debitur. |
| [get_Reference](./get_reference/)() const | Mendapatkan referensi pembayaran kreditur. |
| [get_UnstructuredMessage](./get_unstructuredmessage/)() const | Mendapatkan pesan tidak terstruktur tambahan. |
| [get_Version](./get_version/)() const | Mendapatkan versi standar tagihan SwissQR. |
| [GetHashCode](./gethashcode/)() const override | Mendapatkan kode hash untuk instance ini. |
| [set_Account](./set_account/)(System::String) | Mengatur nomor akun kreditur. |
| [set_AlternativeSchemes](./set_alternativeschemes/)(System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<AlternativeScheme\>>>) | Mendapatkan atau mengatur skema pembayaran alternatif. |
| [set_Amount](./set_amount/)(System::Decimal) | Mengatur jumlah pembayaran. |
| [set_BillInformation](./set_billinformation/)(System::String) | Mengatur informasi tagihan terstruktur tambahan. |
| [set_Creditor](./set_creditor/)(System::SharedPtr\<Address\>) | Mengatur alamat kreditur. |
| [set_Currency](./set_currency/)(System::String) | Mengatur mata uang pembayaran. |
| [set_Debtor](./set_debtor/)(System::SharedPtr\<Address\>) | Mengatur alamat debitur. |
| [set_Reference](./set_reference/)(System::String) | Mengatur referensi pembayaran kreditur. |
| [set_UnstructuredMessage](./set_unstructuredmessage/)(System::String) | Mengatur pesan tidak terstruktur tambahan. |
| [set_Version](./set_version/)(SwissQRBill::QrBillStandardVersion) | Mengatur versi standar tagihan SwissQR. |
## Typedefs

| Typedef | Deskripsi |
| --- | --- |
| [QrBillStandardVersion](./qrbillstandardversion/) | Versi standar tagihan SwissQR |
## Lihat Juga

* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
