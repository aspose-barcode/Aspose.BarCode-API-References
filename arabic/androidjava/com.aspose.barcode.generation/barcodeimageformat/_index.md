---
title: BarCodeImageFormat
second_title: مرجع Aspose.BarCode لنظام Android عبر Java API
description: يحدد تنسيق ملف الصورة.
type: docs
weight: 75
url: /ar/androidjava/com.aspose.barcode.generation/barcodeimageformat/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum BarCodeImageFormat extends Enum<BarCodeImageFormat>
```

يحدد تنسيق ملف الصورة.
## الحقول

| حقل | الوصف |
| --- | --- |
| [BMP](#BMP) | يحدد تنسيق الصورة bitmap (BMP). |
| [EMF](#EMF) | يحدد تنسيق الصورة Enhanced Metafile (EMF). |
| [GIF](#GIF) | يحدد تنسيق الصورة Graphics Interchange Format (GIF). |
| [JPEG](#JPEG) | يحدد تنسيق الصورة Joint Photographic Experts Group (JPEG). |
| [PDF](#PDF) | يحدد تنسيق الصورة Portable Document Format (PDF). |
| [PNG](#PNG) | يحدد تنسيق الصورة W3C Portable Network Graphics (PNG). |
| [WEBP](#WEBP) | يحدد تنسيق الصورة Enhanced Metafile (EMF). |
## Methods

| Method | الوصف |
| --- | --- |
| [<T>valueOf(Class<T> arg0, String arg1)](#-T-valueOf-java.lang.Class-T--java.lang.String-) |  |
| [compareTo(E arg0)](#compareTo-E-) |  |
| [describeConstable()](#describeConstable--) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDeclaringClass()](#getDeclaringClass--) |  |
| [getValue()](#getValue--) |  |
| [hashCode()](#hashCode--) |  |
| [name()](#name--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [ordinal()](#ordinal--) |  |
| [toCompressFormat(BarCodeImageFormat format)](#toCompressFormat-com.aspose.barcode.generation.BarCodeImageFormat-) |  |
| [toString()](#toString--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
| [values()](#values--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### BMP {#BMP}
```
public static final BarCodeImageFormat BMP
```


يحدد تنسيق الصورة bitmap (BMP).

### EMF {#EMF}
```
public static final BarCodeImageFormat EMF
```


يحدد تنسيق الصورة Enhanced Metafile (EMF). (مدعوم فقط على منصة Windows، على منصات \*nix يتم حفظه كـ PNG)

### GIF {#GIF}
```
public static final BarCodeImageFormat GIF
```


يحدد تنسيق الصورة Graphics Interchange Format (GIF).

### JPEG {#JPEG}
```
public static final BarCodeImageFormat JPEG
```


يحدد تنسيق الصورة Joint Photographic Experts Group (JPEG).

### PDF {#PDF}
```
public static final BarCodeImageFormat PDF
```


يحدد تنسيق الصورة Portable Document Format (PDF).

### PNG {#PNG}
```
public static final BarCodeImageFormat PNG
```


يحدد تنسيق الصورة W3C Portable Network Graphics (PNG).

### WEBP {#WEBP}
```
public static final BarCodeImageFormat WEBP
```


يحدد تنسيق الصورة Enhanced Metafile (EMF).

### <T>valueOf(Class<T> arg0, String arg1) {#-T-valueOf-java.lang.Class-T--java.lang.String-}
```
public static T <T>valueOf(Class<T> arg0, String arg1)
```




**Parameters:**
| Parameter | Type | الوصف |
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
| Parameter | Type | الوصف |
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
| Parameter | Type | الوصف |
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
### toCompressFormat(BarCodeImageFormat format) {#toCompressFormat-com.aspose.barcode.generation.BarCodeImageFormat-}
```
public static Bitmap.CompressFormat toCompressFormat(BarCodeImageFormat format)
```




**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| format | [BarCodeImageFormat](../../com.aspose.barcode.generation/barcodeimageformat) |  |

**Returns:**
android.graphics.Bitmap.CompressFormat
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static BarCodeImageFormat valueOf(String name)
```




**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| الاسم | java.lang.String |  |

**Returns:**
[BarCodeImageFormat](../../com.aspose.barcode.generation/barcodeimageformat)
### values() {#values--}
```
public static BarCodeImageFormat[] values()
```




**Returns:**
com.aspose.barcode.generation.BarCodeImageFormat[]
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

