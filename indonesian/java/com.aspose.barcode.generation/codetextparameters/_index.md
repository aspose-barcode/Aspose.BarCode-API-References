---
title: "CodetextParameters"
second_title: "Referensi API Aspose.BarCode untuk Java"
description: "Parameter Codetext."
type: docs
weight: 26
url: /id/java/com.aspose.barcode.generation/codetextparameters/
---
**Inheritance:**
java.lang.Object
```
public class CodetextParameters
```

Parameter Codetext.
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [CodetextParameters()](#CodetextParameters--) |  |
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
|  | [getNoWrap()](#getNoWrap--) | ``` |
Tentukan pembungkus kata (line breaks) dalam teks.
``` |
| [getSpace()](#getSpace--) | Space between the CodeText and the BarCode in  Unit  value. |
| [getTwoDDisplayText()](#getTwoDDisplayText--) | Text that will be displayed instead of codetext in 2D barcodes. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAlignment(TextAlignment value)](#setAlignment-com.aspose.barcode.generation.TextAlignment-) | Sets the alignment of the code text. |
| [setColor(Color value)](#setColor-java.awt.Color-) | Specify the displaying CodeText's Color. |
| [setFont(FontUnit value)](#setFont-com.aspose.barcode.generation.FontUnit-) | Specify the displaying CodeText's font. |
| [setFontMode(FontMode value)](#setFontMode-com.aspose.barcode.generation.FontMode-) | Specify FontMode. |
| [setLocation(CodeLocation value)](#setLocation-com.aspose.barcode.generation.CodeLocation-) | Specify the displaying CodeText Location, set to CodeLocation.None to hide CodeText. |
| [setNoWrap(boolean value)](#setNoWrap-boolean-) | ```
Specify word wraps (line breaks) within text
``` |
| [setSpace(Unit value)](#setSpace-com.aspose.barcode.generation.Unit-) | Spasi antara CodeText dan BarCode dalam nilai Unit. |
| [setTwoDDisplayText(String value)](#setTwoDDisplayText-java.lang.String-) | Teks yang akan ditampilkan sebagai pengganti codetext pada barcode 2D. |
| [toString()](#toString--) | Mengembalikan representasi string yang dapat dibaca manusia dari CodetextParameters ini. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### CodetextParameters() {#CodetextParameters--}
```
public CodetextParameters()
```


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


Mendapatkan perataan teks kode. Nilai default: TextAlignment.CENTER.

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
public FontUnit getFont()
```


Tentukan font tampilan CodeText. Nilai default: Arial 5pt regular. Diabaikan jika FontMode diatur ke FontMode.AUTO.

**Returns:**
[FontUnit](../../com.aspose.barcode.generation/fontunit)
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
### getNoWrap() {#getNoWrap--}
```
public boolean getNoWrap()
```


```
Specify word wraps (line breaks) within text.
 Default value: false.
```

**Returns:**
boolean
### getSpace() {#getSpace--}
```
public Unit getSpace()
```


Spasi antara CodeText dan BarCode dalam nilai Unit. Nilai default: 2pt. Diabaikan untuk EAN8, EAN13, UPCE, UPCA, ISBN, ISMN, ISSN, UpcaGs1DatabarCoupon.

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
public int hashCode()
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


Menetapkan perataan teks kode. Nilai default: TextAlignment.CENTER.

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

### setFont(FontUnit value) {#setFont-com.aspose.barcode.generation.FontUnit-}
```
public void setFont(FontUnit value)
```


Tentukan font tampilan CodeText. Nilai default: Arial 5pt regular. Diabaikan jika FontMode diatur ke FontMode.AUTO.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [FontUnit](../../com.aspose.barcode.generation/fontunit) |  |

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

### setNoWrap(boolean value) {#setNoWrap-boolean-}
```
public void setNoWrap(boolean value)
```


```
Specify word wraps (line breaks) within text
```

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### setSpace(Unit value) {#setSpace-com.aspose.barcode.generation.Unit-}
```
public void setSpace(Unit value)
```


Spasi antara CodeText dan BarCode dalam nilai Unit. Nilai default: 2pt. Diabaikan untuk EAN8, EAN13, UPCE, UPCA, ISBN, ISMN, ISSN, UpcaGs1DatabarCoupon.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [Unit](../../com.aspose.barcode.generation/unit) |  |

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

