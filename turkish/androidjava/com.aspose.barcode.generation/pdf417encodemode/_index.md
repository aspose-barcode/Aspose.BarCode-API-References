---
title: "Pdf417EncodeMode"
second_title: "Aspose.BarCode Android için Java API Referansı"
description: "Pdf417 barkod kodlama modu"
type: docs
weight: 99
url: /tr/androidjava/com.aspose.barcode.generation/pdf417encodemode/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum Pdf417EncodeMode extends Enum<Pdf417EncodeMode>
```

Pdf417 barkod kodlama modu
## Alanlar

| Alan | Açıklama |
| --- | --- |
| [AUTO](#AUTO) | Otomatik modda, CodeText maksimum veri sıkıştırmasıyla kodlanır. |
| [BINARY](#BINARY) | İkili modda, CodeText maksimum veri sıkıştırmasıyla kodlanır. |
| [ECI](#ECI) | ECI modunda, tüm mesaj belirtilen ECIEncoding kodlamasıyla, bir ECI tanımlayıcısı eklenerek yeniden kodlanır. |
| [EXTENDED](#EXTENDED) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [<T>valueOf(Class<T> arg0, String arg1)](#-T-valueOf-java.lang.Class-T--java.lang.String-) |  |
| [compareTo(E arg0)](#compareTo-E-) |  |
| [describeConstable()](#describeConstable--) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [fromValue(int value)](#fromValue-int-) |  |
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
public static final Pdf417EncodeMode AUTO
```


Otomatik modda, CodeText maksimum veri sıkıştırmasıyla kodlanır. Unicode karakterleri, ECIEncoding tarafından belirtilen kodlamada bir ECI tanımlayıcısı eklenerek yeniden kodlanır. Seçilen ECI kodlaması tarafından desteklenmeyen bir karakter bulunursa, bir istisna fırlatılır.

### BINARY {#BINARY}
```
public static final Pdf417EncodeMode BINARY
```


İkili modda, CodeText maksimum veri sıkıştırmasıyla kodlanır. Bir Unicode karakteri bulunursa, bir istisna fırlatılır.

### ECI {#ECI}
```
public static final Pdf417EncodeMode ECI
```


ECI modunda, tüm mesaj ECIEncoding tarafından belirtilen kodlamada bir ECI tanımlayıcısı eklenerek yeniden kodlanır. Seçilen ECI kodlaması tarafından desteklenmeyen bir karakter bulunursa, bir istisna fırlatılır. Lütfen bazı eski (2006 öncesi) tarayıcıların bu modu desteklemeyebileceğini unutmayın.

### EXTENDED {#EXTENDED}
```
public static final Pdf417EncodeMode EXTENDED
```


Birden fazla ECI modunu destekleyen genişletilmiş mod.

Genişletilmiş kod metni oluşturma için Pdf417ExtCodetextBuilder kullanmak daha iyidir.

Görünür metni yönetim karakterlerini kaldıracak şekilde ayarlamak için Display2DText özelliğini kullanın.

ECI tanımlayıcıları tek bir eğik çizgi ve altı basamaklı "\\000026" tanımlayıcısı olarak ayarlanır - UTF8 ECI tanımlayıcısı.

ECI tanımlayıcısından sonraki tüm Unicode karakterleri otomatik olarak doğru karakter kod kümesine kodlanır.

### <T>valueOf(Class<T> arg0, String arg1) {#-T-valueOf-java.lang.Class-T--java.lang.String-}
```
public static T <T>valueOf(Class<T> arg0, String arg1)
```




**Parameters:**
| Parametre | Tür | Açıklama |
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
| Parametre | Tür | Açıklama |
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
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### fromValue(int value) {#fromValue-int-}
```
public static Pdf417EncodeMode fromValue(int value)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

**Returns:**
[Pdf417EncodeMode](../../com.aspose.barcode.generation/pdf417encodemode)
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
public static Pdf417EncodeMode valueOf(String name)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| ad | java.lang.String |  |

**Returns:**
[Pdf417EncodeMode](../../com.aspose.barcode.generation/pdf417encodemode)
### values() {#values--}
```
public static Pdf417EncodeMode[] values()
```




**Returns:**
com.aspose.barcode.generation.Pdf417EncodeMode[]
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

