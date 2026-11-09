---
title: "ExtCodetextBuilder"
second_title: "Aspose.BarCode for Java API Referansı"
description: "Genişletilmiş Kodmetni Modu için otomatik kodmetni üretimi sağlayan yardımcı sınıf"
type: docs
weight: 38
url: /tr/java/com.aspose.barcode.generation/extcodetextbuilder/
---
**Inheritance:**
java.lang.Object
```
public abstract class ExtCodetextBuilder
```

Genişletilmiş Kodmetni Modu için otomatik kodmetni üretimi sağlayan yardımcı sınıf
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [ExtCodetextBuilder()](#ExtCodetextBuilder--) |  |
## Metotlar

| Metot | Açıklama |
| --- | --- |
| [addECICodetext(int ECIEncoding, String codetext)](#addECICodetext-int-java.lang.String-) | Genişletilmiş Kanal Tanımlayıcısı ile kodmetin ekler |
| [addPlainCodetext(String codetext)](#addPlainCodetext-java.lang.String-) | Düz kodmetni genişletilmiş kodmetin öğelerine ekler |
| [clear()](#clear--) | Genişletilmiş kodmetin öğelerini temizler |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getExtendedCodetext()](#getExtendedCodetext--) | Oluşturma öğeleri listesinden genişletilmiş kod metnini oluştur. |
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


Genişletilmiş Kanal Tanımlayıcısı ile kodmetin ekler

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| ECIEncoding | int | Genişletilmiş Kanal Tanımlayıcısı |
| codetext | java.lang.String | Genişletilmiş Kanal Tanımlayıcısı ile genişletilmiş kodmetin öğesi olarak eklemek için unicode'daki kodmetin |

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
public abstract String getExtendedCodetext()
```


Oluşturma öğeleri listesinden genişletilmiş kod metnini oluştur.

**Returns:**
java.lang.String - Genişletilmiş kod metninin String'ini döndürür
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

