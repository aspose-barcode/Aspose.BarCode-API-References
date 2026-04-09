---
title: BaseDecodeType
second_title: Aspose.BarCode for Android via Java API Reference
description: MultiDecodeType 및 SingleDecodeType의 기본 클래스입니다.
type: docs
weight: 23
url: /ko/androidjava/com.aspose.barcode.barcoderecognition/basedecodetype/
---
**Inheritance:**
java.lang.Object
```
public abstract class BaseDecodeType
```

MultiDecodeType 및 SingleDecodeType의 기본 클래스입니다.

--------------------

> ```
> This sample shows how to use BaseDecodeType with SingleDecodeType and MultiDecodeType
>  
>  BaseDecodeType decodeOne = DecodeType.CODE_128;
>  BaseDecodeType decodeTwo = new MultiDecodeType(DecodeType.CODE_128, DecodeType.CODE_39_STANDARD, DecodeType.CODE_39_FULL_ASCII);
> ```
## Methods

| Method | 설명 |
| --- | --- |
| [containsAny(BaseDecodeType[] types)](#containsAny-com.aspose.barcode.barcoderecognition.BaseDecodeType...-) | 주어진 디코드 유형 중 하나가 포함되어 있는지 여부를 결정합니다 |
| [equals(MultiDecodeType other)](#equals-com.aspose.barcode.barcoderecognition.MultiDecodeType-) | 이 인스턴스가 지정된 [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) 값과 같은지 여부를 나타내는 값을 반환합니다. |
| [equals(SingleDecodeType other)](#equals-com.aspose.barcode.barcoderecognition.SingleDecodeType-) | 이 인스턴스가 지정된 [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) 값과 같은지 여부를 나타내는 값을 반환합니다. |
| [equals(Object other)](#equals-java.lang.Object-) | 이 인스턴스가 지정된 [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) 값과 같은지 여부를 나타내는 값을 반환합니다. |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [tryParseBaseDecodeType(String parsingType)](#tryParseBaseDecodeType-java.lang.String-) | 구체적인 유형을 결정한 후 BaseDecodeType의 문자열 표현을 해당 인스턴스로 변환합니다. |
| [tryParseMultiDecodeType(String parsingType)](#tryParseMultiDecodeType-java.lang.String-) | MultiDecodeType의 문자열 표현을 해당 인스턴스로 변환합니다. |
| [tryParseSingleDecodeType(String parsingType)](#tryParseSingleDecodeType-java.lang.String-) | SingleDecodeType의 문자열 표현을 해당 인스턴스로 변환합니다. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### containsAny(BaseDecodeType[] types) {#containsAny-com.aspose.barcode.barcoderecognition.BaseDecodeType...-}
```
public abstract boolean containsAny(BaseDecodeType[] types)
```


주어진 디코드 유형 중 하나가 포함되어 있는지 여부를 결정합니다

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| types | [BaseDecodeType\[\]](../../com.aspose.barcode.barcoderecognition/basedecodetype) | 확인할 유형들. |

**Returns:**
boolean - 유형이 포함되어 있으면 값은 true입니다.
### equals(MultiDecodeType other) {#equals-com.aspose.barcode.barcoderecognition.MultiDecodeType-}
```
public boolean equals(MultiDecodeType other)
```


이 인스턴스가 지정된 [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) 값과 같은지 여부를 나타내는 값을 반환합니다.

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| 기타 | com.aspose.barcode.barcoderecognition.MultiDecodeType | 이 인스턴스와 비교할 java.lang.Object 값. |

**Returns:**
boolean - 객체가 이 인스턴스와 동일한 값을 가지면 true; 그렇지 않으면 false.
### equals(SingleDecodeType other) {#equals-com.aspose.barcode.barcoderecognition.SingleDecodeType-}
```
public boolean equals(SingleDecodeType other)
```


이 인스턴스가 지정된 [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) 값과 같은지 여부를 나타내는 값을 반환합니다.

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| other | [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) | 이 인스턴스와 비교할 java.lang.Object 값. |

**Returns:**
boolean - 객체가 이 인스턴스와 동일한 값을 가지면 true; 그렇지 않으면 false.
### equals(Object other) {#equals-java.lang.Object-}
```
public boolean equals(Object other)
```


이 인스턴스가 지정된 [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) 값과 같은지 여부를 나타내는 값을 반환합니다.

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| 기타 | java.lang.Object | 이 인스턴스와 비교할 java.lang.Object 값. |

**Returns:**
boolean - 객체가 이 인스턴스와 동일한 값을 가지면 true; 그렇지 않으면 false.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
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




**Returns:**
java.lang.String
### tryParseBaseDecodeType(String parsingType) {#tryParseBaseDecodeType-java.lang.String-}
```
public static BaseDecodeType tryParseBaseDecodeType(String parsingType)
```


BaseDecodeType의 문자열 표현을 구체적인 유형을 결정한 후 해당 인스턴스로 변환합니다. 반환 값은 변환이 성공했는지 실패했는지를 나타냅니다.

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| parsingType | java.lang.String | MultiDecodeType 표현을 포함하는 문자열을 변환합니다. |

**Returns:**
[BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) - An actual MultiDecodeType is returned, when conversion has completed successfully;

그렇지 않으면 무한 유형을 반환합니다. 또는 MultiDecodeType ("None").
### tryParseMultiDecodeType(String parsingType) {#tryParseMultiDecodeType-java.lang.String-}
```
public static MultiDecodeType tryParseMultiDecodeType(String parsingType)
```


MultiDecodeType의 문자열 표현을 해당 인스턴스로 변환합니다. 반환 값은 변환이 성공했는지 실패했는지를 나타냅니다.

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| parsingType | java.lang.String | MultiDecodeType 표현을 포함하는 문자열을 변환합니다. |

**Returns:**
com.aspose.barcode.barcoderecognition.MultiDecodeType - 변환이 성공적으로 완료되면 실제 MultiDecodeType이 반환됩니다;

그렇지 않으면 무한 유형을 반환합니다. 또는 MultiDecodeType ("None").
### tryParseSingleDecodeType(String parsingType) {#tryParseSingleDecodeType-java.lang.String-}
```
public static SingleDecodeType tryParseSingleDecodeType(String parsingType)
```


SingleDecodeType의 문자열 표현을 해당 인스턴스로 변환합니다. 반환 값은 변환이 성공했는지 실패했는지를 나타냅니다.

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| parsingType | java.lang.String | "EAN8" 또는 "EAN13" 또는 "CodaBar" 형식의 SingleDecodeType을 포함하는 문자열을 변환합니다. |

**Returns:**
[SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) - An actual SingleDecodeType is returned, when conversion has completed successfully;

그렇지 않으면 무한 유형을 반환합니다. 또는 SingleDecodeType (-1, "None").
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

