---
title: "BarCodeReader"
second_title: "Aspose.BarCode for Python via .NET Referensi API"
description: 
type: docs
url: /id/python-net/aspose.barcode.barcoderecognition/barcodereader/
---

## BarCodeReader class

BarCodeReader membungkus sebuah gambar yang mungkin berisi satu atau beberapa kode batang, kemudian dapat melakukan operasi ReadBarCodes untuk mendeteksi kode batang.

Tipe BarCodeReader menampilkan anggota-anggota berikut:
## Konstruktor
| Nama | Deskripsi |
| :- | :- |
| BarCodeReader() | Menginisialisasi instance baru dari kelas [BarCodeReader](/barcode/python-net/aspose.barcode.barcoderecognition/barcodereader/) dengan nilai default.<br/>            Memerlukan penetapan gambar (SetBitmapImage()) sebelum memanggil metode ReadBarCodes(). |
| BarCodeReader(image) | Menginisialisasi instance baru dari kelas BarCodeReader |
| BarCodeReader(image, decode_types) | Menginisialisasi instance baru dari kelas BarCodeReader |
| BarCodeReader(image, type) | Menginisialisasi instance baru dari kelas BarCodeReader |
| BarCodeReader(image, area, decode_types) | Menginisialisasi instance baru dari kelas BarCodeReader |
| BarCodeReader(image, area, type) | Menginisialisasi instance baru dari kelas BarCodeReader |
| BarCodeReader(image, areas, decode_types) | Menginisialisasi instance baru dari kelas BarCodeReader |
| BarCodeReader(image, areas, type) | Menginisialisasi instance baru dari kelas BarCodeReader |
| BarCodeReader(filename) | Menginisialisasi instance baru dari kelas BarCodeReader |
| BarCodeReader(filename, decode_types) | Menginisialisasi instance baru dari kelas BarCodeReader |
| BarCodeReader(filename, type) | Menginisialisasi instance baru dari kelas BarCodeReader |
| BarCodeReader(stream) | Menginisialisasi instance baru dari kelas BarCodeReader |
| BarCodeReader(stream, type) | Menginisialisasi instance baru dari kelas BarCodeReader |
| BarCodeReader(stream, decode_types) | Menginisialisasi instance baru dari kelas BarCodeReader |
| BarCodeReader(frame, areas, type) | Menginisialisasi instance baru dari kelas BarCodeReader |
| BarCodeReader(frame, areas, decode_types) | Menginisialisasi instance baru dari kelas BarCodeReader |
| BarCodeReader(frame, area, type) | Menginisialisasi instance baru dari kelas BarCodeReader |
| BarCodeReader(frame, area, decode_types) | Menginisialisasi instance baru dari kelas BarCodeReader |
| BarCodeReader(frame, type) | Menginisialisasi instance baru dari kelas BarCodeReader |
| BarCodeReader(frame, decode_types) | Menginisialisasi instance baru dari kelas BarCodeReader |
| BarCodeReader(frame) | Menginisialisasi instance baru dari kelas BarCodeReader |
## Properti
| Nama | Deskripsi |
| :- | :- |
| processor_settings | Mendapatkan pengaturan penggunaan inti prosesor. |
| timeout | Mendapatkan atau mengatur batas waktu proses pengenalan dalam milidetik. |
| found_bar_codes | Mendapatkan array [BarCodeResult](/barcode/python-net/aspose.barcode.barcoderecognition/barcoderesult/) yang dikenali. |
| found_count | Mendapatkan jumlah barcode yang dikenali |
| quality_settings | QualitySettings memungkinkan mengkonfigurasi kualitas dan kecepatan pengenalan secara manual.<br/>            Anda dapat dengan cepat mengatur QualitySettings menggunakan preset bawaan: HighPerformance, NormalQuality, <br/>            HighQuality, MaxBarCodes atau Anda dapat mengkonfigurasi opsi terpisah secara manual.<br/>            Nilai default dari QualitySettings adalah NormalQuality. |
| barcode_settings | Parameter utama dekode BarCode. Berisi parameter yang memengaruhi data yang dikenali. |
| bar_code_read_type | Mendapatkan atau mengatur tipe dekode barcode yang digunakan untuk pengenalan.<br/>            Harus diatur sebelum memanggil [None](/barcode/python-net/aspose.barcode.barcoderecognition/barcodereader/). |
## Metode
| Nama | Deskripsi |
| :- | :- |
| set_bar_code_image(value) | Mengatur gambar bitmap untuk pengenalan. <br/>            Harus dipanggil sebelum metode ReadBarCodes(). |
| set_bar_code_image(value, areas) | Mengatur gambar bitmap dan area untuk pengenalan. <br/>            Harus dipanggil sebelum metode ReadBarCodes(). |
| set_bar_code_image(value, area) | Mengatur gambar bitmap dan area untuk pengenalan. <br/>            Harus dipanggil sebelum metode ReadBarCodes(). |
| set_bar_code_image(filename) | Mengatur file gambar untuk pengenalan. <br/>            Harus dipanggil sebelum metode ReadBarCodes(). |
| set_bar_code_image(stream) | Mengatur aliran gambar untuk pengenalan. <br/>            Harus dipanggil sebelum metode ReadBarCodes(). |
| set_bar_code_image(frame, area) | Mengatur bingkai luminansi dan area untuk pengenalan. Harus dipanggil sebelum metode [None](/barcode/python-net/aspose.barcode.barcoderecognition/barcodereader/). |
| set_bar_code_image(frame, areas) | Mengatur bingkai luminansi dan area-area untuk pengenalan. Harus dipanggil sebelum metode [None](/barcode/python-net/aspose.barcode.barcoderecognition/barcodereader/). |
| set_bar_code_image(frame) | Mengatur bingkai luminansi dan area untuk pengenalan. Harus dipanggil sebelum metode [None](/barcode/python-net/aspose.barcode.barcoderecognition/barcodereader/). |
| export_to_xml(xml_file) | Mengekspor properti BarCode ke file xml yang ditentukan |
| export_to_xml(xml_stream) | Mengekspor properti BarCode ke aliran xml yang ditentukan |
| import_from_xml(xml_file) | Mengimpor properti BarCode dari file xml yang ditentukan dan menerapkannya ke instance BarCodeReader saat ini. |
| import_from_xml(xml_stream) | Mengimpor properti BarCode dari aliran xml yang ditentukan dan menerapkannya ke instance BarCodeReader saat ini. |
| abort() | Fungsi meminta penghentian sesi pengenalan saat ini dari thread lain. Abort adalah metode yang tidak dapat diblokir dan mengembalikan kontrol segera setelah dipanggil. <br/>            Metode ini harus digunakan ketika proses pengenalan terlalu lama. |
| read_bar_codes() | Membaca [BarCodeResult](/barcode/python-net/aspose.barcode.barcoderecognition/barcoderesult/)s dari gambar. |
| set_bar_code_read_type(barcode_types) | Mengatur array tipe [SingleDecodeType](/barcode/python-net/aspose.barcode.barcoderecognition/singledecodetype/) untuk pengenalan. <br/>            Harus dipanggil sebelum metode ReadBarCodes(). |

### Lihat Juga

* namespace [aspose.barcode.barcoderecognition](/barcode/python-net/aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](/barcode/python-net/)

