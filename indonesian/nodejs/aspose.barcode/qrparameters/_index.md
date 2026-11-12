---
title: "QrParameters"
linktitle: "QrParameters"
second_title: "Referensi API Aspose.BarCode untuk Node.js via Java"
description: "Parameter QR."
type: docs
weight: 830
url: /id/nodejs/aspose.barcode/qrparameters/
---

## QrParameters class

Parameter QR.

```js
new QrParameters()
```

## Metode

| Nama | Deskripsi |
| --- | --- |
| [getAspectRatio()](#getaspectratio) | Rasio Tinggi/Lebar modul BarCode 2D. |
| [getECIEncoding()](#geteciencoding) | Pengidentifikasi Interpretasi Saluran Ekstended. Ini digunakan untuk memberi tahu pembaca kode batang detail tentang referensi yang digunakan untuk |
| [getEncodeGS1SeparatorInByteMode()](#getencodegs1separatorinbytemode) | Mendapatkan atau mengatur nilai yang menunjukkan apakah karakter khusus GS1 harus dikodekan dalam mode Byte untuk QR dan RectMicroQR bar |
| [getEncodeMode()](#getencodemode) | Tipe simbol QR dari mode enkoding BarCode. Nilai default: QREncodeMode.Auto. |
| [getErrorLevel()](#geterrorlevel) | Tingkat koreksi kesalahan Reed-Solomon untuk barcode QR, MicroQR, dan RectMicroQR. Dari rendah ke tinggi: LevelL, LevelM, LevelQ |
| [getMicroQRVersion()](#getmicroqrversion) | Versi MicroQR Code. Dari versi M1 hingga versi M4. Nilai default adalah MicroQRVersion.Auto. |
| [getQrECIEncoding()](#getqreciencoding) ~~(deprecated)~~ | Pengidentifikasi Interpretasi Saluran Ekstended. Ini digunakan untuk memberi tahu pembaca kode batang detail tentang referensi yang digunakan untuk |
| [getQrEncodeMode()](#getqrencodemode) | Tipe simbol QR dari mode enkoding BarCode. Nilai default: QREncodeMode.AUTO. |
| [getQrEncodeType()](#getqrencodetype) ~~(deprecated)~~ | Mode pemilih QR / MicroQR. Pilih ForceQR untuk simbol QR standar, Auto untuk MicroQR. |
| [getQrErrorLevel()](#getqrerrorlevel) ~~(deprecated)~~ | Tingkat koreksi kesalahan Reed-Solomon untuk barcode QR. Dari rendah ke tinggi: LEVEL_L, LEVEL_M, LEVEL_Q, LEVEL_H. lihat QRError |
| [getQrVersion()](#getqrversion) ~~(deprecated)~~ | Versi QR Code. Dari Version1 hingga Version40 untuk QR code dan dari M1 hingga M4 untuk MicroQr. Nilai default adalah QRVersion.AUT |
| [getRectMicroQrVersion()](#getrectmicroqrversion) | Versi RectMicroQR Code. Dari versi R7x59 hingga versi R17x139. Nilai default adalah RectMicroQRVersion.Auto. |
| [getStructuredAppend()](#getstructuredappend) | Parameter QR structured append. |
| [getVersion()](#getversion) | Versi QR Code. Dari Version1 hingga Version40. Nilai default adalah QRVersion.Auto. |
| [setAspectRatio()](#setaspectratio) | Rasio Tinggi/Lebar modul BarCode 2D. |
| [setECIEncoding()](#seteciencoding) | Pengidentifikasi Interpretasi Saluran Ekstended. Ini digunakan untuk memberi tahu pembaca kode batang detail tentang referensi yang digunakan untuk |
| [setEncodeGS1SeparatorInByteMode(value)](#setencodegs1separatorinbytemode) | Mendapatkan atau mengatur nilai yang menunjukkan apakah karakter khusus GS1 harus dikodekan dalam mode Byte untuk QR dan RectMicroQR bar |
| [setEncodeMode()](#setencodemode) | Tipe simbol QR dari mode enkoding BarCode. Nilai default: QREncodeMode.Auto. |
| [setErrorLevel()](#seterrorlevel) | Tingkat koreksi kesalahan Reed-Solomon untuk barcode QR, MicroQR, dan RectMicroQR. Dari rendah ke tinggi: LevelL, LevelM, LevelQ |
| [setMicroQRVersion()](#setmicroqrversion) | Versi MicroQR Code. Dari versi M1 hingga versi M4. Nilai default adalah MicroQRVersion.Auto. |
| [setQrECIEncoding()](#setqreciencoding) ~~(deprecated)~~ | Pengidentifikasi Interpretasi Saluran Ekstended. Ini digunakan untuk memberi tahu pembaca kode batang detail tentang referensi yang digunakan untuk |
| [setQrEncodeMode()](#setqrencodemode) ~~(deprecated)~~ | Tipe simbol QR dari mode enkoding BarCode. Nilai default: QREncodeMode.AUTO. |
| [setQrEncodeType()](#setqrencodetype) ~~(deprecated)~~ | Mode pemilih QR / MicroQR. Pilih ForceQR untuk simbol QR standar, Auto untuk MicroQR. |
| [setQrErrorLevel()](#setqrerrorlevel) ~~(deprecated)~~ | Tingkat koreksi kesalahan Reed-Solomon untuk barcode QR. Dari rendah ke tinggi: LEVEL_L, LEVEL_M, LEVEL_Q, LEVEL_H. lihat QRError |
| [setQrVersion()](#setqrversion) ~~(deprecated)~~ | Versi QR Code. Dari Version1 hingga Version40 untuk QR code dan dari M1 hingga M4 untuk MicroQr. Nilai default adalah QRVersion.AUT |
| [setRectMicroQrVersion()](#setrectmicroqrversion) | Versi RectMicroQR Code. Dari versi R7x59 hingga versi R17x139. Nilai default adalah RectMicroQRVersion.Auto. |
| [setStructuredAppend()](#setstructuredappend) | Parameter QR structured append. |
| [setVersion()](#setversion) | Versi QR Code. Dari Version1 hingga Version40. Nilai default adalah QRVersion.Auto. |
| [toString()](#tostring) | Mengembalikan representasi string yang dapat dibaca manusia dari QrParameters ini. |

### getAspectRatio() {#getaspectratio}

Rasio Tinggi/Lebar modul BarCode 2D.

### getECIEncoding() {#geteciencoding}

Identifier Interpretasi Saluran Terluas. Ini digunakan untuk memberi tahu pembaca barcode detail tentang referensi yang digunakan untuk mengenkode data dalam simbol. Implementasi saat ini mencakup semua pengkodean charset yang dikenal. Tidak didukung oleh MicroQR.

### getEncodeGS1SeparatorInByteMode() {#getencodegs1separatorinbytemode}

Mendapatkan atau mengatur nilai yang menunjukkan apakah karakter khusus GS1 harus dikodekan dalam mode Byte untuk barcode QR dan RectMicroQR. Jika false, pemisah GS1 dapat dikodekan sebagai '%' dalam mode Alfanumerik sesuai spesifikasi QR. Jika true, pemisah grup GS1 dikodekan dalam mode Byte sebagai karakter 0x1D, dan karakter '%' juga dikodekan dalam mode Byte untuk mempertahankannya sebagai data. Opsi ini dapat meningkatkan kompatibilitas dengan decoder yang mengharapkan pemisah grup GS1 pada tingkat byte dan mencegah karakter data '%' diinterpretasikan sebagai pemisah GS1.

**Returns:** a value indicating whether GS1 special characters should be encoded in Byte mode for QR and RectMicroQR barcodes.

### getEncodeMode() {#getencodemode}

Tipe simbol QR dari mode enkoding BarCode. Nilai default: QREncodeMode.Auto.

### getErrorLevel() {#geterrorlevel}

Tingkat koreksi kesalahan Reed-Solomon untuk barcode QR, MicroQR, dan RectMicroQR. Dari rendah ke tinggi: LevelL, LevelM, LevelQ, LevelH. Lihat QRErrorLevel.

### getMicroQRVersion() {#getmicroqrversion}

Versi MicroQR Code. Dari versi M1 hingga versi M4. Nilai default adalah MicroQRVersion.Auto.

### getQrECIEncoding() {#getqreciencoding}

> **Deprecated.** See method description for replacement.

Pengidentifikasi Interpretasi Saluran Diperluas. Ini digunakan untuk memberi tahu pembaca kode batang detail tentang referensi yang digunakan untuk mengenkode data dalam simbol. Implementasi saat ini terdiri dari semua pengkodean charset yang dikenal luas.

### getQrEncodeMode() {#getqrencodemode}

Tipe simbol QR dari mode enkoding BarCode. Nilai default: QREncodeMode.AUTO.

### getQrEncodeType() {#getqrencodetype}

> **Deprecated.** See method description for replacement.

Mode pemilih QR / MicroQR. Pilih ForceQR untuk simbol QR standar, Auto untuk MicroQR.

### getQrErrorLevel() {#getqrerrorlevel}

> **Deprecated.** See method description for replacement.

Tingkat koreksi kesalahan Reed-Solomon untuk barcode QR. Dari rendah ke tinggi: LEVEL_L, LEVEL_M, LEVEL_Q, LEVEL_H. lihat QRErrorLevel.

### getQrVersion() {#getqrversion}

> **Deprecated.** See method description for replacement.

Versi QR Code. Dari Version1 hingga Version40 untuk QR code dan dari M1 hingga M4 untuk MicroQr. Nilai default adalah QRVersion.AUTO.

### getRectMicroQrVersion() {#getrectmicroqrversion}

Versi RectMicroQR Code. Dari versi R7x59 hingga versi R17x139. Nilai default adalah RectMicroQRVersion.Auto.

### getStructuredAppend() {#getstructuredappend}

Parameter QR structured append.

### getVersion() {#getversion}

Versi QR Code. Dari Version1 hingga Version40. Nilai default adalah QRVersion.Auto.

### setAspectRatio() {#setaspectratio}

Rasio Tinggi/Lebar modul BarCode 2D.

### setECIEncoding() {#seteciencoding}

Identifier Interpretasi Saluran Terluas. Ini digunakan untuk memberi tahu pembaca barcode detail tentang referensi yang digunakan untuk mengenkode data dalam simbol. Implementasi saat ini mencakup semua pengkodean charset yang dikenal. Tidak didukung oleh MicroQR.

### setEncodeGS1SeparatorInByteMode(value) {#setencodegs1separatorinbytemode}

Mendapatkan atau mengatur nilai yang menunjukkan apakah karakter khusus GS1 harus dikodekan dalam mode Byte untuk barcode QR dan RectMicroQR. Jika false, pemisah GS1 dapat dikodekan sebagai '%' dalam mode Alfanumerik sesuai spesifikasi QR. Jika true, pemisah grup GS1 dikodekan dalam mode Byte sebagai karakter 0x1D, dan karakter '%' juga dikodekan dalam mode Byte untuk mempertahankannya sebagai data. Opsi ini dapat meningkatkan kompatibilitas dengan decoder yang mengharapkan pemisah grup GS1 pada tingkat byte dan mencegah karakter data '%' diinterpretasikan sebagai pemisah GS1.

| Parameter | Deskripsi |
| --- | --- |
| nilai | nilai yang menunjukkan apakah karakter khusus GS1 harus dikodekan dalam mode Byte untuk barcode QR dan RectMicroQR. |

### setEncodeMode() {#setencodemode}

Tipe simbol QR dari mode enkoding BarCode. Nilai default: QREncodeMode.Auto.

### setErrorLevel() {#seterrorlevel}

Tingkat koreksi kesalahan Reed-Solomon untuk barcode QR, MicroQR, dan RectMicroQR. Dari rendah ke tinggi: LevelL, LevelM, LevelQ, LevelH. Lihat QRErrorLevel.

### setMicroQRVersion() {#setmicroqrversion}

Versi MicroQR Code. Dari versi M1 hingga versi M4. Nilai default adalah MicroQRVersion.Auto.

### setQrECIEncoding() {#setqreciencoding}

> **Deprecated.** See method description for replacement.

Pengidentifikasi Interpretasi Saluran Diperluas. Ini digunakan untuk memberi tahu pembaca kode batang detail tentang referensi yang digunakan untuk mengenkode data dalam simbol. Implementasi saat ini terdiri dari semua pengkodean charset yang dikenal luas.

### setQrEncodeMode() {#setqrencodemode}

> **Deprecated.** See method description for replacement.

Tipe simbol QR dari mode enkoding BarCode. Nilai default: QREncodeMode.AUTO.

### setQrEncodeType() {#setqrencodetype}

> **Deprecated.** See method description for replacement.

Mode pemilih QR / MicroQR. Pilih ForceQR untuk simbol QR standar, Auto untuk MicroQR.

### setQrErrorLevel() {#setqrerrorlevel}

> **Deprecated.** See method description for replacement.

Tingkat koreksi kesalahan Reed-Solomon untuk barcode QR. Dari rendah ke tinggi: LEVEL_L, LEVEL_M, LEVEL_Q, LEVEL_H. lihat QRErrorLevel.

### setQrVersion() {#setqrversion}

> **Deprecated.** See method description for replacement.

Versi QR Code. Dari Version1 hingga Version40 untuk QR code dan dari M1 hingga M4 untuk MicroQr. Nilai default adalah QRVersion.AUTO.

### setRectMicroQrVersion() {#setrectmicroqrversion}

Versi RectMicroQR Code. Dari versi R7x59 hingga versi R17x139. Nilai default adalah RectMicroQRVersion.Auto.

### setStructuredAppend() {#setstructuredappend}

Parameter QR structured append.

### setVersion() {#setversion}

Versi QR Code. Dari Version1 hingga Version40. Nilai default adalah QRVersion.Auto.

### toString() {#tostring}

Mengembalikan representasi string yang dapat dibaca manusia dari QrParameters ini.

**Returns:** A string that represents this QrParameters.
