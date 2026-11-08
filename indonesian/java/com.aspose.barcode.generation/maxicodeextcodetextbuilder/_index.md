---
title: "MaxiCodeExtCodetextBuilder"
second_title: "Referensi API Aspose.BarCode untuk Java"
description: "Generator codetext terluas untuk kode batang MaxiCode pada Mode ExtendedCodetext dari MaxiCodeEncodeMode. Gunakan properti TwoDDisplayText dari BarcodeGenerator untuk mengatur teks yang terlihat dengan menghapus karakter pengelola."
type: docs
weight: 54
url: /id/java/com.aspose.barcode.generation/maxicodeextcodetextbuilder/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.generation.ExtCodetextBuilder](../../com.aspose.barcode.generation/extcodetextbuilder)
```
public class MaxiCodeExtCodetextBuilder extends ExtCodetextBuilder
```

Generator codetext yang diperluas untuk barcode MaxiCode dalam Mode ExtendedCodetext dari MaxiCodeEncodeMode. Gunakan properti TwoDDisplayText dari BarcodeGenerator untuk mengatur teks yang terlihat dengan menghapus karakter pengelola. Contoh ini menunjukkan cara menggunakan MaxiCodeExtCodetextBuilder dalam Mode Extended.

```
//create codetext
 MaxiCodeExtCodetextBuilder textBuilder = new MaxiCodeExtCodetextBuilder();
 textBuilder.addECICodetext(ECIEncodings.Win1251, "Will");
 textBuilder.addECICodetext(ECIEncodings.UTF8, "\u72acRight\u72d7");
 textBuilder.addECICodetext(ECIEncodings.UTF16BE, "\u72acPower\u72d7");
 textBuilder.addPlainCodetext("Plain text");

 //generate codetext
 String codetext = textBuilder.getExtendedCodetext();

 //generate
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MAXI_CODE, codetext);
 generator.getParameters().getBarcode().getCodeTextParameters().setTwoDDisplayText("My Text");
 generator.save("test.bmp");
```
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [MaxiCodeExtCodetextBuilder()](#MaxiCodeExtCodetextBuilder--) |  |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [addECICodetext(int ECIEncoding, String codetext)](#addECICodetext-int-java.lang.String-) | Menambahkan codetext dengan Extended Channel Identifier |
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
### MaxiCodeExtCodetextBuilder() {#MaxiCodeExtCodetextBuilder--}
```
public MaxiCodeExtCodetextBuilder()
```


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

