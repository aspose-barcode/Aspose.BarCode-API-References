---
title: "Mailmark2DCodetext"
second_title: "Aspose.BarCode for Python via .NET Referensi API"
description: 
type: docs
url: /id/python-net/aspose.barcode.complexbarcode/mailmark2dcodetext/
---

## Mailmark2DCodetext class

Kelas untuk menyandikan dan menguraikan teks yang tertanam dalam kode Royal Mail 2D Mailmark.

Tipe Mailmark2DCodetext menampilkan anggota berikut:
## Konstruktor
| Nama | Deskripsi |
| :- | :- |
| Mailmark2DCodetext() | Menginisialisasi instance baru dari kelas Mailmark2DCodetext |
## Properti
| Nama | Deskripsi |
| :- | :- |
| upu_country_id | Mengidentifikasi ID Negara UPU. Panjang maksimum: 4 karakter. |
| information_type_id | Mengidentifikasi muatan kode batang Royal Mail Mailmark untuk setiap tipe produk. |
| version_id | Mengidentifikasi versi kode batang yang relevan untuk setiap ID Tipe Informasi. |
| klass | Mengidentifikasi kelas item. |
| supply_chain_id | Mengidentifikasi grup unik pelanggan yang terlibat dalam pengiriman surat.<br/>            Nilai maksimum: 9999999. |
| item_id | Mengidentifikasi item unik dalam ID Rantai Pasokan.<br/>            Setiap kode batang Mailmark harus membawa ID<br/>            sehingga dapat diidentifikasi secara unik setidaknya selama 90 hari.<br/>            Nilai maksimum: 99999999. |
| destination_post_code_and_dps | Berisi Kode Pos dari Alamat Pengiriman dengan DPS<br/>            Jika di daratan, Kode Pos/DP berisi jumlah karakter berikut.<br/>            Area (1 atau 2 karakter) Distrik (1 atau 2 karakter)<br/>            Sektor (1 karakter) Unit (2 karakter) DPS (2 karakter).<br/>            Kode Pos dan DPS harus mematuhi format PAF® yang valid. |
| rts_flag | Bendera yang menunjukkan tingkat layanan Return to Sender yang diminta. |
| return_to_sender_post_code | Berisi Kode Pos Return to Sender tetapi tanpa DPS.<br/>            PC (tanpa DPS) harus mematuhi format PAF®. |
| customer_content | Ruang opsional untuk digunakan oleh pelanggan. |
| customer_content_encode_mode | Mode enkode kode batang Datamatrix.<br/>            Nilai default: EncodeMode.C40. |
| data_matrix_type | Tipe Mailmark 2D menentukan ukuran kode batang Data Matrix. |
## Metode
| Nama | Deskripsi |
| :- | :- |
| get_constructed_codetext() | Bangun teks kode dari data Mailmark. |
| init_from_string(constructed_codetext) | Menginisialisasi data Mailmark dari teks kode yang dibangun. |
| get_barcode_type() | Mendapatkan tipe barcode. |

### Lihat Juga

* namespace [aspose.barcode.complexbarcode](/barcode/python-net/aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](/barcode/python-net/)

