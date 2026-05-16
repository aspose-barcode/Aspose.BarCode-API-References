---
title: MultiDecodeType
second_title: Aspose.BarCode for Android via Java API Reference
description: 복합 디코드 유형입니다.
type: docs
weight: 37
url: /ko/androidjava/com.aspose.barcode.barcoderecognition/multidecodetype/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.barcoderecognition.BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype)
```
public class MultiDecodeType extends BaseDecodeType
```

복합 디코드 유형입니다.

이 샘플은 SingleDecodeType과 MultiDecode 유형을 결합한 복합 MultiDecode 유형을 만드는 방법을 보여줍니다.

```

```
## Constructors

| Constructor | 설명 |
| --- | --- |
| [MultiDecodeType(SingleDecodeType[] barcodeTypes)](#MultiDecodeType-com.aspose.barcode.barcoderecognition.SingleDecodeType...-) | MultiDecodeType 클래스의 새 인스턴스를 초기화합니다. |
| [MultiDecodeType(BaseDecodeType[] barcodeTypes)](#MultiDecodeType-com.aspose.barcode.barcoderecognition.BaseDecodeType...-) | MultiDecodeType 클래스의 새 인스턴스를 초기화합니다. |
## Methods

| Method | 설명 |
| --- | --- |
| [add(SingleDecodeType singleType)](#add-com.aspose.barcode.barcoderecognition.SingleDecodeType-) | MultiDecodeType에 하나의 [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype)를 추가합니다. |
| [containsAll(BaseDecodeType[] barcodeTypes)](#containsAll-com.aspose.barcode.barcoderecognition.BaseDecodeType...-) | 바코드 유형에서 모든 유형을 포함하는지 확인합니다. |
| [containsAny(BaseDecodeType[] decodeTypes)](#containsAny-com.aspose.barcode.barcoderecognition.BaseDecodeType...-) | 어떤 유형이라도 포함하고 있는지 여부 |
| [equals(MultiDecodeType other)](#equals-com.aspose.barcode.barcoderecognition.MultiDecodeType-) | 이 인스턴스가 지정된 MultiDecodeType 값과 같은지 여부를 나타내는 값을 반환합니다. |
| [equals(SingleDecodeType other)](#equals-com.aspose.barcode.barcoderecognition.SingleDecodeType-) | 이 디코드 유형 컬렉션이 지정된 [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) 값만 포함하는지 여부를 나타내는 값을 반환합니다. |
| [equals(Object obj)](#equals-java.lang.Object-) | 이 인스턴스가 지정된 MultiDecodeType 값과 같은지 여부를 나타내는 값을 반환합니다. |
| [exclude(SingleDecodeType singleType)](#exclude-com.aspose.barcode.barcoderecognition.SingleDecodeType-) | [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype)를 MultiDecodeType에서 제외하고 새로운 MultiDecodeType 인스턴스를 반환합니다. |
| [getClass()](#getClass--) |  |
| [getSingleTypes()](#getSingleTypes--) | 단일 유형 목록을 나타냅니다. |
| [getSingleTypesCount()](#getSingleTypesCount--) | 단일 유형의 개수를 반환합니다. |
| [hashCode()](#hashCode--) | 이 인스턴스의 해시 코드를 반환합니다. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | MultiDecodeType을 문자열로 표시하는 재정의된 메서드입니다. |
| [tryParseBaseDecodeType(String parsingType)](#tryParseBaseDecodeType-java.lang.String-) | 구체적인 유형을 결정한 후 BaseDecodeType의 문자열 표현을 해당 인스턴스로 변환합니다. |
| [tryParseMultiDecodeType(String parsingType)](#tryParseMultiDecodeType-java.lang.String-) | MultiDecodeType의 문자열 표현을 해당 인스턴스로 변환합니다. |
| [tryParseSingleDecodeType(String parsingType)](#tryParseSingleDecodeType-java.lang.String-) | SingleDecodeType의 문자열 표현을 해당 인스턴스로 변환합니다. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MultiDecodeType(SingleDecodeType[] barcodeTypes) {#MultiDecodeType-com.aspose.barcode.barcoderecognition.SingleDecodeType...-}
```
public MultiDecodeType(SingleDecodeType[] barcodeTypes)
```


MultiDecodeType 클래스의 새 인스턴스를 초기화합니다.

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| barcodeTypes | [SingleDecodeType\[\]](../../com.aspose.barcode.barcoderecognition/singledecodetype) | 단일 디코드 유형 배열 |

### MultiDecodeType(BaseDecodeType[] barcodeTypes) {#MultiDecodeType-com.aspose.barcode.barcoderecognition.BaseDecodeType...-}
```
public MultiDecodeType(BaseDecodeType[] barcodeTypes)
```


MultiDecodeType 클래스의 새 인스턴스를 초기화합니다.

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| barcodeTypes | [BaseDecodeType\[\]](../../com.aspose.barcode.barcoderecognition/basedecodetype) | 다중 및 단일 디코드 유형 배열 |

### add(SingleDecodeType singleType) {#add-com.aspose.barcode.barcoderecognition.SingleDecodeType-}
```
public final void add(SingleDecodeType singleType)
```


MultiDecodeType에 하나의 [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype)를 추가합니다.

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| singleType | [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) | 목록에 추가될 단일 DecodeType |

### containsAll(BaseDecodeType[] barcodeTypes) {#containsAll-com.aspose.barcode.barcoderecognition.BaseDecodeType...-}
```
public final boolean containsAll(BaseDecodeType[] barcodeTypes)
```


바코드 유형에서 모든 유형을 포함하는지 확인합니다.

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| barcodeTypes | [BaseDecodeType\[\]](../../com.aspose.barcode.barcoderecognition/basedecodetype) | 단일 또는 다중 바코드 유형 입력 |

**Returns:**
boolean - 모든 유형이 포함된 경우 true 값입니다.
### containsAny(BaseDecodeType[] decodeTypes) {#containsAny-com.aspose.barcode.barcoderecognition.BaseDecodeType...-}
```
public boolean containsAny(BaseDecodeType[] decodeTypes)
```


어떤 유형이라도 포함하고 있는지 여부

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| decodeTypes | [BaseDecodeType\[\]](../../com.aspose.barcode.barcoderecognition/basedecodetype) | 디코드 유형 |

**Returns:**
boolean - 어떤 유형이 포함되어 있으면 값은 true입니다
### equals(MultiDecodeType other) {#equals-com.aspose.barcode.barcoderecognition.MultiDecodeType-}
```
public boolean equals(MultiDecodeType other)
```


이 인스턴스가 지정된 MultiDecodeType 값과 같은지 여부를 나타내는 값을 반환합니다.

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| 기타 | com.aspose.barcode.barcoderecognition.MultiDecodeType | 이 인스턴스와 비교할 MultiDecodeType 값. |

**Returns:**
boolean -  **true**  if obj가 이 인스턴스와 동일한 값을 가지고 있는 경우; 그렇지 않은 경우 **false**.
### equals(SingleDecodeType other) {#equals-com.aspose.barcode.barcoderecognition.SingleDecodeType-}
```
public boolean equals(SingleDecodeType other)
```


이 디코드 유형 컬렉션이 지정된 [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) 값만 포함하는지 여부를 나타내는 값을 반환합니다.

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| other | [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) | 이 디코드 유형 컬렉션과 비교할 [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) 값. |

**Returns:**
boolean - **true** 이 컬렉션에 지정된 디코드 타입만 포함된 경우; 그렇지 않으면 **false** .
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


이 인스턴스가 지정된 MultiDecodeType 값과 같은지 여부를 나타내는 값을 반환합니다.

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| obj | java.lang.Object | 이 인스턴스와 비교할 System.Object 값입니다. |

**Returns:**
boolean -  **true**  if obj가 이 인스턴스와 동일한 값을 가지고 있는 경우; 그렇지 않은 경우 **false**.
### exclude(SingleDecodeType singleType) {#exclude-com.aspose.barcode.barcoderecognition.SingleDecodeType-}
```
public final MultiDecodeType exclude(SingleDecodeType singleType)
```


[SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype)를 MultiDecodeType에서 제외하고 새로운 MultiDecodeType 인스턴스를 반환합니다.

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| singleType | [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) | 제외할 단일 DecodeType. |

**Returns:**
com.aspose.barcode.barcoderecognition.MultiDecodeType - 제외된 SingleDecodeType을 포함하는 새로운 MultiDecodeType 인스턴스.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getSingleTypes() {#getSingleTypes--}
```
public final List<SingleDecodeType> getSingleTypes()
```


단일 유형 목록을 나타냅니다.

**Returns:**
java.util.List<com.aspose.barcode.barcoderecognition.SingleDecodeType> - 단일 타입들의 리스트
### getSingleTypesCount() {#getSingleTypesCount--}
```
public final int getSingleTypesCount()
```


단일 유형의 개수를 반환합니다.

**Returns:**
int
### hashCode() {#hashCode--}
```
public int hashCode()
```


이 인스턴스의 해시 코드를 반환합니다.

**Returns:**
int - 32비트 부호 있는 정수 해시 코드입니다.
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


MultiDecodeType을 문자열로 표시하는 재정의된 메서드입니다.

**Returns:**
java.lang.String - MultiDecodeType 인스턴스를 \"singleDecodeType1, singleDecodeType2, ...\" 형태로 나타내는 문자열

 **"AllSupportedTypes"**  returns when all types are included.
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

