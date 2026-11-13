---
title: "DataMatrixParameters"
second_title: "Aspose.BarCode for Python via .NET Referensi API"
description: 
type: docs
url: /id/python-net/aspose.barcode.generation/datamatrixparameters/
---

## DataMatrixParameters class

Parameter DataMatrix.

Tipe DataMatrixParameters menampilkan anggota-anggota berikut:
## Properti
| Nama | Deskripsi |
| :- | :- |
| ecc_type | Mendapatkan atau mengatur tipe ECC Datamatrix.<br/>            Nilai default: DataMatrixEccType.Ecc200. |
| version | Mendapatkan atau mengatur ukuran simbol Datamatrix.<br/>            Nilai default: Version.Auto. |
| encode_mode | Mode enkode barcode Datamatrix.<br/>            Nilai default: EncodeMode.Auto. |
| structured_append_barcode_id | ID barcode untuk mode Structured Append pada barcode Datamatrix.<br/>            Nilai default: 0 |
| structured_append_barcodes_count | Jumlah barcode untuk mode Structured Append pada barcode Datamatrix.<br/>            Nilai default: 0 |
| structured_append_file_id | ID file untuk mode Structured Append pada barcode Datamatrix.<br/>            Nilai default: 0 |
| is_reader_programming | Digunakan untuk memberi instruksi kepada pembaca agar menafsirkan data yang terdapat dalam simbol<br/>            sebagai pemrograman untuk inisialisasi pembaca.<br/>            Nilai default: false |
| macro_characters | Nilai Macro Characters 05 dan 06 digunakan untuk memperoleh enkode yang lebih kompak dalam mode khusus.<br/>            Hanya dapat digunakan dengan DataMatrixEccType.Ecc200 atau DataMatrixEccType.EccAuto.<br/>            Tidak dapat digunakan dengan EncodeTypes.GS1DataMatrix<br/>            Nilai default: MacroCharacters.None. |
| aspect_ratio | Rasio Tinggi/ Lebar modul BarCode 2D. |
| eci_encoding | Mendapatkan atau mengatur enkoding ECI. Digunakan ketika EncodeMode adalah Auto.<br/>            Nilai default: ISO-8859-1 |

### Lihat Juga

* namespace [aspose.barcode.generation](/barcode/python-net/aspose.barcode.generation/)
* assembly [Aspose.BarCode](/barcode/python-net/)

