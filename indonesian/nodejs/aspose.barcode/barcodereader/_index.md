---
title: "BarCodeReader"
linktitle: "BarCodeReader"
second_title: "Referensi API Aspose.BarCode untuk Node.js via Java"
description: "BarCodeReader membungkus sebuah gambar yang mungkin berisi satu atau beberapa barcode, kemudian dapat melakukan operasi ReadBarCodes untuk mendeteksi barcode."
type: docs
weight: 90
url: /id/nodejs/aspose.barcode/barcodereader/
---

## BarCodeReader class

BarCodeReader membungkus sebuah gambar yang mungkin berisi satu atau beberapa barcode, kemudian dapat melakukan operasi ReadBarCodes untuk mendeteksi barcode.

```js
new BarCodeReader(image, areas, decodeTypes)
```

Menginisialisasi sebuah instance baru dari BarCodeReader

| Parameter | Deskripsi |
| --- | --- |
| gambar | dienkode sebagai string base64 atau path ke gambar |
| area | array objek bertipe Rectangle |
| decodeTypes | array objek berdasarkan DecodeType |

**Example:**

```js
//This sample shows how to detect Code39 and Code128 barcodes.
let reader = new BarCodeReader("test.png", null,  [DecodeType.CODE_39, DecodeType.CODE_128]);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
   let result = results[i];
   console.log("BarCode Type: " + result.getCodeTypeName());
   console.log("BarCode CodeText: " + result.getCodeText());
}
```

## Metode

| Nama | Deskripsi |
| --- | --- |
| [importFromXml(xmlFile)](#importfromxml) *(static)* | Mengekspor properti BarCode ke file xml yang ditentukan |
| [containsAny()](#containsany) | Menentukan apakah salah satu tipe decode yang diberikan termasuk ke dalam |
| [exportToXml(xmlFile)](#exporttoxml) | Mengekspor properti BarCode ke file xml yang ditentukan |
| [getBarCodeReadType()](#getbarcodereadtype) | Mendapatkan tipe decode dari proses decoding barcode input |
| [getBarcodeSettings()](#getbarcodesettings) | Parameter decoding BarCode utama. Berisi parameter yang memengaruhi data yang dikenali. |
| [getFoundBarCodes()](#getfoundbarcodes) | Mendapatkan array BarCodeResult yang dikenali |
| [getFoundCount()](#getfoundcount) | Mendapatkan jumlah barcode yang dikenali |
| [getQualitySettings()](#getqualitysettings) | QualitySettings memungkinkan mengkonfigurasi kualitas dan kecepatan pengenalan secara manual. Anda dapat dengan cepat mengatur QualitySettings dengan em |
| [getTimeout()](#gettimeout) | Mendapatkan batas waktu proses pengenalan dalam milidetik. |
| [readBarCodes()](#readbarcodes) | Membaca BarCodeResult dari gambar. |
| [setBarCodeImage(imageResource, …areas)](#setbarcodeimage) | Mengatur gambar bitmap dan area untuk pengenalan. Harus dipanggil sebelum metode ReadBarCodes(). |
| [setBarCodeReadType(…types)](#setbarcodereadtype) | Mengatur array tipe SingleDecodeType untuk pengenalan. Harus dipanggil sebelum metode readBarCodes(). |
| [setQualitySettings()](#setqualitysettings) | QualitySettings memungkinkan mengkonfigurasi kualitas dan kecepatan pengenalan secara manual. Anda dapat dengan cepat mengatur QualitySettings dengan em |
| [setTimeout(value)](#settimeout) | Mengatur batas waktu proses pengenalan dalam milidetik. |

### importFromXml(xmlFile) (static) {#importfromxml}

Mengekspor properti BarCode ke file xml yang ditentukan

| Parameter | Deskripsi |
| --- | --- |
| xmlFile | Nama file |

**Returns:** Whether or not export completed successfully. Returns True in case of success; False Otherwise

### containsAny() {#containsany}

Menentukan apakah salah satu tipe decode yang diberikan termasuk ke dalam

| Parameter | Deskripsi |
| --- | --- |
| ...decodeTypes | Tipe untuk diverifikasi. |

**Returns:** bool Value is a true if any types are included into.

### exportToXml(xmlFile) {#exporttoxml}

Mengekspor properti BarCode ke file xml yang ditentukan

| Parameter | Deskripsi |
| --- | --- |
| xmlFile | Nama file |

**Returns:** Whether or not export completed successfully. Returns True in case of success; False Otherwise

### getBarCodeReadType() {#getbarcodereadtype}

Mendapatkan tipe decode dari proses decoding barcode input

**Returns:** *

### getBarcodeSettings() {#getbarcodesettings}

Parameter decoding BarCode utama. Berisi parameter yang memengaruhi data yang dikenali.

**Returns:** The main BarCode decoding parameters

### getFoundBarCodes() {#getfoundbarcodes}

Mendapatkan array BarCodeResult yang dikenali

**Returns:** recognized BarCodeResult array

**Example:**

```js
//This sample shows how to read barcodes with BarCodeReader
let reader = new BarCodeReader("test.png", null,  [ DecodeType.CODE_39, DecodeType.CODE_128 ]);
reader.readBarCodes();
for(let i = 0; reader.getFoundCount() > i; ++i)
   console.log("BarCode CodeText: " +  reader.getFoundBarCodes()[i].getCodeText());
```

### getFoundCount() {#getfoundcount}

Mendapatkan jumlah barcode yang dikenali

**Example:**

```js
//This sample shows how to read barcodes with BarCodeReader
let reader = new BarCodeReader("test.png", null,  [ DecodeType.CODE_39, DecodeType.CODE_128 ]);
reader.readBarCodes();
for(let i = 0; reader.getFoundCount() > i; ++i)
   console.log("BarCode CodeText: " + reader.getFoundBarCodes()[i].getCodeText());
Value: The recognized barcodes count
```

### getQualitySettings() {#getqualitysettings}

QualitySettings memungkinkan mengkonfigurasi kualitas pengenalan dan kecepatan secara manual. Anda dapat dengan cepat mengatur QualitySettings menggunakan preset tersemat: HighPerformance, NormalQuality, HighQuality, MaxBarCodes atau Anda dapat mengkonfigurasi opsi terpisah secara manual. Nilai default QualitySettings adalah NormalQuality.

**Returns:** QualitySettings to configure recognition quality and speed.

**Example:**

```js
//This sample shows how to use QualitySettings with BarCodeReader

let reader = new BarCodeReader("test.png", null, null);
 //set high performance mode
reader.setQualitySettings(QualitySettings.getHighPerformance());
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
  let result = results[i];
  console.log("BarCode CodeText: " + result.getCodeText());
}
```

### getTimeout() {#gettimeout}

Mendapatkan batas waktu proses pengenalan dalam milidetik.

**Returns:** The timeout.

**Example:**

```js
let reader = new BarCodeReader("test.png", null, null);
reader.setTimeout(5000);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
   let result = results[i];
   console.log("BarCode CodeText: " + result.getCodeText());
}
```

### readBarCodes() {#readbarcodes}

Membaca BarCodeResult dari gambar.

**Returns:** Returns array of recognized `BarCodeResult`s on the image. If nothing is recognized, zero array is returned.

**Example:**

```js
//This sample shows how to read barcodes with BarCodeReader
let reader = new BarCodeReader("test.png", null,  [ DecodeType.CODE_39, DecodeType.CODE_128 ]);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
   let result = results[i];
   console.log("BarCode CodeText: " + result.getCodeText());
}
let reader = new BarCodeReader("test.png", null,  [ DecodeType.CODE_39, DecodeType.CODE_128 ]);
reader.readBarCodes();
for(let i = 0; reader.getFoundCount() > i; ++i)
   console.log("BarCode CodeText: " + reader.getFoundBarCodes()[i].getCodeText());
```

### setBarCodeImage(imageResource, …areas) {#setbarcodeimage}

Mengatur gambar bitmap dan area untuk pengenalan. Harus dipanggil sebelum metode ReadBarCodes().

| Parameter | Deskripsi |
| --- | --- |
| imageResource | Gambar untuk pengenalan. |
| area | daftar area untuk pengenalan |

**Throws:** BarcodeException

**Example:**

```js
//This sample shows how to detect Code39 and Code128 barcodes.
let bmp = "test.png";
let reader = new BarCodeReader();
reader.setBarCodeReadType([ DecodeType.CODE_39, DecodeType.CODE_128 ]);
var img = new Image();
img.src = 'path_to_image';
width = img.width;
height = img.height;
reader.setBarCodeImage(bmp, new Rectangle[] { new Rectangle(0, 0, width, height) });
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
   let result = results[i];
   console.log("BarCode Type: " + result.getCodeTypeName());
   console.log("BarCode CodeText: " + result.getCodeText());
}
```

### setBarCodeReadType(…types) {#setbarcodereadtype}

Mengatur array tipe SingleDecodeType untuk pengenalan. Harus dipanggil sebelum metode readBarCodes().

| Parameter | Deskripsi |
| --- | --- |
| types | Array tipe SingleDecodeType untuk dibaca. |

**Example:**

```js
//This sample shows how to detect Code39 and Code128 barcodes.
let reader = new BarCodeReader();
reader.setBarCodeReadType([ DecodeType.CODE_39, DecodeType.CODE_128 ]);
reader.setBarCodeImage("test.png");
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
   let result = results[i];
    console.log("BarCode Type: " + result.getCodeTypeName());
    console.log("BarCode CodeText: " + result.getCodeText());
}
```

### setQualitySettings() {#setqualitysettings}

QualitySettings memungkinkan mengkonfigurasi kualitas pengenalan dan kecepatan secara manual. Anda dapat dengan cepat mengatur QualitySettings menggunakan preset tersemat: HighPerformance, NormalQuality, HighQuality, MaxBarCodes atau Anda dapat mengkonfigurasi opsi terpisah secara manual. Nilai default QualitySettings adalah NormalQuality.

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

### setTimeout(value) {#settimeout}

Mengatur batas waktu proses pengenalan dalam milidetik.

| Parameter | Deskripsi |
| --- | --- |
| nilai | Batas waktu. |

**Example:**

```js
let reader = new BarCodeReader("test.png", null, null);
reader.setTimeout(5000);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
   let result = results[i];
   console.log("BarCode CodeText: " + result.getCodeText());
}
```
