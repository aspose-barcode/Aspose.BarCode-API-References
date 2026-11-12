---
title: "BarcodeParameters"
linktitle: "BarcodeParameters"
second_title: "Referensi API Aspose.BarCode untuk Node.js via Java"
description: "Parameter generasi Barcode."
type: docs
weight: 140
url: /id/nodejs/aspose.barcode/barcodeparameters/
---

## BarcodeParameters class

Parameter generasi Barcode.

```js
new BarcodeParameters()
```

## Metode

| Nama | Deskripsi |
| --- | --- |
| [getAustralianPost()](#getaustralianpost) | Parameter barcode AustralianPost. |
| [getAztec()](#getaztec) | Parameter Aztec. |
| [getBarColor()](#getbarcolor) | Warna bar. |
| [getBarHeight()](#getbarheight) | Tinggi bar kode batang 1D dalam nilai Unit. Diabaikan jika properti AutoSizeMode disetel ke AutoSizeMode.NEAREST atau AutoSizeMo |
| [getBarWidthReduction()](#getbarwidthreduction) | Dapatkan nilai pengurangan bar yang digunakan untuk mengkompensasi penyebaran tinta saat mencetak. |
| [getChecksumAlwaysShow()](#getchecksumalwaysshow) | Selalu tampilkan digit checksum dalam teks yang dapat dibaca manusia untuk kode batang Code128 dan GS1Code128. |
| [getCodabar()](#getcodabar) | Parameter Codabar. |
| [getCodablock()](#getcodablock) | Parameter Codablock. |
| [getCode16K()](#getcode16k) | Parameter Code16K. |
| [getCode128()](#getcode128) | Parameter Code128. |
| [getCodeTextParameters()](#getcodetextparameters) | Parameter Codetext. |
| [getCoupon()](#getcoupon) | Parameter kupon. Digunakan untuk UpcaGs1DatabarCoupon, UpcaGs1Code128Coupon. |
| [getDataBar()](#getdatabar) | Parameter Databar. |
| [getDataMatrix()](#getdatamatrix) | Parameter DataMatrix. |
| [getDotCode()](#getdotcode) | Parameter DotCode. |
| [getEnableEscape()](#getenableescape) | Menunjukkan apakah karakter "\\" dijelaskan sebagai karakter escape dalam properti CodeText. Digunakan untuk Pdf417, DataMatrix, C |
| [getFilledBars()](#getfilledbars) | Mendapatkan nilai yang menunjukkan apakah bar terisi. Hanya untuk kode batang 1D. Nilai default: true. |
| [getGS1CompositeBar()](#getgs1compositebar) | Parameter GS1 Composite Bar. Contoh ini menunjukkan cara membuat dan menyimpan gambar GS1 Composite Bar. Perhatikan bahwa codetext 1D |
| [getHanXin()](#gethanxin) | Parameter HanXin. |
| [getITF()](#getitf) | Parameter ITF. |
| [getMaxiCode()](#getmaxicode) | Parameter MaxiCode. |
| [getPadding()](#getpadding) | Padding kode batang. Nilai default: 5pt 5pt 5pt 5pt. |
| [getPatchCode()](#getpatchcode) | Parameter PatchCode. |
| [getPdf417()](#getpdf417) | Parameter PDF417. |
| [getPostal()](#getpostal) | Parameter pos. Digunakan untuk Postnet, Planet. |
| [getQR()](#getqr) | Parameter QR. |
| [getSupplement()](#getsupplement) | Parameter supplement. Digunakan untuk Interleaved2of5, Standard2of5, EAN13, EAN8, UPCA, UPCE, ISBN, ISSN, ISMN. |
| [getWideNarrowRatio()](#getwidenarrowratio) | Rasio bar lebar terhadap bar sempit. Nilai default: 3, yaitu bar lebar 3 kali lebar bar sempit. Digunakan untuk ITF, |
| [getXDimension()](#getxdimension) | x-dimension adalah lebar terkecil unit bar BarCode atau spasi. Meningkatkan ini akan meningkatkan seluruh barcode i |
| [isChecksumEnabled()](#ischecksumenabled) | Aktifkan checksum selama pembuatan kode batang 1D. Default diperlakukan sebagai Ya untuk simbol yang harus mengandung checksum, sebagai N |
| [setBarColor(value)](#setbarcolor) | Warna bar. |
| [setBarHeight()](#setbarheight) | Tinggi bar kode batang 1D dalam nilai Unit. Diabaikan jika properti AutoSizeMode disetel ke AutoSizeMode.NEAREST atau AutoSizeMo |
| [setBarWidthReduction()](#setbarwidthreduction) | Mengatur nilai pengurangan bar yang digunakan untuk mengkompensasi penyebaran tinta saat mencetak. |
| [setChecksumAlwaysShow()](#setchecksumalwaysshow) | Selalu tampilkan digit checksum dalam teks yang dapat dibaca manusia untuk kode batang Code128 dan GS1Code128. |
| [setChecksumEnabled()](#setchecksumenabled) | Aktifkan checksum selama pembuatan kode batang 1D. Default diperlakukan sebagai Ya untuk simbol yang harus mengandung checksum, sebagai N |
| [setEnableEscape()](#setenableescape) | Menunjukkan apakah karakter "\\" dijelaskan sebagai karakter escape dalam properti CodeText. Digunakan untuk Pdf417, DataMatrix, C |
| [setFilledBars()](#setfilledbars) | Mengatur nilai yang menunjukkan apakah bar terisi. Hanya untuk kode batang 1D. Nilai default: true. |
| [setGS1CompositeBar()](#setgs1compositebar) | Parameter GS1 Composite Bar. Contoh ini menunjukkan cara membuat dan menyimpan gambar GS1 Composite Bar. Perhatikan bahwa codetext 1D |
| [setPadding()](#setpadding) | Padding kode batang. Nilai default: 5pt 5pt 5pt 5pt. |
| [setWideNarrowRatio()](#setwidenarrowratio) | Rasio bar lebar terhadap bar sempit. Nilai default: 3, yaitu bar lebar 3 kali lebar bar sempit. Digunakan untuk ITF, P |
| [setXDimension()](#setxdimension) | x-dimension adalah lebar terkecil unit bar BarCode atau spasi. Meningkatkan ini akan meningkatkan seluruh barcode i |

### getAustralianPost() {#getaustralianpost}

Parameter barcode AustralianPost.

### getAztec() {#getaztec}

Parameter Aztec.

### getBarColor() {#getbarcolor}

Warna bar.

**Returns:** value of Bar color Default value: #000000

### getBarHeight() {#getbarheight}

Tinggi bar kode batang 1D dalam nilai Unit. Diabaikan jika properti AutoSizeMode disetel ke AutoSizeMode.NEAREST atau AutoSizeMode.INTERPOLATION.

**Throws:** BarcodeException

### getBarWidthReduction() {#getbarwidthreduction}

Dapatkan nilai pengurangan bar yang digunakan untuk mengkompensasi penyebaran tinta saat mencetak.

**Returns:** Unit value of BarWidthReduction

### getChecksumAlwaysShow() {#getchecksumalwaysshow}

Selalu tampilkan digit checksum dalam teks yang dapat dibaca manusia untuk kode batang Code128 dan GS1Code128.

### getCodabar() {#getcodabar}

Parameter Codabar.

### getCodablock() {#getcodablock}

Parameter Codablock.

### getCode16K() {#getcode16k}

Parameter Code16K.

### getCode128() {#getcode128}

Parameter Code128.

### getCodeTextParameters() {#getcodetextparameters}

Parameter Codetext.

### getCoupon() {#getcoupon}

Parameter kupon. Digunakan untuk UpcaGs1DatabarCoupon, UpcaGs1Code128Coupon.

### getDataBar() {#getdatabar}

Parameter Databar.

### getDataMatrix() {#getdatamatrix}

Parameter DataMatrix.

### getDotCode() {#getdotcode}

Parameter DotCode.

### getEnableEscape() {#getenableescape}

Menunjukkan apakah karakter "\\" dijelaskan sebagai karakter escape dalam properti CodeText. Digunakan untuk Pdf417, DataMatrix, Code128 saja. Jika EnableEscape bernilai true, "\\" akan dijelaskan sebagai karakter escape khusus. Jika tidak, "\\" berfungsi sebagai karakter normal. Aspose.BarCode mendukung memasukkan kode ascii desimal dan mnemonic untuk karakter kode kontrol ASCII. Misalnya, \013 dan \\CR mewakili CR.

### getFilledBars() {#getfilledbars}

Mendapatkan nilai yang menunjukkan apakah bar terisi. Hanya untuk kode batang 1D. Nilai default: true.

### getGS1CompositeBar() {#getgs1compositebar}

Parameter GS1 Composite Bar. Contoh ini menunjukkan cara membuat dan menyimpan gambar GS1 Composite Bar. Perhatikan bahwa codetext 1D dan codetext 2D dipisahkan oleh simbol '/'

**Returns:** GS1CompositeBarParameters GS1 Composite Bar parameters.

**Example:**

```js
let codetext = "(01)03212345678906/(21)A1B2C3D4E5F6G7H8";
let generator = new BarcodeGenerator(EncodeTypes.GS_1_COMPOSITE_BAR, codetext);

generator.getParameters().getBarcode().getGS1CompositeBar().setLinearComponentType(EncodeTypes.GS_1_CODE_128);
generator.getParameters().getBarcode().getGS1CompositeBar().setTwoDComponentType(TwoDComponentType.CC_A);

// Aspect ratio of 2D component
generator.getParameters().getBarcode().getPdf417().setAspectRatio(3);

// X-Dimension of 1D and 2D components
generator.getParameters().getBarcode().getXDimension().setPixels(3);
///
// Height of 1D component
generator.getParameters().getBarcode().getBarHeight().setPixels(100);
///
generator.save("test.png", BarcodeImageFormat.PNG);
```

### getHanXin() {#gethanxin}

Parameter HanXin.

### getITF() {#getitf}

Parameter ITF.

### getMaxiCode() {#getmaxicode}

Parameter MaxiCode.

### getPadding() {#getpadding}

Padding kode batang. Nilai default: 5pt 5pt 5pt 5pt.

### getPatchCode() {#getpatchcode}

Parameter PatchCode.

### getPdf417() {#getpdf417}

Parameter PDF417.

### getPostal() {#getpostal}

Parameter pos. Digunakan untuk Postnet, Planet.

### getQR() {#getqr}

Parameter QR.

### getSupplement() {#getsupplement}

Parameter supplement. Digunakan untuk Interleaved2of5, Standard2of5, EAN13, EAN8, UPCA, UPCE, ISBN, ISSN, ISMN.

### getWideNarrowRatio() {#getwidenarrowratio}

Rasio bar lebar terhadap bar sempit. Nilai default: 3, yaitu bar lebar 3 kali lebar bar sempit. Digunakan untuk ITF, PZN, PharmaCode, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, IATA2of5, VIN, DeutschePost, OPC, Code32, DataLogic2of5, PatchCode, Code39Extended, Code39Standard. Nilai parameter WideNarrowRatio kurang dari atau sama dengan 0.

### getXDimension() {#getxdimension}

x-dimension adalah lebar terkecil unit bar BarCode atau spasi. Meningkatkan ini akan meningkatkan lebar seluruh gambar barcode. Diabaikan jika properti AutoSizeMode disetel ke AutoSizeMode.NEAREST atau AutoSizeMode.INTERPOLATION.

### isChecksumEnabled() {#ischecksumenabled}

Aktifkan checksum selama pembuatan kode batang 1D. Default dianggap Ya untuk simbol yang harus mengandung checksum, dan Tidak dimana checksum hanya mungkin. Checksum memungkinkan: Code39 Standard/Extended, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, DeutschePostIdentcode, DeutschePostLeitcode, VIN, Codabar. Checksum selalu digunakan: Simbol lainnya

### setBarColor(value) {#setbarcolor}

Warna bar.

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | String | untuk warna Bar nilai default: #000000. |

### setBarHeight() {#setbarheight}

Tinggi bar kode batang 1D dalam nilai Unit. Diabaikan jika properti AutoSizeMode disetel ke AutoSizeMode.NEAREST atau AutoSizeMode.INTERPOLATION.

**Throws:** BarcodeException

### setBarWidthReduction() {#setbarwidthreduction}

Mengatur nilai pengurangan bar yang digunakan untuk mengkompensasi penyebaran tinta saat mencetak.

### setChecksumAlwaysShow() {#setchecksumalwaysshow}

Selalu tampilkan digit checksum dalam teks yang dapat dibaca manusia untuk kode batang Code128 dan GS1Code128.

### setChecksumEnabled() {#setchecksumenabled}

Aktifkan checksum selama pembuatan kode batang 1D. Default dianggap Ya untuk simbol yang harus mengandung checksum, dan Tidak dimana checksum hanya mungkin. Checksum memungkinkan: Code39 Standard/Extended, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, DeutschePostIdentcode, DeutschePostLeitcode, VIN, Codabar. Checksum selalu digunakan: Simbol lainnya

### setEnableEscape() {#setenableescape}

Menunjukkan apakah karakter "\" dijelaskan sebagai karakter escape dalam properti CodeText. Digunakan hanya untuk Pdf417, DataMatrix, Code128. Jika EnableEscape bernilai true, "\" akan dijelaskan sebagai karakter escape khusus. Jika tidak, "\" berfungsi sebagai karakter normal. Aspose.BarCode mendukung kode ascii desimal dan mnemonic untuk karakter kontrol ASCII. Misalnya, \013 dan \\CR mewakili CR.

### setFilledBars() {#setfilledbars}

Mengatur nilai yang menunjukkan apakah bar terisi. Hanya untuk kode batang 1D. Nilai default: true.

### setGS1CompositeBar() {#setgs1compositebar}

Parameter GS1 Composite Bar. Contoh ini menunjukkan cara membuat dan menyimpan gambar GS1 Composite Bar. Perhatikan bahwa codetext 1D dan codetext 2D dipisahkan oleh simbol '/'

**Example:**

```js
let codetext = "(01)03212345678906/(21)A1B2C3D4E5F6G7H8";
let generator = new BarcodeGenerator(EncodeTypes.GS_1_COMPOSITE_BAR, codetext);

generator.getParameters().getBarcode().getGS1CompositeBar().setLinearComponentType(EncodeTypes.GS_1_CODE_128);
generator.getParameters().getBarcode().getGS1CompositeBar().setTwoDComponentType(TwoDComponentType.CC_A);

// Aspect ratio of 2D component
generator.getParameters().getBarcode().getPdf417().setAspectRatio(3);

// X-Dimension of 1D and 2D components
generator.getParameters().getBarcode().getXDimension().setPixels(3);

// Height of 1D component
generator.getParameters().getBarcode().getBarHeight().setPixels(100);

generator.save("test.png", BarcodeImageFormat.PNG);
```

### setPadding() {#setpadding}

Padding kode batang. Nilai default: 5pt 5pt 5pt 5pt.

### setWideNarrowRatio() {#setwidenarrowratio}

Rasio bar lebar terhadap bar sempit. Nilai default: 3, artinya bar lebar 3 kali lebih lebar daripada bar sempit. Digunakan untuk ITF, PZN, PharmaCode, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, IATA2of5, VIN, DeutschePost, OPC, Code32, DataLogic2of5, PatchCode, Code39Extended, Code39Standard. Nilai parameter WideNarrowRatio kurang dari atau sama dengan 0.

### setXDimension() {#setxdimension}

x-dimension adalah lebar terkecil unit bar BarCode atau spasi. Meningkatkan ini akan meningkatkan lebar seluruh gambar barcode. Diabaikan jika properti AutoSizeMode disetel ke AutoSizeMode.NEAREST atau AutoSizeMode.INTERPOLATION.

**Throws:** BarcodeException
