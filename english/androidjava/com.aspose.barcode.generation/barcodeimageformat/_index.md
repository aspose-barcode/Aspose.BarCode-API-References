---
title: BarCodeImageFormat
second_title: Aspose.BarCode for Android via Java API Reference
description: Specifies the file format of the image.
type: docs
weight: 75
url: /androidjava/com.aspose.barcode.generation/barcodeimageformat/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum BarCodeImageFormat extends Enum<BarCodeImageFormat>
```

Specifies the file format of the image.
## Fields

| Field | Description |
| --- | --- |
| [BMP](#BMP) | Specifies the bitmap (BMP) image format. |
| [EMF](#EMF) | Specifies the Enhanced Metafile (EMF) image format. |
| [GIF](#GIF) | Specifies the Graphics Interchange Format (GIF) image format. |
| [JPEG](#JPEG) | Specifies the Joint Photographic Experts Group (JPEG) image format. |
| [PDF](#PDF) | Specifies the Portable Document Format (PDF) image format. |
| [PNG](#PNG) | Specifies the W3C Portable Network Graphics (PNG) image format. |
| [WEBP](#WEBP) | Specifies the Enhanced Metafile (EMF) image format. |
## Methods

| Method | Description |
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


Specifies the bitmap (BMP) image format.

### EMF {#EMF}
```
public static final BarCodeImageFormat EMF
```


Specifies the Enhanced Metafile (EMF) image format. (Supported only on Windows platform, on \*nix platforms is saved as PNG)

### GIF {#GIF}
```
public static final BarCodeImageFormat GIF
```


Specifies the Graphics Interchange Format (GIF) image format.

### JPEG {#JPEG}
```
public static final BarCodeImageFormat JPEG
```


Specifies the Joint Photographic Experts Group (JPEG) image format.

### PDF {#PDF}
```
public static final BarCodeImageFormat PDF
```


Specifies the Portable Document Format (PDF) image format.

### PNG {#PNG}
```
public static final BarCodeImageFormat PNG
```


Specifies the W3C Portable Network Graphics (PNG) image format.

### WEBP {#WEBP}
```
public static final BarCodeImageFormat WEBP
```


Specifies the Enhanced Metafile (EMF) image format.

### <T>valueOf(Class<T> arg0, String arg1) {#-T-valueOf-java.lang.Class-T--java.lang.String-}
```
public static T <T>valueOf(Class<T> arg0, String arg1)
```




**Parameters:**
| Parameter | Type | Description |
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
| Parameter | Type | Description |
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
| Parameter | Type | Description |
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
| Parameter | Type | Description |
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
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String |  |

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
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

