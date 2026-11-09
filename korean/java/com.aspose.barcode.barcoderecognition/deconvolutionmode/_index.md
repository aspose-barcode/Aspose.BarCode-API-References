---
title: "DeconvolutionMode"
second_title: "Aspose.BarCode for Java API 레퍼런스"
description: 
type: docs
weight: 52
url: /ko/java/com.aspose.barcode.barcoderecognition/deconvolutionmode/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum DeconvolutionMode extends Enum<DeconvolutionMode>
```

Deconvolution (image restorations) 모드는 이미지 손상 정도를 정의합니다. 원래 Deconvolution은 카메라로 이미지를 촬영할 때 흐림과 같은 자연적인 함수에 의해 손상(컨볼루션)된 이미지를 복원할 수 있는 기능입니다. 이미지 손상을 일으키는 함수를 감지할 수 없기 때문에, 우리는 샤프하거나 수학적 형태학과 같은 가장 잘 알려진 함수들을 확인해야 합니다.

--------------------

> ```
> This sample shows how to use Deconvolution mode
>   
>   BarCodeReader reader = new BarCodeReader("c:\\test.png", DecodeType.CODE_39_EXTENDED, DecodeType.CODE_128);
>   reader.getQualitySettings().setDeconvolution(DeconvolutionMode.SLOW);
>   for(BarCodeResult result : reader.readBarCodes())
>      System.out.println(result.getCodeText());
> ```
## 필드

| 필드 | 설명 |
| --- | --- |
| [FAST](#FAST) | 고품질 이미지에 대해 빠른 디컨볼루션 방법을 활성화합니다. |
| [NORMAL](#NORMAL) | 일반 이미지에 대해 일반 디컨볼루션 방법을 활성화합니다. |
| [SLOW](#SLOW) | 저품질 이미지에 대해 느린 디컨볼루션 방법을 활성화합니다. |
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
### FAST {#FAST}
```
public static final DeconvolutionMode FAST
```


고품질 이미지에 대해 빠른 디컨볼루션 방법을 활성화합니다.

### NORMAL {#NORMAL}
```
public static final DeconvolutionMode NORMAL
```


일반 이미지에 대해 일반 디컨볼루션 방법을 활성화합니다.

### SLOW {#SLOW}
```
public static final DeconvolutionMode SLOW
```


저품질 이미지에 대해 느린 디컨볼루션 방법을 활성화합니다.

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
public static DeconvolutionMode fromValue(int value)
```




**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 값 | int |  |

**Returns:**
[DeconvolutionMode](../../com.aspose.barcode.barcoderecognition/deconvolutionmode)
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
public static DeconvolutionMode valueOf(String name)
```




**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 이름 | java.lang.String |  |

**Returns:**
[DeconvolutionMode](../../com.aspose.barcode.barcoderecognition/deconvolutionmode)
### values() {#values--}
```
public static DeconvolutionMode[] values()
```




**Returns:**
com.aspose.barcode.barcoderecognition.DeconvolutionMode[]
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

