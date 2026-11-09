---
title: "SingleDecodeType"
second_title: "Aspose.BarCode for Java API 레퍼런스"
description: "단일 디코드 유형입니다."
type: docs
weight: 44
url: /ko/java/com.aspose.barcode.barcoderecognition/singledecodetype/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.barcoderecognition.BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype)
```
public final class SingleDecodeType extends BaseDecodeType
```

단일 디코드 유형입니다. 인스턴스를 얻으려면 디코드 유형을 참조하십시오.

--------------------

> ```
> This sample shows how to get instance of single decode type.
>  
>  SingleDecodeType singleType = DecodeType.QR
> ```
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [containsAny(BaseDecodeType[] types)](#containsAny-com.aspose.barcode.barcoderecognition.BaseDecodeType...-) | 이 인스턴스가 지정된 목록에 포함되어 있는지 여부를 나타내는 값을 반환합니다. |
| [equals(MultiDecodeType other)](#equals-com.aspose.barcode.barcoderecognition.MultiDecodeType-) |  |
| [equals(SingleDecodeType other)](#equals-com.aspose.barcode.barcoderecognition.SingleDecodeType-) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | 이 인스턴스가 지정된 [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) 값과 같은지 여부를 나타내는 값을 반환합니다. |
| [getClass()](#getClass--) |  |
| [getString()](#getString--) | SingleDecodeType 인스턴스를 다음 형식인 "Index:-1; Name:None"을 사용하여 동등한 문자열 표현으로 변환합니다. |
| [getString(SingleDecodeType instance)](#getString-com.aspose.barcode.barcoderecognition.SingleDecodeType-) | SingleDecodeType 인스턴스를 다음 형식인 "Index:-1; Name:None"을 사용하여 동등한 문자열 표현으로 변환합니다. |
| [getTypeIndex()](#getTypeIndex--) | 디코드 유형의 인덱스를 가져옵니다. |
| [getTypeName()](#getTypeName--) | 디코드 유형의 이름을 가져옵니다. |
| [hashCode()](#hashCode--) | 이 인스턴스의 해시 코드를 반환합니다. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [parseSingleDecodeType(String stringDecodeType)](#parseSingleDecodeType-java.lang.String-) | SingleDecodeType 이름의 문자열 표현을 해당 인스턴스로 변환합니다. |
| [toString()](#toString--) | SingleDecodeType을 이름 문자열로 나타내는 재정의된 메서드입니다. |
| [tryParseBaseDecodeType(String parsingType)](#tryParseBaseDecodeType-java.lang.String-) | 구체적인 유형을 결정한 후 BaseDecodeType의 문자열 표현을 해당 인스턴스로 변환합니다. |
| [tryParseMultiDecodeType(String parsingType)](#tryParseMultiDecodeType-java.lang.String-) | MultiDecodeType의 문자열 표현을 해당 인스턴스로 변환합니다. |
| [tryParseSingleDecodeType(String parsingType)](#tryParseSingleDecodeType-java.lang.String-) | SingleDecodeType의 문자열 표현을 해당 인스턴스로 변환합니다. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### containsAny(BaseDecodeType[] types) {#containsAny-com.aspose.barcode.barcoderecognition.BaseDecodeType...-}
```
public boolean containsAny(BaseDecodeType[] types)
```


이 인스턴스가 지정된 목록에 포함되어 있는지 여부를 나타내는 값을 반환합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| types | [BaseDecodeType\[\]](../../com.aspose.barcode.barcoderecognition/basedecodetype) | 단일 및 다중 디코드 유형의 배열 |

**Returns:**
boolean - 포함된 유형이 있으면 값이 true입니다.
### equals(MultiDecodeType other) {#equals-com.aspose.barcode.barcoderecognition.MultiDecodeType-}
```
public boolean equals(MultiDecodeType other)
```


이 인스턴스가 지정된 [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) 값과 같은지 여부를 나타내는 값을 반환합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| other | [MultiDecodeType](../../com.aspose.barcode.barcoderecognition/multidecodetype) |  |

**Returns:**
boolean
### equals(SingleDecodeType other) {#equals-com.aspose.barcode.barcoderecognition.SingleDecodeType-}
```
public boolean equals(SingleDecodeType other)
```


이 인스턴스가 지정된 [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) 값과 같은지 여부를 나타내는 값을 반환합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| other | [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) |  |

**Returns:**
boolean
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


이 인스턴스가 지정된 [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) 값과 같은지 여부를 나타내는 값을 반환합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| obj | java.lang.Object | 이 인스턴스와 비교할 System.Object 값입니다. |

**Returns:**
boolean - 객체가 이 인스턴스와 동일한 값을 가지고 있으면 true; 그렇지 않으면 false.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getString() {#getString--}
```
public String getString()
```


SingleDecodeType 인스턴스를 다음 형식인 "Index:-1; Name:None"을 사용하여 동등한 문자열 표현으로 변환합니다.

**Returns:**
java.lang.String - 단일 디코드 타입의 전체 값을 나타내는 문자열
### getString(SingleDecodeType instance) {#getString-com.aspose.barcode.barcoderecognition.SingleDecodeType-}
```
public static String getString(SingleDecodeType instance)
```


SingleDecodeType 인스턴스를 다음 형식인 "Index:-1; Name:None"을 사용하여 동등한 문자열 표현으로 변환합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| instance | [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) | 변환할 SingleDecodeType 인스턴스 |

**Returns:**
java.lang.String - 지정된 단일 디코드 타입의 전체 값을 나타내는 문자열
### getTypeIndex() {#getTypeIndex--}
```
public short getTypeIndex()
```


디코드 유형의 인덱스를 가져옵니다.

**Returns:**
short - 디코드 타입의 인덱스
### getTypeName() {#getTypeName--}
```
public String getTypeName()
```


디코드 유형의 이름을 가져옵니다.

**Returns:**
java.lang.String - 디코드 타입의 이름
### hashCode() {#hashCode--}
```
public int hashCode()
```


이 인스턴스의 해시 코드를 반환합니다.

**Returns:**
int - 32비트 부호 있는 정수 해시 코드.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### parseSingleDecodeType(String stringDecodeType) {#parseSingleDecodeType-java.lang.String-}
```
public static SingleDecodeType parseSingleDecodeType(String stringDecodeType)
```


SingleDecodeType 이름의 문자열 표현을 해당 인스턴스로 변환합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| stringDecodeType | java.lang.String | 변환할 SingleDecodeType의 이름을 포함하는 문자열. |

**Returns:**
[SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) - the instance of , if conversion was successful; otherwise, it returns \{@link \}.
### toString() {#toString--}
```
public String toString()
```


SingleDecodeType을 이름 문자열로 나타내는 재정의된 메서드입니다.

**Returns:**
java.lang.String - 단일 디코드 타입의 이름을 나타내는 문자열
### tryParseBaseDecodeType(String parsingType) {#tryParseBaseDecodeType-java.lang.String-}
```
public static BaseDecodeType tryParseBaseDecodeType(String parsingType)
```


BaseDecodeType의 문자열 표현을 구체적인 타입을 결정한 후 해당 인스턴스로 변환합니다. 반환값은 변환이 성공했는지 실패했는지를 나타냅니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| parsingType | java.lang.String | 변환할 MultiDecodeType 표현을 포함하는 문자열. |

**Returns:**
[BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) - An actual MultiDecodeType is returned, when conversion has completed successfully;

그렇지 않으면 불확정 타입을 반환합니다. 또는 MultiDecodeType ("None").
### tryParseMultiDecodeType(String parsingType) {#tryParseMultiDecodeType-java.lang.String-}
```
public static MultiDecodeType tryParseMultiDecodeType(String parsingType)
```


MultiDecodeType의 문자열 표현을 해당 인스턴스로 변환합니다. 반환값은 변환이 성공했는지 실패했는지를 나타냅니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| parsingType | java.lang.String | 변환할 MultiDecodeType 표현을 포함하는 문자열. |

**Returns:**
[MultiDecodeType](../../com.aspose.barcode.barcoderecognition/multidecodetype) - An actual MultiDecodeType is returned, when conversion has completed successfully;

그렇지 않으면 불확정 타입을 반환합니다. 또는 MultiDecodeType ("None").
### tryParseSingleDecodeType(String parsingType) {#tryParseSingleDecodeType-java.lang.String-}
```
public static SingleDecodeType tryParseSingleDecodeType(String parsingType)
```


SingleDecodeType의 문자열 표현을 해당 인스턴스로 변환합니다. 반환값은 변환이 성공했는지 실패했는지를 나타냅니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| parsingType | java.lang.String | 변환할 "EAN8" 또는 "EAN13" 또는 "CodaBar"... 형식의 SingleDecodeType을 포함하는 문자열. |

**Returns:**
[SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) - An actual SingleDecodeType is returned, when conversion has completed successfully;

그렇지 않으면 불확정 타입을 반환합니다. 또는 SingleDecodeType (-1, "None").
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

