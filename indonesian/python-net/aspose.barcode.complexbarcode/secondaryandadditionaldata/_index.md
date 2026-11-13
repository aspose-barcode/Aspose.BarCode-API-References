---
title: "SecondaryAndAdditionalData"
second_title: "Aspose.BarCode for Python via .NET Referensi API"
description: 
type: docs
url: /id/python-net/aspose.barcode.complexbarcode/secondaryandadditionaldata/
---

## SecondaryAndAdditionalData class

Kelas untuk menyimpan data sekunder dan tambahan HIBC LIC.

Tipe SecondaryAndAdditionalData menampilkan anggota-anggota berikut:
## Konstruktor
| Nama | Deskripsi |
| :- | :- |
| SecondaryAndAdditionalData() | Menginisialisasi sebuah instance baru dari kelas SecondaryAndAdditionalData |
## Properti
| Nama | Deskripsi |
| :- | :- |
| expiry_date_format | Mengidentifikasi format tanggal kedaluwarsa. |
| expiry_date | Mengidentifikasi tanggal kedaluwarsa. Akan digunakan jika ExpiryDateFormat tidak diatur ke None. |
| lot_number | Mengidentifikasi nomor lot atau batch. Nomor lot/batch harus berupa string alfanumerik dengan panjang hingga 18 simbol. . |
| serial_number | Mengidentifikasi nomor seri. Nomor seri harus berupa string alfanumerik dengan panjang hingga 18 simbol. |
| date_of_manufacture | Mengidentifikasi tanggal pembuatan.<br/>            Tanggal pembuatan dapat diatur ke DateTime.MinValue untuk tidak menggunakan bidang ini.<br/>            Nilai default: DateTime.MinValue |
| quantity | Mengidentifikasi kuantitas, harus berupa nilai integer dari 0 hingga 500. <br/>            Kuantitas dapat diatur ke -1 untuk tidak menggunakan bidang ini.<br/>            Nilai default: -1 |
## Metode
| Nama | Deskripsi |
| :- | :- |
| parse_from_string(secondary_data_codetext) | Membuat instance data sekunder dan tambahan pelengkap dari format string sesuai spesifikasi HIBC LIC. |

### Lihat Juga

* namespace [aspose.barcode.complexbarcode](/barcode/python-net/aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](/barcode/python-net/)

