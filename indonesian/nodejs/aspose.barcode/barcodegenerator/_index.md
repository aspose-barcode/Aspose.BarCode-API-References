---
title: "BarcodeGenerator"
linktitle: "BarcodeGenerator"
second_title: "Referensi API Aspose.BarCode untuk Node.js via Java"
description: "BarcodeGenerator untuk pembuatan gambar barcode backend."
type: docs
weight: 130
url: /id/nodejs/aspose.barcode/barcodegenerator/
---

## BarcodeGenerator class

BarcodeGenerator untuk pembuatan gambar barcode backend. Simbol yang didukung: 1D: Codabar, Code11, Code128, Code39Standard, Code39Extended, Code93Standard, Code93Extended, EAN13, EAN8, Interleaved2of5, MSI, Standard2of5, UPCA, UPCE, ISBN, GS1Code128, Postnet, Planet, EAN14, SCC14, SSCC18, ITF14, SingaporePost ... 2D: Aztec, DataMatrix, PDf417, QR code ...

```js
new BarcodeGenerator(encodeType, codeText)
```

Konstruktor BarcodeGenerator.

| Parameter | Deskripsi |
| --- | --- |
| encodeType | Tipe simbolologi barcode. Gunakan kelas EncodeTypes untuk mengatur simbolologi |
| codeText | Teks yang akan dienkode. |

**Throws:** BarcodeException

**Example:**

```js
// This sample shows how to create and save a barcode image.
let encode_type = EncodeTypes.CODE_128;
let generator = new BarcodeGenerator(encode_type);
generator.setCodeText("123ABC");
```

## Metode

| Nama | Deskripsi |
| --- | --- |
| [importFromXml(filePath)](#importfromxml) *(static)* | Mengimpor properti BarCode dari file xml yang ditentukan dan membuat instance BarcodeGenerator. |
| [exportToXml(filePath)](#exporttoxml) | Mengekspor properti BarCode ke file xml yang ditentukan. |
| [generateBarCodeImage(format)](#generatebarcodeimage) | Hasilkan gambar barcode dengan pengaturan saat ini. Contoh ini menunjukkan cara membuat dan menyimpan gambar barcode. |
| [getBarcodeType()](#getbarcodetype) | Tipe simbolologi barcode. |
| [getCodeText()](#getcodetext) | Teks yang akan dienkode. |
| [getParameters()](#getparameters) | Parameter generasi. |
| [save(filePath, format)](#save) | Simpan gambar barcode ke file tertentu dalam format tertentu. |
| [setBarcodeType()](#setbarcodetype) | Tipe simbolologi barcode. |
| [setCodeText(codeText, encoding, insertBOM)](#setcodetext) | Mengenkripsi Unicode `codeText ` menjadi urutan byte menggunakan `encoding `. UTF-8 adalah yang paling umum digunakan en |

### importFromXml(filePath) (static) {#importfromxml}

Mengimpor properti BarCode dari file xml yang ditentukan dan membuat instance BarcodeGenerator.

| Parameter | Deskripsi |
| --- | --- |
| filePath | Nama file |

**Returns:** BarcodeGenerator instance

### exportToXml(filePath) {#exporttoxml}

Mengekspor properti BarCode ke file xml yang ditentukan.

| Parameter | Deskripsi |
| --- | --- |
| filePath | File xml |

**Returns:** Whether or not export completed successfully. Returns True in case of success; False Otherwise

**Throws:** IOException

### generateBarCodeImage(format) {#generatebarcodeimage}

Hasilkan gambar barcode dengan pengaturan saat ini. Contoh ini menunjukkan cara membuat dan menyimpan gambar barcode.

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| format | BarCodeImageFormat | Nilai BarCodeImageFormat (PNG, BMP, JPEG, GIF) |

**Returns:** String — base64 representation of image.

**Example:**

```js
let generator = new BarCodeGenerator(EncodeTypes.CODE_128);
let image = generator.generateBarCodeImage(BarCodeImageFormat.GIF);
```

### getBarcodeType() {#getbarcodetype}

Tipe simbolologi barcode.

### getCodeText() {#getcodetext}

Teks yang akan dienkode.

### getParameters() {#getparameters}

Parameter generasi.

**Returns:** BaseGenerationParameters

### save(filePath, format) {#save}

Simpan gambar barcode ke file tertentu dalam format tertentu.

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| filePath | String | Jalur untuk disimpan. |
| format | BarCodeImageFormat | Nilai BarCodeImageFormat (PNG, BMP, JPEG, GIF) |

**Example:**

```js
let generator = new BarCodeGenerator(EncodeTypes.CODE_128);
generator.save("file path", BarCodeImageFormat.GIF);
```

### setBarcodeType() {#setbarcodetype}

Tipe simbolologi barcode.

### setCodeText(codeText, encoding, insertBOM) {#setcodetext}

Mengenkripsi Unicode `codeText ` menjadi urutan byte menggunakan `encoding ` yang ditentukan. UTF-8 adalah encoding yang paling umum digunakan. Jika encoding mendukungnya dan `insertBOM ` disetel ke `true`, fungsi ini menyertakan `byte order mark (BOM) `. Fungsi ini hanya ditujukan untuk penggunaan dengan barcode 2D saja (mis., Aztec, QR, DataMatrix, PDF417, MaxiCode, DotCode, HanXin, RectMicroQR, dll.). Ini memungkinkan enkoding manual teks Unicode menggunakan encoding nasional atau khusus; namun, metode ini dianggap usang dalam aplikasi modern. Untuk kasus penggunaan modern, encoding `ECI ` direkomendasikan untuk data Unicode. Menggunakan fungsi ini dengan barcode 1D, barcode yang sesuai GS1 (termasuk 2D), atau barcode HIBC (termasuk 2D) tidak didukung oleh standar barcode yang bersangkutan dan dapat menghasilkan hasil yang tidak dapat diprediksi. Contoh ini menunjukkan cara menggunakan `SetCodeText` dengan atau tanpa BOM untuk barcode 2D. //Encode codetext using UTF-8 with BOM let gen = new BarcodeGenerator(EncodeTypes.QR, null); gen.setCodeText("車種名", "UTF-8", true); gen.save("barcode.png", BarCodeImageFormat.PNG); let reader = new BarCodeReader("barcode.png", null, DecodeType.QR); let results = reader.readBarCodes(); for(let i = 0; i < results.length; i++) { let result = results[i]; console.log("BarCode CodeText: " + result.getCodeText()); } //Encode codetext using UTF-8 without BOM let gen = new BarcodeGenerator(EncodeTypes.QR, null); gen.setCodeText("車種名", "UTF-8", false); gen.save("barcode.png", BarCodeImageFormat.PNG); let reader = new BarCodeReader("barcode.png", null, DecodeType.QR); let results = reader.readBarCodes(); for(let i = 0; i < results.length; i++) { let result = results[i]; console.log("BarCode CodeText: " + result.getCodeText()); }

| Parameter | Deskripsi |
| --- | --- |
| codeText | String CodeText |
| enkoding | Encoding yang diterapkan |
| insertBOM | Menunjukkan apakah akan menyisipkan byte order mark (BOM) ketika encoding yang ditentukan mendukungnya (mis., UTF-8, UTF-16, UTF-32). Jika disetel ke `true`, BOM akan ditambahkan; jika `false`, BOM akan dihilangkan meskipun encoding biasanya menggunakannya. |
