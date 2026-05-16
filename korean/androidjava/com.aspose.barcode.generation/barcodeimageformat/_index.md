---
title: BarCodeImageFormat
second_title: Aspose.BarCode for Android via Java API Reference
description: 이미지의 파일 형식을 지정합니다.
type: docs
weight: 75
url: /ko/androidjava/com.aspose.barcode.generation/barcodeimageformat/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum BarCodeImageFormat extends Enum<BarCodeImageFormat>
```

이미지의 파일 형식을 지정합니다.
## 필드

| 필드 | 설명 |
| --- | --- |
| [BMP](#BMP) | 비트맵(BMP) 이미지 형식을 지정합니다. |
| [EMF](#EMF) | 향상 메타파일(EMF) 이미지 형식을 지정합니다. |
| [GIF](#GIF) | 그래픽 교환 형식(GIF) 이미지 형식을 지정합니다. |
| [JPEG](#JPEG) | 합동 사진 전문가 그룹(JPEG) 이미지 형식을 지정합니다. |
| [PDF](#PDF) | 휴대용 문서 형식(PDF) 이미지 형식을 지정합니다. |
| [PNG](#PNG) | W3C 휴대용 네트워크 그래픽(PNG) 이미지 형식을 지정합니다. |
| [WEBP](#WEBP) | 향상 메타파일(EMF) 이미지 형식을 지정합니다. |
## Methods

| Method | 설명 |
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


비트맵(BMP) 이미지 형식을 지정합니다.

### EMF {#EMF}
```
public static final BarCodeImageFormat EMF
```


향상 메타파일(EMF) 이미지 형식을 지정합니다. (Windows 플랫폼에서만 지원되며, \\*nix 플랫폼에서는 PNG로 저장됩니다)

### GIF {#GIF}
```
public static final BarCodeImageFormat GIF
```


그래픽 교환 형식(GIF) 이미지 형식을 지정합니다.

### JPEG {#JPEG}
```
public static final BarCodeImageFormat JPEG
```


합동 사진 전문가 그룹(JPEG) 이미지 형식을 지정합니다.

### PDF {#PDF}
```
public static final BarCodeImageFormat PDF
```


휴대용 문서 형식(PDF) 이미지 형식을 지정합니다.

### PNG {#PNG}
```
public static final BarCodeImageFormat PNG
```


W3C 휴대용 네트워크 그래픽(PNG) 이미지 형식을 지정합니다.

### WEBP {#WEBP}
```
public static final BarCodeImageFormat WEBP
```


향상 메타파일(EMF) 이미지 형식을 지정합니다.

### <T>valueOf(Class<T> arg0, String arg1) {#-T-valueOf-java.lang.Class-T--java.lang.String-}
```
public static T <T>valueOf(Class<T> arg0, String arg1)
```




**Parameters:**
| Parameter | Type | 설명 |
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
| Parameter | Type | 설명 |
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
| Parameter | Type | 설명 |
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
| Parameter | Type | 설명 |
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
| Parameter | Type | 설명 |
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
| Parameter | Type | 설명 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

