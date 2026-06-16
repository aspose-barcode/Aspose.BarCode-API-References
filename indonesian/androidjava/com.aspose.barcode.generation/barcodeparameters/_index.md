---
title: BarcodeParameters
second_title: Referensi API Aspose.BarCode untuk Android via Java
description: Parameter pembuatan barcode.
type: docs
weight: 14
url: /id/androidjava/com.aspose.barcode.generation/barcodeparameters/
---
**Inheritance:**
java.lang.Object
```
public class BarcodeParameters
```

Parameter pembuatan barcode.
## Methods

| Method | Deskripsi |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAspectRatio()](#getAspectRatio--) |  |
| [getAustralianPost()](#getAustralianPost--) | Parameter barcode AustralianPost. |
| [getAztec()](#getAztec--) | Parameter Aztec. |
| [getBarColor()](#getBarColor--) | Warna batang. |
| [getBarHeight()](#getBarHeight--) | Tinggi batang kode batang 1D dalam nilai [Unit](../../com.aspose.barcode.generation/unit). |
| [getBarWidthReduction()](#getBarWidthReduction--) | Dapatkan nilai pengurangan batang yang digunakan untuk mengkompensasi penyebaran tinta saat mencetak. |
| [getBarcodeType()](#getBarcodeType--) |  |
| [getChecksumAlwaysShow()](#getChecksumAlwaysShow--) | Selalu tampilkan digit checksum dalam teks yang dapat dibaca manusia untuk barcode Code128 dan GS1Code128. |
| [getClass()](#getClass--) |  |
| [getCodabar()](#getCodabar--) | Parameter Codabar. |
| [getCodablock()](#getCodablock--) | Parameter Codablock. |
| [getCode128()](#getCode128--) | Parameter Code128. |
| [getCode16K()](#getCode16K--) | Parameter Code16K. |
| [getCodeText()](#getCodeText--) |  |
| [getCodeTextParameters()](#getCodeTextParameters--) | Parameter teks kode. |
| [getComplexBarcode()](#getComplexBarcode--) |  |
| [getCoupon()](#getCoupon--) | Parameter kupon. |
| [getDataBar()](#getDataBar--) | Parameter Databar. |
| [getDataMatrix()](#getDataMatrix--) | Parameter DataMatrix. |
| [getDotCode()](#getDotCode--) | Parameter DotCode. |
| [getEnableEscape()](#getEnableEscape--) | Menunjukkan apakah menjelaskan karakter "\\\" sebagai karakter escape dalam properti CodeText. |
| [getFilledBars()](#getFilledBars--) | Mendapatkan nilai yang menunjukkan apakah bar terisi. |
| [getGS1CompositeBar()](#getGS1CompositeBar--) | Parameter Bar Komposit GS1. |
| [getHanXin()](#getHanXin--) | Parameter HanXin. |
| [getITF()](#getITF--) | Parameter ITF. |
| [getMaxiCode()](#getMaxiCode--) | Parameter MaxiCode. |
| [getPadding()](#getPadding--) | Padding barcode. |
| [getPatchCode()](#getPatchCode--) | Parameter PatchCode. |
| [getPdf417()](#getPdf417--) | Parameter PDF417. |
| [getPostal()](#getPostal--) | Parameter pos. |
| [getQR()](#getQR--) | Parameter QR, MicroQR, dan RectMicroQR. |
| [getSupplement()](#getSupplement--) | Parameter suplemen. |
| [getThrowExceptionWhenCodeTextIncorrect()](#getThrowExceptionWhenCodeTextIncorrect--) | Hanya untuk barcode 1D. |
| [getWideNarrowRatio()](#getWideNarrowRatio--) | Rasio bar lebar terhadap bar sempit. |
| [getXDimension()](#getXDimension--) | x-dimension adalah lebar terkecil dari unit bar atau ruang BarCode. |
| [hashCode()](#hashCode--) |  |
| [isChecksumEnabled()](#isChecksumEnabled--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBarColor(int value)](#setBarColor-int-) | Warna batang. |
| [setBarHeight(Unit value)](#setBarHeight-com.aspose.barcode.generation.Unit-) | Tinggi batang kode batang 1D dalam nilai [Unit](../../com.aspose.barcode.generation/unit). |
| [setBarWidthReduction(Unit value)](#setBarWidthReduction-com.aspose.barcode.generation.Unit-) | Mengatur nilai pengurangan bar yang digunakan untuk mengkompensasi penyebaran tinta saat mencetak. |
| [setChecksumAlwaysShow(boolean value)](#setChecksumAlwaysShow-boolean-) | Selalu tampilkan digit checksum dalam teks yang dapat dibaca manusia untuk barcode Code128 dan GS1Code128. |
| [setChecksumEnabled(EnableChecksum value)](#setChecksumEnabled-com.aspose.barcode.generation.EnableChecksum-) |  |
| [setCodeText(String value)](#setCodeText-java.lang.String-) |  |
| [setEnableEscape(boolean value)](#setEnableEscape-boolean-) | Menunjukkan apakah menjelaskan karakter "\\\" sebagai karakter escape dalam properti CodeText. |
| [setFilledBars(boolean value)](#setFilledBars-boolean-) | Mengatur nilai yang menunjukkan apakah bar terisi. |
| [setGS1CompositeBar(GS1CompositeBarParameters value)](#setGS1CompositeBar-com.aspose.barcode.generation.GS1CompositeBarParameters-) | Parameter Bar Komposit GS1. |
| [setThrowExceptionWhenCodeTextIncorrect(boolean value)](#setThrowExceptionWhenCodeTextIncorrect-boolean-) | Hanya untuk barcode 1D. |
| [setWideNarrowRatio(float value)](#setWideNarrowRatio-float-) | Rasio bar lebar terhadap bar sempit. |
| [setXDimension(Unit value)](#setXDimension-com.aspose.barcode.generation.Unit-) | x-dimension adalah lebar terkecil dari unit bar atau ruang BarCode. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getAspectRatio() {#getAspectRatio--}
```
public final float getAspectRatio()
```




**Returns:**
float
### getAustralianPost() {#getAustralianPost--}
```
public final AustralianPostParameters getAustralianPost()
```


Parameter barcode AustralianPost.

**Returns:**
[AustralianPostParameters](../../com.aspose.barcode.generation/australianpostparameters)
### getAztec() {#getAztec--}
```
public final AztecParameters getAztec()
```


Parameter Aztec.

**Returns:**
[AztecParameters](../../com.aspose.barcode.generation/aztecparameters)
### getBarColor() {#getBarColor--}
```
public final int getBarColor()
```


Warna bar. Nilai default: Color.Black.

**Returns:**
int
### getBarHeight() {#getBarHeight--}
```
public final Unit getBarHeight()
```


Tinggi bar barcode 1D dalam nilai [Unit](../../com.aspose.barcode.generation/unit). Diabaikan jika properti BaseGenerationParameters.AutoSizeMode ([BaseGenerationParameters.getAutoSizeMode](../../com.aspose.barcode.generation/basegenerationparameters\\#getAutoSizeMode)/[BaseGenerationParameters.setAutoSizeMode](../../com.aspose.barcode.generation/basegenerationparameters\\#setAutoSizeMode)) disetel ke AutoSizeMode.Nearest atau AutoSizeMode.Interpolation.

**Returns:**
[Unit](../../com.aspose.barcode.generation/unit)
### getBarWidthReduction() {#getBarWidthReduction--}
```
public final Unit getBarWidthReduction()
```


Dapatkan nilai pengurangan bar yang digunakan untuk mengkompensasi penyebaran tinta saat mencetak. Nilai default: 0

**Returns:**
[Unit](../../com.aspose.barcode.generation/unit) - bars reduction value that is used to compensate ink spread while printing.
### getBarcodeType() {#getBarcodeType--}
```
public final BaseEncodeType getBarcodeType()
```




**Returns:**
[BaseEncodeType](../../com.aspose.barcode.generation/baseencodetype)
### getChecksumAlwaysShow() {#getChecksumAlwaysShow--}
```
public final boolean getChecksumAlwaysShow()
```


Selalu tampilkan digit checksum dalam teks yang dapat dibaca manusia untuk barcode Code128 dan GS1Code128.

**Returns:**
boolean
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCodabar() {#getCodabar--}
```
public final CodabarParameters getCodabar()
```


Parameter Codabar.

**Returns:**
[CodabarParameters](../../com.aspose.barcode.generation/codabarparameters)
### getCodablock() {#getCodablock--}
```
public final CodablockParameters getCodablock()
```


Parameter Codablock.

**Returns:**
[CodablockParameters](../../com.aspose.barcode.generation/codablockparameters)
### getCode128() {#getCode128--}
```
public final Code128Parameters getCode128()
```


Parameter Code128.

**Returns:**
[Code128Parameters](../../com.aspose.barcode.generation/code128parameters)
### getCode16K() {#getCode16K--}
```
public final Code16KParameters getCode16K()
```


Parameter Code16K.

**Returns:**
[Code16KParameters](../../com.aspose.barcode.generation/code16kparameters)
### getCodeText() {#getCodeText--}
```
public final String getCodeText()
```




**Returns:**
java.lang.String
### getCodeTextParameters() {#getCodeTextParameters--}
```
public final CodetextParameters getCodeTextParameters()
```


Parameter teks kode.

**Returns:**
[CodetextParameters](../../com.aspose.barcode.generation/codetextparameters)
### getComplexBarcode() {#getComplexBarcode--}
```
public final ComplexBarcode getComplexBarcode()
```




**Returns:**
[ComplexBarcode](../../com.aspose.barcode.generation/complexbarcode)
### getCoupon() {#getCoupon--}
```
public final CouponParameters getCoupon()
```


Parameter kupon. Digunakan untuk UpcaGs1DatabarCoupon, UpcaGs1Code128Coupon.

**Returns:**
[CouponParameters](../../com.aspose.barcode.generation/couponparameters)
### getDataBar() {#getDataBar--}
```
public final DataBarParameters getDataBar()
```


Parameter Databar.

**Returns:**
[DataBarParameters](../../com.aspose.barcode.generation/databarparameters)
### getDataMatrix() {#getDataMatrix--}
```
public final DataMatrixParameters getDataMatrix()
```


Parameter DataMatrix.

**Returns:**
[DataMatrixParameters](../../com.aspose.barcode.generation/datamatrixparameters)
### getDotCode() {#getDotCode--}
```
public final DotCodeParameters getDotCode()
```


Parameter DotCode.

**Returns:**
[DotCodeParameters](../../com.aspose.barcode.generation/dotcodeparameters)
### getEnableEscape() {#getEnableEscape--}
```
public final boolean getEnableEscape()
```


Menunjukkan apakah menjelaskan karakter "\\\" sebagai karakter escape dalam properti CodeText. Digunakan untuk Pdf417, DataMatrix, Code128 saja. Jika EnableEscape bernilai true, "\\\" akan dijelaskan sebagai karakter escape khusus. Jika tidak, "\\\" berfungsi sebagai karakter normal.

Aspose.BarCode mendukung memasukkan kode ascii desimal dan mnemonic untuk karakter kode kontrol ASCII. Misalnya, \\013 dan \\CR mewakili CR.

**Returns:**
boolean
### getFilledBars() {#getFilledBars--}
```
public final boolean getFilledBars()
```


Mendapatkan nilai yang menunjukkan apakah bar terisi. Hanya untuk barcode 1D. Nilai default: true.

**Returns:**
boolean - nilai yang menunjukkan apakah bar terisi.
### getGS1CompositeBar() {#getGS1CompositeBar--}
```
public final GS1CompositeBarParameters getGS1CompositeBar()
```


Parameter Bar Komposit GS1.

Contoh ini menunjukkan cara membuat dan menyimpan gambar GS1 Composite Bar. Perhatikan bahwa codetext 1D dan codetext 2D dipisahkan oleh simbol '|'

```

 [C#]
   var codetext = "(01)03212345678906|(21)A1B2C3D4E5F6G7H8";
 	  using (var generator = new BarcodeGenerator(EncodeTypes.GS1CompositeBar, codetext))
 	  {
       generator.Parameters.Barcode.GS1CompositeBar.LinearComponentType = EncodeTypes.GS1Code128;
       generator.Parameters.Barcode.GS1CompositeBar.TwoDComponentType = TwoDComponentType.CC_A;
       // Aspect ratio of 2D component
       generator.Parameters.Barcode.Pdf417.AspectRatio = 3;
       // X-Dimension of 1D and 2D components
       generator.Parameters.Barcode.XDimension.Pixels = 3;
       // Height of 1D component
       generator.Parameters.Barcode.BarHeight.Pixels = 100;
       generator.Save("test.png");
   }
 	
```

**Returns:**
[GS1CompositeBarParameters](../../com.aspose.barcode.generation/gs1compositebarparameters)
### getHanXin() {#getHanXin--}
```
public final HanXinParameters getHanXin()
```


Parameter HanXin.

**Returns:**
[HanXinParameters](../../com.aspose.barcode.generation/hanxinparameters)
### getITF() {#getITF--}
```
public final ITFParameters getITF()
```


Parameter ITF.

**Returns:**
[ITFParameters](../../com.aspose.barcode.generation/itfparameters)
### getMaxiCode() {#getMaxiCode--}
```
public final MaxiCodeParameters getMaxiCode()
```


Parameter MaxiCode.

**Returns:**
[MaxiCodeParameters](../../com.aspose.barcode.generation/maxicodeparameters)
### getPadding() {#getPadding--}
```
public final Padding getPadding()
```


Padding barcode. Nilai default: 5pt 5pt 5pt 5pt.

**Returns:**
[Padding](../../com.aspose.barcode.generation/padding)
### getPatchCode() {#getPatchCode--}
```
public final PatchCodeParameters getPatchCode()
```


Parameter PatchCode.

**Returns:**
[PatchCodeParameters](../../com.aspose.barcode.generation/patchcodeparameters)
### getPdf417() {#getPdf417--}
```
public final Pdf417Parameters getPdf417()
```


Parameter PDF417.

**Returns:**
[Pdf417Parameters](../../com.aspose.barcode.generation/pdf417parameters)
### getPostal() {#getPostal--}
```
public final PostalParameters getPostal()
```


Parameter pos. Digunakan untuk Postnet, Planet.

**Returns:**
[PostalParameters](../../com.aspose.barcode.generation/postalparameters)
### getQR() {#getQR--}
```
public final QrParameters getQR()
```


Parameter QR, MicroQR, dan RectMicroQR.

**Returns:**
[QrParameters](../../com.aspose.barcode.generation/qrparameters)
### getSupplement() {#getSupplement--}
```
public final SupplementParameters getSupplement()
```


Parameter suplemen. Digunakan untuk Interleaved2of5, Standard2of5, EAN13, EAN8, UPCA, UPCE, ISBN, ISSN, ISMN.

**Returns:**
[SupplementParameters](../../com.aspose.barcode.generation/supplementparameters)
### getThrowExceptionWhenCodeTextIncorrect() {#getThrowExceptionWhenCodeTextIncorrect--}
```
public final boolean getThrowExceptionWhenCodeTextIncorrect()
```


Hanya untuk barcode 1D. Jika codetext tidak benar dan nilai disetel ke true - pengecualian akan dilempar. Jika tidak, codetext akan diperbaiki agar sesuai dengan spesifikasi barcode. Pengecualian selalu akan dilempar untuk: simbol Databar jika codetext tidak benar. Pengecualian tidak akan pernah dilempar untuk: AustraliaPost, SingapurePost, Code39FullASCII, Code93, Code16K, simbol Code128 jika codetext tidak benar.

**Returns:**
boolean
### getWideNarrowRatio() {#getWideNarrowRatio--}
```
public final float getWideNarrowRatio()
```


Rasio bar lebar terhadap bar sempit. Nilai default: 3, yaitu, bar lebar 3 kali lebih lebar daripada bar sempit. Digunakan untuk ITF, PZN, PharmaCode, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, IATA2of5, VIN, DeutschePost, OPC, Code32, DataLogic2of5, PatchCode, Code39, Code39FullASCII.

**Returns:**
float
### getXDimension() {#getXDimension--}
```
public final Unit getXDimension()
```


x-dimension adalah lebar terkecil dari unit bar atau spasi BarCode. Meningkatkan ini akan meningkatkan lebar keseluruhan gambar barcode. Diabaikan jika properti BaseGenerationParameters.AutoSizeMode ([BaseGenerationParameters.getAutoSizeMode](../../com.aspose.barcode.generation/basegenerationparameters\#getAutoSizeMode)/[BaseGenerationParameters.setAutoSizeMode](../../com.aspose.barcode.generation/basegenerationparameters\#setAutoSizeMode)) diatur ke AutoSizeMode.Nearest atau AutoSizeMode.Interpolation.

**Returns:**
[Unit](../../com.aspose.barcode.generation/unit)
### hashCode() {#hashCode--}
```
public int hashCode()
```




**Returns:**
int
### isChecksumEnabled() {#isChecksumEnabled--}
```
public final EnableChecksum isChecksumEnabled()
```


Aktifkan checksum selama pembuatan barcode 1D.

Default dianggap Ya untuk simbol yang harus mengandung checksum, dan Tidak dimana checksum hanya mungkin.

Checksum memungkinkan: Code39 Standard/Extended, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, DeutschePostIdentcode, DeutschePostLeitcode, VIN, Codabar

Checksum selalu digunakan: Simbol lainnya

**Returns:**
[EnableChecksum](../../com.aspose.barcode.generation/enablechecksum)
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setBarColor(int value) {#setBarColor-int-}
```
public final void setBarColor(int value)
```


Warna bar. Nilai default: Color.Black.

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setBarHeight(Unit value) {#setBarHeight-com.aspose.barcode.generation.Unit-}
```
public final void setBarHeight(Unit value)
```


Tinggi bar barcode 1D dalam nilai [Unit](../../com.aspose.barcode.generation/unit). Diabaikan jika properti BaseGenerationParameters.AutoSizeMode ([BaseGenerationParameters.getAutoSizeMode](../../com.aspose.barcode.generation/basegenerationparameters\\#getAutoSizeMode)/[BaseGenerationParameters.setAutoSizeMode](../../com.aspose.barcode.generation/basegenerationparameters\\#setAutoSizeMode)) disetel ke AutoSizeMode.Nearest atau AutoSizeMode.Interpolation.

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| value | [Unit](../../com.aspose.barcode.generation/unit) |  |

### setBarWidthReduction(Unit value) {#setBarWidthReduction-com.aspose.barcode.generation.Unit-}
```
public final void setBarWidthReduction(Unit value)
```


Menetapkan nilai pengurangan bar yang digunakan untuk mengkompensasi penyebaran tinta saat mencetak. Nilai default: 0

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| value | [Unit](../../com.aspose.barcode.generation/unit) | nilai pengurangan bar yang digunakan untuk mengkompensasi penyebaran tinta saat mencetak. |

### setChecksumAlwaysShow(boolean value) {#setChecksumAlwaysShow-boolean-}
```
public final void setChecksumAlwaysShow(boolean value)
```


Selalu tampilkan digit checksum dalam teks yang dapat dibaca manusia untuk barcode Code128 dan GS1Code128.

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| nilai | boolean |  |

### setChecksumEnabled(EnableChecksum value) {#setChecksumEnabled-com.aspose.barcode.generation.EnableChecksum-}
```
public final void setChecksumEnabled(EnableChecksum value)
```


Aktifkan checksum selama pembuatan barcode 1D.

Default dianggap Ya untuk simbol yang harus mengandung checksum, dan Tidak dimana checksum hanya mungkin.

Checksum memungkinkan: Code39 Standard/Extended, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, DeutschePostIdentcode, DeutschePostLeitcode, VIN, Codabar

Checksum selalu digunakan: Simbol lainnya

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| value | [EnableChecksum](../../com.aspose.barcode.generation/enablechecksum) |  |

### setCodeText(String value) {#setCodeText-java.lang.String-}
```
public final void setCodeText(String value)
```




**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### setEnableEscape(boolean value) {#setEnableEscape-boolean-}
```
public final void setEnableEscape(boolean value)
```


Menunjukkan apakah menjelaskan karakter "\\\" sebagai karakter escape dalam properti CodeText. Digunakan untuk Pdf417, DataMatrix, Code128 saja. Jika EnableEscape bernilai true, "\\\" akan dijelaskan sebagai karakter escape khusus. Jika tidak, "\\\" berfungsi sebagai karakter normal.

Aspose.BarCode mendukung memasukkan kode ascii desimal dan mnemonic untuk karakter kode kontrol ASCII. Misalnya, \\013 dan \\CR mewakili CR.

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| nilai | boolean |  |

### setFilledBars(boolean value) {#setFilledBars-boolean-}
```
public final void setFilledBars(boolean value)
```


Menetapkan nilai yang menunjukkan apakah bar terisi. Hanya untuk barcode 1D. Nilai default: true.

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| nilai | boolean | nilai yang menunjukkan apakah bar terisi. |

### setGS1CompositeBar(GS1CompositeBarParameters value) {#setGS1CompositeBar-com.aspose.barcode.generation.GS1CompositeBarParameters-}
```
public final void setGS1CompositeBar(GS1CompositeBarParameters value)
```


Parameter Bar Komposit GS1.

Contoh ini menunjukkan cara membuat dan menyimpan gambar GS1 Composite Bar. Perhatikan bahwa codetext 1D dan codetext 2D dipisahkan oleh simbol '|'

```

 [C#]
   var codetext = "(01)03212345678906|(21)A1B2C3D4E5F6G7H8";
 	  using (var generator = new BarcodeGenerator(EncodeTypes.GS1CompositeBar, codetext))
 	  {
       generator.Parameters.Barcode.GS1CompositeBar.LinearComponentType = EncodeTypes.GS1Code128;
       generator.Parameters.Barcode.GS1CompositeBar.TwoDComponentType = TwoDComponentType.CC_A;
       // Aspect ratio of 2D component
       generator.Parameters.Barcode.Pdf417.AspectRatio = 3;
       // X-Dimension of 1D and 2D components
       generator.Parameters.Barcode.XDimension.Pixels = 3;
       // Height of 1D component
       generator.Parameters.Barcode.BarHeight.Pixels = 100;
       generator.Save("test.png");
   }
 	
```

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| value | [GS1CompositeBarParameters](../../com.aspose.barcode.generation/gs1compositebarparameters) |  |

### setThrowExceptionWhenCodeTextIncorrect(boolean value) {#setThrowExceptionWhenCodeTextIncorrect-boolean-}
```
public final void setThrowExceptionWhenCodeTextIncorrect(boolean value)
```


Hanya untuk barcode 1D. Jika codetext tidak benar dan nilai disetel ke true - pengecualian akan dilempar. Jika tidak, codetext akan diperbaiki agar sesuai dengan spesifikasi barcode. Pengecualian selalu akan dilempar untuk: simbol Databar jika codetext tidak benar. Pengecualian tidak akan pernah dilempar untuk: AustraliaPost, SingapurePost, Code39FullASCII, Code93, Code16K, simbol Code128 jika codetext tidak benar.

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| nilai | boolean |  |

### setWideNarrowRatio(float value) {#setWideNarrowRatio-float-}
```
public final void setWideNarrowRatio(float value)
```


Rasio bar lebar terhadap bar sempit. Nilai default: 3, yaitu, bar lebar 3 kali lebih lebar daripada bar sempit. Digunakan untuk ITF, PZN, PharmaCode, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, IATA2of5, VIN, DeutschePost, OPC, Code32, DataLogic2of5, PatchCode, Code39, Code39FullASCII.

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| nilai | float |  |

### setXDimension(Unit value) {#setXDimension-com.aspose.barcode.generation.Unit-}
```
public final void setXDimension(Unit value)
```


x-dimension adalah lebar terkecil dari unit bar atau spasi BarCode. Meningkatkan ini akan meningkatkan lebar keseluruhan gambar barcode. Diabaikan jika properti BaseGenerationParameters.AutoSizeMode ([BaseGenerationParameters.getAutoSizeMode](../../com.aspose.barcode.generation/basegenerationparameters\#getAutoSizeMode)/[BaseGenerationParameters.setAutoSizeMode](../../com.aspose.barcode.generation/basegenerationparameters\#setAutoSizeMode)) diatur ke AutoSizeMode.Nearest atau AutoSizeMode.Interpolation.

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| value | [Unit](../../com.aspose.barcode.generation/unit) |  |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

