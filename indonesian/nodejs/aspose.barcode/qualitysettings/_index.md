---
title: "QualitySettings"
linktitle: "QualitySettings"
second_title: "Referensi API Aspose.BarCode untuk Node.js via Java"
description: "QualitySettings memungkinkan mengkonfigurasi kualitas pengenalan dan kecepatan secara manual."
type: docs
weight: 860
url: /id/nodejs/aspose.barcode/qualitysettings/
---

## QualitySettings class

QualitySettings memungkinkan mengkonfigurasi kualitas pengenalan dan kecepatan secara manual. Anda dapat dengan cepat mengatur QualitySettings menggunakan preset tersemat: HighPerformance, NormalQuality, HighQuality, MaxBarCodes atau Anda dapat mengkonfigurasi opsi terpisah secara manual. Nilai default QualitySettings adalah NormalQuality.

```js
new QualitySettings()
```

**Example:**

```js
//This sample shows how to use QualitySettings with BarCodeReader
let reader = new BarCodeReader("test.png", null,  [ DecodeType.CODE_39, DecodeType.CODE_128 ]);
//set high performance mode
reader.setQualitySettings(QualitySettings.getHighPerformance());
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
   let result = results[i];
   console.log("BarCode CodeText: " + result.getCodeText());
}
```

## Metode

| Nama | Deskripsi |
| --- | --- |
| [getHighPerformance()](#gethighperformance) *(static)* | Preset kualitas pengenalan HighPerformance. Barcode berkualitas tinggi dikenali dengan baik dalam mode ini. |
| [getHighQuality()](#gethighquality) *(static)* | Preset kualitas pengenalan HighQuality. Preset ini dikembangkan untuk barcode berkualitas rendah. |
| [getMaxQuality()](#getmaxquality) *(static)* | Preset kualitas pengenalan MaxQuality. Preset ini dikembangkan untuk mengenali semua barcode yang mungkin, bahkan barcode yang salah |
| [getNormalQuality()](#getnormalquality) *(static)* | Preset kualitas pengenalan NormalQuality. Cocok untuk sebagian besar barcode. |
| [getAllowIncorrectBarcodes()](#getallowincorrectbarcodes) | Memungkinkan mesin mengenali barcode yang memiliki checksum atau nilai yang salah. Mode ini dapat digunakan untuk mengenali kerusakan |
| [getBarcodeQuality()](#getbarcodequality) | Mode yang memungkinkan metode untuk mengenali elemen kode batang dengan kualitas yang dipilih. Elemen kode batang dengan kualitas lebih rendah r |
| [getComplexBackground()](#getcomplexbackground) | Mode yang mengaktifkan atau menonaktifkan pengenalan tambahan barcode berwarna pada gambar berwarna. |
| [getDeconvolution()](#getdeconvolution) | Mode dekonvolusi (pemulihan gambar) yang mendefinisikan tingkat degradasi gambar. Pada awalnya dekonvolusi adalah fungsi |
| [getInverseImage()](#getinverseimage) | Mode yang mengaktifkan atau menonaktifkan pengenalan tambahan barcode pada gambar dengan warna terbalik (luminansi). |
| [getMinimalXDimension()](#getminimalxdimension) | Ukuran minimal XDimension dalam piksel yang digunakan dengan UseMinimalXDimension. |
| [getXDimension()](#getxdimension) | Mode pengenalan yang menentukan ukuran (dari 1 hingga tak terbatas) elemen minimal barcode: sel matriks atau batang. |
| [setAllowIncorrectBarcodes(value)](#setallowincorrectbarcodes) | Memungkinkan mesin mengenali barcode yang memiliki checksum atau nilai yang salah. Mode ini dapat digunakan untuk mengenali kerusakan |
| [setBarcodeQuality(value)](#setbarcodequality) | Mode yang memungkinkan metode untuk mengenali elemen kode batang dengan kualitas yang dipilih. Elemen kode batang dengan kualitas lebih rendah r |
| [setComplexBackground(value)](#setcomplexbackground) | Mode yang mengaktifkan atau menonaktifkan pengenalan tambahan barcode berwarna pada gambar berwarna. |
| [setDeconvolution(value)](#setdeconvolution) | Mode dekonvolusi (pemulihan gambar) yang mendefinisikan tingkat degradasi gambar. Pada awalnya dekonvolusi adalah fungsi |
| [setInverseImage(value)](#setinverseimage) | Mode yang mengaktifkan atau menonaktifkan pengenalan tambahan barcode pada gambar dengan warna terbalik (luminansi). |
| [setMinimalXDimension(value)](#setminimalxdimension) | Ukuran minimal XDimension dalam piksel yang digunakan dengan UseMinimalXDimension. |
| [setXDimension(value)](#setxdimension) | Mode pengenalan yang menentukan ukuran (dari 1 hingga tak terbatas) elemen minimal barcode: sel matriks atau batang. |

### getHighPerformance() (static) {#gethighperformance}

Preset kualitas pengenalan HighPerformance. Barcode berkualitas tinggi dikenali dengan baik dalam mode ini.

**Example:**

```js
let reader = new BarCodeReader("test.png");
reader.setQualitySettings(QualitySettings.getHighPerformance());
```

### getHighQuality() (static) {#gethighquality}

Preset kualitas pengenalan HighQuality. Preset ini dikembangkan untuk barcode berkualitas rendah.

**Example:**

```js
let reader = new BarCodeReader("test.png");
reader.setQualitySettings(QualitySettings.getHighQuality());
```

### getMaxQuality() (static) {#getmaxquality}

Preset kualitas pengenalan MaxQuality. Preset ini dikembangkan untuk mengenali semua barcode yang mungkin, bahkan barcode yang tidak benar. Contoh ini menunjukkan cara menggunakan mode MaxQuality reader = new BarCodeReader(\"test.png\"null, null, DecodeType.CODE_39_FULL_ASCII, DecodeType.CODE_128); { reader.setQualitySettings(QualitySettings.getMaxQuality()); for(let i = 0; i < reader.readBarCodes().length; i++) echo (reader.getFoundBarcodes()[i].getCodeText()); } Nilai: preset kualitas pengenalan MaxQuality.

### getNormalQuality() (static) {#getnormalquality}

Preset kualitas pengenalan NormalQuality. Cocok untuk sebagian besar barcode.

**Example:**

```js
let reader = new BarCodeReader("test.png");
reader.setQualitySettings(QualitySettings.getNormalQuality());
```

### getAllowIncorrectBarcodes() {#getallowincorrectbarcodes}

Mengizinkan mesin untuk mengenali barcode yang memiliki checksum atau nilai yang tidak benar. Mode ini dapat digunakan untuk mengenali barcode yang rusak dengan teks yang tidak benar.

**Returns:** Allows engine to recognize incorrect barcodes.

### getBarcodeQuality() {#getbarcodequality}

Mode yang mengaktifkan metode untuk mengenali elemen barcode dengan kualitas yang dipilih. Elemen barcode dengan kualitas lebih rendah memerlukan metode yang lebih berat yang memperlambat proses pengenalan.

**Returns:** Mode which enables methods to recognize barcode elements with the selected quality.

### getComplexBackground() {#getcomplexbackground}

Mode yang mengaktifkan atau menonaktifkan pengenalan tambahan barcode berwarna pada gambar berwarna.

**Returns:** Additional recognition of color barcodes on color images.

### getDeconvolution() {#getdeconvolution}

Mode dekonvolusi (pemulihan gambar) yang menentukan tingkat degradasi gambar. Pada awalnya dekonvolusi adalah fungsi yang dapat memulihkan gambar yang terdegradasi (konvolusi) oleh fungsi alami apa pun seperti blur, selama pengambilan gambar oleh kamera. Karena kami tidak dapat mendeteksi fungsi gambar yang merusak gambar, kami harus memeriksa fungsi yang paling dikenal seperti sharp atau morfologi matematis.

**Returns:** Deconvolution mode which defines level of image degradation.

### getInverseImage() {#getinverseimage}

Mode yang mengaktifkan atau menonaktifkan pengenalan tambahan barcode pada gambar dengan warna terbalik (luminansi).

**Returns:** Additional recognition of barcodes on images with inverse colors

### getMinimalXDimension() {#getminimalxdimension}

Ukuran minimal XDimension dalam piksel yang digunakan dengan UseMinimalXDimension.

**Returns:** Minimal size of XDimension in pixels which is used with UseMinimalXDimension.

### getXDimension() {#getxdimension}

Mode pengenalan yang menentukan ukuran (dari 1 hingga tak terbatas) elemen minimal barcode: sel matriks atau batang.

**Returns:** size (from 1 to infinity) of barcode minimal element: matrix cell or bar.

### setAllowIncorrectBarcodes(value) {#setallowincorrectbarcodes}

Mengizinkan mesin untuk mengenali barcode yang memiliki checksum atau nilai yang tidak benar. Mode ini dapat digunakan untuk mengenali barcode yang rusak dengan teks yang tidak benar.

| Parameter | Deskripsi |
| --- | --- |
| nilai | Mengizinkan mesin untuk mengenali barcode yang tidak benar. |

### setBarcodeQuality(value) {#setbarcodequality}

Mode yang mengaktifkan metode untuk mengenali elemen barcode dengan kualitas yang dipilih. Elemen barcode dengan kualitas lebih rendah memerlukan metode yang lebih berat yang memperlambat proses pengenalan.

| Parameter | Deskripsi |
| --- | --- |
| nilai | Mode yang mengaktifkan metode untuk mengenali elemen barcode dengan kualitas yang dipilih. |

### setComplexBackground(value) {#setcomplexbackground}

Mode yang mengaktifkan atau menonaktifkan pengenalan tambahan barcode berwarna pada gambar berwarna.

| Parameter | Deskripsi |
| --- | --- |
| nilai | Pengenalan tambahan barcode berwarna pada gambar berwarna. |

### setDeconvolution(value) {#setdeconvolution}

Mode dekonvolusi (pemulihan gambar) yang menentukan tingkat degradasi gambar. Pada awalnya dekonvolusi adalah fungsi yang dapat memulihkan gambar yang terdegradasi (konvolusi) oleh fungsi alami apa pun seperti blur, selama pengambilan gambar oleh kamera. Karena kami tidak dapat mendeteksi fungsi gambar yang merusak gambar, kami harus memeriksa fungsi yang paling dikenal seperti sharp atau morfologi matematis.

| Parameter | Deskripsi |
| --- | --- |
| nilai | Mode dekonvolusi yang menentukan tingkat degradasi gambar. |

### setInverseImage(value) {#setinverseimage}

Mode yang mengaktifkan atau menonaktifkan pengenalan tambahan barcode pada gambar dengan warna terbalik (luminansi).

| Parameter | Deskripsi |
| --- | --- |
| nilai | Pengenalan tambahan barcode pada gambar dengan warna terbalik |

### setMinimalXDimension(value) {#setminimalxdimension}

Ukuran minimal XDimension dalam piksel yang digunakan dengan UseMinimalXDimension.

| Parameter | Deskripsi |
| --- | --- |
| nilai | Ukuran minimal XDimension dalam piksel yang digunakan dengan UseMinimalXDimension. |

### setXDimension(value) {#setxdimension}

Mode pengenalan yang menentukan ukuran (dari 1 hingga tak terbatas) elemen minimal barcode: sel matriks atau batang.

| Parameter | Deskripsi |
| --- | --- |
| nilai | (dari 1 hingga tak terbatas) elemen minimal barcode: sel matriks atau batang. |
