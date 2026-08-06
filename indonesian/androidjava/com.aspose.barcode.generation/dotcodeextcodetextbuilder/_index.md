---
title: DotCodeExtCodetextBuilder
second_title: Referensi API Aspose.BarCode untuk Android via Java
description: 
type: docs
weight: 35
url: /id/androidjava/com.aspose.barcode.generation/dotcodeextcodetextbuilder/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.generation.ExtCodetextBuilder](../../com.aspose.barcode.generation/extcodetextbuilder)
```
public class DotCodeExtCodetextBuilder extends ExtCodetextBuilder
```

Generator codetext yang diperluas untuk kode batang 2D DotCode dalam Mode ExtendedCodetext dari DotCodeEncodeMode

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
>  {
>      generator.getParameters().getBarcode().getDotCode().setDotCodeEncodeMode(DotCodeEncodeMode.EXTENDED_CODETEXT);
>  	   generator.save("test.bmp");
>  }
> ```
## Constructors

| Constructor | Deskripsi |
| --- | --- |
| [DotCodeExtCodetextBuilder()](#DotCodeExtCodetextBuilder--) |  |
## Methods

| Method | Deskripsi |
| --- | --- |
| [addECICodetext(int ECIEncoding, String codetext)](#addECICodetext-int-java.lang.String-) | Menambahkan codetext dengan Identifikasi Saluran yang Diperluas |
| [addFNC1FormatIdentifier()](#addFNC1FormatIdentifier--) | Menambahkan pengidentifikasi format FNC1 ke item codetext yang diperluas |
| [addFNC3ReaderInitialization()](#addFNC3ReaderInitialization--) | Menambahkan inisialisasi pembaca FNC3 ke item codetext yang diperluas |
| [addFNC3SymbolSeparator()](#addFNC3SymbolSeparator--) | Menambahkan pemisah simbol FNC3 ke item codetext yang diperluas |
| [addPlainCodetext(String codetext)](#addPlainCodetext-java.lang.String-) | Adds plain codetext to the extended codetext items |
| [addStructuredAppendMode(int barcodeId, int barcodesCount)](#addStructuredAppendMode-int-int-) | Menambahkan mode penambahan terstruktur ke item codetext yang diperluas |
| [clear()](#clear--) | Clears extended codetext items |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getExtendedCodetext()](#getExtendedCodetext--) | Generates Extended codetext from the extended codetext list. |
| [hashCode()](#hashCode--) |  |
| [isNeedToShieldItemFromPrevECI(int Index)](#isNeedToShieldItemFromPrevECI-int-) | Checks necessity to shield previous item by "\\000000" |
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
public void addECICodetext(int ECIEncoding, String codetext)
```


Menambahkan codetext dengan Identifikasi Saluran yang Diperluas

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| ECIEncoding | int | Extended Channel Identifier |
| codetext | java.lang.String | Codetext in unicode to add as extended codetext item with Extended Channel Identifier |

### addFNC1FormatIdentifier() {#addFNC1FormatIdentifier--}
```
public void addFNC1FormatIdentifier()
```


Menambahkan pengidentifikasi format FNC1 ke item codetext yang diperluas

### addFNC3ReaderInitialization() {#addFNC3ReaderInitialization--}
```
public void addFNC3ReaderInitialization()
```


Menambahkan inisialisasi pembaca FNC3 ke item codetext yang diperluas

### addFNC3SymbolSeparator() {#addFNC3SymbolSeparator--}
```
public void addFNC3SymbolSeparator()
```


Menambahkan pemisah simbol FNC3 ke item codetext yang diperluas

### addPlainCodetext(String codetext) {#addPlainCodetext-java.lang.String-}
```
public void addPlainCodetext(String codetext)
```


Adds plain codetext to the extended codetext items

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| codetext | java.lang.String | Codetext in unicode to add as extended codetext item |

### addStructuredAppendMode(int barcodeId, int barcodesCount) {#addStructuredAppendMode-int-int-}
```
public void addStructuredAppendMode(int barcodeId, int barcodesCount)
```


Menambahkan mode penambahan terstruktur ke item codetext yang diperluas

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| barcodeId | int | ID barcode |
| barcodesCount | int | Jumlah barcode |

### clear() {#clear--}
```
public void clear()
```


Clears extended codetext items

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


Generates Extended codetext from the extended codetext list.

**Returns:**
java.lang.String - Extended codetext as string
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isNeedToShieldItemFromPrevECI(int Index) {#isNeedToShieldItemFromPrevECI-int-}
```
public boolean isNeedToShieldItemFromPrevECI(int Index)
```


Checks necessity to shield previous item by "\\000000"

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| Index | int | Index in m\_List |

**Returns:**
boolean - Necessity to shield
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

