---
title: Address
second_title: Aspose.BarCode untuk .NET API Referensi
description: Alamat kreditur atau debitur.
type: docs
weight: 320
url: /id/net/aspose.barcode.complexbarcode/address/
---
## Address class

Alamat kreditur atau debitur.

Anda dapat mengatur jalan, nomor rumah, kode pos dan kota (tipealamat terstruktur ) atau alamat baris 1 dan 2 (ketikmenggabungkan elemen alamat ). Jenisnya secara otomatis set setelah salah satu bidang ini disetel. Sebelum menyetel bidang, jenis alamatnya adalahyg tak dpt ditentukan . Jika bidang dari kedua jenis disetel, jenis alamat menjadibertentangan . Nama dan kode negara harus selalu disetel kecuali semua kolom kosong.

```csharp
public sealed class Address : IEquatable<Address>
```

## Konstruktor

| Nama | Keterangan |
| --- | --- |
| [Address](address/)() | Membuat instance dari Address |

## Properti

| Nama | Keterangan |
| --- | --- |
| [AddressLine1](../../aspose.barcode.complexbarcode/address/addressline1/) { get; set; } | Mendapat atau menyetel baris alamat 1. |
| [AddressLine2](../../aspose.barcode.complexbarcode/address/addressline2/) { get; set; } | Mendapat atau menyetel baris alamat 2. |
| [CountryCode](../../aspose.barcode.complexbarcode/address/countrycode/) { get; set; } | Mendapat atau menyetel kode negara ISO dua huruf. |
| [HouseNo](../../aspose.barcode.complexbarcode/address/houseno/) { get; set; } | Mendapat atau menetapkan nomor rumah. |
| [Name](../../aspose.barcode.complexbarcode/address/name/) { get; set; } | Mendapat atau menetapkan nama, baik nama depan dan belakang dari orang perseorangan atau nama nama perusahaan dari badan hukum. |
| [PostalCode](../../aspose.barcode.complexbarcode/address/postalcode/) { get; set; } | Mendapat atau menyetel kode pos. |
| [Street](../../aspose.barcode.complexbarcode/address/street/) { get; set; } | Mendapat atau menyetel jalan. |
| [Town](../../aspose.barcode.complexbarcode/address/town/) { get; set; } | Mendapat atau mengatur kota atau kota. |
| [Type](../../aspose.barcode.complexbarcode/address/type/) { get; } | Mendapat jenis alamat. |

## Metode

| Nama | Keterangan |
| --- | --- |
| [Clear](../../aspose.barcode.complexbarcode/address/clear/)() | Menghapus semua bidang dan menyetel jenisnyaUndetermined . |
| [Equals](../../aspose.barcode.complexbarcode/address/equals/#equals)(Address) | Menentukan apakah alamat yang ditentukan sama dengan alamat saat ini. |
| override [Equals](../../aspose.barcode.complexbarcode/address/equals/#equals_1)(object) | Menentukan apakah objek yang ditentukan sama dengan objek saat ini. |
| override [GetHashCode](../../aspose.barcode.complexbarcode/address/gethashcode/)() | Mendapatkan kode hash untuk instance ini. |

### Lihat juga

* ruang nama [Aspose.BarCode.ComplexBarcode](../../aspose.barcode.complexbarcode/)
* perakitan [Aspose.BarCode](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->
