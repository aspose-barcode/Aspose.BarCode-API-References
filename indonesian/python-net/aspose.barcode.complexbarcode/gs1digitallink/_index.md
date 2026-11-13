---
title: "GS1DigitalLink"
second_title: "Aspose.BarCode for Python via .NET Referensi API"
description: 
type: docs
url: /id/python-net/aspose.barcode.complexbarcode/gs1digitallink/
---

## GS1DigitalLink class

Mewakili teks kode GS1 Digital Link untuk penyandian dan penguraian sebagai urutan terurut dari<br/>            elemen Identifier Aplikasi. Urutan sumber dan Identifier Aplikasi yang berulang dipertahankan.<br/>            Teks kode yang dibangun adalah URI GS1 Digital Link yang tidak terkompresi.<br/>            Parameter kueri non-GS1 dan fragmen URI diabaikan saat parsing.

Tipe GS1DigitalLink menampilkan anggota-anggota berikut:
## Konstruktor
| Nama | Deskripsi |
| :- | :- |
| GS1DigitalLink(uri_stem) | Menginisialisasi sebuah instance baru dari kelas GS1DigitalLink |
| GS1DigitalLink(uri_stem, primary_application_identifier) | Menginisialisasi sebuah instance baru dari kelas GS1DigitalLink |
## Properti
| Nama | Deskripsi |
| :- | :- |
| uri_stem | Mendapatkan awalan URI absolut sebelum segmen jalur kunci utama GS1.<br/>            Stem tidak mengandung string kueri atau fragmen. |
| primary_application_identifier | Mendapatkan Identifier Aplikasi yang digunakan sebagai kunci utama Digital Link.<br/>            Null berarti bahwa kunci utama dipilih secara otomatis saat URI dibangun. |
| barcode_type | Mendapatkan atau mengatur jenis barcode yang digunakan untuk mengkodekan GS1 Digital Link ini.<br/>            Jenis yang didukung adalah QR, DataMatrix, Aztec, Pdf417, MicroPdf417, DotCode, HanXin, CodablockF, dan Code128.<br/>            Nilai default adalah QR. |
| jumlah | Mendapatkan jumlah elemen Identifier Aplikasi. |
| elemen | Mendapatkan salinan semua elemen dalam urutan sumber. |
## Indexer
| Nama | Deskripsi |
| :- | :- |
| [index] | Mendapatkan sebuah elemen berdasarkan posisinya dalam urutan yang teratur. |
## Metode
| Nama | Deskripsi |
| :- | :- |
| create(uri_stem, codetext) | Membuat GS1 Digital Link dengan menyalin semua elemen dari GS1 codetext dan memilih<br/>            satu-satunya kunci utama yang tersedia. |
| create(uri_stem, codetext, primary_application_identifier) | Membuat GS1 Digital Link dengan menyalin semua elemen dari GS1 codetext dan memilih<br/>            satu-satunya kunci utama yang tersedia. |
| get_first(application_identifier) | Mendapatkan nilai pertama untuk sebuah Application Identifier. |
| get_all(application_identifier) | Mendapatkan semua nilai untuk sebuah Application Identifier dalam urutan sumber. |
| add(application_identifier, value) | Menambahkan elemen Application Identifier yang telah divalidasi. |
| validate(value) | Memvalidasi URI GS1 Digital Link yang tidak terkompresi tanpa membuat objek. |
| parse(value) | Menganalisis URI GS1 Digital Link yang tidak terkompresi. |
| try_parse(value, result, validation_result) | Mencoba menganalisis URI GS1 Digital Link yang tidak terkompresi dan mengembalikan kesalahan validasi terstruktur. |
| to_gs1_codetext() | Membuat GS1 codetext independen yang berisi elemen GS1 saat ini.<br/>            Informasi hanya URI tidak termasuk. |
| to_uri_string() | Memformat status objek saat ini sebagai URI GS1 Digital Link yang tidak terkompresi. |
| get_constructed_codetext() | Membangun URI GS1 Digital Link yang tidak terkompresi. |
| init_from_string(constructed_codetext) | Menginisialisasi instance ini dari URI GS1 Digital Link yang tidak terkompresi.<br/>            Status yang ada digantikan hanya setelah URI yang diberikan berhasil dianalisis.<br/>            Tipe barcode yang dipilih dipertahankan. |
| get_barcode_type() | Mendapatkan tipe barcode yang digunakan untuk mengenkode GS1 Digital Link ini. |

### Lihat Juga

* namespace [aspose.barcode.complexbarcode](/barcode/python-net/aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](/barcode/python-net/)

