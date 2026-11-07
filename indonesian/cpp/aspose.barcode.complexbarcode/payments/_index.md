---
title: "Kelas Aspose::BarCode::ComplexBarcode::Payments"
linktitle: "Payments"
second_title: "Aspose.BarCode for C++ Referensi API"
description: "Kelas Aspose::BarCode::ComplexBarcode::Payments. Validasi bidang yang terkait dengan standar Pembayaran Swiss di C++."
type: docs
weight: 2400
url: /id/cpp/aspose.barcode.complexbarcode/payments/
---
## Payments class


Validasi bidang yang terkait dengan standar Pembayaran Swiss.

```cpp
class Payments
```

## Metode

| Metode | Deskripsi |
| --- | --- |
| static [CleanValue](./cleanvalue/)(System::String, Payments::CleaningResult\&) | Membersihkan nilai string agar dapat digunakan untuk Standar Pembayaran Swiss 2018. |
| static [CreateIso11649Reference](./createiso11649reference/)(System::String) | Membuat referensi kreditor ISO11649 dari string mentah dengan menambahkan awalan "RF" dan checksum modulo 97 pada string. |
| static [FormatIban](./formatiban/)(System::String) | Memformat IBAN atau referensi kreditor dengan menyisipkan spasi. |
| static [FormatQrReferenceNumber](./formatqrreferencenumber/)(System::String) | Memformat nomor referensi QR dengan menyisipkan spasi. |
| static [IsAlphaNumeric](./isalphanumeric/)(System::String) |  |
| static [IsValidIban](./isvalidiban/)(System::String) | Memvalidasi apakah string merupakan nomor IBAN yang valid. |
| static [IsValidIso11649Reference](./isvalidiso11649reference/)(System::String) | Memvalidasi apakah string merupakan nomor referensi ISO 11649 yang valid. |
| static [IsValidQrReference](./isvalidqrreference/)(System::String) | Memvalidasi apakah string merupakan referensi QR yang valid. |
| [Payments](./payments/)() |  |
## Lihat Juga

* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
