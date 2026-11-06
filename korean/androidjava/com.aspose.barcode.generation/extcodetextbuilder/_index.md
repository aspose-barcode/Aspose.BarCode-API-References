---
title: "ExtCodetextBuilder"
second_title: "Aspose.BarCode for Android via Java API 참조"
description: "확장 코드텍스트 모드의 자동 코드텍스트 생성을 위한 도우미 클래스"
type: docs
weight: 39
url: /ko/androidjava/com.aspose.barcode.generation/extcodetextbuilder/
---
**Inheritance:**
java.lang.Object
```
public abstract class ExtCodetextBuilder
```

확장 코드텍스트 모드의 자동 코드텍스트 생성을 위한 도우미 클래스
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [ExtCodetextBuilder()](#ExtCodetextBuilder--) |  |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [addECICodetext(int ECIEncoding, String codetext)](#addECICodetext-int-java.lang.String-) | Extended Channel Identifier와 함께 codetext를 추가합니다. |
| [addPlainCodetext(String codetext)](#addPlainCodetext-java.lang.String-) | 확장 codetext 항목에 일반 codetext를 추가합니다. |
| [clear()](#clear--) | 확장 codetext 항목을 삭제합니다. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getExtendedCodetext()](#getExtendedCodetext--) | 생성 항목 목록에서 확장 코드 텍스트를 생성합니다. |
| [hashCode()](#hashCode--) |  |
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
public final void addECICodetext(int ECIEncoding, String codetext)
```


Extended Channel Identifier와 함께 codetext를 추가합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| ECIEncoding | int | Extended Channel Identifier |
| codetext | java.lang.String | Extended Channel Identifier와 함께 확장 codetext 항목으로 추가할 유니코드 codetext |

### addPlainCodetext(String codetext) {#addPlainCodetext-java.lang.String-}
```
public final void addPlainCodetext(String codetext)
```


확장 codetext 항목에 일반 codetext를 추가합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| codetext | java.lang.String | 확장 codetext 항목으로 추가할 유니코드 codetext |

### clear() {#clear--}
```
public void clear()
```


확장 codetext 항목을 삭제합니다.

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
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
java.lang.String - 확장 코드 텍스트의 문자열을 반환합니다
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
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

