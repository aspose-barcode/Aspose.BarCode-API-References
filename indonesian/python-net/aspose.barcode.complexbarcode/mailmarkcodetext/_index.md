---
title: "MailmarkCodetext"
second_title: "Aspose.BarCode for Python via .NET Referensi API"
description: 
type: docs
url: /id/python-net/aspose.barcode.complexbarcode/mailmarkcodetext/
---

## MailmarkCodetext class

Kelas untuk menyandikan dan menguraikan teks yang tertanam dalam kode Royal Mailmark 4-state.

Tipe MailmarkCodetext menampilkan anggota-anggota berikut:
## Konstruktor
| Nama | Deskripsi |
| :- | :- |
| MailmarkCodetext() | Menginisialisasi instance baru dari kelas MailmarkCodetext |
## Properti
| Nama | Deskripsi |
| :- | :- |
| format | "0" – Null atau Tes<br/>            "1" – Surat<br/>            "2" – Surat Besar |
| version_id | Saat ini "1" – Untuk kode batang Mailmark (0 dan 2 hingga 9 serta A sampai Z disiapkan untuk penggunaan di masa depan) |
| klass | "0" - Null atau Tes<br/>            "1" - 1C (Ritel)<br/>            "2" - 2C (Ritel)<br/>            "3" - 3C (Ritel)<br/>            "4" - Premium (RetailPublishing Mail) (untuk penggunaan potensial di masa depan)<br/>            "5" - Ditunda (Ritel)<br/>            "6" - Air (Ritel) (untuk penggunaan potensial di masa depan)<br/>            "7" - Surface (Ritel) (untuk penggunaan potensial di masa depan)<br/>            "8" - Premium (Akses Jaringan)<br/>            "9" - Standar (Akses Jaringan) |
| supply_chain_id | Nilai maksimum adalah 99 untuk Barcode C dan 999999 untuk Barcode L. |
| item_id | Nilai maksimum adalah 99999999. |
| destination_post_code_and_dps | PC dan DP harus mematuhi format PAF.<br/>            String sembilan karakter yang menunjukkan internasional "XY11     " (catat 5 spasi di akhir) atau pola<br/>            karakter yang menunjukkan kode penyortiran domestik.<br/>            Kode penyortiran domestik terdiri dari kode pos keluar, kode pos masuk, dan Sufiks Titik Pengiriman. |
## Metode
| Nama | Deskripsi |
| :- | :- |
| get_constructed_codetext() | Bangun teks kode dari data Mailmark. |
| init_from_string(constructed_codetext) | Menginisialisasi data Mailmark dari teks kode yang dibangun. |
| get_barcode_type() | Mendapatkan tipe barcode. |

### Lihat Juga

* namespace [aspose.barcode.complexbarcode](/barcode/python-net/aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](/barcode/python-net/)

