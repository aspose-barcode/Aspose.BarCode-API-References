---
title: "QrParameters"
second_title: "Aspose.BarCode for Python via .NET Referensi API"
description: 
type: docs
url: /id/python-net/aspose.barcode.generation/qrparameters/
---

## QrParameters class

Parameter QR.

The QrParameters type menampilkan anggota-anggota berikut:
## Properti
| Nama | Deskripsi |
| :- | :- |
| eci_encoding | Pengidentifikasi Interpretasi Saluran Terluas. Ini digunakan untuk memberi pembaca barcode detail<br/>            tentang referensi yang digunakan untuk mengkodekan data dalam simbol.<br/>            Implementasi saat ini mencakup semua pengkodean charset yang dikenal.<br/>            Tidak didukung oleh MicroQR. |
| encode_mode | Tipe simbolologi QR dari mode pengkodean BarCode.<br/>            Nilai default: QREncodeMode.Auto. |
| error_level | Tingkat koreksi kesalahan Reed-Solomon untuk barcode QR, MicroQR, dan RectMicroQR.<br/>             Dari rendah ke tinggi: LevelL, LevelM, LevelQ, LevelH. Lihat QRErrorLevel. |
| version | Versi QR Code. Dari Version1 hingga Version40.<br/>            Nilai default adalah QRVersion.Auto. |
| micro_qr_version | Versi MicroQR Code. Dari versi M1 hingga versi M4.<br/>            Nilai default adalah MicroQRVersion.Auto. |
| rect_micro_qr_version | Versi RectMicroQR Code. Dari versi R7x59 hingga versi R17x139.<br/>            Nilai default adalah RectMicroQRVersion.Auto. |
| aspect_ratio | Rasio Tinggi/ Lebar modul BarCode 2D. |
| structured_append | Parameter penambahan terstruktur QR.<br/>            Mode penambahan terstruktur tidak didukung oleh barcode MicroQR dan RectMicroQR. |
| encode_gs1_separator_in_byte_mode |  |

### Lihat Juga

* namespace [aspose.barcode.generation](/barcode/python-net/aspose.barcode.generation/)
* assembly [Aspose.BarCode](/barcode/python-net/)

