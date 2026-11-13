---
title: "USADriveIdCodetext"
second_title: "Aspose.BarCode for Python via .NET Referensi API"
description: 
type: docs
url: /id/python-net/aspose.barcode.complexbarcode/usadriveidcodetext/
---

## USADriveIdCodetext class

Kelas untuk menyandikan dan menguraikan teks yang tertanam dalam kode PDF417 Surat Izin Mengemudi USA.

Tipe USADriveIdCodetext menampilkan anggota-anggota berikut:
## Konstruktor
| Nama | Deskripsi |
| :- | :- |
| USADriveIdCodetext() | Menginisialisasi instance baru dari kelas USADriveIdCodetext |
## Properti
| Nama | Deskripsi |
| :- | :- |
| issuer_identification_number | Nomor ini secara unik mengidentifikasi <br/>            yurisdiksi penerbit dan dapat diperoleh dengan menghubungi ISO<br/>            Issuing Authority (AAMVA).  6 digit IIN lengkap harus dienkode. |
| aamva_version_number | Nomor Versi AAMVA 00-99 |
| jurisdiction_version_number | Nomor Versi Yurisdiksi 00-99 |
| number_of_entries | Jumlah 00-99 subfile |
| subfile_designator | Berisi informasi tentang subfile berikut, tipe, offset, dan panjang. <br/>            Penting: hanya mengatur tipe, offset, dan panjang yang akan diatur secara otomatis. |
| mandatory_elements | Elemen wajib (field) pada kartu |
| optional_elements | Elemen opsional (field) pada kartu |
| jurisdiction_specific_subfile | Field Spesifik Yurisdiksi |
## Metode
| Nama | Deskripsi |
| :- | :- |
| get_constructed_codetext() | Menyusun codetext dari data USA DL |
| init_from_string(constructed_codetext) | Inisialisasi objek USA DL dari codetext |
| get_barcode_type() | Mengembalikan tipe barcode USA DL (Pdf417) |
| save_to_xml(stream) | Menyimpan ke XML |

### Lihat Juga

* namespace [aspose.barcode.complexbarcode](/barcode/python-net/aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](/barcode/python-net/)

