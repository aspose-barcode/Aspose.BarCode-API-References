---
title: BarCodeImageFormat
second_title: Aspose.BarCode for Android via Java API Reference
description: 画像のファイル形式を指定します。
type: docs
weight: 75
url: /ja/androidjava/com.aspose.barcode.generation/barcodeimageformat/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum BarCodeImageFormat extends Enum<BarCodeImageFormat>
```

画像のファイル形式を指定します。
## フィールド

| フィールド | Description |
| --- | --- |
| [BMP](#BMP) | ビットマップ (BMP) 画像形式を指定します。 |
| [EMF](#EMF) | 拡張メタファイル (EMF) 画像形式を指定します。 |
| [GIF](#GIF) | Graphics Interchange Format (GIF) 画像形式を指定します。 |
| [JPEG](#JPEG) | Joint Photographic Experts Group (JPEG) 画像形式を指定します。 |
| [PDF](#PDF) | Portable Document Format (PDF) 画像形式を指定します。 |
| [PNG](#PNG) | W3C Portable Network Graphics (PNG) 画像形式を指定します。 |
| [WEBP](#WEBP) | 拡張メタファイル (EMF) 画像形式を指定します。 |
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


ビットマップ (BMP) 画像形式を指定します。

### EMF {#EMF}
```
public static final BarCodeImageFormat EMF
```


拡張メタファイル (EMF) 画像形式を指定します。(Windows プラットフォームでのみサポートされ、\*nix プラットフォームでは PNG として保存されます)

### GIF {#GIF}
```
public static final BarCodeImageFormat GIF
```


Graphics Interchange Format (GIF) 画像形式を指定します。

### JPEG {#JPEG}
```
public static final BarCodeImageFormat JPEG
```


Joint Photographic Experts Group (JPEG) 画像形式を指定します。

### PDF {#PDF}
```
public static final BarCodeImageFormat PDF
```


Portable Document Format (PDF) 画像形式を指定します。

### PNG {#PNG}
```
public static final BarCodeImageFormat PNG
```


W3C Portable Network Graphics (PNG) 画像形式を指定します。

### WEBP {#WEBP}
```
public static final BarCodeImageFormat WEBP
```


拡張メタファイル (EMF) 画像形式を指定します。

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
| 名前 | java.lang.String |  |

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

