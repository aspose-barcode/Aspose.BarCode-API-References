---
title: "DataMatrixExtCodetextBuilder"
second_title: "Aspose.BarCode Android için Java API Referansı"
description: 
type: docs
weight: 32
url: /tr/androidjava/com.aspose.barcode.generation/datamatrixextcodetextbuilder/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.generation.ExtCodetextBuilder](../../com.aspose.barcode.generation/extcodetextbuilder)
```
public class DataMatrixExtCodetextBuilder extends ExtCodetextBuilder
```

EncodeMode'un ExtendedCodetext Modu için 2D DataMatrix barkodları için genişletilmiş kod metni oluşturucu.

--------------------

> ```
> //Extended codetext mode
>  //create codetext
>  DataMatrixExtCodetextBuilder textBuilder = new DataMatrixExtCodetextBuilder();
>  codetextBuilder.addECICodetextWithEncodeMode(ECIEncodings.Win1251, EncodeMode.BYTES, "World");
>  codetextBuilder.addPlainCodetext("Will");
>  codetextBuilder.addECICodetext(ECIEncodings.UTF8, "\u72acRight\u72d7");
>  codetextBuilder.addCodetextWithEncodeMode(EncodeMode.C40, "ABCDE");
>  //generate codetext
>  String codetext = textBuilder.getExtendedCodetext();
>  //generate
>  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DATA_MATRIX, codetext);
>  generator.getParameters().getBarcode().getDataMatrix().setEncodeMode(EncodeMode.EXTENDED_CODETEXT);
>  generator.save("test.bmp");
> ```
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [DataMatrixExtCodetextBuilder()](#DataMatrixExtCodetextBuilder--) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [addCodetextWithEncodeMode(DataMatrixEncodeMode encodeMode, String codetext)](#addCodetextWithEncodeMode-com.aspose.barcode.generation.DataMatrixEncodeMode-java.lang.String-) | Tanımlı kodlama moduyla kod metnini genişletilmiş kod metni öğelerine ekler |
| [addECICodetext(int ECIEncoding, String codetext)](#addECICodetext-int-java.lang.String-) | Extended Channel Identifier ile codetext ekler |
| [addECICodetextWithEncodeMode(int ECIEncoding, DataMatrixEncodeMode encodeMode, String codetext)](#addECICodetextWithEncodeMode-int-com.aspose.barcode.generation.DataMatrixEncodeMode-java.lang.String-) | Tanımlı kodlama modu ile Genişletilmiş Kanal Tanımlayıcısı kullanarak kod metnini ekler |
| [addPlainCodetext(String codetext)](#addPlainCodetext-java.lang.String-) | Düz codetext'i genişletilmiş codetext öğelerine ekler |
| [clear()](#clear--) | Genişletilmiş codetext öğelerini temizler |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getExtendedCodetext()](#getExtendedCodetext--) | Genişletilmiş codetext listesinden Extended codetext üretir. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### DataMatrixExtCodetextBuilder() {#DataMatrixExtCodetextBuilder--}
```
public DataMatrixExtCodetextBuilder()
```


### addCodetextWithEncodeMode(DataMatrixEncodeMode encodeMode, String codetext) {#addCodetextWithEncodeMode-com.aspose.barcode.generation.DataMatrixEncodeMode-java.lang.String-}
```
public final void addCodetextWithEncodeMode(DataMatrixEncodeMode encodeMode, String codetext)
```


Tanımlı kodlama moduyla kod metnini genişletilmiş kod metni öğelerine ekler

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| encodeMode | [DataMatrixEncodeMode](../../com.aspose.barcode.generation/datamatrixencodemode) | Kodlama modu değeri |
| codetext | java.lang.String | Genişletilmiş codetext öğesi olarak eklenecek unicode codetext |

### addECICodetext(int ECIEncoding, String codetext) {#addECICodetext-int-java.lang.String-}
```
public final void addECICodetext(int ECIEncoding, String codetext)
```


Extended Channel Identifier ile codetext ekler

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| ECIEncoding | int | Extended Channel Identifier |
| codetext | java.lang.String | Extended Channel Identifier ile genişletilmiş codetext öğesi olarak eklenecek unicode codetext |

### addECICodetextWithEncodeMode(int ECIEncoding, DataMatrixEncodeMode encodeMode, String codetext) {#addECICodetextWithEncodeMode-int-com.aspose.barcode.generation.DataMatrixEncodeMode-java.lang.String-}
```
public final void addECICodetextWithEncodeMode(int ECIEncoding, DataMatrixEncodeMode encodeMode, String codetext)
```


Tanımlı kodlama modu ile Genişletilmiş Kanal Tanımlayıcısı kullanarak kod metnini ekler

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| ECIEncoding | int | Extended Channel Identifier |
| encodeMode | [DataMatrixEncodeMode](../../com.aspose.barcode.generation/datamatrixencodemode) | Kodlama modu değeri |
| codetext | java.lang.String | Tanımlı kodlama modu ve Genişletilmiş Kanal Tanımlayıcısı ile eklenmek üzere unicode kod metni |

### addPlainCodetext(String codetext) {#addPlainCodetext-java.lang.String-}
```
public final void addPlainCodetext(String codetext)
```


Düz codetext'i genişletilmiş codetext öğelerine ekler

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| codetext | java.lang.String | Genişletilmiş codetext öğesi olarak eklenecek unicode codetext |

### clear() {#clear--}
```
public void clear()
```


Genişletilmiş codetext öğelerini temizler

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parametre | Tür | Açıklama |
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


Genişletilmiş codetext listesinden Extended codetext üretir.

**Returns:**
java.lang.String - Genişletilmiş kod metni string olarak.
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
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

