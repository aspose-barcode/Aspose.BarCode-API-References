---
title: "CodetextParameters"
second_title: "Referensi API Aspose.BarCode untuk Android via Java"
description: "Parameter teks kode."
type: docs
weight: 26
url: /id/androidjava/com.aspose.barcode.generation/codetextparameters/
---
**Inheritance:**
java.lang.Object
```
public class CodetextParameters
```

Parameter teks kode.
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
| [getColor()](#getColor--) | Tentukan Warna CodeText yang ditampilkan. |
| [getFont()](#getFont--) | Tentukan font CodeText yang ditampilkan. |
| [getFontMode()](#getFontMode--) | Tentukan FontMode. |
| [getLocation()](#getLocation--) | Tentukan Lokasi CodeText yang ditampilkan, atur ke CodeLocation.None untuk menyembunyikan CodeText. |
|  | [getNoWrap()](#getNoWrap--) | ``` |
Tentukan pembungkus kata (pemutusan baris) dalam teks.
``` |
| [getSpace()](#getSpace--) | Space between the CodeText and the BarCode in  Unit  value. |
| [getTwoDDisplayText()](#getTwoDDisplayText--) | Text that will be displayed instead of codetext in 2D barcodes. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAlignment(TextAlignment value)](#setAlignment-com.aspose.barcode.generation.TextAlignment-) | Sets the alignment of the code text. |
| [setColor(int value)](#setColor-int-) | Specify the displaying CodeText's Color. |
| [setFont(FontUnit value)](#setFont-com.aspose.barcode.generation.FontUnit-) | Specify the displaying CodeText's font. |
| [setFontMode(FontMode value)](#setFontMode-com.aspose.barcode.generation.FontMode-) | Specify FontMode. |
| [setLocation(CodeLocation value)](#setLocation-com.aspose.barcode.generation.CodeLocation-) | Specify the displaying CodeText Location, set to CodeLocation.None to hide CodeText. |
| [setNoWrap(boolean value)](#setNoWrap-boolean-) | ```
Specify word wraps (line breaks) within text
``` |
| [setSpace(Unit value)](#setSpace-com.aspose.barcode.generation.Unit-) | Jarak antara CodeText dan BarCode dalam nilai Unit. |
| [setTwoDDisplayText(String value)](#setTwoDDisplayText-java.lang.String-) | Teks yang akan ditampilkan sebagai pengganti codetext pada kode batang 2D. |
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
public int getColor()
```


Tentukan Warna CodeText yang ditampilkan. Nilai default: Color.BLACK.

**Returns:**
int
### getFont() {#getFont--}
```
public FontUnit getFont()
```


Tentukan font CodeText yang ditampilkan. Nilai default: Arial 5pt regular. Diabaikan jika FontMode diatur ke FontMode.AUTO.

**Returns:**
[FontUnit](../../com.aspose.barcode.generation/fontunit)
### getFontMode() {#getFontMode--}
```
public FontMode getFontMode()
```


Tentukan FontMode. Jika FontMode diatur ke Auto, ukuran font akan dihitung secara otomatis berdasarkan nilai xDimension. Disarankan menggunakan FontMode.AUTO terutama dalam AutoSizeMode.NEAREST atau AutoSizeMode.INTERPOLATION. Nilai default: FontMode.AUTO.

**Returns:**
[FontMode](../../com.aspose.barcode.generation/fontmode)
### getLocation() {#getLocation--}
```
public CodeLocation getLocation()
```


Tentukan Lokasi CodeText yang ditampilkan, atur ke CodeLocation.None untuk menyembunyikan CodeText. Nilai default: CodeLocation.BELOW untuk kode batang 1D dan CodeLocation.None untuk kode batang 2D.

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


Jarak antara CodeText dan BarCode dalam nilai Unit. Nilai default: 2pt. Diabaikan untuk EAN8, EAN13, UPCE, UPCA, ISBN, ISMN, ISSN, UpcaGs1DatabarCoupon.

**Returns:**
[Unit](../../com.aspose.barcode.generation/unit)
### getTwoDDisplayText() {#getTwoDDisplayText--}
```
public String getTwoDDisplayText()
```


Teks yang akan ditampilkan sebagai pengganti codetext pada kode batang 2D. Digunakan untuk: Aztec, Pdf417, DataMatrix, QR, MaxiCode, DotCode.

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


Mengatur perataan teks kode. Nilai default: TextAlignment.CENTER.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [TextAlignment](../../com.aspose.barcode.generation/textalignment) |  |

### setColor(int value) {#setColor-int-}
```
public void setColor(int value)
```


Tentukan Warna CodeText yang ditampilkan. Nilai default: Color.BLACK.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setFont(FontUnit value) {#setFont-com.aspose.barcode.generation.FontUnit-}
```
public void setFont(FontUnit value)
```


Tentukan font CodeText yang ditampilkan. Nilai default: Arial 5pt regular. Diabaikan jika FontMode diatur ke FontMode.AUTO.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [FontUnit](../../com.aspose.barcode.generation/fontunit) |  |

### setFontMode(FontMode value) {#setFontMode-com.aspose.barcode.generation.FontMode-}
```
public void setFontMode(FontMode value)
```


Tentukan FontMode. Jika FontMode diatur ke Auto, ukuran font akan dihitung secara otomatis berdasarkan nilai xDimension. Disarankan menggunakan FontMode.AUTO terutama dalam AutoSizeMode.NEAREST atau AutoSizeMode.INTERPOLATION. Nilai default: FontMode.AUTO.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [FontMode](../../com.aspose.barcode.generation/fontmode) |  |

### setLocation(CodeLocation value) {#setLocation-com.aspose.barcode.generation.CodeLocation-}
```
public void setLocation(CodeLocation value)
```


Tentukan Lokasi CodeText yang ditampilkan, atur ke CodeLocation.None untuk menyembunyikan CodeText. Nilai default: CodeLocation.BELOW untuk kode batang 1D dan CodeLocation.None untuk kode batang 2D.

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
| nilai | boolean |  |

### setSpace(Unit value) {#setSpace-com.aspose.barcode.generation.Unit-}
```
public void setSpace(Unit value)
```


Jarak antara CodeText dan BarCode dalam nilai Unit. Nilai default: 2pt. Diabaikan untuk EAN8, EAN13, UPCE, UPCA, ISBN, ISMN, ISSN, UpcaGs1DatabarCoupon.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [Unit](../../com.aspose.barcode.generation/unit) |  |

### setTwoDDisplayText(String value) {#setTwoDDisplayText-java.lang.String-}
```
public void setTwoDDisplayText(String value)
```


Teks yang akan ditampilkan sebagai pengganti codetext pada kode batang 2D. Digunakan untuk: Aztec, Pdf417, DataMatrix, QR, MaxiCode, DotCode.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

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
public final void wait(long arg0)
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

