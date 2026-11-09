---
title: "FontUnit"
second_title: "Aspose.BarCode for Java API 레퍼런스"
description: "텍스트에 대한 특정 형식을 정의하며, 여기에는 글꼴 종류, 크기 및 스타일 속성이 포함됩니다. 크기는 Unit 값 속성에 있습니다."
type: docs
weight: 42
url: /ko/java/com.aspose.barcode.generation/fontunit/
---
**Inheritance:**
java.lang.Object
```
public final class FontUnit
```

텍스트에 대한 특정 형식을 정의합니다. 여기에는 글꼴, 크기 및 스타일 속성이 포함되며, 크기는 Unit 값 속성에 있습니다.

--------------------

> ```
> This sample shows how to create and save a BarCode image.
>   
>          BarCodeGenerator generator = new BarCodeGenerator(EncodeTypes.CODE_128);
>          generator.getCodeTextStyle().getFont().setStyle(FontStyle.ITALIC);
>          generator.getCodeTextStyle().getFont().getSize().setPoint(18);
>          generator.save("test.png");
> ```
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getFamilyName()](#getFamilyName--) | 이 Font의 글꼴 이름을 가져옵니다. |
| [getSize()](#getSize--) | 이 FontUnit의 크기를 Unit 값으로 가져옵니다. |
| [getStyle()](#getStyle--) | 이 FontUnit에 대한 스타일 정보를 가져옵니다. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setFamilyName(String value)](#setFamilyName-java.lang.String-) | 이 Font의 글꼴 이름을 설정합니다. |
| [setStyle(int value)](#setStyle-int-) | 이 FontUnit에 대한 스타일 정보를 설정합니다. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| 매개변수 | 유형 | 설명 |
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
### getFamilyName() {#getFamilyName--}
```
public String getFamilyName()
```


이 Font의 글꼴 이름을 가져옵니다.

**Returns:**
java.lang.String
### getSize() {#getSize--}
```
public Unit getSize()
```


이 FontUnit의 크기를 Unit 값으로 가져옵니다.

**Returns:**
[Unit](../../com.aspose.barcode.generation/unit)
### getStyle() {#getStyle--}
```
public int getStyle()
```


이 FontUnit에 대한 스타일 정보를 가져옵니다.

**Returns:**
int
### hashCode() {#hashCode--}
```
public int hashCode()
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




### setFamilyName(String value) {#setFamilyName-java.lang.String-}
```
public void setFamilyName(String value)
```


이 Font의 글꼴 이름을 설정합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### setStyle(int value) {#setStyle-int-}
```
public void setStyle(int value)
```


이 FontUnit에 대한 스타일 정보를 설정합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 값 | int |  |

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

