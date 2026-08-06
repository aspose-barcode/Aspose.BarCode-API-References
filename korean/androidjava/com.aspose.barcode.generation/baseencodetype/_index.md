---
title: BaseEncodeType
second_title: Aspose.BarCode for Android via Java API Reference
description: SymbologyEncodeType의 기본 클래스.
type: docs
weight: 16
url: /ko/androidjava/com.aspose.barcode.generation/baseencodetype/
---
**Inheritance:**
java.lang.Object
```
public class BaseEncodeType
```

SymbologyEncodeType의 기본 클래스.
## Methods

| Method | 설명 |
| --- | --- |
| [equals(Object other)](#equals-java.lang.Object-) | 이 인스턴스가 지정된 BaseEncodeType 값과 동일한지 여부를 나타내는 값을 반환합니다. |
| [getClass()](#getClass--) |  |
| [getClassification()](#getClassification--) | 이 심볼의 분류를 가져옵니다. |
| [getString()](#getString--) | BaseEncodeType 인스턴스를 해당 문자열 표현으로 변환합니다. |
| [getString(BaseEncodeType instance)](#getString-com.aspose.barcode.generation.BaseEncodeType-) | BaseEncodeType 인스턴스를 해당 문자열 표현으로 변환합니다. |
| [getTypeIndex()](#getTypeIndex--) | 인코드 유형의 인덱스를 가져옵니다. |
| [getTypeName()](#getTypeName--) | 인코드 유형의 이름을 가져옵니다. |
| [hashCode()](#hashCode--) | 이 인스턴스의 해시 코드를 반환합니다. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [parse(String stringEncodeType)](#parse-java.lang.String-) | BaseEncodeType 이름의 문자열 표현을 해당 인스턴스로 변환합니다. |
| [toString()](#toString--) | 주어진 BaseEncodeType의 이름을 문자열로 반환합니다. |
| [tryParse(String parsingType, BaseEncodeType[] result)](#tryParse-java.lang.String-com.aspose.barcode.generation.BaseEncodeType---) | BaseEncodeType의 문자열 표현을 해당 인스턴스로 변환합니다. |
| [tryParse(String parsingType, SymbologyEncodeType[] result)](#tryParse-java.lang.String-com.aspose.barcode.generation.SymbologyEncodeType---) | BaseEncodeType의 문자열 표현을 해당 인스턴스로 변환합니다. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object other) {#equals-java.lang.Object-}
```
public boolean equals(Object other)
```


이 인스턴스가 지정된 BaseEncodeType 값과 동일한지 여부를 나타내는 값을 반환합니다.

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| 기타 | java.lang.Object | 이 인스턴스와 비교할 BaseEncodeType 값. |

**Returns:**
boolean -  **true**  if obj가 이 인스턴스와 동일한 값을 가지고 있는 경우; 그렇지 않은 경우 **false**.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getClassification() {#getClassification--}
```
public BarcodeClassifications getClassification()
```


이 심볼의 분류를 가져옵니다.

**Returns:**
[BarcodeClassifications](../../com.aspose.barcode.generation/barcodeclassifications)
### getString() {#getString--}
```
public String getString()
```


BaseEncodeType 인스턴스를 해당 문자열 표현으로 변환합니다. 문자열 형식은: "Index:0; Name:Codabar".

**Returns:**
java.lang.String - 인코드 타입의 전체 값을 나타내는 문자열
### getString(BaseEncodeType instance) {#getString-com.aspose.barcode.generation.BaseEncodeType-}
```
public static String getString(BaseEncodeType instance)
```


BaseEncodeType 인스턴스를 해당 문자열 표현으로 변환합니다. 문자열 형식은: "Index:-1; Name:None".

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| instance | [BaseEncodeType](../../com.aspose.barcode.generation/baseencodetype) | 변환할 BaseEncodeType 인스턴스 |

**Returns:**
java.lang.String - 지정된 인코드 타입의 전체 값을 나타내는 문자열
### getTypeIndex() {#getTypeIndex--}
```
public short getTypeIndex()
```


인코드 유형의 인덱스를 가져옵니다.

**Returns:**
short
### getTypeName() {#getTypeName--}
```
public String getTypeName()
```


인코드 유형의 이름을 가져옵니다.

**Returns:**
java.lang.String
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




### parse(String stringEncodeType) {#parse-java.lang.String-}
```
public static BaseEncodeType parse(String stringEncodeType)
```


BaseEncodeType 이름의 문자열 표현을 해당 인스턴스로 변환합니다.

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| stringEncodeType | java.lang.String | 변환할 BaseEncodeType 이름을 포함하는 문자열. |

**Returns:**
[BaseEncodeType](../../com.aspose.barcode.generation/baseencodetype) - the instance of , if conversion was successful; otherwise, it returns   .
### toString() {#toString--}
```
public String toString()
```


주어진 BaseEncodeType의 이름을 문자열로 반환합니다.

**Returns:**
java.lang.String - 인코드 타입 이름을 나타내는 문자열
### tryParse(String parsingType, BaseEncodeType[] result) {#tryParse-java.lang.String-com.aspose.barcode.generation.BaseEncodeType---}
```
public static boolean tryParse(String parsingType, BaseEncodeType[] result)
```


BaseEncodeType의 문자열 표현을 인스턴스로 변환합니다. 반환값은 변환이 성공했는지 실패했는지를 나타냅니다.

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| parsingType | java.lang.String | 변환할 "Index:-1; Name:None" 형식의 문자열. |
|  | result | [BaseEncodeType\[\]](../../com.aspose.barcode.generation/baseencodetype) | 변환이 성공적으로 완료되면 실제 SingleEncodeType을 반환합니다; |

그렇지 않으면 null을 반환합니다. |

**Returns:**
boolean -  **true**  가 성공적으로 변환된 경우; 그렇지 않으면  **false** .
### tryParse(String parsingType, SymbologyEncodeType[] result) {#tryParse-java.lang.String-com.aspose.barcode.generation.SymbologyEncodeType---}
```
public static boolean tryParse(String parsingType, SymbologyEncodeType[] result)
```


BaseEncodeType의 문자열 표현을 인스턴스로 변환합니다. 반환값은 변환이 성공했는지 실패했는지를 나타냅니다.

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| parsingType | java.lang.String | 변환할 "Index:-1; Name:None" 형식의 문자열. |
|  | result | [SymbologyEncodeType\[\]](../../com.aspose.barcode.generation/symbologyencodetype) | 변환이 성공적으로 완료되면 실제 SingleEncodeType을 반환합니다; |

그렇지 않으면 null을 반환합니다. |

**Returns:**
boolean -  **true**  가 성공적으로 변환된 경우; 그렇지 않으면  **false** .
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

