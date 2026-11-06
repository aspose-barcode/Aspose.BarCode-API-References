---
title: "AutoSizeMode"
second_title: "Aspose.BarCode Android için Java API Referansı"
description: "Otomatik boyutlandırma modlarının farklı türlerini belirtir."
type: docs
weight: 70
url: /tr/androidjava/com.aspose.barcode.generation/autosizemode/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum AutoSizeMode extends Enum<AutoSizeMode>
```

Otomatik boyutlandırma modlarının farklı türlerini belirtir.
## Alanlar

| Alan | Açıklama |
| --- | --- |
| [INTERPOLATION](#INTERPOLATION) | Barkodu belirtilen boyuta yeniden boyutlandırır. |
| [NEAREST](#NEAREST) | Barkodu, ImageWidth ve ImageHeight özellikleriyle belirtilen en yakın en düşük olası boyuta yeniden boyutlandırır. |
| [NONE](#NONE) | Otomatik yeniden boyutlandırma devre dışı bırakıldı. |
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
### INTERPOLATION {#INTERPOLATION}
```
public static final AutoSizeMode INTERPOLATION
```


Barkodu belirtilen boyuta yeniden boyutlandırır. Boyut, ImageWidth ve ImageHeight özellikleriyle belirtilebilir. Ölçeklendirmeden sonra oluşturulan barkod geçersiz (okunamaz) olabilir.

### NEAREST {#NEAREST}
```
public static final AutoSizeMode NEAREST
```


Barkodu, ImageWidth ve ImageHeight özellikleriyle belirtilen en yakın en düşük olası boyuta yeniden boyutlandırır. Varsayılan en-boy oranını korur.

### NONE {#NONE}
```
public static final AutoSizeMode NONE
```


Otomatik yeniden boyutlandırma devre dışı bırakıldı.

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
public static AutoSizeMode fromValue(int value)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

**Returns:**
[AutoSizeMode](../../com.aspose.barcode.generation/autosizemode)
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
public static AutoSizeMode valueOf(String name)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| ad | java.lang.String |  |

**Returns:**
[AutoSizeMode](../../com.aspose.barcode.generation/autosizemode)
### values() {#values--}
```
public static AutoSizeMode[] values()
```




**Returns:**
com.aspose.barcode.generation.AutoSizeMode[]
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

