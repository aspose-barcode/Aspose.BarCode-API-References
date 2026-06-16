---
title: DotCodeEncodeMode
second_title: Referensi API Aspose.BarCode untuk Android via Java
description: Mode enkoding untuk kode batang DotCode.
type: docs
weight: 85
url: /id/androidjava/com.aspose.barcode.generation/dotcodeencodemode/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum DotCodeEncodeMode extends Enum<DotCodeEncodeMode>
```

Mode enkoding untuk kode batang DotCode.

--------------------

> ```
> //Auto mode with macros
>  String codetext = ""[)>05CodetextWithMacros05"";
>  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DOT_CODE, codetext);
>  {
>      generator.save("test.bmp");
>  }
> 
>  //Auto mode
>  String codetext = "\u72acRight\u72d7";
>  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DOT_CODE, codetext);
>  {
>      generator.getParameters().getBarcode().getDotCode().setECIEncoding(ECIEncodings.UTF8);
>      generator.save("test.bmp");
>  }
> 
>  //Bytes mode
>  byte[] encodedArr = { 0xFF, 0xFE, 0xFD, 0xFC, 0xFB, 0xFA, 0xF9 };
>  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DOT_CODE);
>  {
>      generator.setCodetext(encodedArr);
>      generator.getParameters().getBarcode().getDotCode().setDotCodeEncodeMode(DotCodeEncodeMode.BINARY);
>      generator.save("test.bmp");
>  }
>  //Extended codetext mode
>  //create codetext
>  DotCodeExtCodetextBuilder textBuilder = new DotCodeExtCodetextBuilder();
>  textBuilder.addFNC1FormatIdentifier();
>  textBuilder.addECICodetext(ECIEncodings.Win1251, "Will");
>  textBuilder.addFNC1FormatIdentifier();
>  textBuilder.addECICodetext(ECIEncodings.UTF8, "\u72acRight\u72d7");
>  textBuilder.addFNC3SymbolSeparator();
>  textBuilder.addFNC1FormatIdentifier();
>  textBuilder.addECICodetext(ECIEncodings.UTF16BE, "\u72acPower\u72d7");
>  textBuilder.addPlainCodetext("Plain text");
>  //generate codetext
>  String codetext = textBuilder.getExtended();
>  //generate
>  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DOT_CODE, codetext);
>  {
>      generator.getParameters().getBarcode().getDotCode().setDotCodeEncodeMode(DotCodeEncodeMode.EXTENDED_CODETEXT);
>  	   generator.save("test.bmp");
>  }
> ```
## Bidang

| Bidang | Deskripsi |
| --- | --- |
| [AUTO](#AUTO) | Dalam mode Auto, CodeText dikodekan dengan kepadatan data maksimum. |
| [BINARY](#BINARY) | Dalam mode Binary, CodeText dikodekan dengan kepadatan data maksimum. |
| [BYTES](#BYTES) | Enkode teks kode sebagai byte biasa. |
| [ECI](#ECI) | Dalam mode ECI, seluruh pesan di-encode ulang dengan encoding yang ditentukan oleh ECIEncoding dengan penyisipan pengidentifikasi ECI. |
| [EXTENDED](#EXTENDED) |  |
| [EXTENDED_CODETEXT](#EXTENDED-CODETEXT) |  |
## Methods

| Method | Deskripsi |
| --- | --- |
| [<T>valueOf(Class<T> arg0, String arg1)](#-T-valueOf-java.lang.Class-T--java.lang.String-) |  |
| [compareTo(E arg0)](#compareTo-E-) |  |
| [describeConstable()](#describeConstable--) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDeclaringClass()](#getDeclaringClass--) |  |
| [getValue()](#getValue--) |  |
| [hashCode()](#hashCode--) |  |
| [name()](#name--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [ordinal()](#ordinal--) |  |
| [toString()](#toString--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
| [values()](#values--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### AUTO {#AUTO}
```
public static final DotCodeEncodeMode AUTO
```


Dalam mode Auto, CodeText di-encode dengan kepadatan data maksimum. Karakter Unicode di-encode ulang dengan encoding yang ditentukan oleh ECIEncoding dengan penyisipan pengidentifikasi ECI. Jika ditemukan karakter yang tidak didukung oleh encoding ECI yang dipilih, sebuah pengecualian dilempar.

### BINARY {#BINARY}
```
public static final DotCodeEncodeMode BINARY
```


Dalam mode Binary, CodeText di-encode dengan kepadatan data maksimum. Jika ditemukan karakter Unicode, sebuah pengecualian dilempar.

### BYTES {#BYTES}
```
public static final DotCodeEncodeMode BYTES
```


Enkode teks kode sebagai byte biasa. Jika mendeteksi karakter Unicode apa pun, karakter tersebut akan dienkode sebagai dua byte, byte rendah terlebih dahulu.

### ECI {#ECI}
```
public static final DotCodeEncodeMode ECI
```


Dalam mode ECI, seluruh pesan di-encode ulang dengan encoding yang ditentukan oleh ECIEncoding dengan penyisipan pengidentifikasi ECI. Jika ditemukan karakter yang tidak didukung oleh encoding ECI yang dipilih, sebuah pengecualian dilempar. Harap dicatat bahwa beberapa pemindai lama (sebelum 2006) mungkin tidak mendukung mode ini.

### EXTENDED {#EXTENDED}
```
public static final DotCodeEncodeMode EXTENDED
```


Mode diperluas yang mendukung beberapa mode ECI.

Lebih baik menggunakan DotCodeExtCodetextBuilder untuk menghasilkan teks kode yang diperluas.

Gunakan properti Display2DText untuk mengatur teks yang terlihat dengan menghapus karakter pengelola.

Pengidentifikasi ECI ditetapkan sebagai satu garis miring dan pengidentifikasi enam digit "\\000026" - pengidentifikasi ECI UTF8

Semua karakter unicode setelah pengidentifikasi ECI secara otomatis di-encode ke dalam set karakter yang benar.

### EXTENDED_CODETEXT {#EXTENDED-CODETEXT}
```
public static final DotCodeEncodeMode EXTENDED_CODETEXT
```


Mode diperluas yang mendukung beberapa mode ECI.

Lebih baik menggunakan DotCodeExtCodetextBuilder untuk menghasilkan teks kode yang diperluas.

Gunakan properti Display2DText untuk mengatur teks yang terlihat dengan menghapus karakter pengelola.

Pengidentifikasi ECI ditetapkan sebagai satu garis miring dan pengidentifikasi enam digit "\\000026" - pengidentifikasi ECI UTF8

Semua karakter unicode setelah pengidentifikasi ECI secara otomatis di-encode ke dalam set karakter yang benar.

### <T>valueOf(Class<T> arg0, String arg1) {#-T-valueOf-java.lang.Class-T--java.lang.String-}
```
public static T <T>valueOf(Class<T> arg0, String arg1)
```




**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| arg0 | java.lang.Class<T> |  |
| arg1 | java.lang.String |  |

**Returns:**
T
### compareTo(E arg0) {#compareTo-E-}
```
public final int compareTo(E arg0)
```




**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| arg0 | E |  |

**Returns:**
int
### describeConstable() {#describeConstable--}
```
public final Optional<Enum.EnumDesc<E>> describeConstable()
```




**Returns:**
java.util.Optional<java.lang.Enum.EnumDesc<E>>
### equals(Object arg0) {#equals-java.lang.Object-}
```
public final boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDeclaringClass() {#getDeclaringClass--}
```
public final Class<E> getDeclaringClass()
```




**Returns:**
java.lang.Class<E>
### getValue() {#getValue--}
```
public int getValue()
```




**Returns:**
int
### hashCode() {#hashCode--}
```
public final int hashCode()
```




**Returns:**
int
### name() {#name--}
```
public final String name()
```




**Returns:**
java.lang.String
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### ordinal() {#ordinal--}
```
public final int ordinal()
```




**Returns:**
int
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static DotCodeEncodeMode valueOf(String name)
```




**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| name | java.lang.String |  |

**Returns:**
[DotCodeEncodeMode](../../com.aspose.barcode.generation/dotcodeencodemode)
### values() {#values--}
```
public static DotCodeEncodeMode[] values()
```




**Returns:**
com.aspose.barcode.generation.DotCodeEncodeMode[]
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

