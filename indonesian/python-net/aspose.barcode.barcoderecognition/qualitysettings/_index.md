---
title: "QualitySettings"
second_title: "Aspose.BarCode for Python via .NET Referensi API"
description: 
type: docs
url: /id/python-net/aspose.barcode.barcoderecognition/qualitysettings/
---

## QualitySettings class

QualitySettings memungkinkan mengkonfigurasi kualitas dan kecepatan pengenalan secara manual.<br/>            Anda dapat dengan cepat mengatur QualitySettings dengan preset tersemat: HighPerformance, NormalQuality, HighQuality, MaxQuality atau Anda dapat mengkonfigurasi opsi terpisah secara manual.<br/>            Nilai default QualitySettings adalah NormalQuality.

Tipe QualitySettings menampilkan anggota-anggota berikut:
## Properti
| Nama | Deskripsi |
| :- | :- |
| high_performance | Preset kualitas pengenalan HighPerformance. Kode batang berkualitas tinggi dikenali dengan baik dalam mode ini. |
| normal_quality | Preset kualitas pengenalan NormalQuality. Cocok untuk sebagian besar barcode |
| high_quality | Preset kualitas pengenalan HighQuality. Preset ini dikembangkan untuk barcode kualitas rendah. Memungkinkan mendeteksi barcode yang sangat rusak. |
| max_quality | Preset kualitas pengenalan MaxQuality. Preset ini dikembangkan untuk mengenali semua barcode yang mungkin, bahkan barcode yang tidak tepat. |
| x_dimension | Mode pengenalan yang menentukan ukuran (dari 1 hingga tak terhingga) elemen minimal barcode: sel matriks atau bar. |
| minimal_x_dimension | Ukuran minimal XDimension dalam piksel yang digunakan dengan UseMinimalXDimension. |
| barcode_quality | Mode yang memungkinkan metode untuk mengenali elemen barcode dengan kualitas yang dipilih. Elemen barcode dengan kualitas lebih rendah memerlukan metode yang lebih berat yang memperlambat proses pengenalan. |
| deconvolution | Mode dekonvolusi (pemulihan gambar) yang menentukan tingkat degradasi gambar. Secara awal dekonvolusi adalah fungsi yang dapat memulihkan gambar yang terdegradasi <br/>            (konvolusi) oleh fungsi alami apa pun seperti blur, selama pengambilan gambar dengan kamera. Karena kami tidak dapat mendeteksi fungsi gambar yang merusak gambar, <br/>            kami harus memeriksa fungsi yang paling dikenal seperti sharp atau morfologi matematis. |
| inverse_image | Mode yang mengaktifkan atau menonaktifkan pengenalan tambahan barcode pada gambar dengan warna terbalik (luminansi). |
| complex_background | Mode yang mengaktifkan atau menonaktifkan pengenalan tambahan barcode berwarna pada gambar berwarna. |
| allow_incorrect_barcodes | Memungkinkan mesin untuk mengenali barcode yang memiliki checksum atau nilai yang tidak tepat. Mode ini dapat digunakan untuk mengenali barcode yang rusak dengan teks yang tidak tepat. |

### Lihat Juga

* namespace [aspose.barcode.barcoderecognition](/barcode/python-net/aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](/barcode/python-net/)

