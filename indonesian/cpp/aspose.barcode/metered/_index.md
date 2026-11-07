---
title: "Aspose::BarCode::Metered kelas"
linktitle: "Metered"
second_title: "Aspose.BarCode for C++ Referensi API"
description: "Aspose::BarCode::Metered kelas. Menyediakan metode untuk mengatur kunci metered dalam C++."
type: docs
weight: 500
url: /id/cpp/aspose.barcode/metered/
---
## Metered class


Menyediakan metode untuk mengatur kunci bermeter.

```cpp
class Metered : public System::Object
```

## Metode

| Metode | Deskripsi |
| --- | --- |
| static [GetConsumptionCredit](./getconsumptioncredit/)() | Mendapatkan kredit konsumsi |
| static [GetConsumptionQuantity](./getconsumptionquantity/)() | Mendapatkan ukuran file konsumsi |
| [GetProductName](./getproductname/)() | Mendapatkan nama produk berlisensi |
| static [IsMeteredLicensed](./ismeteredlicensed/)() | Periksa apakah metered berlisensi |
| [Metered](./metered/)() | Menginisialisasi instance baru dari kelas ini. |
| [SetMeteredKey](./setmeteredkey/)(System::String, System::String) | Mengatur kunci publik dan privat metered. Jika Anda membeli lisensi metered, saat memulai aplikasi, API ini harus dipanggil, biasanya, ini sudah cukup. Namun, jika selalu gagal mengunggah data konsumsi dan melebihi 24 jam, lisensi akan diatur ke status evaluasi, untuk menghindari kasus tersebut, Anda harus secara teratur memeriksa status lisensi, jika statusnya evaluasi, panggil API ini lagi. |
## Catatan


Dalam contoh ini, percobaan akan dilakukan untuk mengatur kunci publik dan privat metered

<ms>
```cpp
[C#]
@verbatim
Metered matered = new Metered();
matered.SetMeteredKey("PublicKey", "PrivateKey");


[Visual Basic]

Dim matered As Metered = New Metered
matered.SetMeteredKey("PublicKey", "PrivateKey")
@endverbatim
```
</ms>

<java> file jar komponen:
```cpp
Metered matered = new Metered();
matered.setMeteredKey("PublicKey", "PrivateKey");
```
</java>
## Lihat Juga

* Namespace [Aspose::BarCode](../)
* Library [Aspose.BarCode for C++](../../)
