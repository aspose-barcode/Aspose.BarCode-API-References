---
title: CaptionParameters
second_title: Aspose.BarCode for Android via Java API Reference
description: 캡션 매개변수.
type: docs
weight: 20
url: /ko/androidjava/com.aspose.barcode.generation/captionparameters/
---
**Inheritance:**
java.lang.Object
```
public class CaptionParameters
```

캡션 매개변수.
## Constructors

| Constructor | 설명 |
| --- | --- |
| [CaptionParameters()](#CaptionParameters--) |  |
## Methods

| Method | 설명 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAlignment()](#getAlignment--) | 캡션 텍스트 수평 정렬. |
| [getClass()](#getClass--) |  |
| [getFont()](#getFont--) | 캡션 글꼴. |
|  | [getNoWrap()](#getNoWrap--) | ``` |
텍스트 내에서 단어 줄 바꿈(줄 바꿈)을 지정합니다.
``` |
| [getPadding()](#getPadding--) | Captions paddings. |
| [getText()](#getText--) | Caption text. |
| [getTextColor()](#getTextColor--) | Caption text color. |
| [getVisible()](#getVisible--) | Caption text visibility. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAlignment(TextAlignment value)](#setAlignment-com.aspose.barcode.generation.TextAlignment-) | Caption test horizontal alignment. |
| [setNoWrap(boolean value)](#setNoWrap-boolean-) | ```
Specify word wraps (line breaks) within text
``` |
| [setPadding(Padding value)](#setPadding-com.aspose.barcode.generation.Padding-) | 캡션 패딩. |
| [setText(String value)](#setText-java.lang.String-) | 캡션 텍스트. |
| [setTextColor(int value)](#setTextColor-int-) | 캡션 텍스트 색상. |
| [setVisible(boolean value)](#setVisible-boolean-) | 캡션 텍스트 표시 여부. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### CaptionParameters() {#CaptionParameters--}
```
public CaptionParameters()
```


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
### getAlignment() {#getAlignment--}
```
public TextAlignment getAlignment()
```


캡션 텍스트 수평 정렬. 기본값: StringAlignment.Center.

**Returns:**
[TextAlignment](../../com.aspose.barcode.generation/textalignment)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getFont() {#getFont--}
```
public FontUnit getFont()
```


캡션 글꼴. 기본값: Arial 8pt regular.

**Returns:**
[FontUnit](../../com.aspose.barcode.generation/fontunit)
### getNoWrap() {#getNoWrap--}
```
public boolean getNoWrap()
```


```
Specify word wraps (line breaks) within text.
 Default value: false.
```

**Returns:**
boolean
### getPadding() {#getPadding--}
```
public Padding getPadding()
```


캡션 패딩. CaptionAbove의 기본값: 5pt 5pt 0 5pt. CaptionBelow의 기본값: 0 5pt 5pt 5pt.

**Returns:**
[Padding](../../com.aspose.barcode.generation/padding)
### getText() {#getText--}
```
public String getText()
```


캡션 텍스트. 기본값: 빈 문자열.

**Returns:**
java.lang.String
### getTextColor() {#getTextColor--}
```
public int getTextColor()
```


캡션 텍스트 색상. 기본값: Color.BLACK.

**Returns:**
int
### getVisible() {#getVisible--}
```
public boolean getVisible()
```


캡션 텍스트 표시 여부. 기본값: false.

**Returns:**
boolean
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




### setAlignment(TextAlignment value) {#setAlignment-com.aspose.barcode.generation.TextAlignment-}
```
public void setAlignment(TextAlignment value)
```


캡션 텍스트 수평 정렬. 기본값: StringAlignment.Center.

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| value | [TextAlignment](../../com.aspose.barcode.generation/textalignment) |  |

### setNoWrap(boolean value) {#setNoWrap-boolean-}
```
public void setNoWrap(boolean value)
```


```
Specify word wraps (line breaks) within text
```

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

### setPadding(Padding value) {#setPadding-com.aspose.barcode.generation.Padding-}
```
public void setPadding(Padding value)
```


캡션 패딩. CaptionAbove의 기본값: 5pt 5pt 0 5pt. CaptionBelow의 기본값: 0 5pt 5pt 5pt.

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| value | [Padding](../../com.aspose.barcode.generation/padding) |  |

### setText(String value) {#setText-java.lang.String-}
```
public void setText(String value)
```


캡션 텍스트. 기본값: 빈 문자열.

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### setTextColor(int value) {#setTextColor-int-}
```
public void setTextColor(int value)
```


캡션 텍스트 색상. 기본값: Color.BLACK.

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setVisible(boolean value) {#setVisible-boolean-}
```
public void setVisible(boolean value)
```


캡션 텍스트 표시 여부. 기본값: false.

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

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

