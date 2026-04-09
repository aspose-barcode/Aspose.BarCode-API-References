---
title: DataMatrixEncodeMode
second_title: Referensi API Aspose.BarCode untuk Android via Java
description: Mode pengkodean enkoder DataMatrix default ke Auto
type: docs
weight: 83
url: /id/androidjava/com.aspose.barcode.generation/datamatrixencodemode/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum DataMatrixEncodeMode extends Enum<DataMatrixEncodeMode>
```

Mode enkoding encoder DataMatrix, default ke Auto

--------------------

> ```
> This sample shows how to do codetext in Extended Mode.
>  
>  //Auto mode
>  String codetext = "\u72acRight\u72d7";
>  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DATA_MATRIX, codetext);
>  generator.getParameters().getBarcode().getDataMatrix().setECIEncoding(ECIEncodings.UTF8);
>  generator.save("test.bmp");
>  //Bytes mode
>  byte[] encodedArr = { (byte)0xFF, (byte)0xFE, (byte)0xFD, (byte)0xFC, (byte)0xFB, (byte)0xFA, (byte)0xF9 };
>  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DATA_MATRIX);
>  generator.setCodetext(encodedArr);
>  generator.getParameters().getBarcode().getDataMatrix().setEncodeMode(EncodeMode.BINARY);
>  generator.save("test.bmp");
>  //Extended codetext mode
>  //create codetext
>  DataMatrixExtCodetextBuilder codetextBuilder=new DataMatrixExtCodetextBuilder();
>  codetextBuilder.addECICodetextWithEncodeMode(ECIEncodings.Win1251,EncodeMode.BYTES,"World");
>  codetextBuilder.addPlainCodetext("Will");
>  codetextBuilder.addECICodetext(ECIEncodings.UTF8,"\u72acRight\u72d7");
>  codetextBuilder.addCodetextWithEncodeMode(EncodeMode.C40,"ABCDE");
>  //generate codetext
>  String codetext=codetextBuilder.getExtended();
>  //generate
>  BarcodeGenerator generator=new BarcodeGenerator(EncodeTypes.DATA_MATRIX,codetext);
>  generator.getParameters().getBarcode().getDataMatrix().setEncodeMode(EncodeMode.EXTENDED_CODETEXT);
>  generator.save("test.bmp");
> ```
## Bidang

| Bidang | Deskripsi |
| --- | --- |
| [ANSIX12](#ANSIX12) | Menggunakan pengkodean ANSI X12. |
| [ASCII](#ASCII) | Mengkodekan satu karakter alfanumerik atau dua karakter numerik per byte |
| [AUTO](#AUTO) | Dalam mode Auto, CodeText dikodekan dengan kepadatan data maksimum. |
| [BASE_256](#BASE-256) | Mengkode nilai 8 bit |
| [BINARY](#BINARY) | Dalam mode Binary, CodeText dikodekan dengan kepadatan data maksimum. |
| [BYTES](#BYTES) | Mengkode nilai 8 bit |
| [C40](#C40) | Menggunakan pengkodean C40. |
| [ECI](#ECI) | Dalam mode ECI, seluruh pesan di-encode ulang dengan encoding yang ditentukan oleh ECIEncoding dengan penyisipan pengidentifikasi ECI. |
| [EDIFACT](#EDIFACT) | Menggunakan encoding EDIFACT. |
| [EXTENDED](#EXTENDED) | Mode ExtendedCodetext memungkinkan untuk secara manual beralih skema enkoding dan encoding ECI dalam codetext. |
| [EXTENDED_CODETEXT](#EXTENDED-CODETEXT) |  |
| [TEXT](#TEXT) | Menggunakan encoding Text. |
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
### ANSIX12 {#ANSIX12}
```
public static final DataMatrixEncodeMode ANSIX12
```


Menggunakan pengkodean ANSI X12.

### ASCII {#ASCII}
```
public static final DataMatrixEncodeMode ASCII
```


Mengkodekan satu karakter alfanumerik atau dua karakter numerik per byte

### AUTO {#AUTO}
```
public static final DataMatrixEncodeMode AUTO
```


Dalam mode Auto, CodeText di-encode dengan kepadatan data maksimum. Karakter Unicode di-encode ulang dengan encoding yang ditentukan oleh ECIEncoding dengan penyisipan pengidentifikasi ECI. Jika ditemukan karakter yang tidak didukung oleh encoding ECI yang dipilih, sebuah pengecualian dilempar.

### BASE_256 {#BASE-256}
```
public static final DataMatrixEncodeMode BASE_256
```


Mengkode nilai 8 bit

### BINARY {#BINARY}
```
public static final DataMatrixEncodeMode BINARY
```


Dalam mode Binary, CodeText di-encode dengan kepadatan data maksimum. Jika ditemukan karakter Unicode, sebuah pengecualian dilempar.

### BYTES {#BYTES}
```
public static final DataMatrixEncodeMode BYTES
```


Mengkode nilai 8 bit

### C40 {#C40}
```
public static final DataMatrixEncodeMode C40
```


Menggunakan encoding C40. Meng-encode alfanumerik huruf besar, huruf kecil, dan karakter khusus.

### ECI {#ECI}
```
public static final DataMatrixEncodeMode ECI
```


Dalam mode ECI, seluruh pesan di-encode ulang dengan encoding yang ditentukan oleh ECIEncoding dengan penyisipan pengidentifikasi ECI. Jika ditemukan karakter yang tidak didukung oleh encoding ECI yang dipilih, sebuah pengecualian dilempar. Harap dicatat bahwa beberapa pemindai lama (sebelum 2006) mungkin tidak mendukung mode ini.

### EDIFACT {#EDIFACT}
```
public static final DataMatrixEncodeMode EDIFACT
```


Menggunakan encoding EDIFACT. Menggunakan enam bit per karakter, meng-encode digit, huruf besar, dan banyak tanda baca, tetapi tidak mendukung huruf kecil.

### EXTENDED {#EXTENDED}
```
public static final DataMatrixEncodeMode EXTENDED
```


Mode ExtendedCodetext memungkinkan untuk secara manual beralih skema enkoding dan encoding ECI dalam codetext. Lebih baik menggunakan DataMatrixExtCodetextBuilder untuk menghasilkan codetext yang diperluas. Gunakan properti Display2DText untuk mengatur teks yang terlihat dengan menghapus karakter pengelola. Pengidentifikasi ECI ditetapkan sebagai satu garis miring dan pengidentifikasi enam digit "\\000026" - pengidentifikasi ECI UTF8. Semua karakter unicode setelah pengidentifikasi ECI secara otomatis di-encode ke dalam set karakter yang benar. Skema enkoding ditetapkan dalam format berikut: "\\Encodation\_scheme\_name:text\\Encodation\_scheme\_name:text". Skema enkoding yang diizinkan adalah: EDIFACT, ANSIX12, ASCII, C40, Text, Auto. Semua backslash (\\) harus digandakan dalam teks.

### EXTENDED_CODETEXT {#EXTENDED-CODETEXT}
```
public static final DataMatrixEncodeMode EXTENDED_CODETEXT
```


Mode ExtendedCodetext memungkinkan untuk secara manual beralih skema enkoding dan encoding ECI dalam codetext.

Lebih baik menggunakan DataMatrixExtCodetextBuilder untuk menghasilkan codetext yang diperluas.

Gunakan properti Display2DText untuk mengatur teks yang terlihat dengan menghapus karakter pengelola.

Pengidentifikasi ECI ditetapkan sebagai satu garis miring dan pengidentifikasi enam digit "\\000026" - pengidentifikasi ECI UTF8

Semua karakter unicode setelah pengidentifikasi ECI secara otomatis di-encode ke dalam set karakter yang benar.

Skema enkoding ditetapkan dalam format berikut: "\\Encodation\_scheme\_name:text\\Encodation\_scheme\_name:text".

Skema enkoding yang diizinkan adalah: EDIFACT, ANSIX12, ASCII, C40, Text, Auto.

Semua backslash (\\) harus digandakan dalam teks.

### TEXT {#TEXT}
```
public static final DataMatrixEncodeMode TEXT
```


Menggunakan encoding Text. Meng-encode alfanumerik huruf kecil, huruf besar, dan karakter khusus.

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
public static DataMatrixEncodeMode valueOf(String name)
```




**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| name | java.lang.String |  |

**Returns:**
[DataMatrixEncodeMode](../../com.aspose.barcode.generation/datamatrixencodemode)
### values() {#values--}
```
public static DataMatrixEncodeMode[] values()
```




**Returns:**
com.aspose.barcode.generation.DataMatrixEncodeMode[]
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

