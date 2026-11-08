---
title: "CodetextParametersUI"
second_title: "Referensi API Aspose.BarCode untuk Java"
description: "Pembungkus UI untuk kelas com.aspose.barcode.generation.CodetextParameters."
type: docs
weight: 13
url: /id/java/com.aspose.barcode.barcodecontrol/codetextparametersui/
---
**Inheritance:**
java.lang.Object
```
public class CodetextParametersUI
```

Pembungkus UI untuk kelas com.aspose.barcode.generation.CodetextParameters.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAlignment()](#getAlignment--) | Mendapatkan perataan teks kode. |
| [getClass()](#getClass--) |  |
| [getColor()](#getColor--) | Tentukan warna tampilan CodeText. |
| [getFont()](#getFont--) | Tentukan font tampilan CodeText. |
| [getFontMode()](#getFontMode--) | Tentukan FontMode. |
| [getLocation()](#getLocation--) | Tentukan lokasi tampilan CodeText, atur ke CodeLocation.None untuk menyembunyikan CodeText. |
| [getSpace()](#getSpace--) | Spasi antara CodeText dan BarCode dalam  nilai. |
| [getTwoDDisplayText()](#getTwoDDisplayText--) | Teks yang akan ditampilkan sebagai pengganti codetext pada barcode 2D. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAlignment(TextAlignment value)](#setAlignment-com.aspose.barcode.generation.TextAlignment-) | Mengatur perataan teks kode. |
| [setColor(Color value)](#setColor-java.awt.Color-) | Tentukan warna tampilan CodeText. |
| [setFont(Font value)](#setFont-java.awt.Font-) | Tentukan font tampilan CodeText. |
| [setFontMode(FontMode value)](#setFontMode-com.aspose.barcode.generation.FontMode-) | Tentukan FontMode. |
| [setLocation(CodeLocation value)](#setLocation-com.aspose.barcode.generation.CodeLocation-) | Tentukan lokasi tampilan CodeText, atur ke CodeLocation.None untuk menyembunyikan CodeText. |
| [setTwoDDisplayText(String value)](#setTwoDDisplayText-java.lang.String-) | Teks yang akan ditampilkan sebagai pengganti codetext pada barcode 2D. |
| [toString()](#toString--) | Mengembalikan representasi string yang dapat dibaca manusia dari CodetextParameters ini. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getAlignment() {#getAlignment--}
```
public TextAlignment getAlignment()
```


Mendapatkan perataan teks kode. Nilai default: StringAlignment.Center.

**Returns:**
[TextAlignment](../../com.aspose.barcode.generation/textalignment)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColor() {#getColor--}
```
public Color getColor()
```


Tentukan warna tampilan CodeText. Nilai default: Color.BLACK.

**Returns:**
java.awt.Color
### getFont() {#getFont--}
```
public Font getFont()
```


Tentukan font tampilan CodeText. Nilai default: Arial 5pt regular. Diabaikan jika FontMode diatur ke FontMode.AUTO.

**Returns:**
java.awt.Font
### getFontMode() {#getFontMode--}
```
public FontMode getFontMode()
```


Tentukan FontMode. Jika FontMode diatur ke Auto, ukuran font akan dihitung secara otomatis berdasarkan nilai xDimension. Disarankan untuk menggunakan FontMode.AUTO terutama dalam AutoSizeMode.NEAREST atau AutoSizeMode.INTERPOLATION. Nilai default: FontMode.AUTO.

**Returns:**
[FontMode](../../com.aspose.barcode.generation/fontmode)
### getLocation() {#getLocation--}
```
public CodeLocation getLocation()
```


Tentukan lokasi tampilan CodeText, atur ke CodeLocation.None untuk menyembunyikan CodeText. Nilai default: CodeLocation.BELOW untuk barcode 1D dan CodeLocation.None untuk barcode 2D.

**Returns:**
[CodeLocation](../../com.aspose.barcode.generation/codelocation)
### getSpace() {#getSpace--}
```
public Unit getSpace()
```


Spasi antara CodeText dan BarCode dalam  nilai. Nilai default: 2pt. Diabaikan untuk EAN8, EAN13, UPCE, UPCA, ISBN, ISMN, ISSN, UpcaGs1DatabarCoupon.

**Returns:**
[Unit](../../com.aspose.barcode.generation/unit)
### getTwoDDisplayText() {#getTwoDDisplayText--}
```
public String getTwoDDisplayText()
```


Teks yang akan ditampilkan sebagai pengganti codetext pada barcode 2D. Digunakan untuk: Aztec, Pdf417, DataMatrix, QR, MaxiCode, DotCode.

**Returns:**
java.lang.String
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setAlignment(TextAlignment value) {#setAlignment-com.aspose.barcode.generation.TextAlignment-}
```
public void setAlignment(TextAlignment value)
```


Mengatur perataan teks kode. Nilai default: StringAlignment.Center.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [TextAlignment](../../com.aspose.barcode.generation/textalignment) |  |

### setColor(Color value) {#setColor-java.awt.Color-}
```
public void setColor(Color value)
```


Tentukan warna tampilan CodeText. Nilai default: Color.BLACK.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | java.awt.Color |  |

### setFont(Font value) {#setFont-java.awt.Font-}
```
public void setFont(Font value)
```


Tentukan font tampilan CodeText. Nilai default: Arial 5pt regular. Diabaikan jika FontMode diatur ke FontMode.AUTO.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | java.awt.Font |  |

### setFontMode(FontMode value) {#setFontMode-com.aspose.barcode.generation.FontMode-}
```
public void setFontMode(FontMode value)
```


Tentukan FontMode. Jika FontMode diatur ke Auto, ukuran font akan dihitung secara otomatis berdasarkan nilai xDimension. Disarankan untuk menggunakan FontMode.AUTO terutama dalam AutoSizeMode.NEAREST atau AutoSizeMode.INTERPOLATION. Nilai default: FontMode.AUTO.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [FontMode](../../com.aspose.barcode.generation/fontmode) |  |

### setLocation(CodeLocation value) {#setLocation-com.aspose.barcode.generation.CodeLocation-}
```
public void setLocation(CodeLocation value)
```


Tentukan lokasi tampilan CodeText, atur ke CodeLocation.None untuk menyembunyikan CodeText. Nilai default: CodeLocation.BELOW untuk barcode 1D dan CodeLocation.None untuk barcode 2D.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [CodeLocation](../../com.aspose.barcode.generation/codelocation) |  |

### setTwoDDisplayText(String value) {#setTwoDDisplayText-java.lang.String-}
```
public void setTwoDDisplayText(String value)
```


Teks yang akan ditampilkan sebagai pengganti codetext pada barcode 2D. Digunakan untuk: Aztec, Pdf417, DataMatrix, QR, MaxiCode, DotCode.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | java.lang.String |  |

### toString() {#toString--}
```
public String toString()
```


Mengembalikan representasi string yang dapat dibaca manusia dari CodetextParameters ini.

**Returns:**
java.lang.String - String yang mewakili CodetextParameters ini.
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final native void wait(long arg0)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

