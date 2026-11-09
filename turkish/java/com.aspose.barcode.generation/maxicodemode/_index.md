---
title: "MaxiCodeMode"
second_title: "Aspose.BarCode for Java API Referansı"
description: "MaxiCode kodlama modlarını içerir."
type: docs
weight: 94
url: /tr/java/com.aspose.barcode.generation/maxicodemode/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum MaxiCodeMode extends Enum<MaxiCodeMode>
```

MaxiCode kodlama modlarını içerir.
## Alanlar

| Alan | Açıklama |
| --- | --- |
| [MODE_2](#MODE-2) | Mod 2, ilk mesajda posta bilgilerini ve ikinci mesajda verileri kodlar. |
| [MODE_3](#MODE-3) | Mod 3, ilk mesajda posta bilgilerini ve ikinci mesajda verileri kodlar. |
| [MODE_4](#MODE-4) | Mod 4, kısa ECC düzeltmesiyle ilk ve ikinci mesajlarda verileri kodlar. |
| [MODE_5](#MODE-5) | Mod 5, uzun ECC düzeltmesiyle ilk ve ikinci mesajlarda verileri kodlar. |
| [MODE_6](#MODE-6) | Mod 6, kısa ECC düzeltmesiyle ilk ve ikinci mesajlarda verileri kodlar. |
## Metotlar

| Metot | Açıklama |
| --- | --- |
| [<T>valueOf(Class<T> arg0, String arg1)](#-T-valueOf-java.lang.Class-T--java.lang.String-) |  |
| [compareTo(E arg0)](#compareTo-E-) |  |
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
### MODE_2 {#MODE-2}
```
public static final MaxiCodeMode MODE_2
```


Mod 2, ilk mesajda posta bilgilerini ve ikinci mesajda verileri kodlar. 9 haneli posta koduna sahiptir ve yalnızca ABD'de kullanılır.

### MODE_3 {#MODE-3}
```
public static final MaxiCodeMode MODE_3
```


Mod 3, ilk mesajda posta bilgilerini ve ikinci mesajda verileri kodlar. 6 karakterli alfanümerik posta koduna sahiptir ve dünya çapında kullanılır.

### MODE_4 {#MODE-4}
```
public static final MaxiCodeMode MODE_4
```


Mod 4, kısa ECC düzeltmesiyle ilk ve ikinci mesajlarda verileri kodlar.

### MODE_5 {#MODE-5}
```
public static final MaxiCodeMode MODE_5
```


Mod 5, uzun ECC düzeltmesiyle ilk ve ikinci mesajlarda verileri kodlar.

### MODE_6 {#MODE-6}
```
public static final MaxiCodeMode MODE_6
```


Mod 6, kısa ECC düzeltmesiyle ilk ve ikinci mesajlarda verileri kodlar. Cihazları kodlamak için kullanılır.

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
public static MaxiCodeMode fromValue(int value)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

**Returns:**
[MaxiCodeMode](../../com.aspose.barcode.generation/maxicodemode)
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
public static MaxiCodeMode valueOf(String name)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| ad | java.lang.String |  |

**Returns:**
[MaxiCodeMode](../../com.aspose.barcode.generation/maxicodemode)
### values() {#values--}
```
public static MaxiCodeMode[] values()
```




**Returns:**
com.aspose.barcode.generation.MaxiCodeMode[]
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

