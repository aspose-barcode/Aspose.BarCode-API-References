---
title: XDimensionMode
second_title: Aspose.BarCode for Android via Java API Reference
description: 
type: docs
weight: 58
url: /ko/androidjava/com.aspose.barcode.barcoderecognition/xdimensionmode/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum XDimensionMode extends Enum<XDimensionMode>
```

바코드 최소 요소(매트릭스 셀 또는 바)의 크기(1부터 무한대까지)를 설정하는 인식 모드.

--------------------

> ```
> This sample shows how to use XDimension mode
>   
>   BarCodeReader reader = new BarCodeReader("test.png", DecodeType.CODE_39_EXTENDED, DecodeType.CODE_128);
>   reader.getQualitySettings().setXDimension(XDimensionMode.SMALL);
>   for(BarCodeResult result : reader.readBarCodes())
>      System.out.println(result.getCodeText());
> ```
## 필드

| 필드 | 설명 |
| --- | --- |
| [AUTO](#AUTO) | XDimension 값은 AI(SVM)에 의해 감지됩니다. |
| [LARGE](#LARGE) | 고해상도 카메라로 캡처된 BarcodeQuality의 품질을 사용하여 큰 XDimension을 가진 바코드를 감지합니다. |
| [NORMAL](#NORMAL) | 2픽셀 이상인 클래식 XDimension을 가진 바코드를 BarcodeQuality의 품질 또는 고품질 바코드로 감지합니다. |
| [SMALL](#SMALL) | 1픽셀 이상인 작은 XDimension을 가진 바코드를 BarcodeQuality의 품질로 감지합니다. |
| [USE_MINIMAL_X_DIMENSION](#USE-MINIMAL-X-DIMENSION) | MinimalXDimension에 설정된 크기의 바코드를 BarcodeQuality의 품질로 감지합니다. |
## Methods

| Method | 설명 |
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
public static final XDimensionMode AUTO
```


XDimension 값은 AI(SVM)에 의해 감지됩니다. 현재는 Normal과 동일합니다.

### LARGE {#LARGE}
```
public static final XDimensionMode LARGE
```


고해상도 카메라로 캡처된 BarcodeQuality의 품질을 사용하여 큰 XDimension을 가진 바코드를 감지합니다.

### NORMAL {#NORMAL}
```
public static final XDimensionMode NORMAL
```


2픽셀 이상인 클래식 XDimension을 가진 바코드를 BarcodeQuality의 품질 또는 고품질 바코드로 감지합니다.

### SMALL {#SMALL}
```
public static final XDimensionMode SMALL
```


1픽셀 이상인 작은 XDimension을 가진 바코드를 BarcodeQuality의 품질로 감지합니다.

### USE_MINIMAL_X_DIMENSION {#USE-MINIMAL-X-DIMENSION}
```
public static final XDimensionMode USE_MINIMAL_X_DIMENSION
```


MinimalXDimension에 설정된 크기의 바코드를 BarcodeQuality의 품질로 감지합니다.

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
### fromValue(int value) {#fromValue-int-}
```
public static XDimensionMode fromValue(int value)
```




**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| 값 | int |  |

**Returns:**
[XDimensionMode](../../com.aspose.barcode.barcoderecognition/xdimensionmode)
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
public static XDimensionMode valueOf(String name)
```




**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| name | java.lang.String |  |

**Returns:**
[XDimensionMode](../../com.aspose.barcode.barcoderecognition/xdimensionmode)
### values() {#values--}
```
public static XDimensionMode[] values()
```




**Returns:**
com.aspose.barcode.barcoderecognition.XDimensionMode[]
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

