---
title: "BaseGenerationParameters"
linktitle: "BaseGenerationParameters"
second_title: "Referensi API Aspose.BarCode untuk Node.js via Java"
description: "Parameter generasi gambar Barcode."
type: docs
weight: 160
url: /id/nodejs/aspose.barcode/basegenerationparameters/
---

## BaseGenerationParameters class

Parameter generasi gambar Barcode.

```js
new BaseGenerationParameters()
```

## Metode

| Nama | Deskripsi |
| --- | --- |
| [getAutoSizeMode()](#getautosizemode) | Menentukan berbagai jenis mode penyesuaian ukuran otomatis. Nilai default: AutoSizeMode.NONE. |
| [getBackColor()](#getbackcolor) | Warna latar belakang gambar barcode. Nilai default: #FFFFFF |
| [getBarcode()](#getbarcode) | Mendapatkan BarcodeParameters yang berisi semua properti barcode. |
| [getBorder()](#getborder) | Mendapatkan BorderParameters yang berisi semua properti konfigurasi untuk batas barcode. |
| [getCaptionAbove()](#getcaptionabove) | Keterangan di Atas gambar BarCode. Lihat CaptionParameters. |
| [getCaptionBelow()](#getcaptionbelow) | Keterangan di Bawah gambar BarCode. Lihat CaptionParameters. |
| [getImage()](#getimage) | Parameter gambar. Lihat ImageParameters. |
| [getImageHeight()](#getimageheight) | Tinggi gambar BarCode ketika properti AutoSizeMode diatur ke AutoSizeMode.NEAREST atau AutoSizeMode.INTERPOLATION. |
| [getImageWidth()](#getimagewidth) | Lebar gambar BarCode ketika properti AutoSizeMode diatur ke AutoSizeMode.NEAREST atau AutoSizeMode.INTERPOLATION. |
| [getResolution()](#getresolution) | Mendapatkan resolusi gambar BarCode. Satu nilai untuk kedua dimensi. Nilai default: 96 dpi. Parameter Resolution |
| [getRotationAngle()](#getrotationangle) | Sudut rotasi gambar BarCode, diukur dalam derajat, mis. RotationAngle = 0 atau RotationAngle = 360 berarti tidak ada rotasi. Jika Ro |
| [getUseAntiAlias()](#getuseantialias) | Mendapatkan nilai yang menunjukkan apakah mode anti-aliasing digunakan untuk merender gambar |
| [setAutoSizeMode()](#setautosizemode) | Menentukan berbagai jenis mode penyesuaian ukuran otomatis. Nilai default: AutoSizeMode.NONE. |
| [setBackColor()](#setbackcolor) | Warna latar belakang gambar barcode. Nilai default: #FFFFFF |
| [setImageHeight()](#setimageheight) | Tinggi gambar BarCode ketika properti AutoSizeMode diatur ke AutoSizeMode.NEAREST atau AutoSizeMode.INTERPOLATION. |
| [setImageWidth()](#setimagewidth) | Lebar gambar BarCode ketika properti AutoSizeMode diatur ke AutoSizeMode.NEAREST atau AutoSizeMode.INTERPOLATION. |
| [setResolution()](#setresolution) | Mengatur resolusi gambar BarCode. Satu nilai untuk kedua dimensi. Nilai default: 96 dpi. Parameter Resolution |
| [setRotationAngle()](#setrotationangle) | Sudut rotasi gambar BarCode, diukur dalam derajat, mis. RotationAngle = 0 atau RotationAngle = 360 berarti tidak ada rotasi. Jika Ro |
| [setUseAntiAlias()](#setuseantialias) | Mengatur nilai yang menunjukkan apakah mode anti-aliasing digunakan untuk merender gambar |

### getAutoSizeMode() {#getautosizemode}

Menentukan berbagai jenis mode penyesuaian ukuran otomatis. Nilai default: AutoSizeMode.NONE.

### getBackColor() {#getbackcolor}

Warna latar belakang gambar barcode. Nilai default: #FFFFFF

### getBarcode() {#getbarcode}

Mendapatkan BarcodeParameters yang berisi semua properti barcode.

### getBorder() {#getborder}

Mendapatkan BorderParameters yang berisi semua properti konfigurasi untuk batas barcode.

### getCaptionAbove() {#getcaptionabove}

Keterangan di Atas gambar BarCode. Lihat CaptionParameters.

### getCaptionBelow() {#getcaptionbelow}

Keterangan di Bawah gambar BarCode. Lihat CaptionParameters.

### getImage() {#getimage}

Parameter gambar. Lihat ImageParameters.

**Returns:** ImageParameters

### getImageHeight() {#getimageheight}

Tinggi gambar BarCode ketika properti AutoSizeMode diatur ke AutoSizeMode.NEAREST atau AutoSizeMode.INTERPOLATION.

### getImageWidth() {#getimagewidth}

Lebar gambar BarCode ketika properti AutoSizeMode diatur ke AutoSizeMode.NEAREST atau AutoSizeMode.INTERPOLATION.

### getResolution() {#getresolution}

Mendapatkan resolusi gambar BarCode. Satu nilai untuk kedua dimensi. Nilai default: 96 dpi. Nilai parameter Resolution kurang dari atau sama dengan 0.

### getRotationAngle() {#getrotationangle}

Sudut rotasi gambar BarCode, diukur dalam derajat, mis. RotationAngle = 0 atau RotationAngle = 360 berarti tidak ada rotasi. Jika RotationAngle TIDAK sama dengan 90, 180, 270, atau 0, hal ini dapat meningkatkan kesulitan pemindai untuk membaca gambar . Nilai default: 0.

**Example:**

```js
//This sample shows how to create and save a BarCode image.
    let generator = new BarcodeGenerator( EncodeTypes.DATA_MATRIX);
    generator.getParameters().setRotationAngle(7);
    generator.save("test.png", BarcodeImageFormat.PNG);
```

### getUseAntiAlias() {#getuseantialias}

Mendapatkan nilai yang menunjukkan apakah mode anti-aliasing digunakan untuk merender gambar

### setAutoSizeMode() {#setautosizemode}

Menentukan berbagai jenis mode penyesuaian ukuran otomatis. Nilai default: AutoSizeMode.NONE.

### setBackColor() {#setbackcolor}

Warna latar belakang gambar barcode. Nilai default: #FFFFFF

### setImageHeight() {#setimageheight}

Tinggi gambar BarCode ketika properti AutoSizeMode diatur ke AutoSizeMode.NEAREST atau AutoSizeMode.INTERPOLATION.

### setImageWidth() {#setimagewidth}

Lebar gambar BarCode ketika properti AutoSizeMode diatur ke AutoSizeMode.NEAREST atau AutoSizeMode.INTERPOLATION.

### setResolution() {#setresolution}

Mengatur resolusi gambar BarCode. Satu nilai untuk kedua dimensi. Nilai default: 96 dpi. Nilai parameter Resolution kurang dari atau sama dengan 0.

### setRotationAngle() {#setrotationangle}

Sudut rotasi gambar BarCode, diukur dalam derajat, mis. RotationAngle = 0 atau RotationAngle = 360 berarti tidak ada rotasi. Jika RotationAngle TIDAK sama dengan 90, 180, 270, atau 0, hal ini dapat meningkatkan kesulitan pemindai untuk membaca gambar. Nilai default: 0.

**Example:**

```js
//This sample shows how to create and save a BarCode image.
    let generator = new BarcodeGenerator( EncodeTypes.DATA_MATRIX);
    generator.getParameters().setRotationAngle(7);
    generator.save("test.png", BarcodeImageFormat.PNG);
```

### setUseAntiAlias() {#setuseantialias}

Mengatur nilai yang menunjukkan apakah mode anti-aliasing digunakan untuk merender gambar
