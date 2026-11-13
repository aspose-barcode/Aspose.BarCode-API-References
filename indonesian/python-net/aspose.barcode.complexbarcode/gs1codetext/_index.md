---
title: "GS1Codetext"
second_title: "Aspose.BarCode for Python via .NET Referensi API"
description: 
type: docs
url: /id/python-net/aspose.barcode.complexbarcode/gs1codetext/
---

## GS1Codetext class

Mewakili teks kode GS1 untuk penyandian dan penguraian sebagai urutan terurut dari<br/>            elemen Identifier Aplikasi. Urutan sumber dan Identifier Aplikasi yang berulang<br/>            dipertahankan. Representasi dalam kurung memiliki bentuk (AI)value(AI)value.<br/>            Tanda kurung buka literal '(' di dalam nilai harus ditulis sebagai \(; ini adalah<br/>            satu-satunya urutan escape yang didukung. Tanda kurung tutup ')' di dalam nilai tidak<br/>            memerlukan escape.

Tipe GS1Codetext menampilkan anggota-anggota berikut:
## Konstruktor
| Nama | Deskripsi |
| :- | :- |
| GS1Codetext() | Menginisialisasi sebuah instance baru dari kelas GS1Codetext |
## Properti
| Nama | Deskripsi |
| :- | :- |
| barcode_type | Mendapatkan atau mengatur jenis barcode yang digunakan untuk mengkodekan GS1 codetext ini.<br/>            Jenis yang didukung adalah GS1Aztec, GS1CodablockF, GS1Code128, GS1DataMatrix,<br/>            GS1DotCode, GS1HanXin, GS1MicroPdf417, GS1QR, dan tipe GS1 DataBar.<br/>            Nilai default adalah GS1Code128. |
| jumlah | Mendapatkan jumlah elemen Identifier Aplikasi. |
| elemen | Mendapatkan salinan semua elemen dalam urutan sumber. |
## Indexer
| Nama | Deskripsi |
| :- | :- |
| [index] | Mendapatkan sebuah elemen berdasarkan posisinya dalam urutan yang teratur. |
## Metode
| Nama | Deskripsi |
| :- | :- |
| get_first(application_identifier) | Mendapatkan nilai pertama untuk sebuah Application Identifier. |
| get_all(application_identifier) | Mendapatkan semua nilai untuk sebuah Application Identifier dalam urutan sumber. |
| add(application_identifier, value) | Menambahkan elemen Application Identifier yang telah divalidasi. |
| validate(value) | Memvalidasi string elemen GS1 dalam tanda kurung dengan format (AI)nilai(AI)nilai tanpa<br/>            membuat objek. Karakter '(' literal di dalam nilai harus ditulis sebagai \(; tidak<br/>            ada urutan pelarian lain yang didukung, dan ')' tidak memerlukan pelarian. |
| parse(value) | Menganalisis string elemen GS1 dalam tanda kurung dengan format (AI)nilai(AI)nilai. Karakter '(' literal<br/>            di dalam nilai harus ditulis sebagai \(; tidak ada urutan pelarian lain yang didukung,<br/>            dan ')' tidak memerlukan pelarian. |
| try_parse(value, result, validation_result) | Mencoba menganalisis string elemen GS1 dalam tanda kurung dengan format (AI)nilai(AI)nilai<br/>            dan mengembalikan kesalahan validasi terstruktur. Karakter '(' literal di dalam nilai harus<br/>            ditulis sebagai \(; tidak ada urutan pelarian lain yang didukung, dan ')' tidak memerlukan<br/>            pelarian. |
| get_constructed_codetext() | Menyusun GS1 codetext dalam tanda kurung dengan format (AI)nilai(AI)nilai.<br/>            Tanda kurung buka literal dalam nilai di-escape sebagai \(. |
| init_from_string(constructed_codetext) | Menginisialisasi instance ini dari GS1 codetext dalam tanda kurung dengan format (AI)nilai(AI)nilai.<br/>            Elemen yang ada hanya diganti setelah codetext yang diberikan berhasil diurai. |
| get_barcode_type() | Mendapatkan jenis barcode yang digunakan untuk mengkodekan GS1 codetext ini. |

### Lihat Juga

* namespace [aspose.barcode.complexbarcode](/barcode/python-net/aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](/barcode/python-net/)

