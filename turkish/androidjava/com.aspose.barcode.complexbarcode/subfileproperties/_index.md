---
title: "USADriveIdCodetext.SubfileProperties"
second_title: "Aspose.BarCode Android için Java API Referansı"
description: "USA DL alt dosya özellikleri ofseti ve uzunluğu otomatik olarak ayarlanır."
type: docs
weight: 12
url: /tr/androidjava/com.aspose.barcode.complexbarcode/usadriveidcodetext.subfileproperties/
---
**Inheritance:**
java.lang.Object
```
public static class USADriveIdCodetext.SubfileProperties
```

ABD Sürücü Belgesi alt dosya özellikleri, ofset ve uzunluk otomatik olarak ayarlanır.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [SubfileProperties(String type)](#SubfileProperties-java.lang.String-) |  |
| [SubfileProperties()](#SubfileProperties--) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getLength()](#getLength--) | 4 Bu baytlar, Alt Dosyanın uzunluğunu bayt cinsinden belirten 4 basamaklı sayısal bir değer içerir. Segment sonlandırıcısı, alt dosyanın uzunluğunu hesaplarken dahil edilmelidir. Bir segment sonlandırıcısı = 1. |
| [getOffset()](#getOffset--) | 4 basamaklı sayısal değer, dosyanın başından (veya başlangıcından) belirli alt dosyayla ilgili verinin bulunduğu konuma kadar olan bayt sayısını belirtir. Dosyadaki ilk bayt ofset 0'da yer alır. |
| [getType()](#getType--) | 2 baytlık alt dosya türü, örneğin "DL" |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setLength(int value)](#setLength-int-) | 4 Bu baytlar, Alt Dosyanın uzunluğunu bayt cinsinden belirten 4 basamaklı sayısal bir değer içerir. Segment sonlandırıcısı, alt dosyanın uzunluğunu hesaplarken dahil edilmelidir. Bir segment sonlandırıcısı = 1. |
| [setOffset(int value)](#setOffset-int-) | 4 basamaklı sayısal değer, dosyanın başından (veya başlangıcından) belirli alt dosyayla ilgili verinin bulunduğu konuma kadar olan bayt sayısını belirtir. Dosyadaki ilk bayt ofset 0'da yer alır. |
| [setType(String value)](#setType-java.lang.String-) | 2 baytlık alt dosya türü, örneğin "DL" |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### SubfileProperties(String type) {#SubfileProperties-java.lang.String-}
```
public SubfileProperties(String type)
```


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| tür | java.lang.String |  |

### SubfileProperties() {#SubfileProperties--}
```
public SubfileProperties()
```


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
### getLength() {#getLength--}
```
public final int getLength()
```


4 Bu baytlar, Alt Dosyanın uzunluğunu bayt cinsinden belirten 4 basamaklı sayısal bir değer içerir. Segment sonlandırıcısı, alt dosyanın uzunluğunu hesaplarken dahil edilmelidir. Bir segment sonlandırıcısı = 1. Her alt dosya iki karakterlik SubFile Type ile başlamalı ve bu iki karakter de uzunluğa dahil edilmelidir.

**Returns:**
int
### getOffset() {#getOffset--}
```
public final int getOffset()
```


4 basamaklı sayısal değer, dosyanın başından (veya başlangıcından) belirli alt dosyayla ilgili verinin bulunduğu konuma kadar olan bayt sayısını belirtir. Dosyadaki ilk bayt ofset 0'da yer alır.

**Returns:**
int
### getType() {#getType--}
```
public final String getType()
```


2 baytlık alt dosya türü, örneğin "DL"

**Returns:**
java.lang.String
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




### setLength(int value) {#setLength-int-}
```
public final void setLength(int value)
```


4 Bu baytlar, Alt Dosyanın uzunluğunu bayt cinsinden belirten 4 basamaklı sayısal bir değer içerir. Segment sonlandırıcısı, alt dosyanın uzunluğunu hesaplarken dahil edilmelidir. Bir segment sonlandırıcısı = 1. Her alt dosya iki karakterlik SubFile Type ile başlamalı ve bu iki karakter de uzunluğa dahil edilmelidir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### setOffset(int value) {#setOffset-int-}
```
public final void setOffset(int value)
```


4 basamaklı sayısal değer, dosyanın başından (veya başlangıcından) belirli alt dosyayla ilgili verinin bulunduğu konuma kadar olan bayt sayısını belirtir. Dosyadaki ilk bayt ofset 0'da yer alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### setType(String value) {#setType-java.lang.String-}
```
public final void setType(String value)
```


2 baytlık alt dosya türü, örneğin "DL"

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

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

