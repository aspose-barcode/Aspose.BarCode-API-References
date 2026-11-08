---
title: "QrExtCodetextBuilder"
second_title: "Referensi API Aspose.BarCode untuk Java"
description: 
type: docs
weight: 61
url: /id/java/com.aspose.barcode.generation/qrextcodetextbuilder/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.generation.ExtCodetextBuilder](../../com.aspose.barcode.generation/extcodetextbuilder)
```
public class QrExtCodetextBuilder extends ExtCodetextBuilder
```

Generator teks kode ekstended untuk kode QR 2D untuk Mode ExtendedCodetext dari EncodeMode

Gunakan properti TwoDDisplayText dari BarcodeGenerator untuk mengatur teks yang terlihat dengan menghapus karakter pengelola.

Contoh ini menunjukkan cara menggunakan FNC1 pada posisi pertama dalam Mode Extended.

```

 //create codetext
 QrExtCodetextBuilder textBuilder = new QrExtCodetextBuilder();
 textBuilder.addFNC1FirstPosition();
 textBuilder.addPlainCodetext("000%89%%0");
 textBuilder.addFNC1GroupSeparator();
 textBuilder.addPlainCodetext("12345<FNC1>");
 //generate codetext
 String codetext = textBuilder.getExtendedCodetext();
 //generate
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.QR);
 generator.getParameters().getBarcode().getQR().setEncodeMode(QREncodeMode.EXTENDED_CODETEXT);
 generator.getParameters().getBarcode().getQR().setErrorLevel(QRErrorLevel.LEVEL_L);
 generator.setCodeText(codetext);
 generator.getParameters().getBarcode().getCodeTextParameters().setTwoDDisplayText("My Text");
 generator.save("test.bmp");
 
```

Contoh ini menunjukkan cara menggunakan FNC1 pada posisi kedua dalam Mode Extended.

```

 //create codetext
 QrExtCodetextBuilder textBuilder = new QrExtCodetextBuilder();
 textBuilder.addFNC1SecondPosition("12");
 textBuilder.addPlainCodetext("TRUE3456");
 //generate codetext
 String codetext = textBuilder.getExtendedCodetext();
 //generate
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.QR);
 generator.getParameters().getBarcode().getQR().setEncodeMode(QREncodeMode.EXTENDED_CODETEXT);
 generator.getParameters().getBarcode().getQR().setErrorLevel(QRErrorLevel.LEVEL_L);
 generator.setCodeText(codetext);
 generator.getParameters().getBarcode().getCodeTextParameters().setTwoDDisplayText("My Text");
 generator.save("test.bmp");
 
```

Contoh ini menunjukkan cara menggunakan mode multi ECI dalam Mode Extended.

```

 //create codetext
 QrExtCodetextBuilder textBuilder = new QrExtCodetextBuilder();
 textBuilder.addECICodetext(ECIEncodings.WIN_1251, "Will");
 textBuilder.addECICodetext(ECIEncodings.UTF_8, "Right");
 textBuilder.addECICodetext(ECIEncodings.UTF_16_BE, "Power");
 textBuilder.addPlainCodetext("t\\e\\\\st");
 textBuilder.addCodetextWithCompactionMode(QrExtCompactionMode.ALPHA_NUMERIC, "ASPOSE2001");
 textBuilder.addCodetextWithCompactionMode(QrExtCompactionMode.NUMERIC, "20012026");
 //generate codetext
 String codetext = textBuilder.getExtendedCodetext();
 //generate
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.QR);
 generator.getParameters().getBarcode().getQR().setEncodeMode(QREncodeMode.EXTENDED_CODETEXT);
 generator.getParameters().getBarcode().getQR().setErrorLevel(QRErrorLevel.LEVEL_L);
 generator.setCodeText(codetext);
 generator.getParameters().getBarcode().getCodeTextParameters().setTwoDDisplayText("My Text");
 generator.save("test.bmp");
 
```
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [QrExtCodetextBuilder()](#QrExtCodetextBuilder--) |  |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [addCodetextWithCompactionMode(QrExtCompactionMode mode, String codetext)](#addCodetextWithCompactionMode-com.aspose.barcode.generation.QrExtCompactionMode-java.lang.String-) | Menambahkan teks kode dengan mode kompaksi QR yang ditentukan ke item teks kode ekstended. |
| [addECICodetext(int ECIEncoding, String codetext)](#addECICodetext-int-java.lang.String-) | Menambahkan codetext dengan Extended Channel Identifier |
| [addFNC1FirstPosition()](#addFNC1FirstPosition--) | Mengatur FNC1 pada posisi pertama. |
| [addFNC1GroupSeparator()](#addFNC1GroupSeparator--) | Menambahkan Group Separator (GS - '\\\\u001D') ke item teks kode ekstended |
| [addFNC1SecondPosition(String codetext)](#addFNC1SecondPosition-java.lang.String-) | Mengatur FNC1 pada posisi kedua. |
| [addPlainCodetext(String codetext)](#addPlainCodetext-java.lang.String-) | Menambahkan codetext biasa ke item codetext yang diperluas |
| [clear()](#clear--) | Menghapus item codetext yang diperluas |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getExtendedCodetext()](#getExtendedCodetext--) | Menghasilkan Extended codetext dari daftar codetext yang diperluas. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### QrExtCodetextBuilder() {#QrExtCodetextBuilder--}
```
public QrExtCodetextBuilder()
```


### addCodetextWithCompactionMode(QrExtCompactionMode mode, String codetext) {#addCodetextWithCompactionMode-com.aspose.barcode.generation.QrExtCompactionMode-java.lang.String-}
```
public final void addCodetextWithCompactionMode(QrExtCompactionMode mode, String codetext)
```


Menambahkan teks kode dengan mode kompaksi QR yang ditentukan ke item teks kode ekstended.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| mode | [QrExtCompactionMode](../../com.aspose.barcode.generation/qrextcompactionmode) | Mode kompaksi QR untuk teks kode. |
| codetext | java.lang.String | Teks kode dalam Unicode untuk ditambahkan sebagai item teks kode ekstended. |

### addECICodetext(int ECIEncoding, String codetext) {#addECICodetext-int-java.lang.String-}
```
public final void addECICodetext(int ECIEncoding, String codetext)
```


Menambahkan codetext dengan Extended Channel Identifier

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| ECIEncoding | int | Extended Channel Identifier |
| codetext | java.lang.String | Codetext dalam unicode untuk ditambahkan sebagai item codetext yang diperluas dengan Extended Channel Identifier |

### addFNC1FirstPosition() {#addFNC1FirstPosition--}
```
public final void addFNC1FirstPosition()
```


Mengatur FNC1 pada posisi pertama. Jika mode FNC1 lain telah diatur sebelumnya, maka akan diganti.

### addFNC1GroupSeparator() {#addFNC1GroupSeparator--}
```
public final void addFNC1GroupSeparator()
```


Menambahkan Group Separator (GS - '\\\\u001D') ke item teks kode ekstended

### addFNC1SecondPosition(String codetext) {#addFNC1SecondPosition-java.lang.String-}
```
public final void addFNC1SecondPosition(String codetext)
```


Mengatur FNC1 pada posisi kedua. Jika mode FNC1 lain telah diatur sebelumnya, maka akan diganti.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| codetext | java.lang.String | Nilai FNC1 pada posisi kedua. Nilai harus berupa satu huruf dari a-z atau A-Z, atau angka dua digit dari 00 hingga 99. |

### addPlainCodetext(String codetext) {#addPlainCodetext-java.lang.String-}
```
public final void addPlainCodetext(String codetext)
```


Menambahkan codetext biasa ke item codetext yang diperluas

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| codetext | java.lang.String | Codetext dalam unicode untuk ditambahkan sebagai item codetext ekstensi |

### clear() {#clear--}
```
public void clear()
```


Menghapus item codetext yang diperluas

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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getExtendedCodetext() {#getExtendedCodetext--}
```
public String getExtendedCodetext()
```


Menghasilkan Extended codetext dari daftar codetext yang diperluas.

**Returns:**
java.lang.String - Codetext ekstensi sebagai string
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

