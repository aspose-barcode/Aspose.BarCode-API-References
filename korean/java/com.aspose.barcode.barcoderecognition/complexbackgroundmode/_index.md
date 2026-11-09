---
title: "ComplexBackgroundMode"
second_title: "Aspose.BarCode for Java API 레퍼런스"
description: 
type: docs
weight: 50
url: /ko/java/com.aspose.barcode.barcoderecognition/complexbackgroundmode/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum ComplexBackgroundMode extends Enum<ComplexBackgroundMode>
```

컬러 이미지에서 컬러 바코드의 추가 인식을 활성화하거나 비활성화하는 모드.

--------------------

> ```
> This sample shows how to use ComplexBackground mode
>   
>   BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.CODE_39_EXTENDED, DecodeType.CODE_128);
>   reader.getQualitySettings().setComplexBackground(ComplexBackgroundMode.ENABLED);
>   for(BarCodeResult result : reader.readBarCodes())
>      System.out.println(result.getCodeText());
> ```
## 필드

| 필드 | 설명 |
| --- | --- |
| [AUTO](#AUTO) | 현재는 Disabled와 동일합니다. |
| [DISABLED](#DISABLED) | 컬러 이미지에서 컬러 바코드의 추가 인식을 비활성화합니다. |
| [ENABLED](#ENABLED) | 컬러 이미지에서 컬러 바코드의 추가 인식을 활성화합니다. |
## 메서드

| 메서드 | 설명 |
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
### AUTO {#AUTO}
```
public static final ComplexBackgroundMode AUTO
```


현재는 Disabled와 동일합니다. 컬러 이미지에서 컬러 바코드의 추가 인식을 비활성화합니다.

### DISABLED {#DISABLED}
```
public static final ComplexBackgroundMode DISABLED
```


컬러 이미지에서 컬러 바코드의 추가 인식을 비활성화합니다.

### ENABLED {#ENABLED}
```
public static final ComplexBackgroundMode ENABLED
```


컬러 이미지에서 컬러 바코드의 추가 인식을 활성화합니다.

### <T>valueOf(Class<T> arg0, String arg1) {#-T-valueOf-java.lang.Class-T--java.lang.String-}
```
public static T <T>valueOf(Class<T> arg0, String arg1)
```




**Parameters:**
| 매개변수 | 유형 | 설명 |
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
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| arg0 | E |  |

**Returns:**
int
### equals(Object arg0) {#equals-java.lang.Object-}
```
public final boolean equals(Object arg0)
```




**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### fromValue(int value) {#fromValue-int-}
```
public static ComplexBackgroundMode fromValue(int value)
```




**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 값 | int |  |

**Returns:**
[ComplexBackgroundMode](../../com.aspose.barcode.barcoderecognition/complexbackgroundmode)
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
public static ComplexBackgroundMode valueOf(String name)
```




**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 이름 | java.lang.String |  |

**Returns:**
[ComplexBackgroundMode](../../com.aspose.barcode.barcoderecognition/complexbackgroundmode)
### values() {#values--}
```
public static ComplexBackgroundMode[] values()
```




**Returns:**
com.aspose.barcode.barcoderecognition.ComplexBackgroundMode[]
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final native void wait(long arg0)
```




**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

