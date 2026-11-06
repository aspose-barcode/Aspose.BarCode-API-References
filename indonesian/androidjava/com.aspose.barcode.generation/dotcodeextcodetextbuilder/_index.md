---
title: "DotCodeExtCodetextBuilder"
second_title: "Referensi API Aspose.BarCode untuk Android via Java"
description: 
type: docs
weight: 34
url: /id/androidjava/com.aspose.barcode.generation/dotcodeextcodetextbuilder/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.generation.ExtCodetextBuilder](../../com.aspose.barcode.generation/extcodetextbuilder)
```
public class DotCodeExtCodetextBuilder extends ExtCodetextBuilder
```

Generator kode teks ekstended untuk barcode DotCode 2D dalam Mode ExtendedCodetext dari DotCodeEncodeMode

--------------------

> ```
> //Extended codetext mode
>  //create codetext
>  DotCodeExtCodetextBuilder textBuilder = new DotCodeExtCodetextBuilder();
>  textBuilder.addFNC1FormatIdentifier();
>  textBuilder.addECICodetext(ECIEncodings.Win1251, "Will");
>  textBuilder.addFNC1FormatIdentifier();
>  textBuilder.addECICodetext(ECIEncodings.UTF8, "\u72acRight\u72d7");
>  textBuilder.addFNC1FormatIdentifier();
>  textBuilder.addECICodetext(ECIEncodings.UTF16BE, "\u72acPower\u72d7");
>  textBuilder.addPlainCodetext("Plain text");
>  textBuilder.addFNC3SymbolSeparator();
>  textBuilder.addFNC3ReaderInitialization();
>  textBuilder.addPlainCodetext("Reader initialization info");
>  //generate codetext
>  String codetext = textBuilder.getExtendedCodetext();
>  //generate
>  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DOT_CODE, codetext);
>  generator.getParameters().getBarcode().getDotCode().setDotCodeEncodeMode(DotCodeEncodeMode.EXTENDED_CODETEXT);
>  generator.save("test.bmp");
> ```
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [DotCodeExtCodetextBuilder()](#DotCodeExtCodetextBuilder--) |  |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [addECICodetext(int ECIEncoding, String codetext)](#addECICodetext-int-java.lang.String-) | Menambahkan codetext dengan Extended Channel Identifier |
| [addFNC1FormatIdentifier()](#addFNC1FormatIdentifier--) | Menambahkan pengidentifikasi format FNC1 ke item kode teks ekstended |
| [addFNC3ReaderInitialization()](#addFNC3ReaderInitialization--) | Menambahkan inisialisasi pembaca FNC3 ke item kode teks ekstended |
| [addFNC3SymbolSeparator()](#addFNC3SymbolSeparator--) | Menambahkan pemisah simbol FNC3 ke item kode teks ekstended |
| [addPlainCodetext(String codetext)](#addPlainCodetext-java.lang.String-) | Menambahkan codetext biasa ke item codetext yang diperluas |
| [addStructuredAppendMode(int barcodeId, int barcodesCount)](#addStructuredAppendMode-int-int-) | Menambahkan mode penambahan terstruktur ke item kode teks ekstended |
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
### DotCodeExtCodetextBuilder() {#DotCodeExtCodetextBuilder--}
```
public DotCodeExtCodetextBuilder()
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

### addFNC1FormatIdentifier() {#addFNC1FormatIdentifier--}
```
public final void addFNC1FormatIdentifier()
```


Menambahkan pengidentifikasi format FNC1 ke item kode teks ekstended

### addFNC3ReaderInitialization() {#addFNC3ReaderInitialization--}
```
public final void addFNC3ReaderInitialization()
```


Menambahkan inisialisasi pembaca FNC3 ke item kode teks ekstended

### addFNC3SymbolSeparator() {#addFNC3SymbolSeparator--}
```
public final void addFNC3SymbolSeparator()
```


Menambahkan pemisah simbol FNC3 ke item kode teks ekstended

### addPlainCodetext(String codetext) {#addPlainCodetext-java.lang.String-}
```
public final void addPlainCodetext(String codetext)
```


Menambahkan codetext biasa ke item codetext yang diperluas

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| codetext | java.lang.String | Codetext dalam unicode untuk ditambahkan sebagai item codetext yang diperluas |

### addStructuredAppendMode(int barcodeId, int barcodesCount) {#addStructuredAppendMode-int-int-}
```
public final void addStructuredAppendMode(int barcodeId, int barcodesCount)
```


Menambahkan mode penambahan terstruktur ke item kode teks ekstended

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| barcodeId | int | ID barcode |
| barcodesCount | int | Jumlah barcode |

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
java.lang.String - Codetext yang diperluas sebagai string
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

