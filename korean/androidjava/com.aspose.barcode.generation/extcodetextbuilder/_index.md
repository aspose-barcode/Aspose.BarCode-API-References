---
title: ExtCodetextBuilder
second_title: Aspose.BarCode for Android via Java API Reference
description: 확장 코드텍스트 모드의 자동 코드텍스트 생성을 위한 도우미 클래스
type: docs
weight: 40
url: /ko/androidjava/com.aspose.barcode.generation/extcodetextbuilder/
---
**Inheritance:**
java.lang.Object
```
public abstract class ExtCodetextBuilder
```

확장 코드텍스트 모드의 자동 코드텍스트 생성을 위한 도우미 클래스
## Constructors

| Constructor | 설명 |
| --- | --- |
| [ExtCodetextBuilder()](#ExtCodetextBuilder--) |  |
## Methods

| Method | 설명 |
| --- | --- |
| [addECICodetext(int ECIEncoding, String codetext)](#addECICodetext-int-java.lang.String-) | Extended Channel Identifier와 함께 코드텍스트를 추가합니다. |
| [addPlainCodetext(String codetext)](#addPlainCodetext-java.lang.String-) | 일반 코드 텍스트를 확장된 코드 텍스트 항목에 추가합니다 |
| [clear()](#clear--) | 확장된 코드 텍스트 항목을 지웁니다 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getExtendedCodetext()](#getExtendedCodetext--) | 생성 항목 목록에서 확장 코드 텍스트를 생성합니다. |
| [hashCode()](#hashCode--) |  |
| [isNeedToShieldItemFromPrevECI(int Index)](#isNeedToShieldItemFromPrevECI-int-) | 이전 항목을 "\\000000"으로 보호해야 하는지 확인합니다 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ExtCodetextBuilder() {#ExtCodetextBuilder--}
```
public ExtCodetextBuilder()
```


### addECICodetext(int ECIEncoding, String codetext) {#addECICodetext-int-java.lang.String-}
```
public void addECICodetext(int ECIEncoding, String codetext)
```


Extended Channel Identifier와 함께 코드텍스트를 추가합니다.

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| ECIEncoding | int | 확장 채널 식별자 |
| 코드 텍스트 | java.lang.String | 확장 채널 식별자를 사용하여 확장 코드 텍스트 항목으로 추가할 유니코드 코드 텍스트 |

### addPlainCodetext(String codetext) {#addPlainCodetext-java.lang.String-}
```
public void addPlainCodetext(String codetext)
```


일반 코드 텍스트를 확장된 코드 텍스트 항목에 추가합니다

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| 코드 텍스트 | java.lang.String | 확장 코드 텍스트 항목으로 추가할 유니코드 코드 텍스트 |

### clear() {#clear--}
```
public void clear()
```


확장된 코드 텍스트 항목을 지웁니다

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
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
### getExtendedCodetext() {#getExtendedCodetext--}
```
public abstract String getExtendedCodetext()
```


생성 항목 목록에서 확장 코드 텍스트를 생성합니다.

**Returns:**
java.lang.String - 확장 코드 텍스트 문자열을 반환합니다.
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isNeedToShieldItemFromPrevECI(int Index) {#isNeedToShieldItemFromPrevECI-int-}
```
public boolean isNeedToShieldItemFromPrevECI(int Index)
```


이전 항목을 "\\000000"으로 보호해야 하는지 확인합니다

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| 인덱스 | int | m\_List의 인덱스 |

**Returns:**
boolean - 보호 필요성
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

