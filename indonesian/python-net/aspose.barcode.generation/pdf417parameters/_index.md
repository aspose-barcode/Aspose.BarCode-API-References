---
title: "Pdf417Parameters"
second_title: "Aspose.BarCode for Python via .NET Referensi API"
description: 
type: docs
url: /id/python-net/aspose.barcode.generation/pdf417parameters/
---

## Pdf417Parameters class

Parameter PDF417. Berisi parameter PDF417, MacroPDF417, MicroPDF417, dan GS1MicroPdf417.<br/>            MacroPDF417 memerlukan dua bidang: Pdf417MacroFileID dan Pdf417MacroSegmentID. Semua bidang lain bersifat opsional.<br/>            MicroPDF417 dalam mode Structured Append (sama dengan mode MacroPDF417) memerlukan dua bidang: Pdf417MacroFileID dan Pdf417MacroSegmentID. Semua bidang lain bersifat opsional.

Tipe Pdf417Parameters menampilkan anggota-anggota berikut:
## Properti
| Nama | Deskripsi |
| :- | :- |
| encode_mode | Mengidentifikasi mode enkode Pdf417. <br/>            Nilai default: Auto. |
| error_level | Mendapatkan atau mengatur tipe simbolologi Pdf417 dari tingkat koreksi kesalahan BarCode<br/>            yang berkisar dari level0 hingga level8, level0 berarti tidak ada info koreksi kesalahan,<br/>            level8 berarti koreksi kesalahan terbaik yang menghasilkan gambar lebih besar. |
| truncate | Apakah tipe simbolologi Pdf417 dari BarCode dipotong (untuk mengurangi ruang). <br/>            Juga dikenal sebagai CompactPDF417. Indikator baris kanan dan pola berhenti kanan dihapus dalam mode ini. |
| kolom | Jumlah kolom. |
| baris | Jumlah baris. |
| aspect_ratio | Rasio Tinggi/ Lebar modul BarCode 2D. |
| macro_pdf_417_file_id | ID berkas barcode MacroPdf417 (field wajib).<br/>            ID berkas barcode MicroPDF417 (field wajib untuk mode Structured Append). |
| macro_pdf_417_segment_id | ID segmen barcode MacroPdf417 (field wajib), yang dimulai dari 0 hingga MacroSegmentsCount - 1.<br/>            ID segmen barcode MicroPDF417 (field wajib untuk mode Structured Append). |
| macro_pdf_417_segments_count | Jumlah segmen barcode MacroPdf417 (field opsional).<br/>            Jumlah segmen barcode MicroPDF417 (field opsional untuk mode Structured Append). |
| macro_pdf_417_file_name | Nama berkas barcode MacroPdf417 (field opsional).<br/>            Nama berkas barcode MicroPDF417 (field opsional untuk mode Structured Append). |
| macro_pdf_417_time_stamp | Stempel waktu barcode MacroPdf417 (field opsional).<br/>            Stempel waktu barcode MicroPDF417 (field opsional untuk mode Structured Append). |
| macro_pdf_417_sender | Nama pengirim barcode MacroPdf417 (field opsional).<br/>            Nama pengirim barcode MicroPDF417 (field opsional untuk mode Structured Append). |
| macro_pdf_417_addressee | Nama penerima barcode MacroPdf417 (field opsional).<br/>            Nama penerima barcode MicroPDF417 (field opsional untuk mode Structured Append). |
| macro_pdf_417_file_size | Ukuran file MacroPdf417 (field opsional).<br/>            Ukuran file MicroPDF417 (field opsional untuk mode Structured Append)<br/>            Field ukuran file berisi ukuran dalam byte dari seluruh file sumber. |
| macro_pdf_417_checksum | Checksum barcode MacroPdf417 (field opsional).<br/>            Checksum barcode MicroPDF417 (field opsional untuk mode Structured Append)<br/>            Field checksum berisi nilai checksum CRC 16-bit (2 byte) menggunakan polinomial CCITT-16. x^16 + x^12 + x^5 + 1 |
| eci_encoding | Pengidentifikasi Interpretasi Saluran Terluas. Ini digunakan untuk memberi tahu pembaca barcode detail<br/>            tentang referensi yang digunakan untuk mengenkode data dalam simbol. Tidak diterapkan untuk field teks Macro PDF417.<br/>            Implementasi saat ini mencakup semua pengkodean charset yang dikenal. |
| macro_pdf_417eci_encoding | Pengidentifikasi Interpretasi Saluran Terluas. Berlaku untuk field teks Macro PDF417. |
| macro_pdf_417_terminator | Digunakan untuk memberi tahu enkoder apakah menambahkan Terminator Macro PDF417 (codeword 922) ke segmen. <br/>            Hanya diterapkan untuk Macro PDF417. |
| is_reader_initialization | Digunakan untuk memberi instruksi kepada pembaca agar menafsirkan data yang terdapat dalam simbol<br/>            sebagai pemrograman untuk inisialisasi pembaca. |
| macro_characters | Nilai Macro Characters 05 dan 06 digunakan untuk memperoleh enkoding yang lebih kompak dalam mode khusus.<br/>            Hanya dapat digunakan dengan MicroPdf417 dan mengenkode mode MicroPdf417 916 dan 917<br/>            Nilai default: MacroCharacters.None. |
| is_linked | Mendefinisikan mode terhubung dengan barcode GS1MicroPdf417, MicroPdf417, dan Pdf417<br/>            Dengan simbolologi GS1MicroPdf417 mengenkode mode UCC/EAN-128 “Linked” 906, 907, 912, 913, 914, 915<br/>            Dengan simbolologi MicroPdf417 dan Pdf417 mengenkode flag tautan 918 ke komponen linear terkait selain EAN.UCC |
| is_code_128_emulation | Hanya dapat digunakan dengan MicroPdf417 dan mengenkode mode emulasi Code 128<br/>            Dapat mengenkode FNC1 pada mode posisi kedua 908 dan 909, juga dapat mengenkode 910 dan 911 yang hanya menunjukkan bahwa MicroPdf417 yang dikenali dapat diinterpretasikan sebagai Code 128 |

### Lihat Juga

* namespace [aspose.barcode.generation](/barcode/python-net/aspose.barcode.generation/)
* assembly [Aspose.BarCode](/barcode/python-net/)

