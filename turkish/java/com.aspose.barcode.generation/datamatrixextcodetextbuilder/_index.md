---
title: "DataMatrixExtCodetextBuilder"
second_title: "Aspose.BarCode for Java API Referansı"
description: 
type: docs
weight: 31
url: /tr/java/com.aspose.barcode.generation/datamatrixextcodetextbuilder/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.generation.ExtCodetextBuilder](../../com.aspose.barcode.generation/extcodetextbuilder)
```
public class DataMatrixExtCodetextBuilder extends ExtCodetextBuilder
```

EncodeMode'un ExtendedCodetext Modu için 2D DataMatrix barkodları için genişletilmiş kod metni oluşturucu

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
## Metotlar

| Metot | Açıklama |
| --- | --- |
| [addCodetextWithEncodeMode(DataMatrixEncodeMode encodeMode, String codetext)](#addCodetextWithEncodeMode-com.aspose.barcode.generation.DataMatrixEncodeMode-java.lang.String-) | Tanımlı kodlama modu ile kod metnini genişletilmiş kod metni öğelerine ekler |
| [addECICodetext(int ECIEncoding, String codetext)](#addECICodetext-int-java.lang.String-) | Genişletilmiş Kanal Tanımlayıcısı ile kodmetin ekler |
| [addECICodetextWithEncodeMode(int ECIEncoding, DataMatrixEncodeMode encodeMode, String codetext)](#addECICodetextWithEncodeMode-int-com.aspose.barcode.generation.DataMatrixEncodeMode-java.lang.String-) | Tanımlı kodlama modu ile Genişletilmiş Kanal Tanımlayıcısı içeren kod metnini ekler |
| [addPlainCodetext(String codetext)](#addPlainCodetext-java.lang.String-) | Düz kodmetni genişletilmiş kodmetin öğelerine ekler |
| [clear()](#clear--) | Genişletilmiş kodmetin öğelerini temizler |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getExtendedCodetext()](#getExtendedCodetext--) | Genişletilmiş kodmetin listesinden Genişletilmiş kodmetin oluşturur. |
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


Tanımlı kodlama modu ile kod metnini genişletilmiş kod metni öğelerine ekler

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| encodeMode | [DataMatrixEncodeMode](../../com.aspose.barcode.generation/datamatrixencodemode) | Kodlama modu değeri |
| codetext | java.lang.String | Unicode'da kod metni, genişletilmiş kod metni öğesi olarak eklemek için |

### addECICodetext(int ECIEncoding, String codetext) {#addECICodetext-int-java.lang.String-}
```
public final void addECICodetext(int ECIEncoding, String codetext)
```


Genişletilmiş Kanal Tanımlayıcısı ile kodmetin ekler

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| ECIEncoding | int | Genişletilmiş Kanal Tanımlayıcısı |
| codetext | java.lang.String | Genişletilmiş Kanal Tanımlayıcısı ile genişletilmiş kodmetin öğesi olarak eklemek için unicode'daki kodmetin |

### addECICodetextWithEncodeMode(int ECIEncoding, DataMatrixEncodeMode encodeMode, String codetext) {#addECICodetextWithEncodeMode-int-com.aspose.barcode.generation.DataMatrixEncodeMode-java.lang.String-}
```
public final void addECICodetextWithEncodeMode(int ECIEncoding, DataMatrixEncodeMode encodeMode, String codetext)
```


Tanımlı kodlama modu ile Genişletilmiş Kanal Tanımlayıcısı içeren kod metnini ekler

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| ECIEncoding | int | Genişletilmiş Kanal Tanımlayıcısı |
| encodeMode | [DataMatrixEncodeMode](../../com.aspose.barcode.generation/datamatrixencodemode) | Kodlama modu değeri |
| codetext | java.lang.String | Tanımlı kodlama modu ve Genişletilmiş Kanal Tanımlayıcısı ile eklemek için Unicode'da kod metni, genişletilmiş kod metni öğesi olarak |

### addPlainCodetext(String codetext) {#addPlainCodetext-java.lang.String-}
```
public final void addPlainCodetext(String codetext)
```


Düz kodmetni genişletilmiş kodmetin öğelerine ekler

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| codetext | java.lang.String | Unicode'da kod metni, genişletilmiş kod metni öğesi olarak eklemek için |

### clear() {#clear--}
```
public void clear()
```


Genişletilmiş kodmetin öğelerini temizler

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


Genişletilmiş kodmetin listesinden Genişletilmiş kodmetin oluşturur.

**Returns:**
java.lang.String - Genişletilmiş kod metni dize olarak.
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

