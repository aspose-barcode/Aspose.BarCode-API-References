---
title: QREncodeMode
second_title: Referensi API Aspose.BarCode untuk Android via Java
description: Mode enkoding untuk kode batang QR.
type: docs
weight: 102
url: /id/androidjava/com.aspose.barcode.generation/qrencodemode/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum QREncodeMode extends Enum<QREncodeMode>
```

Mode enkoding untuk kode batang QR.

--------------------

> ```
> Example how to use ECI encoding
>  
>      BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.QR);
>      generator.setCodeText("12345TEXT");
>      generator.getParameters().getBarcode().getQR().setEncodeMode(QREncodeMode.ECI_ENCODING);
>      generator.getParameters().getBarcode().getQR().setQrECIEncoding(ECIEncodings.UTF8);
>      generator.save("test.png");
> ```

--------------------

> ```
> Example how to use FNC1 first position in Extended Mode
>   
>       QrExtCodetextBuilder textBuilder = new QrExtCodetextBuilder();
>       textBuilder.addPlainCodetext("000%89%%0");
>       textBuilder.addFNC1GroupSeparator();
>       textBuilder.addPlainCodetext("12345<FNC1>");
>       //generate barcode
>       BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.QR);
>       generator.setCodeText(textBuilder.getExtended());
>       generator.getParameters().getBarcode().getQR().setEncodeMode(QREncodeMode.EXTENDED_CODETEXT);
>       generator.getParameters().getBarcode().getCodeTextParameters().setTwoDDisplayText("My Text");
>       generator.save("d:/test.png");
>  
>       *
>  This sample shows how to use FNC1 second position in Extended Mode.
>  
> 
>     //create codetext
>     QrExtCodetextBuilder textBuilder = new QrExtCodetextBuilder();
>     textBuilder.addFNC1SecondPosition("12");
>     textBuilder.addPlainCodetext("TRUE3456");
>     //generate barcode
>     BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.QR);
>     generator.setCodeText(textBuilder.getExtended());
>     generator.getParameters().getBarcode().getCodeTextParameters().setTwoDDisplayText("My Text");
>     generator.save("d:/test.png");
>     
> 
>     This sample shows how to use multi ECI mode in Extended Mode.
>     
> 
>    //create codetext
>    QrExtCodetextBuilder textBuilder = new QrExtCodetextBuilder();
>    textBuilder.addECICodetext(ECIEncodings.Win1251, "Will");
>    textBuilder.addECICodetext(ECIEncodings.UTF8, "Right");
>    textBuilder.addECICodetext(ECIEncodings.UTF16BE, "Power");
>    textBuilder.addPlainCodetext("t\e\\st");
>    //generate barcode
>    BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.QR);
>    generator.setCodeText(textBuilder.getExtended());
>    generator.getParameters().getBarcode().getQR().setEncodeMode(QREncodeMode.EXTENDED_CODETEXT);
>    generator.getParameters().getBarcode().getCodeTextParameters().setTwoDDisplayText("My Text");
>    generator.save("d:/test.png");
> ```
## Bidang

| Bidang | Deskripsi |
| --- | --- |
| [AUTO](#AUTO) | Dalam mode Auto, CodeText dikodekan dengan kepadatan data maksimum. |
| [BINARY](#BINARY) | Dalam mode Binary, CodeText dikodekan dengan kepadatan data maksimum. |
| [BYTES](#BYTES) | Enkode teks kode sebagai byte biasa. |
| [ECI](#ECI) | Dalam mode ECI, seluruh pesan di-encode ulang dengan encoding yang ditentukan oleh ECIEncoding dengan penyisipan pengidentifikasi ECI. |
| [ECI_ENCODING](#ECI-ENCODING) | Enkode teks kode dengan nilai yang ditetapkan pada properti ECIEncoding. |
| [EXTENDED](#EXTENDED) | Mode Saluran Ekstended yang mendukung posisi pertama FNC1, posisi kedua FNC1, dan mode ECI multi. Lebih baik menggunakan QrExtCodetextBuilder untuk menghasilkan teks kode yang diperluas. Gunakan properti Display2DText untuk mengatur teks yang terlihat dengan menghapus karakter pengelola. Prinsip Pengkodean: Semua simbol "\\" harus digandakan menjadi "\\\\" dalam teks kode. FNC1 pada posisi pertama ditetapkan dalam teks kode sebagai "<FNC1>". FNC1 pada posisi kedua ditetapkan dalam teks kode sebagai "<FNC1(value)>". |
| [EXTENDED_CODETEXT](#EXTENDED-CODETEXT) | Mode Saluran Ekstended yang mendukung posisi pertama FNC1, posisi kedua FNC1, dan mode ECI multi. Lebih baik menggunakan QrExtCodetextBuilder untuk menghasilkan teks kode yang diperluas. Gunakan properti Display2DText untuk mengatur teks yang terlihat dengan menghapus karakter pengelola. Prinsip Pengkodean: Semua simbol "\\" harus digandakan menjadi "\\\\" dalam teks kode. FNC1 pada posisi pertama ditetapkan dalam teks kode sebagai "<FNC1>". FNC1 pada posisi kedua ditetapkan dalam teks kode sebagai "<FNC1(value)>". |
| [UTF_16_BEBOM](#UTF-16-BEBOM) | Enkode teks kode dengan pengkodean UTF8 menggunakan karakter ByteOfMark pertama. |
| [UTF_8_BOM](#UTF-8-BOM) | Enkode teks kode dengan pengkodean UTF8 menggunakan karakter ByteOfMark pertama. |
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
public static final QREncodeMode AUTO
```


Dalam mode Auto, CodeText dienkode dengan kepadatan data maksimum. Karakter Unicode dienkode dalam mode kanji bila memungkinkan, atau mereka dienkode ulang dengan pengkodean yang ditentukan oleh ECIEncoding beserta penyisipan pengidentifikasi ECI. Jika ditemukan karakter yang tidak didukung oleh pengkodean ECI yang dipilih, sebuah pengecualian akan dilempar.

### BINARY {#BINARY}
```
public static final QREncodeMode BINARY
```


Dalam mode Binary, CodeText di-encode dengan kepadatan data maksimum. Jika ditemukan karakter Unicode, sebuah pengecualian dilempar.

### BYTES {#BYTES}
```
public static final QREncodeMode BYTES
```


Enkode teks kode sebagai byte biasa. Jika mendeteksi karakter Unicode apa pun, karakter tersebut akan dienkode sebagai dua byte, byte rendah terlebih dahulu.

### ECI {#ECI}
```
public static final QREncodeMode ECI
```


Dalam mode ECI, seluruh pesan dienkode ulang dengan pengkodean yang ditentukan oleh ECIEncoding beserta penyisipan pengidentifikasi ECI. Jika ditemukan karakter yang tidak didukung oleh pengkodean ECI yang dipilih, sebuah pengecualian akan dilempar. Harap dicatat bahwa beberapa pemindai lama (sebelum 2006) mungkin tidak mendukung mode ini. Mode ini tidak didukung oleh kode batang MicroQR.

### ECI_ENCODING {#ECI-ENCODING}
```
public static final QREncodeMode ECI_ENCODING
```


Enkode teks kode dengan nilai yang ditetapkan pada properti ECIEncoding. Mungkin ada masalah dengan beberapa pemindai kode batang lama (sebelum 2006). Mode ini tidak didukung oleh kode batang MicroQR.

### EXTENDED {#EXTENDED}
```
public static final QREncodeMode EXTENDED
```


Mode Saluran Ekstended yang mendukung posisi pertama FNC1, posisi kedua FNC1, dan mode ECI multi. Lebih baik menggunakan QrExtCodetextBuilder untuk menghasilkan teks kode yang diperluas. Gunakan properti Display2DText untuk mengatur teks yang terlihat dengan menghapus karakter pengelola. Prinsip Pengkodean: Semua simbol "\\" harus digandakan menjadi "\\\\" dalam teks kode. FNC1 pada posisi pertama ditetapkan dalam teks kode sebagai "<FNC1>". FNC1 pada posisi kedua ditetapkan dalam teks kode sebagai "<FNC1(value)>". Nilai harus berupa simbol tunggal (a-z, A-Z) atau digit dari 0 hingga 99. Pemisah Grup untuk mode FNC1 ditetapkan sebagai karakter 0x1D '\\\\u001D'. Jika Anda perlu menyisipkan string "<FNC1>" ke dalam kode batang, tulis sebagai "<\\FNC1>". Pengidentifikasi ECI ditetapkan sebagai garis miring tunggal dan pengidentifikasi enam digit "\\000026" - pengidentifikasi ECI UTF8. Untuk menonaktifkan mode ECI saat ini dan mengubah ke mode JIS8 default, pengidentifikasi mode nol ECI ditetapkan "\\000000". Semua karakter unicode setelah pengidentifikasi ECI secara otomatis dienkode ke dalam set karakter yang tepat. Mode ini tidak didukung oleh kode batang MicroQR.

### EXTENDED_CODETEXT {#EXTENDED-CODETEXT}
```
public static final QREncodeMode EXTENDED_CODETEXT
```


Mode Saluran Ekstended yang mendukung posisi pertama FNC1, posisi kedua FNC1, dan mode ECI multi. Lebih baik menggunakan QrExtCodetextBuilder untuk menghasilkan teks kode yang diperluas. Gunakan properti Display2DText untuk mengatur teks yang terlihat dengan menghapus karakter pengelola. Prinsip Pengkodean: Semua simbol "\\" harus digandakan menjadi "\\\\" dalam teks kode. FNC1 pada posisi pertama ditetapkan dalam teks kode sebagai "<FNC1>". FNC1 pada posisi kedua ditetapkan dalam teks kode sebagai "<FNC1(value)>". Nilai harus berupa simbol tunggal (a-z, A-Z) atau digit dari 0 hingga 99. Pemisah Grup untuk mode FNC1 ditetapkan sebagai karakter 0x1D '\\\\u001D'. Jika Anda perlu menyisipkan string "<FNC1>" ke dalam kode batang, tulis sebagai "<\\FNC1>". Pengidentifikasi ECI ditetapkan sebagai garis miring tunggal dan pengidentifikasi enam digit "\\000026" - pengidentifikasi ECI UTF8. Untuk menonaktifkan mode ECI saat ini dan mengubah ke mode JIS8 default, pengidentifikasi mode nol ECI ditetapkan "\\000000". Semua karakter unicode setelah pengidentifikasi ECI secara otomatis dienkode ke dalam set karakter yang tepat. Mode ini tidak didukung oleh kode batang MicroQR.

### UTF_16_BEBOM {#UTF-16-BEBOM}
```
public static final QREncodeMode UTF_16_BEBOM
```


Enkode teks kode dengan pengkodean UTF8 menggunakan karakter ByteOfMark pertama. Mungkin ada masalah dengan beberapa pemindai kode batang.

### UTF_8_BOM {#UTF-8-BOM}
```
public static final QREncodeMode UTF_8_BOM
```


Enkode teks kode dengan pengkodean UTF8 menggunakan karakter ByteOfMark pertama.

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
public static QREncodeMode valueOf(String name)
```




**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| name | java.lang.String |  |

**Returns:**
[QREncodeMode](../../com.aspose.barcode.generation/qrencodemode)
### values() {#values--}
```
public static QREncodeMode[] values()
```




**Returns:**
com.aspose.barcode.generation.QREncodeMode[]
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

