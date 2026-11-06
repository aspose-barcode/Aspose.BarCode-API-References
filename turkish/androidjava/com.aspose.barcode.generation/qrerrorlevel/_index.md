---
title: "QRErrorLevel"
second_title: "Aspose.BarCode Android için Java API Referansı"
description: "Reed-Solomon hata düzeltme seviyesi."
type: docs
weight: 104
url: /tr/androidjava/com.aspose.barcode.generation/qrerrorlevel/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum QRErrorLevel extends Enum<QRErrorLevel>
```

Reed-Solomon hata düzeltme seviyesi. Düşükten yükseğe: LEVEL\_L, LEVEL\_M, LEVEL\_Q, LEVEL\_H.
## Alanlar

| Alan | Açıklama |
| --- | --- |
| [LEVEL_H](#LEVEL-H) | H hata düzeltme seviyesi QR ve RectMicroQR barkodlarına uygulanabilir. |
| [LEVEL_L](#LEVEL-L) | L hata düzeltme seviyesi QR ve MicroQR barkodlarına uygulanabilir. |
| [LEVEL_M](#LEVEL-M) | M hata düzeltme seviyesi QR barkodlarına, RectMicroQR barkodlarına ve M2'den M4'e kadar sürümlere sahip MicroQR barkodlarına uygulanabilir. |
| [LEVEL_Q](#LEVEL-Q) | Q hata düzeltme seviyesi QR barkodlarına ve M4 sürümüne sahip MicroQR barkodlarına uygulanabilir. |
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
### LEVEL_H {#LEVEL-H}
```
public static final QRErrorLevel LEVEL_H
```


H hata düzeltme seviyesi QR ve RectMicroQR barkodlarına uygulanabilir. Kod metninin %30'unun geri kazanılmasını sağlar

### LEVEL_L {#LEVEL-L}
```
public static final QRErrorLevel LEVEL_L
```


L hata düzeltme seviyesi QR ve MicroQR barkodlarına uygulanabilir. Kod metninin %7'sinin geri kazanılmasını sağlar.

### LEVEL_M {#LEVEL-M}
```
public static final QRErrorLevel LEVEL_M
```


M hata düzeltme seviyesi QR barkodlarına, RectMicroQR barkodlarına ve M2'den M4'e kadar sürümlere sahip MicroQR barkodlarına uygulanabilir. Kod metninin %15'inin geri kazanılmasını sağlar

### LEVEL_Q {#LEVEL-Q}
```
public static final QRErrorLevel LEVEL_Q
```


Q hata düzeltme seviyesi QR barkodlarına ve M4 sürümüne sahip MicroQR barkodlarına uygulanabilir. Kod metninin %25'inin geri kazanılmasını sağlar

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
public static QRErrorLevel fromValue(int value)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

**Returns:**
[QRErrorLevel](../../com.aspose.barcode.generation/qrerrorlevel)
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
public static QRErrorLevel valueOf(String name)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| ad | java.lang.String |  |

**Returns:**
[QRErrorLevel](../../com.aspose.barcode.generation/qrerrorlevel)
### values() {#values--}
```
public static QRErrorLevel[] values()
```




**Returns:**
com.aspose.barcode.generation.QRErrorLevel[]
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

