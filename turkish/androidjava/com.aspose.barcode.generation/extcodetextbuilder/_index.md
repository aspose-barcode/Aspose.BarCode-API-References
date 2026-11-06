---
title: "ExtCodetextBuilder"
second_title: "Aspose.BarCode Android için Java API Referansı"
description: "Genişletilmiş Kod Metni Modu için otomatik kod metni oluşturma yardımcı sınıfı"
type: docs
weight: 39
url: /tr/androidjava/com.aspose.barcode.generation/extcodetextbuilder/
---
**Inheritance:**
java.lang.Object
```
public abstract class ExtCodetextBuilder
```

Genişletilmiş Kod Metni Modu için otomatik kod metni oluşturma yardımcı sınıfı
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [ExtCodetextBuilder()](#ExtCodetextBuilder--) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [addECICodetext(int ECIEncoding, String codetext)](#addECICodetext-int-java.lang.String-) | Extended Channel Identifier ile codetext ekler |
| [addPlainCodetext(String codetext)](#addPlainCodetext-java.lang.String-) | Düz codetext'i genişletilmiş codetext öğelerine ekler |
| [clear()](#clear--) | Genişletilmiş codetext öğelerini temizler |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getExtendedCodetext()](#getExtendedCodetext--) | Oluşturma öğeleri listesinden genişletilmiş kod metnini üret. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ExtCodetextBuilder() {#ExtCodetextBuilder--}
```
public ExtCodetextBuilder()
```


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
public abstract String getExtendedCodetext()
```


Oluşturma öğeleri listesinden genişletilmiş kod metnini üret.

**Returns:**
java.lang.String - Genişletilmiş kod metninin String'ini döndür.
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

