---
title: "FontUnit"
second_title: "Aspose.BarCode for Android via Java API 참조"
description: "텍스트에 대한 특정 형식을 정의하며, 여기에는 글꼴 얼굴 크기와 스타일 속성이 포함되고 크기는 Unit 값 속성에 지정됩니다."
type: docs
weight: 43
url: /ko/androidjava/com.aspose.barcode.generation/fontunit/
---
**Inheritance:**
java.lang.Object
```
public final class FontUnit
```

텍스트에 대한 특정 형식을 정의하며, 여기에는 글꼴, 크기 및 스타일 속성이 포함되고 크기는 Unit 값 속성으로 지정됩니다.

--------------------

> ```
> This sample shows how to create and save a BarCode image.
>   
>          BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.CODE_128);
>          generator.getCodeTextStyle().getFont().setStyle(FontStyle.ITALIC);
>          generator.getCodeTextStyle().getFont().getSize().setPoint(18);
>          generator.save("test.png");
> ```
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [FontUnit(FontUnit source)](#FontUnit-com.aspose.barcode.generation.FontUnit-) |  |
| [FontUnit(Typeface familyName, float sizeValue, GraphicsUnit graphicsUnit, float dpi)](#FontUnit-android.graphics.Typeface-float-com.aspose.barcode.generation.GraphicsUnit-float-) |  |
| [FontUnit(Typeface familyName, float sizeValue, GraphicsUnit graphicsUnit, float dpi, int style)](#FontUnit-android.graphics.Typeface-float-com.aspose.barcode.generation.GraphicsUnit-float-int-) |  |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getFamilyName()](#getFamilyName--) | 이 Font의 글꼴 이름을 가져옵니다. |
| [getSize()](#getSize--) | 이 FontUnit의 크기를 Unit 값으로 가져옵니다. |
| [getStyle()](#getStyle--) | 이 FontUnit의 스타일 정보를 가져옵니다. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setFamilyName(Typeface value)](#setFamilyName-android.graphics.Typeface-) | 이 Font의 글꼴 이름을 설정합니다. |
| [setStyle(int value)](#setStyle-int-) | 이 FontUnit에 대한 스타일 정보를 설정합니다. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### FontUnit(FontUnit source) {#FontUnit-com.aspose.barcode.generation.FontUnit-}
```
public FontUnit(FontUnit source)
```


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| source | [FontUnit](../../com.aspose.barcode.generation/fontunit) |  |

### FontUnit(Typeface familyName, float sizeValue, GraphicsUnit graphicsUnit, float dpi) {#FontUnit-android.graphics.Typeface-float-com.aspose.barcode.generation.GraphicsUnit-float-}
```
public FontUnit(Typeface familyName, float sizeValue, GraphicsUnit graphicsUnit, float dpi)
```


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| familyName | android.graphics.Typeface |  |
| sizeValue | float |  |
| graphicsUnit | [GraphicsUnit](../../com.aspose.barcode.generation/graphicsunit) |  |
| dpi | float |  |

### FontUnit(Typeface familyName, float sizeValue, GraphicsUnit graphicsUnit, float dpi, int style) {#FontUnit-android.graphics.Typeface-float-com.aspose.barcode.generation.GraphicsUnit-float-int-}
```
public FontUnit(Typeface familyName, float sizeValue, GraphicsUnit graphicsUnit, float dpi, int style)
```


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| familyName | android.graphics.Typeface |  |
| sizeValue | float |  |
| graphicsUnit | [GraphicsUnit](../../com.aspose.barcode.generation/graphicsunit) |  |
| dpi | float |  |
| style | int |  |

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
### getFamilyName() {#getFamilyName--}
```
public Typeface getFamilyName()
```


이 Font의 글꼴 이름을 가져옵니다.

**Returns:**
android.graphics.Typeface
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


이 FontUnit의 스타일 정보를 가져옵니다.

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




### setFamilyName(Typeface value) {#setFamilyName-android.graphics.Typeface-}
```
public void setFamilyName(Typeface value)
```


이 Font의 글꼴 이름을 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | android.graphics.Typeface |  |

### setStyle(int value) {#setStyle-int-}
```
public void setStyle(int value)
```


이 FontUnit에 대한 스타일 정보를 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
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

