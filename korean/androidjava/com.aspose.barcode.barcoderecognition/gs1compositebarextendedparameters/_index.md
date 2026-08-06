---
title: GS1CompositeBarExtendedParameters
second_title: Aspose.BarCode for Android via Java API Reference
description: GS1 Composite Bar 인식 바코드의 특수 데이터를 저장합니다.
type: docs
weight: 34
url: /ko/androidjava/com.aspose.barcode.barcoderecognition/gs1compositebarextendedparameters/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.barcoderecognition.BaseExtendedParameters](../../com.aspose.barcode.barcoderecognition/baseextendedparameters)
```
public final class GS1CompositeBarExtendedParameters extends BaseExtendedParameters
```

인식된 바코드의  **GS1 Composite Bar**  특수 데이터를 저장합니다
## Methods

| Method | 설명 |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | 이 인스턴스가 지정된  GS1CompositeBarExtendedParameters  값과 같은지 여부를 나타내는 값을 반환합니다. |
| [getClass()](#getClass--) |  |
| [getOneDCodeText()](#getOneDCodeText--) | GS1 Composite의 1D (선형) 바코드 값을 가져옵니다. |
| [getOneDType()](#getOneDType--) | GS1 Composite의 1D (선형) 바코드 유형을 가져옵니다. |
| [getTwoDCodeText()](#getTwoDCodeText--) | GS1 Composite의 2D 바코드 값을 가져옵니다. |
| [getTwoDType()](#getTwoDType--) | GS1 Composite의 2D 바코드 유형을 가져옵니다. |
| [hashCode()](#hashCode--) | 이 인스턴스의 해시 코드를 반환합니다. |
| [isEmpty()](#isEmpty--) | 모든 매개변수가 기본값만 가지고 있는지 테스트합니다. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | 이  GS1CompositeBarExtendedParameters  의 사람이 읽을 수 있는 문자열 표현을 반환합니다. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


이 인스턴스가 지정된  GS1CompositeBarExtendedParameters  값과 같은지 여부를 나타내는 값을 반환합니다.

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| obj | java.lang.Object | 이 인스턴스와 비교할 System.Object 값입니다. |

**Returns:**
boolean -  **true**  if obj가 이 인스턴스와 동일한 값을 가지고 있는 경우; 그렇지 않은 경우 **false**.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getOneDCodeText() {#getOneDCodeText--}
```
public String getOneDCodeText()
```


GS1 Composite의 1D (선형) 바코드 값을 가져옵니다.

값: 1D 바코드 값

**Returns:**
java.lang.String
### getOneDType() {#getOneDType--}
```
public SingleDecodeType getOneDType()
```


GS1 Composite의 1D (선형) 바코드 유형을 가져옵니다.

값: 2D 바코드 유형

**Returns:**
[SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype)
### getTwoDCodeText() {#getTwoDCodeText--}
```
public String getTwoDCodeText()
```


GS1 Composite의 2D 바코드 값을 가져옵니다.

값: 2D 바코드 값

**Returns:**
java.lang.String
### getTwoDType() {#getTwoDType--}
```
public SingleDecodeType getTwoDType()
```


GS1 Composite의 2D 바코드 유형을 가져옵니다.

값: 2D 바코드 유형

**Returns:**
[SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype)
### hashCode() {#hashCode--}
```
public int hashCode()
```


이 인스턴스의 해시 코드를 반환합니다.

**Returns:**
int - 32비트 부호 있는 정수 해시 코드입니다.
### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


모든 매개변수가 기본값만 가지고 있는지 테스트합니다.

값: 모든 매개변수가 기본값만 가지고 있으면 **true**, 그렇지 않으면 **false**를 반환합니다.

**Returns:**
boolean
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### toString() {#toString--}
```
public String toString()
```


이  GS1CompositeBarExtendedParameters  의 사람이 읽을 수 있는 문자열 표현을 반환합니다.

**Returns:**
java.lang.String - 이  GS1CompositeBarExtendedParameters  를 나타내는 문자열입니다.
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

