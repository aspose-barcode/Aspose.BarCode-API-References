---
title: "Aspose::BarCode::ComplexBarcode::MailmarkCodetext kelas"
linktitle: "MailmarkCodetext"
second_title: "Aspose.BarCode for C++ Referensi API"
description: "Aspose::BarCode::ComplexBarcode::MailmarkCodetext kelas. Kelas untuk mengenkode dan mendekode teks yang tertanam dalam kode Royal Mailmark 4-state dalam C++."
type: docs
weight: 1500
url: /id/cpp/aspose.barcode.complexbarcode/mailmarkcodetext/
---
## MailmarkCodetext class


Kelas untuk mengkodekan dan mendekode teks yang tertanam dalam kode Royal Mailmark 4-state.

```cpp
class MailmarkCodetext : public Aspose::BarCode::ComplexBarcode::IComplexCodetext
```

## Metode

| Metode | Deskripsi |
| --- | --- |
| [get_Class](./get_class/)() const | "0" - Null atau Tes "1" - 1C (Retail) "2" - 2C (Retail) "3" - 3C (Retail) "4" - Premium (RetailPublishing Mail) (untuk penggunaan potensial di masa depan) "5" - Deferred (Retail) "6" - Air (Retail) (untuk penggunaan potensial di masa depan) "7" - Surface (Retail) (untuk penggunaan potensial di masa depan) "8" - Premium (Network Access) "9" - Standard (Network Access) |
| [get_DestinationPostCodePlusDPS](./get_destinationpostcodeplusdps/)() const | PC dan DP harus mematuhi format PAF. String sembilan karakter yang menunjukkan internasional "XY11     " (catat 5 spasi di akhir) atau pola karakter yang menunjukkan kode penyortiran domestik. Kode penyortiran domestik terdiri dari kode pos keluar, kode pos masuk, dan Sufiks Titik Pengiriman. |
| [get_Format](./get_format/)() const | "0" – Null atau Tes "1" – Surat "2" – Surat Besar |
| [get_ItemID](./get_itemid/)() const | Nilai maksimum adalah 99999999. |
| [get_SupplychainID](./get_supplychainid/)() const | Nilai maksimum adalah 99 untuk Barcode C dan 999999 untuk Barcode L. |
| [get_VersionID](./get_versionid/)() const | Saat ini "1" – Untuk barcode Mailmark (0 dan 2 hingga 9 serta A sampai Z disiapkan untuk penggunaan di masa depan) |
| [GetBarcodeType](./getbarcodetype/)() override | Mendapatkan tipe barcode. |
| [GetConstructedCodetext](./getconstructedcodetext/)() override | Bangun kode teks dari data Mailmark. |
| [InitFromString](./initfromstring/)(System::String) override | Menginisialisasi data Mailmark dari kode teks yang dibangun. |
| [MailmarkCodetext](./mailmarkcodetext/)() | Menginisialisasi sebuah instance baru dari kelas [MailmarkCodetext](./). |
| [set_Class](./set_class/)(System::String) | "0" - Null atau Tes "1" - 1C (Retail) "2" - 2C (Retail) "3" - 3C (Retail) "4" - Premium (RetailPublishing Mail) (untuk penggunaan potensial di masa depan) "5" - Deferred (Retail) "6" - Air (Retail) (untuk penggunaan potensial di masa depan) "7" - Surface (Retail) (untuk penggunaan potensial di masa depan) "8" - Premium (Network Access) "9" - Standard (Network Access) |
| [set_DestinationPostCodePlusDPS](./set_destinationpostcodeplusdps/)(System::String) | PC dan DP harus mematuhi format PAF. String sembilan karakter yang menunjukkan internasional "XY11     " (catat 5 spasi di akhir) atau pola karakter yang menunjukkan kode penyortiran domestik. Kode penyortiran domestik terdiri dari kode pos keluar, kode pos masuk, dan Sufiks Titik Pengiriman. |
| [set_Format](./set_format/)(int32_t) | "0" – Null atau Tes "1" – Surat "2" – Surat Besar |
| [set_ItemID](./set_itemid/)(int32_t) | Nilai maksimum adalah 99999999. |
| [set_SupplychainID](./set_supplychainid/)(int32_t) | Nilai maksimum adalah 99 untuk Barcode C dan 999999 untuk Barcode L. |
| [set_VersionID](./set_versionid/)(int32_t) | Saat ini "1" – Untuk barcode Mailmark (0 dan 2 hingga 9 serta A sampai Z disiapkan untuk penggunaan di masa depan) |
## Lihat Juga

* Class [IComplexCodetext](../icomplexcodetext/)
* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
